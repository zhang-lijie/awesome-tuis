# AGENTS.md

Guidance for AI agents working in this repository.

## What this repo is

A curated "awesome list" of terminal UI applications. **The deliverable is `README.md`** — there is no build, no package manager, no test suite, no lint config.

- `README.md` — the English list: 14 `<details>` sections, 747 entries.
- `README.zh-CN.md` — full Chinese translation. It mirrors `README.md` exactly: same sections, same entries, same order, same project names and URLs. Only prose (headings, descriptions) is translated.
- `.github/src/*.py` — standalone, stdlib-only Python scripts (see below).
- `.github/workflows/` — three scheduled/PR workflows.
- `.github/pull_request_template.md` — the rules a new entry must satisfy.

## Commands

**Verify the two READMEs are still in sync** (run after *any* edit to either file):

```bash
python3 .github/src/check_translation_sync.py
```

It compares section count, per-section entry counts, project names, URLs, entry order and TOC anchors. Exits non-zero and lists the mismatches. This is the only guard on the Chinese file — the CI bots ignore it.

**Python version**: the scripts use PEP 604 unions (`X | None`), so they need **Python 3.10+**. macOS `python3` is 3.9 and fails at import time with `TypeError: unsupported operand type(s) for |`. Use `python3.12` (or `/opt/homebrew/bin/python3.12`) instead.

**Reproduce the PR bot's alphabetical check** (it only flags violations involving lines the PR added):

```bash
python3.12 - <<'PY'
import importlib.util
spec = importlib.util.spec_from_file_location("alpha", ".github/src/readme_pr_alphabetical.py")
m = importlib.util.module_from_spec(spec); spec.loader.exec_module(m)
sections = m.parse_sections(open("README.md", encoding="utf-8").read())
for name, items in m.iter_checkable_groups(sections):
    inv, desc = m.find_ordering_violations(items, set())
    if inv: print(name, desc)
PY
```

**Dry-run the monthly audit** (prints the issue body, touches no GitHub state):

```bash
DRY_RUN=1 GITHUB_TOKEN=<token> python3 .github/src/repo_audit.py
```

Without `DRY_RUN` it opens, updates, or closes the real "Repository audit" issue. It reads `GITHUB_TOKEN`/`GH_TOKEN`, `GITHUB_REPOSITORY` (default `rothgar/awesome-tuis`) and `README_PATH` (default `README.md`).

**Do not run `.github/src/readme_pr_repo_first_commit.py` casually** — it posts comments to a real PR and *closes* it when every added repo is too young. It needs `GITHUB_TOKEN`, `PR_NUMBER` and `GITHUB_REPOSITORY`.

## CI gates

All three bots look at `README.md` **only**. `README.zh-CN.md` is never age-checked, order-checked or link-checked.

| Workflow | Trigger | What it does |
|---|---|---|
| `readme_pr_repo_first_commit.yml` | `pull_request_target` on README.md changes | Posts a per-repo age table plus alphabetical-order findings. **Auto-closes the PR when every added GitHub repo is younger than 6 months.** |
| `link_check.yml` | weekly, Mon 06:17 UTC | lychee over `README.md`, `fail: true`. Accepts 403/429/3xx; excludes `github.com/*/(issues\|pulls\|actions)`. |
| `repo_audit.yml` | monthly, 1st 07:23 UTC | Audits every GitHub repo in the list; keeps one issue titled "Repository audit" (marker `<!-- repo-audit -->`) with archived/missing/renamed/young/stale sections. |

**Age rule**: a repo's age is measured from the *later* of its first commit and its GitHub creation date. Non-GitHub URLs and unparseable dates are `UNKNOWN`, and `UNKNOWN` blocks the auto-close so the PR is not killed on a false positive.

## Adding an entry

Entry format — one line, project name is the link text:

```markdown
- [Name](https://github.com/owner/repo) Short description
```

- Insert it **alphabetically (case-insensitive)** within its `<details>` section. In `Libraries`, alphabetical order is per `<h3>` language subsection, not across the whole section.
- The alphabetical bot only flags violations that involve a line the PR added, so pre-existing misordering is tolerated — but do not add new misordering.
- In `Libraries`, bold the language name in the description (`**Python**`).
- A description may not be empty; a handful of legacy entries use `: Description` instead of ` Description`.
- New `<h2>` section → also add the entry to the Table of Contents, and close the section with a `---` line then `</details>`.
- New `<h3>` subsection → wrap it in blank lines, like the existing ones.

Then mirror the change into `README.zh-CN.md`: same position, same project name and URL byte-for-byte (project names are proper nouns and are **not** translated), translated description.

### Section and heading shape

```markdown
<details open><summary><h2>Section Name</h2></summary>

- [Name](url) Description

---

</details>
```

Headings live *inside* `<summary>`, so GitHub derives the TOC anchor from the heading text. `README.zh-CN.md` declares the anchors explicitly with `<a id="..."></a>` before each `<details>` so both languages share anchor names (`#dockerlxck8s`, `#file-managers`, …).

## Contribution rules

From `.github/pull_request_template.md`:

- Repos must be **at least 6 months old**.
- Applications should be unique.
- Interfaces should be unique — no wrappers of other interactive commands (e.g. `fzf`).
- Interfaces must be interactive or re-draw output; **output formatters are not TUIs**.

PR titles follow `Add <name> to <Section>`. Commits land via squash merge.

## Conventions

- Upstream is `rothgar/awesome-tuis`; the local `origin` remote is a GitCode mirror.
- Content PRs touch `README.md` (and now `README.zh-CN.md`) only. Never edit `.github/workflows/` or the scripts to make a check pass.
- Keep the Chinese file's section order and entry order identical to the English one — that is what makes the two diffable line by line.
