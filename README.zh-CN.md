<h1 align="center">
  <code>Awesome TUIs</code>
</h1>

[English](README.md) | [简体中文](README.zh-CN.md)

这是一份由社区共同维护的 TUI 应用清单。TUI 应用运行在终端里，并具备一定程度的交互能力。本清单收录的命令不应当只是对其他交互式命令的封装（例如 `fzf`），并且需要有人持续维护。

我为这份清单中自己最喜欢的 TUI 拍了一段视频（每个章节挑一个）。点击图片即可观看。👇

[![](https://i.ytimg.com/vi/_fLmA4fjiAE/maxresdefault.jpg)](https://youtu.be/_fLmA4fjiAE?si=IgXuo)

这里有很多很棒的项目，我与它们并无任何关联。请自行承担使用风险。如果你有想分享的好工具，欢迎 [提交 PR](https://github.com/rothgar/awesome-tuis/pulls)。

## 目录

- [AI 智能体](#ai-agents)
- [仪表盘](#dashboards)
- [开发工具](#development)
- [Docker/LXC/K8s](#dockerlxck8s)
- [编辑器](#editors)
- [文件管理器](#file-managers)
- [游戏](#games)
- [库](#libraries)
- [消息通讯](#messaging)
- [杂项](#miscellaneous)
- [多媒体](#multimedia)
- [效率工具](#productivity)
- [屏保](#screensavers)
- [网页](#web)

<a id="ai-agents"></a>
<details open><summary><h2>AI 智能体</h2></summary>

- [AgenC Core](https://github.com/tetsuo-ai/agenc-core) 开源的 AI 编程智能体，带终端界面，可对接任意模型供应商
- [agent-deck](https://github.com/asheshgoplani/agent-deck) 用于管理多个 AI 编程智能体会话的终端仪表盘
- [amux](https://github.com/andyrewlee/amux) 轻松并行运行多个编程智能体
- [Brief](https://github.com/WilliamAGH/brief) 终端优先的 OpenAI 聊天客户端，支持斜杠命令面板和本地工具执行。
- [Claude Code Bridge](https://github.com/SeemSeam/claude_codex_bridge) Claude、Codex 与 Gemini 在终端中实时协同
- [Claude Code Usage Monitor](https://github.com/Maciek-roboblog/Claude-Code-Usage-Monitor) 监控 Claude 的 token 用量
- [clausona](https://github.com/larcane97/clausona) 在 Claude Code 与 Codex 账号之间切换并保留对话历史，按套餐用量分流运行，管理各账号的技能、MCP 服务器与钩子
- [codex](https://github.com/openai/codex) 运行在终端里的轻量级编程智能体
- [crush](https://github.com/charmbracelet/crush) 极具魅力的 AI 编程智能体
- [elia](https://github.com/darrenburns/elia) 用 Textual 打造的终端 ChatGPT 客户端
- [fast-resume](https://github.com/angristan/fast-resume) 为编程智能体会话建立索引并支持模糊搜索
- [hcom](https://github.com/aannoo/hcom) 在多个终端间对 AI 编程智能体（Claude Code、Antigravity、Codex、OpenCode、Kilo、Cursor）进行实时消息互通、观察与编排的 CLI 与 TUI
- [Keen Code](https://github.com/mochow13/keen-code) 一个具备上下文感知的终端 AI 编程智能体，用 Go 编写，支持多种模型提供方、MCP、多个子智能体、智能体技能、可控的工具输出保留以及哈希行编辑
- [lilbee](https://github.com/tobocop2/lilbee) 本地模型引擎，内置搜索引擎与网络爬虫：结合文件、笔记、代码与已抓取的站点进行对话，答案会标注出处所在行
- [llm-cost-dashboard](https://github.com/Mattbusel/llm-cost-dashboard) 为 OpenAI、Anthropic 和 Claude Code 日志中的每一次 LLM API 调用计价，提供预算、月末预测与成本异常告警
- [models](https://github.com/reyamira/models) 用于浏览 AI 模型与编程智能体的 TUI
- [Neuron](https://github.com/RAHUL-DevelopeRR/neuron-v2) 开源 AI 编程智能体，全屏终端界面，支持读取、编辑和测试代码，并带有权限提示
- [opencode](https://github.com/anomalyco/opencode) 为终端打造的 AI 编程智能体
- [qmax-code](https://github.com/Quality-Max/qmax-code) 专注于 QA 的 AI 终端智能体，用 Go 编写，附带独立的仓库工作流，并可选集成 QualityMax。
- [Quorum](https://github.com/Detrol/quorum-cli) 多智能体 AI 讨论系统，用结构化辩论的形式让多个大模型协同
- [SpurCode](https://github.com/getspur/SpurCode) Rust TUI 控制塔，把任务拆解为 DAG 计划，并在相互隔离的 git worktree 中编排一整支编程智能体队伍（Claude Code、Codex、Gemini、Kimi、OpenCode、ACP）
- [SynapsCLI](https://github.com/HaseebKhalid1507/SynapsCLI) 终端原生 AI 智能体运行时，支持并行子智能体、可共享的守护进程会话，以及从 Claude 到本地 Ollama 的任意模型
- [tenere](https://github.com/pythops/tenere) 用 Rust 编写的 ChatGPT TUI。
- [Toad](https://github.com/batrachianai/toad) 一个统一的 AI 交互界面
- [VT Code](https://github.com/vinhnx/vtcode) VT Code —— 语义化编程智能体

---

</details>

<a id="dashboards"></a>
<details open><summary><h2>仪表盘</h2></summary>

- [AdGuardian-Term](https://github.com/lissy93/AdGuardian-Term) 用于监控 AdGuard Home 实例实时流量的 TUI 仪表盘
- [ADSB-TUI](https://github.com/WPTK/ADSB-TUI) 观测你自己的 readsb 或 dump1090-fa 接收器收到的飞机，可排序的表格搭配雷达显示
- [apachetop](https://github.com/tessus/apachetop) 显示正在运行的 Apache 实例状态。
- [atop](https://github.com/Atoptool/atop/) 面向 Linux 的 root 级系统与进程监控器
- [Backlog.md](https://github.com/MrLesk/Backlog.md) 在 git 生态中管理人与 AI 智能体协作项目的工具
- [bandwhich](https://github.com/imsnif/bandwhich) 终端带宽占用工具
- [bashtop](https://github.com/aristocratos/bashtop) 用 bash 编写的资源管理器
- [below](https://github.com/facebookincubator/below) 面向现代 Linux 系统的时旅行资源监控器
- [binsider](https://github.com/orhun/binsider) 用于分析 Linux 二进制文件的 TUI。
- [bmon](https://github.com/Jafaral/bmon) 捕获并可视化网络相关统计数据的监控与调试工具。
- [bottom](https://github.com/ClementTsang/bottom) 可自定义的图形化终端进程/系统监控器。
- [bpytop](https://github.com/aristocratos/bpytop) 功能丰富的 Python 系统监控器。
- [btop++](https://github.com/aristocratos/btop) 带有额外功能的资源监控器
- [bullmq-dash](https://github.com/quanghuynt14/bullmq-dash) 用于管理 BullMQ 队列、检视任务并重试失败的仪表盘
- [cgdb](https://github.com/cgdb/cgdb) GNU 调试器的前端控制台
- [chdig](https://github.com/azat/chdig) 带 TUI 界面的 ClickHouse 交互工具
- [cheatshh](https://github.com/AnirudhG07/cheatshh) 管理自定义 Unix 命令速查表的 fzf TUI。
- [claws](https://github.com/clawscli/claws) 用于管理 AWS 资源的终端界面，支持 vim 风格快捷键、命令模式导航与只读模式。
- [CoreFreq](https://github.com/cyring/CoreFreq) 面向 64 位处理器的 CPU 监控软件
- [cronstable](https://github.com/ptweezy/cronstable) 作业调度器，带实时终端仪表盘，展示作业状态、日志、运行历史、工作流与集群健康度
- [csysdig](https://github.com/draios/sysdig) 面向 sysdig 的 root 级 Ncurses 界面，深入探索 Linux 系统并对容器提供一流支持
- [damon](https://github.com/hashicorp/damon) Hashicorp Nomad 的 TUI 界面
- [dashbrew](https://github.com/rasjonell/dashbrew) 通过脚本与 API 构建的 TUI 仪表盘搭建器。
- [dolphie](https://github.com/charles-001/dolphie) 汇聚 MySQL/MariaDB 与 ProxySQL 实时分析数据的单屏界面
- [dynamite](https://github.com/wolfwfr/dynamite) 面向 Amazon DynamoDB 的 TUI 查询引擎，细节体验出色。
- [flowrs](https://github.com/jvanbuel/flowrs) 用于监控、检查与管理 Apache Airflow DAG 的 TUI
- [framework-tool-tui](https://github.com/grouzen/framework-tool-tui) 用 Rust 编写的、用于控制与监控 Framework Computers 硬件的 TUI
- [fubar](https://github.com/irishmaestro/fubar) 气势十足的 Unix 二进制军火库。基于 TUI 打造，专为 gtfobins 重度用户设计。
- [gh-dash](https://github.com/dlvhdr/gh-dash) 面向 GitHub PR 与 Issue 的功能丰富终端界面
- [Glances](https://github.com/nicolargo/glances) 一览系统状况的 Glances，top/htop 的替代品。
- [Gloomberb](https://github.com/gloom-sh/gloomberb) 开源金融终端，涵盖投资组合、观察列表、图表、新闻、研究与券商连接。
- [Goaccess](https://github.com/allinurl/goaccess) GoAccess 是一款实时 Web 日志分析器与交互式查看器，可在 nix 系统终端中或通过浏览器使用。
- [gobang](https://github.com/TaKO8Ki/gobang) 用 Rust 编写的跨平台 TUI 数据库管理工具
- [gonzo](https://github.com/control-theory/gonzo) 灵感源自 k9s 的强大实时日志分析终端界面
- [gotop](https://github.com/xxxserxxx/gotop) 灵感源自 gtop 与 vtop 的终端图形化活动监控器
- [gping](https://github.com/orf/gping) 带图形的 ping
- [Grafterm](https://github.com/slok/grafterm) 面向终端的 Grafana 风格指标仪表盘
- [htop](https://github.com/htop-dev/htop) 面向 Unix 系统的交互式文本模式进程查看器，目标成为更好的 top
- [htui](https://github.com/PierreKieffer/htui) Heroku 终端用户界面
- [hwatch](https://github.com/blacknon/hwatch) watch 的现代替代品，记录命令输出历史并提供交互式差异对比、滚动、过滤、JSON 日志与钩子。
- [hwinfo-tui](https://github.com/JuanjoFuchs/hwinfo-tui) 借鉴 gping 的终端可视化工具，用于监控 HWInfo 提供的实时硬件传感器数据
- [ID-Spoofer](https://github.com/NubleX/ID-Spoofer) 面向跨平台的网络安全工具包，可对指纹与流量进行混淆。
- [kaskade](https://github.com/sauljabin/kaskade) 用于消费与管理 Kafka topic 的 TUI，用起来非常顺手！
- [kmon](https://github.com/orhun/kmon) Linux 内核管理器与活动监控器
- [Kyanos](https://github.com/hengyoush/kyanos) 基于 eBPF 的 Linux 网络分析工具
- [lazyslurm](https://github.com/hill/lazyslurm) 风格类似 lazygit 的 Slurm 终端界面。监控作业、跟踪日志、检视节点与分区。
- [ls-horizons](https://github.com/litescript/ls-horizons) 在终端中实时可视化 NASA 深空网络
- [macmon](https://github.com/vladkens/macmon) 面向 Apple Silicon 且无需 sudo 的性能监控工具，用 Rust 编写
- [metropolis](https://github.com/5c0/metropolis) 赛博朋克风系统监控器，把内核指标变成会呼吸的终端天际线
- [nerdlog](https://github.com/dimonomid/nerdlog) 快速、远程优先的多主机 TUI 日志查看器
- [nethogs](https://github.com/raboof/nethogs) 类似 net top 的工具
- [netscanner](https://github.com/Chleba/netscanner) 网络扫描器
- [nvtop](https://github.com/Syllo/nvtop) 用于监控 AMD、Intel 与 NVIDIA GPU 的进程占用
- [oryx](https://github.com/pythops/oryx) 基于 eBPF 的终端流量嗅探 TUI
- [otel-tui](https://github.com/ymtdzzz/otel-tui) 终端版 OpenTelemetry 查看器
- [process-compose](https://github.com/F1bonacc1/process-compose) 用于运行应用与进程的 TUI
- [prt](https://github.com/rekurt/prt) 交互式网络端口监控器，附带进程详情与 SSH 隧道检视，支持 macOS 与 Linux。
- [psmux](https://github.com/psmux/psmux) 用 Rust 结合 ratatui 实现的、兼容 tmux 的 Windows 终端多路复用器。
- [psnet](https://github.com/psmux/psnet) 面向 Windows 的实时 TUI 网络监控器，支持速率图表、DNS 解析与数据包检视。
- [pstop](https://github.com/psmux/pstop) 风格类似 htop 的 Windows 系统监控器，提供每核心 CPU 条形图、树形视图与 7 套配色方案。
- [Puffin](https://github.com/siddhantac/puffin) 漂亮的 hledger 终端仪表盘
- [Raijin](https://github.com/MasonStooksbury/Raijin) 免费易用的天气 TUI，无需 API key、账号或订阅即可获取数据
- [RunWisp](https://github.com/runwisp/runwisp) 定时任务管理器与进程守护器，带 TUI 实时输出与运行历史
- [rustnet](https://github.com/domcyrus/rustnet) 跨平台网络监控工具，支持深度包检测
- [s-tui](https://github.com/amanusk/s-tui) CPU 压力与监控工具
- [sacha](https://github.com/Sachamama/sacha) 双栏 AWS TUI，可浏览、搜索并管理七类服务上的资源，包括 CloudWatch Logs、S3、DynamoDB、Lambda、SSM、SQS 与 EC2。
- [ServerHub](https://github.com/nickprotop/ServerHub) 面向 Linux 的 TUI 服务器监控仪表盘，提供实时指标、可脚本化组件与远程管理
- [Servonaut](https://github.com/zb-ss/servonaut) 用于管理 AWS、Hetzner、OVH 及自定义 SSH 服务器的 TUI，支持日志查看、CloudWatch/CloudTrail 浏览、IP 封禁、AI 日志分析与内置 MCP 服务器
- [sockttop](https://github.com/jasonwitty/socktop) socktop 是一款远程系统监控器，拥有丰富的 TUI，灵感来自 top/btop，通过 WebSockets 与轻量级 agent 通信。
- [sysz](https://github.com/joehillen/sysz) 面向 systemctl 的 fzf 终端界面
- [talos linux](https://github.com/siderolabs/talos) 带有 TUI 仪表盘的 Linux 发行版，支持本地与远程使用
- [tdash](https://github.com/jessfraz/tdash) 汇集 Google Analytics、GitHub、Travis CI 与 Jenkins 数据的终端仪表盘。基本是按我个人需求定制的。
- [tegratop](https://github.com/pythops/tegratop) 面向 Nvidia Jetson 系列的监控工具（类 top）
- [TermUI](https://github.com/gizak/termui) 用 Golang 编写的终端仪表盘
- [ticker](https://github.com/achannarasappa/ticker) 在终端中实时跟踪股票、加密货币与衍生品的价格和持仓
- [tmd-top](https://github.com/CDWEN0526/tmd-top) 用于监控 Linux 系统进程 TCP 流量的工具，细化到每个 IP 连接
- [topic](https://github.com/yurirocha15/topic) 容器内部的 top：按容器的 cgroup 限额（而非宿主机）显示 CPU、内存、GPU、磁盘、网络与进程用量
- [toptop](https://github.com/ur-grue/toptop) htop/btop 级系统监控器，附本地 LLM 视角：每秒 token 数、显存溢出与内存带宽判定，支持 NVIDIA 与 Apple Silicon
- [trek](https://github.com/franckverrot/trek) 用于浏览 Hashicorp Nomad 集群的 ncurses 资源管理器
- [trippy](https://github.com/fujiapple852/trippy) 网络诊断工具，功能类似 mtr 且更进一步
- [ttl](https://github.com/lance0/ttl) 快速、现代的 traceroute，带实时 TUI、逐跳统计与 ASN/地理查询
- [ttop](https://github.com/inv2004/ttop) 带历史数据服务、触发器与类 top TUI 的系统监控工具
- [tufw](https://github.com/peltho/tufw) ufw 的终端界面
- [tuicamp](https://github.com/AbeEstrada/tuicamp) 非官方的 TimeCamp TUI
- [unifly](https://github.com/hyperb1iss/unifly) 面向 Ubiquiti UniFi 网络的 CLI 与 TUI，含实时流量图表、拓扑、客户端与防火墙管理
- [updo](https://github.com/Owloops/updo) 网站监控工具，提供可用性追踪、响应时间指标与 SSL 证书监控。
- [wander](https://github.com/robinovitch61/wander) HashiCorp Nomad 终端客户端
- [WTF](https://github.com/wtfutil/wtf) 属于你自己的终端个人仪表盘。
- [Yozefu](https://github.com/MAIF/yozefu) 用于探索 Kafka 集群数据的 TUI。
- [zenith](https://github.com/bvaisvil/zenith) 用 Rust 编写的、面向 *nix 系统的终端图形化指标工具

---

</details>

<a id="development"></a>
<details open><summary><h2>开发工具</h2></summary>

- [act3](https://github.com/dhth/act3) 一眼查看最近 3 次 Github Actions 运行结果
- [amtui](https://github.com/pehlicd/amtui/) Alertmanager TUI —— 你的 Alertmanager 终端伴侣
- [ATAC](https://github.com/Julien-cpsn/ATAC) 用 Rust 编写的功能完备 TUI API 客户端。ATAC 免费、开源、可离线使用且无需账号。
- [austin-tui](https://github.com/P403n1x87/austin-tui) 面向 Austin 的类 top 文本用户界面
- [blinkenlights](https://github.com/jart/blink) 可跨平台用于调试 x86_64-linux 或 i8086 程序的 TUI
- [brows](https://github.com/rubysolo/brows) 用于浏览 GitHub 发行版的 CLI
- [burf](https://github.com/razeghi71/burf) 面向 Google Cloud Storage (GCS) 的 TUI
- [cargo-seek](https://github.com/tareqimbasher/cargo-seek) 用于搜索、添加和安装 cargo crate 的 TUI
- [catalyst](https://github.com/PraveenGongada/catalyst) 优雅的 TUI，可按矩阵配置触发 GitHub Actions 工作流。
- [chiko](https://github.com/felangga/chiko) 终极美观的 TUI gRPC 客户端
- [Close Mongo Ops Manager](https://github.com/closeio/close-mongo-ops-manager) 监控并终止 MongoDB 操作
- [Cloudeval](https://github.com/ganakailabs/cloudeval-cli) 交互式云端评估与评审，带项目上下文、报告视图与对话会话。支持 Azure 和静态 AWS CloudFormation（beta）；需要 Cloudeval 账号。
- [cnTUI](https://github.com/fipso/cntui) 在终端中用 curl 重放 Chrome 请求
- [csope](https://github.com/agvxov/csope) 基于 cscope 的 C 源代码浏览器
- [dbee](https://github.com/murat-cileli/dbee) 快速且极简的数据库浏览器
- [dblab](https://github.com/danvergara/dblab) 每个命令行爱好者都值得拥有的数据库客户端
- [dbterm](https://github.com/shreyam1008/dbterm) 支持 PostgreSQL、MySQL、SQLite、Turso 与 Cloudflare D1 的终端数据库工作台
- [ddqa](https://github.com/DataDog/ddqa) 辅助软件发布的 Jira TUI
- [ddv](https://github.com/lusingander/ddv) 终端 DynamoDB 查看器
- [delta](https://github.com/dandavison/delta) 为 git、diff 与 grep 输出提供语法高亮的分页器
- [deputui](https://github.com/twiddler/deputui) 审阅并安装 NPM 包更新
- [DevProjex](https://github.com/Avazbek22/DevProjex) 跨平台 TUI，用于浏览项目树、选择文件、预览可供 AI 使用的上下文，并导出结构化的代码库快照。
- [differ](https://github.com/JanSmrcka/differ) 用于查看 git diff 的 TUI
- [ec](https://github.com/chojs23/ec) 三栏式原生 Git 合并工具 TUI
- [euporie](https://github.com/joouha/euporie) 运行在终端中的 Jupyter notebook
- [every-other-token](https://github.com/Mattbusel/Every-Other-Token) 流式输出 LLM 响应，并按模型置信度为每个 token 着色，全屏展示困惑度与最可能的候选
- [Feluda](https://github.com/anistark/feluda) 检测项目所有依赖中受限且不兼容的许可证。
- [Froggit](https://github.com/thewizardshell/froggit) 集成 GitHub CLI 的极简 Git TUI
- [fx](https://github.com/antonmedv/fx) 终端 JSON 查看与处理工具
- [ggc](https://github.com/bmf-san/ggc) 用 Go 编写的终端版 Git CLI 工具
- [gh-enhance](https://github.com/dlvhdr/gh-enhance) 速度飞快的 GitHub Actions 终端界面
- [git-crecord](https://github.com/andrewshadura/git-crecord) 交互式选择性提交工具
- [git-scope](https://github.com/Bharath-code/git-scope) 用于检视多个本地 Git 仓库的终端仪表盘。
- [git-tailor](https://github.com/jordfras/git-tailor) 交互式终端工具，用于整理分支上的 Git 提交
- [gitui](https://github.com/gitui-org/gitui) 用 Rust 编写的、速度飞快的 git 终端界面
- [gitv](https://github.com/jayanaxhf/gitv): 漂亮、功能丰富且性能出色的 GitHub Issue 终端客户端。
- [gitwig](https://github.com/tareqmy/gitwig) —— 用 Rust 构建的、支持鼠标操作的 git TUI 与多仓库仪表盘。
- [grv](https://github.com/rgburke/grv) 用于查看 git 仓库的终端界面
- [harlequin](https://github.com/tconbeer/harlequin) 属于你的终端的 SQL IDE
- [heretek](https://github.com/wcampbell0x2a/heretek) GDB TUI 仪表盘
- [jqp](https://github.com/noahgorstein/jqp) 用于体验 jq 的 TUI  playground
- [lazygit](https://github.com/jesseduffield/lazygit) 用于 git 命令的简洁终端界面
- [lazyjournal](https://github.com/Lifailon/lazyjournal) 用于 journalctl、文件系统日志以及 Docker 与 Podman 容器的 TUI，方便快速查看与过滤
- [lazymake](https://github.com/rshelekhov/lazymake) 现代的 Makefile TUI，支持交互式目标选择、依赖可视化与命令安全性分析。
- [lazysql](https://github.com/jorgerojas26/lazysql) 用 Go 编写的跨平台 TUI 数据库管理工具。
- [lean-tui](https://codeberg.org/wvhulle/lean-tui) 交互式可视化 Lean4 证明助手中编写的证明与程序
- [LogLens](https://github.com/Caelrith/loglens-core) 面向终端的结构化日志查看器与查询引擎。
- [logradar](https://github.com/nanook72/logradar) 用 Rust 编写的快速 TUI，用于交互式日志过滤与高亮。
- [logshark](https://github.com/ugosan/logshark) 用 Go 编写的 JSON 日志调试 CLI
- [mitmproxy](https://www.mitmproxy.org) 免费开源的交互式 HTTPS 代理
- [nap](https://github.com/maaslalani/nap) 在终端里随手记代码片段
- [nodebro](https://github.com/jonaburg/nodebro) 在终端中轻松查看最新的 Github 发行版/标签与发布说明
- [opcilloscope](https://github.com/SquareWaveSystems/opcilloscope) OPC UA 客户端 TUI，带实时示波器视图，面向工业自动化
- [pho](https://github.com/utkarsh261/pho) 在终端中审阅、评论并合并 GitHub PR
- [play](https://github.com/paololazzari/play) 用于体验 grep、sed、awk、jq、yq 等常用程序的 TUI playground
- [postbear](https://github.com/carban/postbear) Postbear 是一款高速轻量的 API 客户端，相当于终端里的 Postman
- [posting](https://github.com/darrenburns/posting) 住在你终端里的强大 HTTP 客户端
- [pproftui](https://github.com/Oloruntobi1/pproftui) 面向 Go pprof 的终端界面，让性能分析变得可交互
- [proxelar](https://github.com/emanuele-em/proxelar) 可脚本化的 MITM 代理 TUI，用于检视、拦截、重放与改写 HTTP(S) 及 WebSocket 流量
- [proxymock](https://proxymock.io) 网络录制器，可在 TUI 中展示 API 载荷，并自动根据观测结果生成测试与 mock。
- [prs](https://github.com/dhth/prs) 不离开终端也能掌握 PR 进展
- [pudb](https://github.com/inducer/pudb) 基于控制台的 Python 可视化调试器
- [pyautogit](https://github.com/jwlodek/pyautogit) 用 py_cui 编写的 git 仓库管理终端界面
- [qo](https://github.com/kiki-ki/go-qo) 面向 JSON、CSV、TSV 等数据流的交互式 SQL 过滤器。
- [qrypad](https://github.com/wheelibin/qrypad) 属于你的终端的快速 SQL 草稿本。
- [rainfrog](https://github.com/achristmascarl/rainfrog) 用 Rust 编写的、支持 Postgres、MySQL 与 SQLite 的数据库管理 TUI
- [raygun](https://github.com/yetidevworks/raygun) Spatie Ray 调试器的终端接收端，协议与桌面端相同，支持 PHP、Laravel 与 Grav
- [regex-tui](https://github.com/vitor-mariano/regex-tui) 用于可视化与测试正则表达式的简易 TUI
- [resterm](https://github.com/unkn0wn-root/resterm) 支持 HTTP/GraphQL/gRPC 的终端客户端，涵盖 WebSocket、SSE、工作流、性能分析、OpenAPI 与响应差异对比。
- [runme](https://github.com/runmedev/runme) 直接从 README.md 或其他 markdown 中发现并运行代码片段
- [sabiql](https://github.com/riii111/sabiql) 快速、无需驱动、Vim 优先的数据库 TUI，支持安全编辑与 ER 图。
- [scope](https://github.com/matheuswhite/scope-rs) 跨平台串口与 RTT 监控器，带彩色时间戳 I/O、十六进制/@tag 输入宏、搜索、会话录制、自动重连与 Lua 插件
- [serie](https://github.com/lusingander/serie) 精美的 git 提交图谱
- [sls-dev-tools](https://github.com/aleios-cloud/sls-dev-tools) 面向 Serverless 世界的开发工具
- [snips.sh](https://github.com/robherley/snips.sh) ✂️ 无密码、匿名的 SSH 驱动 pastebin，配有友好的 TUI 与网页界面
- [sot](https://github.com/anistark/sot) 用 Python 编写的类 top 系统可观测性工具
- [sq](https://github.com/sheenazien8/sq) 专为 vim 用户打造的数据库客户端
- [sqlit](https://github.com/Maxteabag/sqlit) 灵感来自 lazygit 的轻量级 SQL 数据库 TUI
- [sshs](https://github.com/quantumsheep/sshs) SSH 的终端用户界面
- [stu](https://github.com/lusingander/stu) 面向 Amazon S3 的 TUI
- [termdbms](https://github.com/mathaou/termdbms) 用于查看和编辑数据库文件的 TUI。
- [terraform-tui](https://github.com/idoavrah/terraform-tui) 查看并操作 Terraform 状态
- [therapist](https://github.com/M-Komorek/therapist) —— 面向数 GB 大文件的轻量级 TUI 日志查看器，支持书签、grep 标签页与短语高亮。
- [tig](https://github.com/jonas/tig) git 的文本模式界面
- [tokui](https://github.com/zdyxry/tokui) 用于可视化 tokei 代码统计的交互式 TUI。
- [toolui](https://github.com/jinek/ToolUI) 用于管理已安装 nuget 工具的 .NET core 应用程序
- [turbostream](https://github.com/turboline-ai/turbostream) 借助 AI 智能体从高速流式数据中提取关键信号的工具
- [Twig](https://github.com/workdone0/twig) 用于交互式浏览 JSON 与 YAML 文件的终端界面。
- [vctui](https://github.com/thebsdbox/vctui) vCenter 的控制台界面
- [violet](https://github.com/braheezy/violet) 运行 Vagrant 命令的彩色 TUI 前端
- [Wikit](https://github.com/BryanCE/wikit) 管理 Wiki.js 实例的 TUI
- [y509](https://github.com/kanywst/y509) 检视 X.509 证书链，揪出那些让 curl 报错而浏览器却无所谓的缺失中间证书
- [ygrep](https://github.com/yetidevworks/ygrep) 快速、本地、带索引的代码搜索 TUI，基于 Tantivy 全文索引，为 AI 编程助手而优化
- [zlodev](https://github.com/vandot/zlodev) 本地开发 HTTPS 大门：支持 `*.lo` 域名与真实证书、多应用路由，以及用于检视、拦截和重放流量的 TUI

---

</details>

<a id="dockerlxck8s"></a>
<details open><summary><h2>Docker/LXC/K8s</h2></summary>

- [Argonaut](https://github.com/darksworm/argonaut) ArgoCD TUI
- [cruise](https://github.com/cruise-org/cruise) 容器管理 TUI
- [ctop](https://github.com/bcicen/ctop) 类 top 的容器指标界面
- [d4s](https://github.com/jr-k/d4s) 快速、键盘驱动的终端界面，以 K9s 的手感管理 Docker 容器、Compose 栈与 Swarm 服务
- [dive](https://github.com/wagoodman/dive) 用于逐层探索 docker 镜像的工具
- [docker-dash](https://github.com/GustavoCaso/docker-dash) 功能完整的 Docker 管理 TUI 工具
- [dockly](https://github.com/lirantal/dockly) 沉浸式的 docker 容器与服务管理终端界面
- [DockMate](https://github.com/shubh-io/dockmate) 轻量级的 Docker 与 Podman TUI 管理器
- [dockup](https://github.com/paulo-amaral/dockup) 一条命令完成 Docker、Podman、NVIDIA 工具包与 Apple 容器环境的安装、加固与维护
- [dprs](https://github.com/durableprogramming/dprs) 用于管理 Docker 容器的 TUI，提供实时监控与日志流
- [dry](https://github.com/moncho/dry) 面向终端的 Docker 管理器
- [dtop](https://github.com/amir20/dtop) 跨多主机监控 Docker 的终端仪表盘
- [ducker](https://github.com/robertpsoane/ducker) 基于 k9s 的、有点"嘎嘎"风的 Docker TUI
- [e1s](https://github.com/keidarcy/e1s) 用于管理 AWS ECS 资源的 TUI
- [eks-node-viewer](https://github.com/awslabs/eks-node-viewer/) 可视化 kubernetes 集群内节点的动态用量
- [etcd-walker](https://github.com/nexusriot/etcd-walker/) 管理 etcd 键值的开源 TUI 工具
- [k8s-tui](https://github.com/otavioCosta2110/k8s-tui) 支持多集群的 Kubernetes 资源管理 TUI
- [k9s](https://github.com/derailed/k9s) 管理 Kubernetes 集群的 TUI
- [kdash](https://github.com/kdash-rs/kdash) 简洁快速的 Kubernetes 仪表盘
- [kftui](https://github.com/hcavarsan/kftray) 用于管理多条 kubectl port-forward 命令的 TUI，支持 UDP 与 K8s 代理。
- [ktop](https://github.com/vladimirvivien/ktop) 面向 Kubernetes 集群的类 top 工具
- [kubetui](https://github.com/sarub0b0/kubetui) 专为监控 Kubernetes 资源设计的 TUI 工具。
- [layerx](https://github.com/deveshctl/layerx) 在交互式 TUI 中检视容器镜像分层，支持文件系统差异对比、内联文件查看与文件提取；兼容 Docker、Podman 与 OCI 归档
- [lazycontainer](https://github.com/andreybleme/lazycontainer) 管理 Apple 容器的 TUI
- [lazydocker](https://github.com/jesseduffield/lazydocker) 更省力地管理 docker 的一切
- [lazytrivy](https://github.com/owenrumney/lazytrivy) 用 Trivy 更省力地扫描镜像、k8s 与文件系统
- [lfk](https://github.com/janosmiko/lfk) 以键盘为中心、灵感来自 yazi 的 Kubernetes 导航器，采用 Miller 分栏布局与基于 owner 的资源层级
- [oxker](https://github.com/mrjackwills/oxker) 用于查看和控制 docker 容器的简易 TUI
- [Pocker](https://github.com/pommee/Pocker) 基于 TUI 的 docker 相关任务处理应用。
- [Podman-tui](https://github.com/containers/podman-tui) Podman 容器的 TUI
- [sen](https://github.com/TomasTomecek/sen) docker engine 的终端用户界面
- [SwarmCLI](https://github.com/Eldara-Tech/swarmcli) 思维般疾速的 Swarm 管理 —— 实时日志流、瞬时进入容器 shell、无缝端口转发、按需查看密钥，让你完整掌控 Docker Swarm 而不打断工作流。
- [talos-pilot](https://github.com/handfish/talos-pilot) 面向 Talos Linux 的 TUI，提供实时节点监控、日志流与多种诊断手段

---

</details>

<a id="editors"></a>
<details open><summary><h2>编辑器</h2></summary>

- [amp](https://github.com/jmacdonald/amp) 面向终端的完整文本编辑器
- [C-Edit](https://github.com/velorek1/c-edit) 风格仿照 MS-DOS Editor、带有下拉菜单的文本编辑器
- [Durdraw](https://github.com/durdraw/durdraw) 支持 ASCII、Unicode 与 ANSI 艺术创作的编辑器
- [edamame](https://github.com/mijowi/edamame) 边编辑边保持渲染的终端 Markdown 编辑器
- [Edit](https://github.com/microsoft/edit) 简洁的文本编辑器，向经典 MS-DOS Editor 致敬。
- [flow-control](https://github.com/neurocyte/flow) 用 Zig 编写的、闪电般快速且功能丰富的文本编辑器
- [Fresh](https://github.com/sinelaw/fresh) 易用、强大且快速的终端文本编辑器。
- [frogmouth](https://github.com/Textualize/frogmouth) 面向终端的 Markdown 浏览器
- [hake](https://github.com/mithraeums/hako-edit) 单文件 C 实现的 Vim 风格模态编辑器，侧边栏内置 AI 智能体
- [helix](https://helix-editor.com/) 后现代文本编辑器。
- [hexed](https://codeberg.org/quorend/hexed) （又一个）十六进制编辑器。
- [kakoune](http://kakoune.org/) 现代模态文本编辑器，强调交互性与效率
- [kilo](https://github.com/antirez/kilo) 约 1000 行 C 代码实现的极简但完整的编辑器。
- [lazyide](https://github.com/TysonLabs/lazyide) 用 Rust 编写的轻量级终端 IDE：文件树、标签页、分栏、LSP、git diff 视图、缩略图、32 套主题
- [maki](https://sr.ht/~bscit/maki/) 简洁的标签页式文本编辑器，支持文件导航并着重延长电池续航
- [markln](https://github.com/xqtr/markln) 用 Textual 构建的终端 Markdown 编辑器。
- [micro](https://github.com/micro-editor/micro) 现代且直观的终端文本编辑器
- [nino](https://github.com/evanlin96069/nino) 用 C 编写的迷你终端文本编辑器。
- [orbiton](https://github.com/xyproto/orbiton) 受限于 VT100 的文本编辑器，适合编程、撰写 git commit 信息与编辑 Markdown
- [PNANA](https://github.com/Cyxuan0311/PNANA) 用 FTXUI 构建的现代终端文本编辑器，灵感来自 Nano、Micro 与 Sublime Text。
- [slap](https://github.com/slap-editor/slap) 风格类似 Sublime 的终端文本编辑器
- [thymus](https://github.com/blademd/thymus) 用于交互式浏览与编辑网络配置文件的工具。
- [tilde](https://github.com/gphalkes/tilde) 直观的终端文本编辑器
- [treemd](https://github.com/Epistates/treemd) 基于树形结构导航的 markdown 导航器
- [turbo](https://github.com/magiblot/turbo) 实验性终端文本编辑器，基于 Scintilla 与 Turbo Vision
- [vis](https://github.com/martanne/vis) 基于 Plan 9 结构化正则表达式的类 vi 编辑器
- [zee](https://github.com/zee-editor/zee) 用 Rust 编写的现代终端文本编辑器

---

</details>

<a id="file-managers"></a>
<details open><summary><h2>文件管理器</h2></summary>

- [adbtuifm](https://github.com/darkhz/adbtuifm) 基于 Android Debug Bridge (ADB) 的 Android TUI 文件管理器。
- [broot](https://github.com/Canop/broot) 探索与浏览目录树的全新方式
- [deletor](https://github.com/pashkov256/deletor) 通过交互式 TUI 与可脚本化 CLI 高效管理和删除文件。
- [elio](https://github.com/elio-fm/elio) 干净利落、开箱即用的终端文件管理器。
- [far2l](https://github.com/elfmz/far2l) Far v2 文件管理器的 Linux 移植版
- [FileView](https://github.com/Hiro-Chiba/fileview) 带图片预览、Git 状态、搜索与 MCP 服务器的终端文件浏览器。
- [fml](https://github.com/wick3dr0se/fml) :file_folder: 用 BASH v4.2+ 编写的简单粗暴但速度飞快的文件管理器。
- [fyzenor](https://github.com/Bimbok/fyzenor) 用 C++ 构建的现代、疾速终端文件管理器，具备实时预览、异步工作流与精致的三栏界面。
- [goful](https://github.com/anmitsu/goful) 用 Go 编写的强大 TUI 文件管理器。
- [lf](https://github.com/gokcehan/lf) 用 Go 编写的终端文件管理器，大量借鉴 ranger 文件管理器。
- [mc](https://github.com/MidnightCommander/mc) GNU Midnight Commander。自由跨平台的正统文件管理器。
- [nnn](https://github.com/jarun/nnn) n³ 非正统终端文件管理器。
- [ntc](https://codeberg.org/ItsZariep/ntc) 基于 Ncurses 的标签页式文件选择器。
- [ranger](https://github.com/ranger/ranger) 灵感来自 VIM 的控制台文件管理器。
- [rovr](https://github.com/NSPC911/rovr) 后现代终端文件管理器。
- [s3duck-tui](https://github.com/nexusriot/s3duck-tui) TUI 版 S3 客户端。
- [sfm](https://github.com/afify/sfm) 简单的文件管理器。
- [superfile](https://github.com/yorukot/superfile) 相当漂亮且现代的终端文件管理器。
- [TUIFIManager](https://github.com/GiorgosXou/TUIFIManager) 跨平台的终端文件管理器 _（支持 termux）_。
- [Vifm](https://github.com/vifm/vifm) 带 vi 键位与其他 vim 风格行为的 TUI 文件管理器。
- [yazi](https://github.com/sxyazi/yazi) 用 Rust 编写的疾速终端文件管理器，基于异步 I/O。
- [ytreenova](https://github.com/robkam/ytreenova) Unix 早该就有的 XTree&trade; 风格文件管理器。

---

</details>

<a id="games"></a>
<details open><summary><h2>游戏</h2></summary>

- [awkaster](https://github.com/TheMozg/awk-raycaster) 完全用 gawk 编写、采用光线投射技术的伪 3D 射击游戏
- [balatrotui](https://github.com/Passeriform/BalatroTUI) Balatro 的 TUI 复刻版
- [bastet](https://github.com/fph/bastet) 邪恶的俄罗斯方块游戏
- [bell-system-sim](https://github.com/WPTK/bell-system-sim) 在 1983 年的仿 UNIX V7 shell 中值守贝尔系统维修测试台，并处理完电话故障工单
- [botany](https://github.com/jifunks/botany/) 虚拟植物伙伴
- [brickgame-4bit](https://github.com/ilyakurdyukov/brickgame-4bit) Brick Game 模拟器（4 位 Holtek 芯片）
- [BrogueCE](https://github.com/tmewett/BrogueCE) 精美的 roguelike 地牢探险游戏
- [cbonsai](https://gitlab.com/jallbrit/cbonsai) 盆景树生成器
- [CHAOS RPG](https://github.com/Mattbusel/chaos-rpg) 一款 roguelike，每次命中、治疗与掉落都由真实数学运算串联决定（洛伦兹吸引子、曼德博集合、考拉兹猜想）
- [chess-tui](https://github.com/thomas-mauran/chess-tui) 在终端中下国际象棋，用 Rust 构建
- [cli-chess](https://github.com/trb346/cli-chess) 在终端下棋的高度可定制方案。可在线对弈（通过 Lichess.org），也可离线与 Fairy-Stockfish 引擎对战。支持 Lichess 的所有变体。
- [clidle](https://github.com/ajeetdsouza/clidle) 在终端里玩 Wordle。通过 SSH 也能玩！
- [csol](https://github.com/nielssp/csol) 纸牌/接龙游戏合集，如 Klondike、FreeCell、Spider 与 Yukon
- [DOOM-ASCII](https://github.com/wojciech-graj/doom-ascii) 运行在终端中的文字版 DOOM。
- [Gameboy Emulator](https://github.com/gabrielrcouto/php-terminal-gameboy-emulator) PHP 终端 GameBoy 模拟器
- [GitType](https://github.com/unhappychoice/gittype) 把你的源代码变成打字练习的 CLI 游戏
- [go-life](https://github.com/sachaos/go-life) 终端版康威生命游戏
- [gokemon](https://github.com/nathanieltooley/gokemon) 终端版宝可梦对战模拟器
- [Gravitype](https://github.com/kanakOS01/gravitype) 单词从天而降的终端打字游戏
- [Greed](https://gitlab.com/esr/greed) 一款关于消费的游戏。在把自己吃进死角之前，尽可能多地吃！
- [LeTrain](https://github.com/antoniovazquezaraujo/LeTrain) - 使用 Java 17、LibGDX 与 Lanterna 的开源程序化列车模拟器。
- [Maze](https://github.com/itchyny/maze) 用 Go 编写的简单迷宫游戏。
- [Maze TUI](https://github.com/agl-alexglopez/maze-tui) 构建迷宫并用多种算法求解。
- [Micro Snake](https://github.com/troglobit/snake) 小巧的贪吃蛇游戏，利用 ANSI 转义序列绘制棋盘。
- [Micro Tetris](https://github.com/troglobit/tetris) 世界上最小的俄罗斯方块实现之一，仅用 ANSI 转义序列绘制棋盘。
- [minesweeper_4d_rs](https://github.com/itabesamesa/minesweeper_4d_rs) 用 Rust 与 Ratatui 编写的 4 维扫雷（也可用于经典扫雷）
- [moon-buggy](https://github.com/seehuhn/moon-buggy) 开着车横穿月球
- [MyMan](https://sourceforge.net/projects/myman/) MyMan 是一款面向彩色与单色文本终端的电子游戏，玩法类似南梦宫的 Pac-Man
- [nchess](https://github.com/billyvinning/nchess) 终端国际象棋，用 C 编写。
- [NetHack](https://github.com/NetHack/NetHack) 地牢探险游戏
- [nInvaders](http://ninvaders.sourceforge.net/) 太空侵略者
- [nSnake](https://github.com/alexdantas/nSnake) 经典贪吃蛇，文本界面
- [nudoku](https://github.com/jubalh/nudoku) 基于 ncurses 的数独游戏
- [onx](https://github.com/jerkyworks/onx) 与搭档对战的三子棋客户端-服务器游戏。基于文本界面与 Python。
- [pokete](https://github.com/lxgr-linux/pokete) 终端版宝可梦风格游戏
- [Rebels in the sky](https://github.com/ricott1/rebels-in-the-sky) 关于太空海盗跨星系打篮球的 P2P 终端游戏。
- [snake](https://github.com/wick3dr0se/snake) :video_game: 用纯 BASH v5.1+ 编写的超级极简 TUI 贪吃蛇
- [Square Tic Tac Toe](https://github.com/learnbyexample/TUI-apps/tree/main/SquareTicTacToe) 和井字棋一样，但用四个角围成正方形而非直线
- [ssHattrick](https://github.com/ricott1/sshattrick) 通过 SSH 在终端里玩 Hattrick。
- [sshtron](https://github.com/zachlatta/sshtron) 通过 SSH 运行的多人光轮游戏
- [sssnake](https://github.com/AngelJumbo/sssnake) 经典终端贪吃蛇，能自己玩，也能当屏保用。
- [steam-tui](https://github.com/dmadisetti/steam-tui) 简单的 steamcmd TUI 客户端。通过一个简易终端客户端图形化地启动、更新与下载 Steam 游戏。
- [sudoku-rs](https://github.com/MitchelPaulin/sudoku-rs) 用 tui-rs 构建的数独
- [sweeper](https://github.com/igor47/sweeper) 使用 curtsies 编写的扫雷游戏
- [terminal-phase](https://gitlab.com/dustyweb/terminal-phase) 运行在终端里的太空射击游戏！
- [terminal-pong](https://github.com/IshmamR/terminal.pong) 简单有趣、可以全程在终端中进行的乒乓球游戏。
- [termrex](https://github.com/SATYADAHAL/termrex) 灵感来自 Chrome 恐龙离线游戏的终端无尽跑酷游戏。
- [tetro-tui](https://github.com/Strophox/tetro-tui) 高度可配置的俄罗斯方块类游戏，支持 ASCII 粒子、回放等。
- [tinytetris](https://github.com/taylorconor/tinytetris) 80x23 的终端俄罗斯方块！
- [tty-solitaire](https://github.com/mpereira/tty-solitaire) 纸牌游戏在你的终端里跑起来！
- [tui-2048](https://github.com/ps06756/tui-2048) 属于你终端的 2048 游戏
- [typeinc](https://github.com/AnirudhG07/Typeinc) 基于 ncurses 的打字速度测试，提供多种难度。
- [typing-game-cli](https://github.com/akgondber/typing-game-cli) 命令行打字练习游戏，可与 typer-robot 或自己的最佳成绩比拼
- [UniPac](https://github.com/jesper-olsen/UniPac) 由 Unicode 驱动的终端版吃豆人，用 Rust 编写。
- [wocogo](https://codeberg.org/kedlubnowski/wocogo) 用给定的词块拼出词语。一个用 Python 编写的简单 TUI 游戏，类似《纽约时报》的 Combinations。
- [Wordle](https://github.com/m-dango/raku-wordle/) 用 Raku 编写的 Wordle 脚本与库
- [Zigtris](https://github.com/ringtailsoftware/zigtris) 又一个终端俄罗斯方块
- [Zoridor](https://github.com/ringtailsoftware/zoridor) 在终端里玩 Quoridor

---

</details>

<a id="libraries"></a>
<details open><summary><h2>库</h2></summary>

<h3>Python</h3>

- [animpy](https://github.com/13DoesPython/animpy) - 不再痛苦地用 **Python** 做终端动画。
- [Argenta](https://github.com/koloideal/Argenta) 用于构建模块化 **Python** 应用的库
- [blessed](https://github.com/jquast/blessed) Blessed 是一个简单实用的 **Python** 终端应用开发库
- [blessings](https://github.com/erikrose/blessings) **Python** 的 ncurses 封装库，让代码更漂亮
- [flexablelib](https://github.com/Opus-Perpetuus/flexablelib) 零依赖的 **Python** 终端表格库，支持 56 种边框样式、颜色、单元格合并与小数对齐。
- [notcurses](https://github.com/dankamongmen/notcurses) 炫酷的字符图形/TUI 库，支持 **C** 与 **Python**。绝对不叫 curses。
- [py_cui](https://github.com/jwlodek/py_cui) **Python** 库，让基于控件的 TUI/CUI 界面尽可能简单，支持标准控件与菜单、文本框、表单、文件浏览器等弹窗。
- [pyTermTk](https://github.com/ceccopierangiolieugenio/pyTermTk) 自包含的 **Python** TUI 库，具备 QT 风格的 API 语义
- [Python Prompt Toolkit](https://github.com/prompt-toolkit/python-prompt-toolkit) 用于构建强大交互式命令行应用的 **Python** 库
- [Rich](https://github.com/Textualize/rich) 是一个 **Python** 库，为终端提供富文本与精美排版。
- [textual](https://github.com/Textualize/textual) 灵感来自现代 Web 开发的 **Python** TUI（文本用户界面）框架。
- [textual-themes](https://github.com/michaelblaess/textual-themes) 41 款复古配色的 Textual 主题，**Python** 实现
- [textual-widgets](https://github.com/michaelblaess/textual-widgets) 面向 Textual 应用的**可复用组件**：**Python** 日期选择器、上下文菜单、分栏器、日志面板与模态对话框
- [UniCurses](https://github.com/unicurses/unicurses) **Python** 模块，在所有操作系统上提供 Curses 功能。
- [urwid](https://github.com/urwid/urwid) 面向 Linux、OSX、Cygwin 或其他类 Unix 系统的控制台用户界面库。
- [Vindauga](https://github.com/gabbpuy/vindauga) **Python** 对 BSD 许可的 C++ Turbo Vision 库的实现。
- [xnano](https://github.com/hsaeed3/xnano) 构建于 Rust ratatui 与 tachyonfx 之上的现代、轻量、声明式 **Python** TUI 框架。([文档](https://xnano.hammad.app))

<h3>GO</h3>

- [bubbletea](https://github.com/charmbracelet/bubbletea) 基于 Elm、用于构建函数式优雅终端应用的 **Go** 框架
- [gocui](https://github.com/jroimartin/gocui) 极简的 **Go** 控制台用户界面包
- [pterm](https://github.com/pterm/pterm/) 现代 **Go** 模块，美化控制台输出。支持图表、进度条、表格、树形结构等，功能全面，跨平台。
- [stickers](https://github.com/76creates/stickers) 为 charmbracelet/lipgloss 提供积木式组件的 **Go** 库
- [tcell](https://github.com/gdamore/tcell) tcell 是另一个 **Go** 终端包，在若干方面与 termbox 相似，但更出色。
- [tview](https://github.com/rivo/tview/) 用 **Go** 编写、功能丰富的终端 UI 库

<h3>C</h3>

- [AnbUI](https://github.com/oerg866/anbui) 极简的文本 UI 库，用 **C** 编写
- [libuv](https://github.com/libuv/libuv) 跨平台异步 I/O 库，用 **C** 编写
- [ncurses](https://invisible-island.net/ncurses/announce.html) 经典的 **C** 库，并带有多种语言的绑定
- [tuibox](https://github.com/Cubified/tuibox) 单头文件 **C** 终端 UI 库，可在命令行构建支持鼠标驱动的交互式应用。

<h3>C++</h3>

- [ASCII_Board_Game_Engine](https://github.com/tjunruh/ASCII_Board_Game_Engine) 用 **C++** 编写的图形引擎，用于制作棋盘游戏
- [ConsoleCraftEngine](https://github.com/ural89/ConsoleCraftEngine) 基于终端的 2D 游戏引擎，用 **C++** 编写。
- [FINAL CUT](https://github.com/gansm/finalcut) **C++** 库，用于创建基于文本控件的终端应用
- [FTXUI](https://github.com/ArthurSonzogni/FTXUI) 💻 **C++** 函数式终端用户界面。❤️
- [GGUI](https://github.com/Gabidal/GGUI) **C++17** 结构化终端用户界面。🐧/🪟
- [imtui](https://github.com/ggerganov/imtui) 立即模式的文本用户界面 **C++** 库，支持 256 色 ANSI 与鼠标/键盘输入。
- [koto](https://github.com/saber-88/koto) 现代、零依赖的立即模式 **C++23** TUI 库。
- [rang](https://github.com/agauniyal/rang) 极简、仅头文件、现代 **C++** 的终端小工具库。
- [termdb](https://github.com/agauniyal/termdb) 面向现代 **C++** 的 Terminfo 解析器
- [Tui Widgets](https://github.com/tuiwidgets/tuiwidgets) 面向 **C++** 终端应用的高层控件工具箱
- [tvision](https://github.com/magiblot/tvision) 现代版 **C++** Turbo Vision 2.0，支持跨平台与 Unicode。
- [uvw](https://github.com/skypjack/uvw) 仅头文件、事件驱动、易用的现代 **C++** libuv 封装
  同时提供共享库与静态库形式！
- [xtd](https://github.com/gammasoft71/xtd) 免费开源的现代 **C++** 框架，可在 Windows、macOS、Linux、iOS、Android、FreeBSD 与 Haiku 上构建控制台 (CLI)、窗体（WinForms 风格 GUI）与单元测试 (xUnit) 应用和库。

<h3>Java</h3>

- [casciian](https://github.com/crramirez/casciian) 基于 "Jexer" 且不依赖 AWT/Swing 的文本用户界面 **Java** 库，针对 GraalVM AOT 原生编译做了优化，着重关注性能、远程连接质量与终端兼容性。
- [Jexer](https://gitlab.com/AutumnMeowMeow/jexer) 实现文本窗口系统的 **Java** 库，设计上 loosely 借鉴了 Borland 的 Turbo Vision 系统。
- [Lanterna](https://github.com/mabe02/lanterna) 用于创建文本界面的 **Java** 库，功能与 C 语言 curses 库非常相似。
- [TamboUI](https://github.com/tamboui/tamboui) **Java** 库，用于构建现代终端用户界面。最初移植自 Ratatui，同时吸收了 Textual 的高层灵感，提供高效立即模式与一套带层叠样式表 (CSS) 的大型可复用组件库。
- [TUI4J](https://github.com/WilliamAGH/tui4j) **Java** 终端 UI 框架，是 Bubble Tea (Go) 的移植版，并融合了部分 Textual 特性。

<h3>.NET</h3>

- [Consolonia](https://github.com/Consolonia/Consolonia) 支持 XAML 的 **.NET** 终端 GUI 框架
- [Elaris.UI](https://github.com/ambystechcom/Ambystech.Elaris.UI) 轻量级终端 UI 库，面向 **.NET**，支持 24 位真彩色。基于现代终端构建，跨平台可用。
- [Hex1b](https://github.com/mitchdenny/hex1b) 用于构建丰富交互式 TUI 的 **.NET** 库，采用受 React 启发的声明式 API
- [RazorConsole](https://github.com/RazorConsole/RazorConsole) 使用 Razor 组件构建交互式终端界面的 **.NET** 库，支持按键与鼠标
- [SharpConsoleUI](https://github.com/nickprotop/ConsoleEx) **.NET** 多窗口 TUI 框架，支持窗口重叠、合成器特效与 Spectre.Console 集成
- [Spectre.Console](https://github.com/spectreconsole/spectre.console) 用于打造精美控制台应用程序的 **.NET** 库
- [Terminal.Gui](https://github.com/tui-cs/Terminal.Gui) 跨平台终端 UI 工具包，面向 **.NET**

<h3>Rust</h3>

- [AppCUI-rs](https://github.com/gdt050579/AppCUI-rs) 跨平台 **Rust** TUI 框架，支持窗口重叠、菜单、对话框与 50 多种内建控件（列表、树、图表、日期选择器、十六进制查看器）、主题与鼠标支持。
- [iocraft](https://github.com/ccbrown/iocraft) **Rust** crate，用于打造精致手工质感的 TUI 与文本 IO，采用类似 Ink 的声明式 API。
- [Ratatui](https://github.com/ratatui/ratatui) 用于构建终端 UI 的 **Rust** crate（tui-rs 的活跃维护分支）。
- [Ratatui Kit](https://github.com/yexiyue/ratatui-kit) **Rust** crate，允许在 Ratatui 之上构建类 React 组件。
- [tui-input](https://github.com/sayanarijit/tui-input) TUI 输入库，支持多种后端，包括 **Rust** 的 tui-rs 与 ratatui

<h3>其他</h3>

- [Ashen](https://github.com/colinta/Ashen) 用 **Swift** 编写的、类 Elm 的框架
- [blessed](https://github.com/chjj/blessed) 面向 **Node.js** 的高级终端界面库
  用于开发有状态的 TUI 应用。
- [dart_tui](https://github.com/codenameakshay/dart_tui) 类 Elm 的终端 UI 框架，面向 **Dart**：包含组件、表单，风格贴近 Lip Gloss。
- [gum](https://github.com/charmbracelet/gum) 让 **shell** 脚本也炫起来的工具
- [ink](https://github.com/vadimdemedes/ink) 面向 **Node.js** 交互式命令行应用的 React
- [ink-web](https://github.com/cjroth/ink-web) 浏览器端 Ink 运行时，通过 xterm.js 在浏览器中渲染 React TUI 应用。
- [Melker](https://melker.sh) 类 HTML、以文档为先的 TUI 框架，面向 **TypeScript/Deno**，支持权限沙箱、flexbox 布局与从 URL 直接运行。
- [moulti](https://moulti.run/) 由 CLI 驱动的 TUI，把任意输出以可视化、可折叠的块呈现。深耕 **shell** 脚本场景，对 **Ansible** 同样友好。
- [nimwave](https://github.com/ansiwave/nimwave) 为终端或浏览器构建文本界面的 **Nim** 库
- [nocterm](https://github.com/Norbert515/nocterm) 类 Flutter 的 TUI 框架，面向 **Dart**，支持热重载、45+ 组件与声明式页面结构。
- [OpenTUI](https://github.com/anomalyco/opentui) 用于构建终端用户界面 (TUI) 的 **TypeScript** 库
- [php-tui](https://github.com/php-tui/php-tui) 面向 **PHP** 的综合 TUI 库，大量借鉴 Ratatui。
- [Raxol](https://github.com/DROOdotFOO/raxol) 面向 **Elixir** 的多表面运行时：单个应用可渲染到终端、浏览器、SSH 与智能体表面，具备按组件隔离的崩溃处理与 BEAM 热重载。
- [termbox2](https://github.com/termbox/termbox2) 用于构建 TUI 的终端渲染库。
- [TermDOM](https://github.com/bikeshaving/termdom) 在终端中显示 HTML 与 CSS 的 **JavaScript** 库，拥有真正的 DOM
- [TermGL](https://github.com/wojciech-graj/TermGL) 终端图形库，支持 2D 与 3D 图形。
- [Thermage](https://github.com/thermage/thermage) Thermage 是一个 **PHP** 库，通过流畅且极其强大的 API 控制终端输出文本颜色、背景、格式、主题等。

---

</details>

<a id="messaging"></a>
<details open><summary><h2>消息通讯</h2></summary>

- [aerc](https://aerc-mail.org/) 邮件客户端
- [alpine](https://alpineapp.email/) 邮件客户端
- [basalt](https://github.com/erikjuhani/basalt) 用于直接在终端中管理 Obsidian 仓库与笔记的 TUI 应用。
- [concord](https://github.com/chojs23/concord) 功能丰富的 Discord TUI 客户端
- [Devzat](https://github.com/quackduck/devzat) 用 Golang 编写的 SSH 聊天工具，支持自托管。
- [dexchat](https://github.com/dexchat/dex) 面向终端的现代 IRC 客户端。
- [discordo](https://github.com/ayn2op/discordo) 轻量、安全且功能丰富的 Discord 终端客户端
- [endcord](https://github.com/sparklost/endcord) 功能丰富的 Discord TUI 客户端。
- [gomuks](https://github.com/gomuks/gomuks) Matrix 客户端
- [gurk-rs](https://github.com/boxdot/gurk-rs) 终端版 Signal Messenger 客户端
- [iamb](https://iamb.chat) 用 Rust 编写、专为 Vim 爱好者打造的 Matrix 客户端
- [instagram-cli](https://github.com/supreme-gg-gg/instagram-cli) 在终端中使用 Instagram，脑rot 的终结者来了
- [irssi](https://irssi.org/) IRC 终端客户端
- [local-chat](https://github.com/DongGunYoon/local-chat) 同一个 WiFi 下人人可用的终端聊天，无需托管、无需账号，消息不落盘
- [marchat](https://github.com/Cod-e-Codes/marchat) 自托管终端聊天，采用 WebSocket 客户端/服务器架构，可选共享密钥加密，并支持插件。
- [mastui](https://github.com/kimusan/mastui) Mastodon TUI
- [matcha](https://github.com/floatpane/matcha) 邮件客户端
- [matterhorn](https://github.com/matterhorn-chat/matterhorn) Mattermost 终端客户端。
- [mcabber](https://mcabber.com/) XMPP (Jabber) 客户端
- [meli](https://meli.delivery/) 邮件客户端
- [Mutt](https://gitlab.com/muttmua/mutt) 邮件客户端
- [nchat](https://github.com/d99kris/nchat) Telegram/WhatsApp/Signal 客户端
- [nomadnet](https://github.com/markqvist/NomadNet) 构建于 Reticulum 之上的安全消息网络
- [nostratui](https://github.com/adamm-xyz/nostratui) 用于浏览 Nostr 帖子的终端用户界面 (TUI)，用 Rust 编写。
- [nostui](https://github.com/akiomik/nostui) Nostr 客户端
- [Profanity](https://profanity-im.github.io) XMPP (Jabber) 客户端
- [rtg](https://github.com/bercly0b/rtg) 用 Rust 编写的快速类 vim Telegram TUI 客户端，基于 TDLib
- [sclack](https://github.com/haskellcamargo/sclack) Slack 终端客户端
- [scli](https://github.com/isamert/scli/) 面向 Signal Messenger 的简易终端用户界面
- [Slack-term](https://github.com/jpbruinsslot/slack-term) 面向终端的 Slack 客户端
- [sup](https://github.com/sup-heliotrope/sup) 采用 curses 线程加标签风格的邮件客户端
- [SuperChat](https://github.com/serialexp/superchat) 基于终端的线程式聊天应用，使用自定义二进制协议。
- [tele](https://github.com/sorokin-vladimir/tele) - 键盘优先的 Telegram 客户端，兼具 TUI、CLI 与后台守护进程
- [tgt](https://github.com/FedericoBruzzone/tgt) 用 Rust 编写的 Telegram TUI
- [toot](https://github.com/ihabunek/toot) Mastodon CLI 与 TUI
- [toxic](https://github.com/JFreegman/toxic/) 基于 Tox 的即时通讯与视频聊天客户端
- [tuisky](https://github.com/sugyan/tuisky) BlueSky 的 TUI 客户端
- [tuix](https://github.com/pythops/tuix) 用于管理终端屏幕的 TUI
- [tut](https://github.com/RasmusLindroth/tut) Mastodon TUI 客户端
- [twitch-tui](https://github.com/Xithrius/twitch-tui) 在终端里看 Twitch 聊天
- [Weechat](https://weechat.org/) 可扩展的聊天客户端
- [zulip-terminal](https://github.com/zulip/zulip-terminal) Zulip 官方终端客户端（类似 matterhorn）

---

</details>

<a id="miscellaneous"></a>
<details open><summary><h2>杂项</h2></summary>

- [arttime](https://github.com/poetaman/arttime) 把文字艺术的美感与时钟、计时器、基于模式的时间管理器的功能融为一体。
- [asciiMol](https://github.com/dewberryants/asciiMol) 基于 Curses 的 ASCII 分子查看器，适用于 Linux 终端。
- [bluetui](https://github.com/pythops/bluetui) 用于管理蓝牙设备的 TUI。
- [bluetuith](https://github.com/bluetuith-org/bluetuith) 基于 TUI 的蓝牙连接管理器，可与蓝牙适配器及设备交互。
- [Caligula](https://github.com/ifd3f/caligula) 友好轻量的磁盘镜像 TUI。
- [Captain's log](https://github.com/NikolaDucak/caps-log) 小巧的 TUI 日记工具
- [cava](https://github.com/karlstav/cava) 跨平台音频可视化工具
- [cfdisk](https://github.com/util-linux/util-linux) util-linux 自带的 TUI 分区编辑器
- [cgdisk](https://www.rodsbooks.com/gdisk/cgdisk-walkthrough.html) 用于操作 GUID 分区表的 TUI 分区编辑器，仿照 cfdisk 设计
- [Clanki](https://github.com/alvenw/clanki) 基于 TUI 的 Anki 复习客户端，甚至支持进度同步。
- [codename-generator](https://github.com/michaelblaess/codename-generator) 依据希腊诸神、宝石或星座等主题生成项目代号，支持修饰词与音韵变体
- [CrunchyCleaner](https://github.com/knuspii/crunchycleaner) 适用于 Windows 与 Linux 的轻量级软件缓存清理工具。
- [csvlens](https://github.com/YS-L/csvlens) TUI 版 CSV 文件查看器，就像为 CSV 打造的 less。
- [diary](https://github.com/actuday6418/Diary) 用 Rust 编写的日记应用，同时加密文本与文件数据，并可按需解密并生成精美的 HTML 日记页面。
- [DigiSurf](https://github.com/SeanMcLoughlin/digisurf) TUI 信号波形查看器
- [diskonaut](https://github.com/imsnif/diskonaut) 终端磁盘空间导航器
- [dua-cli](https://github.com/byron/dua-cli) 快速查看磁盘空间占用并删除无用数据。
- [distrobox-tui](https://github.com/phanirithvij/distrobox-tui) 管理 distrobox 容器的 TUI
- [dupster](https://github.com/karimz1/dupster) 在终端里查找重复文件的省事办法。轻松找出重复项、预览并删除。
- [ec2-instance-selector](https://github.com/aws/amazon-ec2-instance-selector) 一个 CLI 工具兼 Go 库，可按 vcpus、内存等资源条件推荐实例类型
- [emu2](https://github.com/dmsc/emu2) 面向 Linux 文本控制台的简易 DOS 模拟器，支持基本 DOS 系统调用与控制台 I/O。
- [flawz](https://github.com/orhun/flawz) 用于浏览安全漏洞 (CVE) 的终端界面
- [fnf](https://github.com/leo-arch/fnf) 终端交互式模糊查找器
- [fzf](https://github.com/junegunn/fzf) 通用的命令行模糊查找器
- [gdu](https://github.com/dundee/gdu) 用 Go 编写的快速磁盘占用分析器，带控制台界面
- [godap](https://github.com/Macmod/godap) 用 Golang 编写的完整 LDAP TUI
- [golazo](https://github.com/0xjuanma/golazo) 在终端中获取足球赛事的逐分钟进展与完场统计
- [gpg-tui](https://github.com/orhun/gpg-tui) GnuPG 的终端用户界面
- [HumBLE Explorer](https://github.com/koenvervloesem/humble-explorer) 跨平台、命令行且对人类友好的低功耗蓝牙扫描器
- [impala](https://github.com/pythops/impala) 管理 Wi-Fi 的 TUI
- [isw](https://gitlab.com/thom-cameron/isw) 适合番茄钟等场景的简易终端秒表应用
- [jrnl](https://jrnl.sh/) 不离开命令行就能记录想法与笔记。对人类友好，面向未来，安全可靠。
- [keydex](https://github.com/shikaan/keydex) KeePass 数据库的 TUI 密码管理器。
- [lazynginx](https://github.com/giacomomasseron/lazynginx) 简洁的 nginx 管理 TUI。
- [LearnByExample](https://github.com/learnbyexample/TUI-apps) 包含教程与 300+ 道练习的 TUI，覆盖 python、grep、awk、sed 与终端通用技巧。
- [linecast](https://github.com/ashuttl/linecast) 交互式天气、雷达、潮汐、日月视图，带星象与星座的 planetarium，以及可旋转地球仪式的地图，专为终端打造。
- [lnav](https://lnav.org/) 面向小规模场景的高级日志文件查看器
- [mac-cleanup-go](https://github.com/2ykwang/mac-cleanup-go) macOS 磁盘清理 TUI：扫描缓存/开发产物、预览、排除，并将条目移入废纸篓。
- [mapscii](https://github.com/rastapasta/mapscii) 面向控制台的盲文与 ASCII 世界地图渲染器
- [moc](https://moc.daper.net/download) 控制台音频播放器
- [Mole](https://github.com/tw93/Mole) 在 macOS 与 Windows 上用交互式 TUI 清理缓存与应用残留、卸载应用，并浏览磁盘用量与实时系统状态
- [moribito](https://github.com/ericschmar/moribito) 浏览 LDAP 目录树、查看记录并执行自定义查询。
- [mqttui](https://github.com/EdJoPaTo/mqttui) 用 Rust 编写的 MQTT 客户端
- [NanoCore](https://github.com/AfaanBilal/NanoCore) 用 Rust 编写的 8 位 CPU 模拟器 TUI，附带汇编器与自定义 ISA。
- [nbtui](https://codeberg.org/ItsZariep/nbtui) 面向 Linux 的 Ncurses 蓝牙 TUI 管理器
- [ncdu](https://dev.yorhel.nl/ncdu) 带 ncurses 界面的磁盘占用分析器
- [nemu](https://github.com/nemuTUI/nemu) 面向 QEMU 的 TUI
- [neoss](https://github.com/PabloLec/neoss) 面向 Unix 系统的套接字统计可视化与解读工具。
- [nmtui](https://developer.gnome.org/NetworkManager/stable/nmtui.html) ncurses 网络管理器
- [oeis-tui](https://github.com/hako/oeis-tui)  在终端中浏览在线整数序列百科 (OEIS) 的 TUI 与 CLI。
- [oha](https://github.com/hatoo/oha) HTTP 负载生成器
- [packemon](https://github.com/ddddddO/packemon) 数据包生成器与监视器。
- [pass-cli](https://github.com/reyamira/pass-cli) 兼具 TUI 与 CLI 的密码管理器，支持 rclone 云端同步
- [passtui](https://github.com/fjmoralesp/passtui) 标准 Unix 密码管理器 **pass** 的终端用户界面。
- [PesterExplorer](https://github.com/HeyItsGilbert/PesterExplorer) 用于浏览 Pester 测试结果的 TUI。
- [physics-TUI](https://github.com/ClaudioRMalvino/Physics-TUI) 面向本科学习的物理 TUI 应用
- [pug](https://github.com/leg100/pug) terraform 与 tofu 模块及基础设施管理。
- [recoverpy](https://github.com/PabloLec/recoverpy) 用于恢复被覆盖或已删除数据的 TUI。
- [redu](https://github.com/drdo/redu) 面向 restic 仓库的 ncdu，通过排除列表裁剪已有仓库中的文件并跳过新增文件
- [rocket.term](https://github.com/gerstner-hub/rocket.term) 面向 Rocket.chat 消息方案的文本聊天客户端。
- [sbb-tui](https://github.com/necrom4/sbb-tui) 瑞士公共交通时刻表的 TUI 客户端，灵感来自 SBB/CFF/FFS 应用。
- [smassh](https://github.com/kraanzu/smassh) 灵感来自 MonkeyType 的 TUI 打字测试应用。
- [steam_friends_list_tui](https://github.com/AdamWHY2K/steam_friends_list_tui) 命令行里的 Steam 好友列表
- [Systemd-manager-tui](https://github.com/matheus-git/systemd-manager-tui) 通过 TUI 管理 systemd 服务的程序。
- [tab-pal](https://github.com/ben-nour/tab-pal) 从命令行为 Tableau 添加与编辑自定义配色板。
- [tcpterm](https://github.com/sachaos/tcpterm) tcpterm 是一款 TUI 界面的数据包可视化工具。
- [term.everything](https://github.com/mmulet/term.everything) 在终端中运行任意 GUI 应用
- [terminalperiodictable](https://github.com/velorek1/terminalperiodictable) 用 C 编写、面向 Unix 系统的精美 TUI 元素周期表。
- [termshark](https://github.com/gcla/termshark) tshark 的终端界面
- [thokr](https://github.com/jrnxf/thokr) 用 Rust 编写的 sleek 打字 TUI
- [tlock](https://github.com/eklairs/tlock) 终端中的双因素认证令牌管理器
- [tray-tui](https://github.com/Levizor/tray-tui) 终端里的系统托盘
- [try-rs](https://github.com/tassiovirginio/try-rs/) 闪电般快速的临时项目管理 TUI。瞬间创建、浏览并克隆仓库，不给系统添乱。
- [tttui](https://github.com/reidoboss/tttui) 完全运行在终端中的 MonkeyType 风格打字测试
- [ttyper](https://github.com/max-niederman/ttyper) 基于终端的打字测试
- [tui-shop](https://github.com/rainbow-sh/tui-shop) 介于 CLI 与 GUI 之间的 TUI/CLI 下载方式
- [tweakcc](https://github.com/Piebald-AI/tweakcc) 用于自定义 Claude Code 主题、思考动词等设置的 TUI。
- [typtea](https://github.com/ashish0kumar/typtea) 极简的终端打字速度测试工具，支持数十种编程语言。
- [vortix](https://github.com/Harry-kp/vortix) 面向 WireGuard 与 OpenVPN 的终端界面，提供实时遥测、泄漏检测与 kill switch。
- [wavemon](https://github.com/uoaerg/wavemon) 无线设备监控应用
- [wb](https://github.com/mmertgunduz/wb) 面向 Linux 及其衍生系统的 TUI 词汇笔记本应用。
- [wego](https://github.com/schachmat/wego) 天气应用
- [WG Commander](https://github.com/andrianbdn/wg-cmd) 用于快速搭建 WireGuard VPN 的 TUI：对等端管理、二维码与配置向导。
- [wifitui](https://github.com/shazow/wifitui) 快速、功能丰富且友好的 Wi-Fi 终端界面，支持通过 dbus 接入 NetworkManager 与 iwd。
- [WifUI](https://github.com/sohamw03/wifui) 原生运行于 Windows 的 Wi-Fi 连接管理 TUI (Rust)
- [wlctl](https://github.com/aashish-thapa/wlctl) 基于 NetworkManager 的 Linux Wi-Fi、有线与 VPN 管理 TUI
- [wttr.in](https://github.com/chubin/wttr.in) 查询天气的正确方式
- [wwlog](https://github.com/ali5ter/wwlog) 浏览、对比并导出 Weight Watchers 饮食记录，本地归档不受订阅期限影响
- [x-cmd](https://github.com/x-cmd/x-cmd) 大量有趣工具的集合，能以一致、结构化的方式驱动众多其他程序/功能。
- [xplr](https://github.com/sayanarijit/xplr) 可折腾、极简且快速的 TUI 文件浏览器，思路借鉴自 nnn 与 fzf。
- [ytunnel](https://github.com/yetidevworks/ytunnel) 用于创建与管理带自定义域名的 Cloudflare Tunnel 的 TUI

---

</details>

<a id="multimedia"></a>
<details open><summary><h2>多媒体</h2></summary>

- [ani-l](https://github.com/komposer-aml/ani-l) 基于 Rust 的动漫浏览与串流工具，全程无需离开终端
- [asak](https://github.com/chaosprint/asak) 跨平台的录音/播放 TUI
- [bookokrat](https://github.com/bugzmanov/bookokrat) 功能完备的 EPUB 电子书阅读器，支持 Vim 键位。
- [chafa](https://hpjansson.org/chafa/) 强大的转换工具，可将图像数据（包括动图 GIF）转换为图形格式或适合在终端显示的 ANSI/Unicode 字符画。
- [cmdpxl](https://github.com/knosmos/cmdpxl) 非常实用的命令行图像编辑器
- [cmus](https://cmus.github.io/) 面向类 Unix 操作系统的小巧、快速且强大的控制台音乐播放器。
- [ctune](https://github.com/An7ar35/ctune) 基于 ncurses 的 Linux 网络电台播放器。
- [draw](https://github.com/maaslalani/draw) 终端中的简易绘图工具。
- [fancy-cat](https://github.com/freref/fancy-cat) 轻量级的终端 PDF 阅读器，支持 Vim 键位
- [favicon-editor](https://github.com/xyproto/favicon-editor) 极简灰度 favicon 编辑器
- [gadacz](https://github.com/rareitems/gadacz) 有声书播放器
- [GopherTube](https://github.com/krishnassh/gophertube) 终端 YouTube 客户端，抓取 YouTube 搜索结果并用 mpv 播放视频
- [Gorae](https://github.com/Han8931/gorae) PDF 与 EPUB 的 TUI 阅读器，支持 Vim 风格导航。
- [goweeb](https://github.com/EliasLd/goweeb) 从多个来源、多种语言下载漫画（pdf 或 cbz 格式），配备快速 TUI 与容器支持。
- [image-sorter](https://github.com/jgalat/image-sorter) 用 Rust 编写的图片整理终端用户界面
- [invidtui](https://github.com/darkhz/invidtui) 面向 Windows、Linux 与 MacOS 的 TUI Invidious 客户端，可从 invidious 实例获取并播放音视频，也支持浏览与播放播放列表和频道。
- [jellyfin-tui](https://github.com/dhonus/jellyfin-tui) Jellyfin 客户端
- [kew](https://github.com/ravachol/kew) 面向 Linux 的终端音乐播放器
- [line](https://github.com/pd3v/line) 迷你的命令行 MIDI 音序器与实时编程语言
- [MAL-Cli](https://github.com/L4z3x/mal-cli) 用 Rust 编写的、面向官方 myanimelist API 的终端接口。
- [managarr](https://github.com/Dark-Alex-17/managarr) 用于管理 *arr 服务器的 TUI 与 CLI
- [mangap](https://github.com/hongnoul/mangap) 终端漫画阅读器，通过 kitty 图形协议渲染真实图片页面，支持实时搜索与 Anilist 同步。
- [manga-tui](https://github.com/josueBarretogit/manga-tui) 基于终端的漫画阅读与下载器，支持图片渲染
- [marstui-audio](https://github.com/schooldanlp6/marstui-rustio) 不错的音频管理界面，类似 pavucontrol 且一切可定制
- [mps-youtube](https://github.com/mps-youtube/yewtube) 基于终端的 YouTube 播放器与下载器
- [mpv-music](https://github.com/FurqanHun/mpv-music) 用 Rust 编写的跨平台 CLI/TUI 音乐播放器与曲库浏览器，可过滤挑选想听的内容且不打扰你，没有后台守护进程。
- [mpvc](https://github.com/gmt4/mpvc) 类 mpc 的 mpv 控制界面
- [MusicTUI](https://github.com/anthonymaley/MusicTUI) 面向 macOS 的 Apple Music TUI 与 CLI，用 Swift 编写，支持多房间 AirPlay 路由、带封面图的曲库浏览、播放列表、收音机与场地均衡器
- [nap](https://nap.sourceforge.net/) Linux 版 napster 客户端
- [ncspot](https://github.com/hrkfdn/ncspot) 用 Rust 编写的跨平台 ncurses Spotify 客户端
- [NoctaVox](https://github.com/Jaxx497/NoctaVox) 本地 TUI 音乐播放器
- [ostui](https://git.sr.ht/~ser/ostui) 面向 gonic、Navidrome 等 Subsonic API 服务器的 CLI 客户端
- [pipe-viewer](https://github.com/trizen/pipe-viewer) 面向 Linux 的轻量 YouTube 客户端，无需 API key。
- [pyradio](https://github.com/coderholic/pyradio) TUI 网络电台播放器，收录世界各地数千个电台
- [RadioGoGo](https://github.com/matteo-pacini/RadioGoGo) 由 Go 驱动的 CLI，通过 sleek 的 TUI 收听全球广播。
- [Relax-player](https://github.com/ebithril/relax-player) 轻量、无干扰的网页环境音播放器替代方案。
- [retro-amp](https://github.com/michaelblaess/retro-amp) 复古风格音乐播放器，带实时频谱可视化、同步歌词、播放列表与 38 款主题
- [rmpc](https://rmpc.mierak.dev/) 可配置的 MPD 客户端，灵感来自 ncmpcpp 与 ranger，并通过多种图形协议支持专辑封面。
- [roku-cli](https://github.com/winsbe01/roku-tui) Roku 的命令行 TUI 遥控器
- [rustune](https://github.com/dzulfikar08/rustune) 终端音乐播放器，支持 YouTube 搜索、本地播放、同步歌词、网络电台与 Winamp 皮肤
- [rusty-pipes](https://github.com/dividebysandwich/rusty-pipes) 采样驱动的 MIDI 控制虚拟管风琴乐器，兼容 GrandOrgue 与 Hauptwerk 音色库。
- [sgram-tui](https://github.com/arian-shamaei/sgram-tui) 用于实时麦克风或音频文件的校准频谱图分析器，支持导出带标注的 PNG 图表与无头渲染模式
- [spotatui](https://github.com/LargeModGames/spotatui) Spotify 客户端，支持原生串流、同步歌词与实时音频可视化
- [spotify-player](https://github.com/aome510/spotify-player) 功能齐备的终端 Spotify 播放器
- [spotui](https://github.com/ceuk/spotui) 用 Python 编写的 Spotify 客户端
- [tdf](https://github.com/itsjunetime/tdf) 基于 TUI 的 PDF 阅读器
- [terminal-yt](https://github.com/jooooscha/terminal-yt) 灵感来自 newsboat 的迷你终端 YouTube 管理器
- [termusic](https://github.com/tramhao/termusic) 用 Rust 编写的音乐播放器 TUI
- [textual-paint](https://github.com/1j01/textual-paint) 终端里的 MS Paint
- [timg](https://github.com/hzeller/timg) 终端图像查看器
- [tizonia-openmax-il](https://github.com/tizonia/tizonia-openmax-il) 面向 Linux 的命令行云音乐播放器，支持 Spotify、Google Play Music、YouTube、SoundCloud、Dirble、Plex 服务器与 Chromecast 设备
- [tortuise](https://github.com/buildoak/tortuise) 终端中的高斯泼溅 3D 查看器。6 种渲染模式，纯 CPU，基于 crossterm + rayon
- [Trophy](https://github.com/taigrr/trophy) 用于查看 OBJ 与 GLB 文件的 TUI 3D 模型查看器
- [Tanko](https://github.com/Alexandro521/Tanko) 在终端中阅读与下载漫画的工具，支持图片渲染
- [upiano](https://github.com/eliasdorneles/upiano) 终端里的一架钢琴
- [valveFM](https://github.com/zorig/valvefm) 复古 FM 电台 TUI，可串流 radio-browser.info 上的电台
- [vlc](https://github.com/videolan/vlc) VLC 自带 ncurses 界面，`vlc --intf ncurses`
- [waves](https://github.com/llehouerou/waves) 终端音乐播放器，支持 vim 风格导航与电台模式（播放曲库中风格相近的艺人）
- [wiremix](https://github.com/tsowell/wiremix) 面向 PipeWire 的 TUI 音频混音器，类似 pavucontrol，可调节音量、切换输入/输出设备及其配置
- [xytz](https://github.com/xdagiz/xytz) 用于下载 YouTube 视频/播放列表/频道的精美 TUI。
- [ytdl-tui](https://github.com/darky/ytdl-tui) 用于下载 YouTube 视频的 TUI
- [ytfzf](https://github.com/pystardust/ytfzf) POSIX 脚本，无需 API 即可搜索 YouTube 或 Peertube 视频，并用 mpv/youtube-dl 打开或下载
- [ytui-music](https://github.com/sudipghimire533/ytui-music) 从 YouTube 听音乐。可配置、极简、轻量、私密又好看的音乐客户端。

---

</details>

<a id="productivity"></a>
<details open><summary><h2>效率工具</h2></summary>

- [abook](https://abook.sourceforge.io/) TUI 地址簿，集成 [mutt](http://www.mutt.org/)
- [awsui](https://github.com/junminhong/awsui) 强大且友好的 AWS Profile 与 SSO 管理终端界面。
- [Bada](https://github.com/Han8931/bada) 极简、Vim 优先的任务管理器，帮助你专注而不受干扰。
- [Bagels](https://github.com/EnhancedJax/Bagels) TUI 开支记录器
- [budget-tracker-tui](https://github.com/Feromond/budget-tracker-tui) TUI 预算管理应用，用于跟踪收入、支出、投资、预算目标，并做可视化与洞察分析。
- [calcure](https://github.com/anufrievroman/calcure) 现代 TUI 日历与任务管理器，界面极简且可自定义。
- [calcurse](https://calcurse.org/) 面向命令行的日历与日程安排应用
- [christophorus](https://github.com/michaelblaess/christophorus) 车辆行车记录簿，含行程、里程链、合理性校验，可导出为 Excel、PDF、JSON 或 Markdown
- [Chronos](https://github.com/samuelstranges/chronos) 类 Vim 的日历 TUI
- [clipse](https://github.com/savedra1/clipse) 基于 TUI 的剪贴板管理应用
- [Desktop-TUI](https://github.com/Julien-cpsn/desktop-tui) 没有图形界面的桌面环境
- [doxx](https://github.com/bgreenwell/doxx) 用于查看 Microsoft Word 文档的 TUI
- [drako](https://github.com/lucky7xz/drako) 基于网格、可定制可扩展的命令与 TUI 面板启动器
- [dvtm](https://github.com/martanne/dvtm) 具备 dwm 风格窗口管理的终端多路复用器
- [fjira](https://github.com/mk-5/fjira) 面向 Atlassian Jira 的 TUI 应用
- [fuzz.fish](https://github.com/jedipunkz/fuzz.fish) 面向 Fish shell 的模糊查找器，带命令历史、文件、git 分支、worktree 与提交的预览面板
- [GeekCalendar](https://github.com/fearlessgeekmedia/GeekCalendar) 带 vim 键位的 TUI 日历，可从 calcure 或 calcurse 导入。
- [Glow](https://github.com/charmbracelet/glow) Markdown 阅读器，从零开始设计以展现 TUI 的优雅与能力。
- [gocheat](https://github.com/Achno/gocheat) 漂亮的 TUI 速查表，涵盖键位绑定、hotkey、手势与别名
- [h-m-m](https://github.com/nadrad/h-m-m) 黑客心智导图
- [helm](https://github.com/0xjuanma/helm) 极简且可自定义的番茄钟式终端计时器
- [hledger-ui](https://github.com/hledgerorg/hledger) 用于浏览复式记账数据的快速 TUI
- [hnjobs](https://github.com/mwinters0/hnjobs) 在 Who's Hiring 上寻找下一份工作
- [HydroFetch](https://github.com/Henriquehnnm/hydrofetch) 专为 Fish shell 编写、快速、美观且轻量的系统信息工具。
- [HydroToDo](https://github.com/Henriquehnnm/hydrotodo) 简洁美观的 TUI 待办清单
- [hygg](https://github.com/kruseio/hygg) 📚 让阅读变得更简单。极简的类 Vim TUI 文档阅读器。
- [intelli-shell](https://github.com/lasantosr/intelli-shell) 管理命令模板与代码片段，支持动态补全与 AI 集成
- [jiratui](https://github.com/whyisdifficult/jiratui) 直接在 shell 中与 Atlassian Jira 交互的 TUI
- [Judo](https://github.com/giacomopiccinini/judo) 多数据库 TUI 工具用于管理待办列表，基于 Rust + Ratatui + SQLite
- [kabmat](https://github.com/PlankCipher/kabmat) 管理看板的 TUI 程序，支持类 vim 键位
- [kanban](https://github.com/kanban-rs/kanban) 用于项目管理的 TUI 看板，带冲刺跟踪与任务优先级。
- [kanban-python](https://github.com/Zaloog/kanban-python) 用 Python 编写的看板终端应用
- [khal](https://github.com/pimutils/khal) 遵循标准的 CLI 日历程序，可与 CalDAV 服务器同步
- [LazySSH](https://github.com/adembc/lazyssh) TUI SSH 管理器，可从 ssh config 文件中浏览、连接并管理服务器。
- [leetrs](https://github.com/shadowmkj/leetrs) 疾速、由 Rust 驱动的 TUI 与引擎，用于在终端中求解 LeetCode 题目
- [levite](https://github.com/RauliL/levite) TUI 电子表格应用，采用 RPN 公式，界面对 vi 友好
- [linear-tui](https://github.com/roeyazroel/linear-tui) 用 Go 与 tview 构建的 Linear 终端用户界面。
- [longbridge-terminal](https://github.com/longbridge/longbridge-terminal) 面向长桥证券的 AI 原生 TUI：覆盖港股/美股/A股/新加坡市场的实时行情、投资组合管理与交易。
- [lssh](https://github.com/blacknon/lssh) 终端原生的远程访问套件，覆盖 SSH 工作流，包括交互式主机选择、并行命令、mux 工作区、文件传输、同步、差异对比、端口转发与多主机监控。
- [mcfly](https://github.com/cantino/mcfly) 智能的、感知上下文的 shell 历史搜索引擎
- [monolog](https://github.com/maksmas/monolog) 键盘驱动的个人待办清单，每个任务存为一个 JSON 文件并置于你自己掌控的 git 仓库中，可跨设备无冲突同步
- [multranslate](https://github.com/Lifailon/multranslate) 同时在多个翻译引擎间翻译文本的 TUI，支持翻译历史与语言检测
- [mynav](https://github.com/GianlucaP106/mynav) 面向终端环境的工作区与会话管理
- [nless](https://github.com/mpryor/nothing-less) 用于浏览表格数据的终端分页器，支持 vi 键位并自动推断分隔符
- [numr](https://github.com/nasedkinpv/numr) 自然语言计算器，支持单位/货币换算与 vim 风格键位
- [openmux](https://github.com/monotykamary/openmux) 采用主从堆叠布局（Zellij 风格）的终端多路复用器
- [Paca](https://github.com/wes/paca) 面向项目的任务、计时与 Stripe 开票，本地优先的 SQLite 存储
- [pagerduty-tui](https://github.com/Mk555/pagerduty-tui) 极简的终端界面，用于管理已触发的事件
- [patat](https://github.com/jaspervdj/patat) 基于 Pandoc 的终端演示工具
- [pdiary](https://github.com/manipuladordedados/pdiary) 用 Python 编写的简易终端日记应用，支持加密
- [pkm](https://github.com/wick3dr0se/pkm) 用 BASH v4.2+ 编写的超极简 TUI 包管理器封装。
- [pomo](https://github.com/Bahaaio/pomo) 极简、可自定义的 TUI 番茄钟，带 ASCII 艺术、进度条、桌面通知与生产力统计。
- [portfolio_rs](https://github.com/MarkusZoppelt/portfolio_rs) 用于管理金融投资组合的命令行工具。
- [pream-team](https://github.com/nikoladucak/pream-team/) 帮助你在多个仓库中跟踪团队 GitHub PR 的 TUI 工具
- [presenterm](https://github.com/mfontanini/presenterm) Markdown 终端幻灯片工具
- [procmux](https://github.com/napisani/procmux) 在易于切换的终端中并行运行多条命令的 TUI
- [productivity-timer](https://github.com/h-sifat/productivity-timer) 带 sleek TUI 的命令行时间追踪应用。
- [sc-im](https://github.com/andmarti1424/sc-im) 面向终端的 ncurses 电子表格程序，sc 的重燃之作
- [SheetsUI](https://github.com/zaphar/sheetsui) 基于控制台的电子表格应用
- [slides](https://github.com/maaslalani/slides) 基于终端的演示工具，支持 markdown 语法。
- [ssh-slides](https://github.com/ivantsepp/ssh-slides) 通过 SSH 进行终端演示
- [sshm](https://github.com/gu1llaum-3/sshm) 让 SSH 变得简单快捷：借助现代 TUI 在终端中浏览、连接与控制
- [Suvadu](https://github.com/AppachiTech/suvadu) 面向 Zsh 与 Bash 的 shell 历史搜索，同时记录 AI 编程智能体执行的命令
- [Tabiew](https://github.com/shshemi/tabiew) 轻量应用，用于查看与查询 CSV、TSV、parquet 等表格数据文件。
- [taskline](https://github.com/perryrh0dan/taskline) 命令行环境下的任务、看板与笔记
- [taskwarrior-tui](https://github.com/kdheepak/taskwarrior-tui) Taskwarrior 的终端用户界面
- [television](https://github.com/alexpasmantier/television) 快速且多用途的模糊查找 TUI
- [termscp](https://github.com/veeso/termscp) TUI 文件传输与浏览器，支持 SCP/SFTP/FTP/S3。
- [tiki](https://github.com/boolean-maybe/tiki) 基于 Markdown、用 git 版本管理的项目与问题管理器
- [tmux](https://github.com/tmux/tmux) 终端多路复用器
- [Tock](https://github.com/kriuchkov/tock) 面向命令行的强大时间追踪工具，配有美观的交互式 TUI。
- [tododo](https://github.com/bmarse/tododo) 管理任务与项目的漂亮 TUI TODO.md 管理器
- [todoman](https://github.com/pimutils/todoman) 简洁、遵循标准（ics、DAV）的命令行任务管理器
- [Tomatui](https://github.com/Hiro-Chiba/tomatui) 番茄钟计时器，提供全屏 TUI、极简单行模式与本地会话统计。
- [Toney](https://github.com/SourcewareLab/Toney) 面向现代开发者的快速、轻量、基于终端的记事应用。
- [topydo](https://github.com/topydo/topydo) 使用 todo.txt 格式的强大待办列表应用
- [trx](https://github.com/pie-314/trx) - 终端包管理器，支持模糊搜索与键盘驱动的包发现。
- [ttm](https://github.com/vst93/ttm) SSH 书签管理器，基于 Bubble Tea TUI —— 连接、管理并通过 Gist 同步
- [ttyplot](https://github.com/tenox7/ttyplot) 面向终端的实时绘图工具，数据可从 stdin/管道输入。
- [tui-deck](https://github.com/mebitek/tui-deck) 用 GO 编写的 Nextcloud Deck 应用 TUI 前端
- [tui-slides](https://github.com/Chleba/tui-slides) 终端演示工具，可渲染图片与众多其他组件。
- [TUI_ProjectManager](https://github.com/NicoDblc/TUI_ProjectManager) 用 Rust 编写的简易项目管理待办清单
- [tuidict](https://github.com/404Simon/tuidict) 快速离线词典，支持应用内下载，并从 FreeDict 获取多语言支持
- [tuihub](https://github.com/ashis0013/tuihub) 供个人使用的工具中心/仪表盘
- [TUIOS](https://github.com/Gaurav-Gosain/tuios) 用于管理多个终端会话的 TUI 窗口管理器
- [tvterm](https://github.com/magiblot/tvterm) 运行在终端里的终端模拟器
- [Visidata](https://github.com/saulpw/visidata) 用于发现与整理数据的终端电子表格多面手
- [xleak](https://github.com/bgreenwell/xleak) 带交互式 TUI 的快速终端 Excel 查看器
- [zeit](https://github.com/mrusme/zeit) 用于追踪各项活动耗时的命令行工具。
- [zellij](https://github.com/zellij-org/zellij) 开箱即用的终端工作区

---

</details>

<a id="screensavers"></a>
<details open><summary><h2>屏保</h2></summary>

- [astroterm](https://github.com/da-luce/astroterm) 属于你终端的 planetarium！探索恒星、行星、星座以及更多
- [cbirds](https://github.com/clainstone/cbirds) 终端中的一群 boids，用 C99 编写且零依赖：处处可用盲点字符，在 Kitty 与 Ghostty 中可用精灵图
- [gitlogue](https://github.com/unhappychoice/gitlogue) 在终端中可视化 Git 提交历史的 TUI 屏保
- [neo](https://github.com/st3w/neo) 模拟《黑客帝国》中的数字雨
- [pond](https://gitlab.com/alice-lefebvre/pond) 令人放松的终端待机画面，模拟一方小池塘。
- [rxpipes](https://github.com/inunix3/rxpipes) 经典 Pipes 屏保的 2D 终端复刻版。
- [weathr](https://github.com/veirt/weathr) 带 ASCII 动画的终端天气应用，用动画呈现天气状况

---

</details>

<a id="web"></a>
<details open><summary><h2>网页</h2></summary>

- [bombadillo](https://bombadillo.colorfield.space/) 面向非 Web 世界的 TUI 浏览器：Gopher、Gemini、Finger
- [browsh](https://github.com/browsh-org/browsh) 现代化的纯文本浏览器，可渲染到 TTY 与浏览器
- [bulletty](https://github.com/CrociDB/bulletty) 漂亮的订阅源阅读器 (ATOM/RSS)，把文章存为 Markdown 文件
- [carbonyl](https://github.com/fathyb/carbonyl) 在你的终端里运行的 Chromium
- [castero](https://github.com/xgi/castero) 收听播客的 TUI 应用
- [CatenaVetus](https://github.com/jimbob88/CatenaVetus) 阅读教父（教父）的 TUI
- [Chawan](https://chawan.net) TUI 浏览器（同时支持 (S)FTP、Gopher、Gemini），带 CSS、内联图片与 JavaScript 支持。
- [cloudflare-speed-cli](https://github.com/kavehtehrani/cloudflare-speed-cli) 通过 Cloudflare 测速
- [console-error-scanner](https://github.com/michaelblaess/console-error-scanner) 从 URL 或站点地图扫描网站，报告浏览器控制台错误与 HTTP 失败 (404、5xx)，输出 HTML 与 JSON 报告
- [eilmeldung](https://github.com/christo-auer/eilmeldung) RSS 阅读器，支持多种 RSS 提供方、批量操作与配置选项。
- [elinks](https://github.com/rkd77/elinks) ELinks (HTTP/FTP/..) 浏览器，支持 mujs javascript。
- [hackernews-TUI](https://github.com/aome510/hackernews-TUI) 在终端里浏览 Hacker News 的 TUI
- [haxor-news](https://github.com/donnemartin/haxor-news) 浏览 Hacker News，就像一个黑客：Hacker News 命令行界面 (CLI)
- [Lagrange](https://gmi.skyjake.fi/lagrange) Lagrange 是一个浏览 Geminispace 的跨平台客户端
- [LYNX](https://lynx.invisible-island.net/) 经典的纯文本终端浏览器
- [newsboat](https://github.com/newsboat/newsboat) 面向文本控制台的 RSS/Atom 订阅源阅读器
- [nyaa](https://github.com/Beastwick18/nyaa) 用于浏览与下载种子文件的 nyaa.si TUI
- [omaro](https://github.com/Rolv-Apneseth/omaro) 用于浏览 lobste.rs 帖子与评论的 TUI
- [podliner](https://github.com/timkicker/podliner) 跨平台播客客户端
- [rfc_reader](https://github.com/ozan2003/rfc_reader) 带 TUI 的 RFC 阅读工具，可获取、缓存并浏览 RFC 文档。
- [rtorrent](https://github.com/rakshasa/rtorrent) 基于文本的 BitTorrent 客户端，用 C++ 编写
- [rttt](https://gitlab.com/BlackEdder/rttt) 用 C++ 编写的、支持 Hackernews、RSS 与 Reddit 的终端阅读器。
- [searxngr](https://github.com/scross01/searxngr) 面向 SearXNG 的 TUI 网页搜索
- [sitemap-tracker](https://github.com/michaelblaess/sitemap-tracker) 爬取网站并生成 sitemap.xml，带站点地图树形视图与爬取历史
- [Slumber](https://github.com/LucasPickering/slumber) 基于终端的 HTTP/REST 客户端
- [stegodon](https://github.com/deemkeen/stegodon) 以 SSH 为先的联邦式微型博客，支持 ActivityPub、网页界面与 RSS 订阅源
- [surge](https://github.com/SurgeDM/Surge) 简洁漂亮、运行飞快的 TUI 下载管理器，用 Go 编写。
- [tblogs](https://github.com/ezeoleaf/tblogs) 在终端中阅读与浏览开发博客
- [textual-web](https://github.com/Textualize/textual-web) 在浏览器中运行 TUIs 与终端
- [twterm](https://github.com/ryota-ka/twterm) 功能完备的 TUI Twitter 客户端
- [w3m](https://github.com/tats/w3m) 文本模式的 WWW 浏览器

---

</details>
