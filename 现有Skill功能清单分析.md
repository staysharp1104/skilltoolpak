# 现有 Skill 功能清单分析

> 分析时间: 2026-07-03  
> 总技能数: 2813+ 个  
> 插件来源: 15 个（Superpowers / BB Browser / UI-UX Pro Max / Gingiris Skills / Rlues VibeCoding / CataForge / Sopify / Hermes Skills / UI-UX Pro Max Skill / GitHubM / ECC / impeccable / wiseflow / xiaohongshu-mcp / openclaw-master-skills）

---

## 一、Superpowers（14 个技能）

> 开发者效率工具箱 — 编码工作流全链路

| 技能名称 | 功能描述 | 触发场景 |
|---------|---------|---------|
| **using-superpowers** | Superpowers 入口路由，指导如何发现和调用各子 skill | 任何对话开始 |
| **writing-plans** | 根据 spec 或需求编写多步骤执行计划 | 多步骤任务前 |
| **executing-plans** | 在独立 session 中以检查点方式执行已有计划 | 有书面计划时 |
| **subagent-driven-development** | 在当前 session 中用独立 subagent 并行执行计划中的独立任务 | 有独立可并行任务时 |
| **brainstorming** | 任何创意工作前的头脑风暴（feature、组件、函数）| 任何创造性工作前 |
| **test-driven-development** | 实现代码前先写测试的 TDD 流程 | 任何 feature/bugfix 前 |
| **systematic-debugging** | 系统性 bug 诊断流程，提出修复方案前先定位根因 | 遇到 bug/测试失败时 |
| **requesting-code-review** | 完成任务后请求代码审查，确保满足需求 | 功能实现完成/合并前 |
| **receiving-code-review** | 收到审查反馈后实施修改的流程 | 收到 review 意见时 |
| **verification-before-completion** | 声称工作完成前做最终核验 | 提 PR/提交前 |
| **finishing-a-development-branch** | 实现完成后的分支整合决策流程（commit/PR/更新plan）| 实现完成时 |
| **dispatching-parallel-agents** | 面对 2+ 个独立无依赖任务时，分派并行 subagent | 多个独立任务并行 |
| **using-git-worktrees** | 使用 git worktree 隔离 feature 工作区 | 需要隔离当前工作区时 |
| **writing-skills** | 创建/编辑/验证 skill 的标准化流程 | 新建或修改 skill 时 |

---

## 二、BB Browser（2 个技能）

> 浏览器自动化 + 开放数据采集

| 技能名称 | 功能描述 | 触发场景 |
|---------|---------|---------|
| **bb-browser** | 浏览器自动化工具，可访问任意网页/内部系统/登录后页面，执行表单填写、信息提取、页面操作。支持 36 平台 103 命令 | 需要获取公域/私域信息、自动化页面操作 |
| **bb-browser-openclaw** | 将任意网站转化为 CLI 命令。36 平台 103 命令 — Twitter/Reddit/GitHub/YouTube 等 | 需要以 CLI 方式操作或采集网站数据 |

---

## 三、UI-UX Pro Max（7 个技能）

> UI/UX 设计全流程

| 技能名称 | 功能描述 | 触发场景 |
|---------|---------|---------|
| **ui-ux-pro-max** | UI/UX 设计入口路由。含 50+ 风格、161 色调色板、57 种字体配对 | 整体 UI/UX 设计需求 |
| **design** | 综合设计：品牌识别、设计 tokens、UI 样式、Logo 生成（55 风格） | 品牌+UI 综合设计 |
| **design-system** | Token 架构、组件规范、幻灯片生成。三层 Token（primitive→semantic→component）| 设计系统搭建 |
| **ui-styling** | 使用 shadcn/ui 组件创建美观可访问的 UI（基于 Radix UI + Tailwind）| 具体 UI 样式实现 |
| **banner-design** | 社媒/广告/网站 Hero/创意资产/印刷品横幅设计，多种艺术方向 | 横幅/广告设计 |
| **slides** | 使用 Chart.js、设计 tokens、响应式布局创建战略 HTML 演示文稿 | 创建演示文稿 |
| **brand** | 品牌调性、视觉识别、信息传达框架、资产管理 | 品牌建设与一致性维护 |

---

## 四、Gingiris Skills（58 个技能）

> 出海增长运营工具箱 — 覆盖 ASO/SEO/B2B SaaS/PH Launch/开源营销等

### 4.1 核心增长 Playbooks（14 个）

| 技能名称 | 功能描述 | 适用场景 |
|---------|---------|---------|
| **gingiris-aso-growth** | ASO & App 冷启动：关键词优化、应用商店排名、UGC 创作者运营、TikTok/YouTube Shorts 营销 | App 发布与增长 |
| **gingiris-b2b-growth** | B2B SaaS 增长：PLG vs SLG 诊断、PMF→$10M ARR 完整路径 | B2B SaaS 增长策略 |
| **gingiris-seo-geo** | SEO & GEO（生成式引擎优化）双引擎：Google 排名 + AI 搜索（ChatGPT/Perplexity/Gemini）引用 | 搜索引擎与 AI 搜索双优化 |
| **gingiris-seo-geo-agent** | SEO/GEO Agent 运维：月均 32K 曝光量自动化运营 SOP | SEO Agent 自动化 |
| **gingiris-go-global** | AI 产品出海全流程：从竞品研究到发布到变现的完整 SOP | 全球化出海 |
| **gingiris-launch** | 产品发布：多渠道 GTM 发布时序。T-14 预热→发布日→冷启动 | 产品发布 |
| **gingiris-opensource** | 开源营销 & GitHub Stars 增长系统：各增长阶段决策框架 | 开源项目增长 |
| **gingiris-github-star-growth** | GitHub Stars 持续增长：月均 300+ Stars SOP | GitHub Stars |
| **gingiris-kol-outreach** | KOL 拓展 & 网红营销：从发现到 ROI 追踪的完整 SOP | KOL 合作 |
| **gingiris-ugc-matrix** | UGC 矩阵增长：AI+真人创作用户生成内容规模化 | UGC 规模化 |
| **gingiris-growth-finder** | 增长路由器：诊断增长问题并调用正确的 playbook | 增长策略诊断 |
| **gingiris-user-interview** | 用户访谈 & PMF 验证：937 次访谈验证的 JTBD 框架 | 用户研究 |
| **gingiris-twitter-agent-ops** | Twitter/X Agent 运营：自动发推、内容策略、互动管理 | 社媒自动化 |
| **gingiris-ugc-matrix** | UGC 矩阵增长：Viral Distribution System | 内容病毒传播 |

### 4.2 GR 执行技能（18 个）

| 技能名称 | 功能描述 | 适用场景 |
|---------|---------|---------|
| **gr** | 增长工具箱主入口，自动路由到对应子 skill | 增长问题入口 |
| **gr-core** | 增长工具箱主入口路由（同上） | 增长问题入口 |
| **gr-aso** | ASO 执行：App Store 关键词 & 评分优化 | ASO 执行 |
| **gr-b2b-growth** | B2B 增长执行：PLG 漏斗 & 企业销售 | B2B 执行 |
| **gr-backlinks** | 外链建设：5 渠道 SEO 权威系统（Wikipedia/PR/G2/Reddit/通用）| 外链建设 |
| **gr-blog-post** | Jekyll 博客发布流水线：Iris 文风写作（时间锚定/括号旁白/em-dash转折/Key Stats 表格）| SEO 博客 |
| **gr-competitor** | 竞品深度扫描：批量抓取落地页/定价页/博客。底层调 actionbook（30 tab 并发）| 竞品分析 |
| **gr-competitor-research** | 竞品调研执行 | 竞品调研 |
| **gr-geo-cite** | GEO 引用追踪优化：每周检测 Claude/GPT/Perplexity/Gemini 引用情况 | AI 搜索优化 |
| **gr-community-ambassador** | 社区大使执行 | 社区运营 |
| **gr-oss-marketing** | 开源营销执行：GitHub/KOL/Reddit/HN/Discord 社群分发 | 开源营销 |
| **gr-ph-launch** | Product Hunt 发布执行：T-14→T-0→T+7 完整流程 | PH 发布 |
| **gr-product-dev-ops** | 产品开发运维 | 产品工程 |
| **gr-readme** | GitHub README 写作：3 秒转化框架（AFFiNE 0→60K Stars 经验）| README 优化 |
| **gr-seo-geo-agent** | SEO Agent 运维：自动化每日审计、排名追踪、schema 校验 | SEO Agent |
| **gr-seo-patrol** | 每日 SEO/GEO 巡逻：SERP 排名/Google 索引/llms.txt/GA4/Canonical | SEO 日常 |
| **gr-social-distill** | 社媒蒸馏：一篇博客 → 4 社媒变体（X Thread/小红书/LinkedIn/dev.to）| 内容复用 |
| **gr-user-interview** | 用户访谈框架：招募→问题设计→执行→合成 | 用户访谈 |

### 4.3 营销 Playbooks & 指南（23 个）

| 技能名称 | 功能描述 | 适用场景 |
|---------|---------|---------|
| agent-workflow-playbook | AI Agent 工作流 & Skill 架构设计指南 | Agent 系统设计 |
| ai-launch-playbook | AI 产品全球发布：Manus/Devin/AFFiNE 破圈策略 | AI 产品发布 |
| ai-product-launch | 首次 AI 产品发布：30 天从 0 到上线 | 首次发布 |
| aso-playbook | ASO 入门指南：关键词/截图/评分 | ASO 入门 |
| b2b-marketing-playbook | B2B 营销管道：LinkedIn 内容 + Cold Email + Webinar 漏斗 | B2B 营销 |
| community-ambassador-playbook | 社区大使 SOP：招募→分级管理→留存→治理 | 社区大使 |
| community-building-playbook | 开发者/用户社区自建 | 社区建设 |
| competitor-research-playbook | 竞品调研：Wayback 官网演变 + Twitter 传播链 + 飞轮评分（150+ 实战）| 竞品调研 |
| developer-marketing-playbook | 开发者营销：DevRel/Documentation as Marketing/API | 开发者营销 |
| devrel-playbook | 开发者关系：社区建设→文档策略→活动 | DevRel |
| github-stars-playbook | GitHub Stars 14 天冲刺计划 | Stars 冲刺 |
| go-to-market-playbook | GTM 策略模板：B2B+B2C 定位/消息/渠道 | GTM 策略 |
| growth-hacking-playbook | 50 种增长手段（按投入/影响排序）| 增长实验 |
| kol-outreach | KOL 冷联系模板：Twitter DM/Email 脚本/跟进 | KOL 联系 |
| open-source-marketing-playbook | 非技术创始人的开源项目营销 | 开源营销 |
| plg-playbook | PLG 完整指南：Freemium/自助 Onboarding/激活 | PLG 策略 |
| product-hunt-launch-guide | 首次 PH 发布指南：时机/Hunter 选择/素材 | PH 首次 |
| product-hunt-launch-playbook-win-1-daily | PH 发布—赢取日冠：30 次日冠经验 | PH 冲冠 |
| product-hunt-playbook | PH 发布操作手册：排名算法/时间/社区 | PH 发布 |
| saas-growth-playbook | SaaS $0→$50K MRR：定价实验/留存/渠道 | SaaS 增长 |
| saas-marketing-playbook | SaaS 营销栈：工具/渠道/指标按阶段组织 | SaaS 营销 |
| startup-consultant | 初创增长顾问：PH 发布/开源营销/GTM | 创业咨询 |
| startup-growth-playbook | 种子期增长：渠道选择与优先级 | 种子期增长 |
| startup-launch | 发布日逐小时执行清单 | 发布日 |
| startup-launch-playbook | 早期初创 Pre-seed→首批 1000 用户 | 早期启动 |
| startup-marketing-playbook | 零预算初创营销：纯有机渠道 | 零预算营销 |
| viral-marketing-playbook | 产品病毒循环设计：推荐/邀请/分享机制 | 病毒增长 |

---

## 五、Rlues VibeCoding（6 个技能）

> VibeCoding RIPER-7 开发工作流 — 项目初始化→需求精炼→技术调研→方案定稿→计划排期→编码执行→测试审查→断点恢复

| 技能名称 | 功能描述 | 触发场景 |
|---------|---------|---------|
| **rlues-vibecoding-vibecoding-init** | 项目初始化。创建 `.ai_state/` 状态管理目录和 5 个模板文件，检测项目类型 | 首次启动 VibeCoding 工作流 |
| **rlues-vibecoding-vibecoding-plan** | 规划三阶段：R0 需求精炼（MUST/SHOULD/COULD 分级）→ R 技术调研（复用代码/新增依赖/技术风险）→ D 方案定稿（接口最小化/错误处理/变更文件清单） | 用户给出开发需求时 |
| **rlues-vibecoding-vibecoding-execute** | 执行阶段：P 计划排期（原子任务拆分 + Sprint Contract）+ E 编码执行（Reflexion 自查 + Sisyphus 规则） | 方案确认后开始编码 |
| **rlues-vibecoding-vibecoding-review** | 审查阶段：T 测试验证 + Quality Gate 四维评估（功能完整性/代码质量/一致性/安全性），含 PASS/CONCERNS/REWORK/FAIL 判定 | 编码完成后 |
| **rlues-vibecoding-vibecoding-workflow** | 核心工作流引擎。根据 Path A/B/C/D 编排 RIPER-7 各阶段，调度子 skill 执行，含 V 归档阶段 | 任何开发任务开始时 |
| **rlues-vibecoding-vibecoding-recovery** | 断点恢复。从 `.ai_state/` 读取上次进度（phase/进度/积压）并恢复执行 | 会话中断后继续开发 |

---

## 六、CataForge（3 个技能 + 12 个 Agent）

> CataForge 工程开发框架 — 调查研究、UI 设计、技术评估三大核心技能，配以 12 个子 Agent 角色

| 技能名称 | 功能描述 | 触发场景 |
|---------|---------|---------|
| **cataforge-research** | 调查研究：网络检索（web-search）+ 用户访谈（user-interview）+ 资料查阅（doc-lookup），解决信息不确定性。产出调研记录与选项，标注来源和可信度 | 遇到信息缺失/需求模糊/技术选型需对比时 |
| **cataforge-ui-design** | UI 设计：设计方向决策→设计系统 Token（色彩/排版/间距）→页面布局→组件规范→交互流程→响应式策略→组件目录维护 | 需要做 UI 设计、定义设计系统时 |
| **cataforge-tech-eval** | 技术评估：方案对比分析（四维：性能/生态/学习成本/EOL风险）+ 版本生命周期验证 + 选型推荐 | 技术选型、框架/库对比时 |

### 附加 Agent 角色（12 个）

| Agent | 职责 |
|-------|------|
| **orchestrator** | 中央编排，路由各阶段到对应 Agent |
| **architect** | 架构设计，技术方案审核 |
| **product-manager** | 需求分析，PRD 编写 |
| **ui-designer** | UI 与设计系统 |
| **tech-lead** | 技术规划，开发计划 |
| **implementer** | 编码实现 |
| **test-writer** | 测试编写 |
| **refactorer** | 代码重构 |
| **qa-engineer** | 质量保障 |
| **devops** | 部署运维 |
| **debugger** | Bug 诊断修复 |
| **reviewer** | 代码审查 |

---

## 七、Sopify（6 个技能）

> Sopify 方案设计与开发实施 SOP — 需求分析→方案设计→开发实施→交叉评审→知识库管理

| 技能名称 | 功能描述 | 触发场景 |
|---------|---------|---------|
| **sopify-analyze** | 需求分析：需求评分、追问、复杂度路由判定。知识库检查→需求类型判定→完整性评分 | 进入开发工作流需求分析阶段 |
| **sopify-design** | 方案设计：方案分级（light/standard/full）→ 任务拆分 → 方案包输出，含评分区块 | 需求明确后进入方案设计 |
| **sopify-develop** | 开发实施：任务执行→状态更新→知识库同步→收尾迁移。按编号顺序执行任务 | 方案确认后开始开发 |
| **sopify-kb** | 知识库管理：分层知识管理（blueprint/project/user/preferences/history），初始化/更新/同步策略 | 管理 `.sopify/` 知识库 |
| **sopify-templates** | 文档模板集合：知识库模板和方案文件模板，含 project.md/design.md/tasks.md 等完整模板 | 创建 SOP 文档时 |
| **sopify-cross-review** | 交叉评审：隔离上下文中审查 AI 生成代码变更。ReviewPack 打包→渲染 prompt→隔离审查→ingest→Advisory Verdict | 开发完成后代码审查 |

---

## 八、Hermes Skills（309 个技能）

> 全能 AI 技能包，覆盖工程开发、设计、游戏、生产力、学术研究、DevOps、多媒体等几乎所有领域

### 8.1 领域分布总览

| 能力域 | 技能数 | 能力域 | 技能数 |
|--------|:------:|--------|:------:|
| 🔧 **专项技能**（specialized）| 45 | 🎯 **销售**（sales）| 8 |
| 📣 **营销**（marketing）| 35 | 💰 **金融**（finance）| 8 |
| 🖥️ **工程开发**（engineering）| 34 | 🛍️ **付费媒体**（paid-media）| 7 |
| 🤖 **MLOps/ML**（mlops）| 22 | 📱 **软件开发**（software-development）| 7 |
| 🧪 **测试**（testing）| 9 | 🐙 **GitHub**（github）| 7 |
| 🎨 **创意**（creative）| 9 | 🔬 **研究**（research）| 6 |
| ✏️ **设计**（design）| 8 | 🧠 **空间计算**（spatial-computing）| 6 |

### 8.2 各领域概要

| 领域 | 技能数 | 典型技能 | 核心能力 |
|------|:------:|---------|---------|
| **专项技能** | 45 | 泛指各领域专项能力组合 | 45 个跨领域专项能力 |
| **营销** | 35 | 社媒营销、邮件营销、广告优化、A/B测试等 | 全渠道营销执行能力 |
| **工程开发** | 34 | 前端/后端/嵌入式/SRE/数据库/架构/微信小程序/钉钉集成 | 全栈工程能力，含移动端与内部系统集成 |
| **MLOps/ML** | 22 | 模型训练管道、数据标注、模型部署、A/B实验平台 | 机器学习全生命周期管理 |
| **设计** | 8 | UI设计、UX研究、视觉叙事、品牌守护、包容性设计、动效注入 | 完整设计链路 |
| **游戏开发** | 20+ | Unreal Engine（世界构建/多人架构/系统/TA）、Unity（架构/编辑器/多人/Shader/艺术家）、Godot（多人/Shader/脚本）、Roblox Studio、Minecraft | 多引擎游戏开发全覆盖 |
| **生产力工具** | 6 | Notion、Linear、PDF、OCR、PowerPoint、Google Workspace | 日常办公自动化 |
| **学术研究** | 6 | ArXiv、ML论文写作、LLM Wiki、BlogWatcher、PolyMarket | 学术调研与论文辅助 |
| **DevOps** | 2 | Memory GitHub 同步、Webhook 订阅 | CI/CD 与自动化 |
| **多媒体** | 4 | YouTube、音乐生成、GIF搜索 | 音视频内容创作 |
| **社媒运营** | 2 | Xitter、Binance Square | 社媒内容发布 |
| **智能家居** | 1 | OpenHue（飞利浦 Hue 灯光控制）| 物联网设备控制 |
| **AI Agent** | 5 | Claude Code、Agent Browser、Codex、Hermes Agent、OpenCode | AI Agent 开发与管理 |

> Hermes Skills 包含来自 50+ 子目录的 309 个技能，覆盖从底层工程到上层营销的完整技术栈
  
---

## 九、UI-UX Pro Max Skill（7 个技能）

> UI-UX Pro Max 设计技能包（新版独立插件）

| 技能名称 | 功能描述 | 触发场景 |
|---------|---------|---------|
| **uiuxskill-ui-ux-pro-max** | UI/UX 设计入口路由，含风格库/色调板/字体配对 | 整体 UI/UX 设计需求 |
| **uiuxskill-design** | 综合设计：品牌识别、设计 tokens、UI 样式、Logo 生成 | 品牌+UI 综合设计 |
| **uiuxskill-design-system** | Token 架构、组件规范、幻灯片生成。三层 Token 架构 | 设计系统搭建 |
| **uiuxskill-ui-styling** | 使用 shadcn/ui 创建美观可访问的 UI（Radix UI + Tailwind）| 具体 UI 样式实现 |
| **uiuxskill-banner-design** | 社媒/广告/网站 Hero/创意资产横幅设计 | 横幅/广告设计 |
| **uiuxskill-slides** | 使用 Chart.js、设计 tokens 创建 HTML 演示文稿 | 创建演示文稿 |
| **uiuxskill-brand** | 品牌调性、视觉识别、信息传达框架 | 品牌建设与一致性维护 |

> 此插件与 Superpowers 的 UI-UX Pro Max（7 技能）功能重叠，为同一设计体系的不同发行版本

---

## 十、GitHubM（69 个技能）

> 实用工具 API 技能包 — 百度 API、AI 生成、OCR 识别、金融行情等

| 类别 | 技能数 | 典型技能 |
|------|:------:|---------|
| 🌐 **百度 API 系列** | 11 | 搜索/地理编码/SEO排名/IP定位/POI/天气/交通/百科/AI搜索 |
| 🤖 **MiniMax AI** | 7 | 对话/文生图/图生视频/文生视频/TTS/主题视频 |
| 📄 **OCR 识别** | 9 | 身份证/飞机票/火车票/出租车票/网约车/汽车票/高精度 OCR |
| 🎨 **AI 生成** | 5 | 文生图/图生图/文生视频/图生视频/Sora 视频 |
| 🖼️ **图像识别** | 3 | 人脸对比/人脸识别/物体场景识别 |
| 🔄 **快手 Kling AI** | 4 | 视频生成/图生视频/图片扩展/Omni 图片生成 |
| 💹 **金融行情** | 3 | 股票/汇率/贵金属 K 线 |
| 🏢 **企业查询** | 3 | 工商信息/招聘数据/专利查询 |
| 🎤 **语音 TTS** | 2 | 短文本 TTS/超长文本 TTS |
| 🎧 **语音识别** | 1 | 短语音识别 |
| 🌍 **翻译** | 1 | 200+ 语言翻译 |
| 📅 **生活服务** | 4 | 驾照题库/彩票/快递/限行 |
| 🆔 **身份验证** | 2 | 企业三要素/短信验证码 |
| 🔥 **热搜榜** | 2 | 多平台热搜/垂类热搜 |
| 📝 **文档/PPT** | 2 | AI 生成 PPT/文档格式转换 |
| 🌤️ **天气查询** | 1 | 实时天气/未来 7-15 天预报 |
| 📚 **其他** | 5 | 网页阅读/摘要/多模态/ISBN/路线规划 |

| 技能名称 | 功能描述 | 触发场景 |
|---------|---------|---------|
| **githubm-baidu-search** | 百度千帆 AI 全网搜索，返回结构化引用 | 中文实时信息搜索 |
| **githubm-baidu-geocoding** | 地址/坐标互转、LBS 定位 | 地图定位、导航 |
| **githubm-baidu-seo-keyword-ranking** | 百度 PC 端关键词排名查询 | SEO 分析与竞品监控 |
| **githubm-baidu-weather-query** | 国内城市实时天气+未来7天预报 | 天气查询 |
| **githubm-baidu-encyclopedia** | 百度百科词条查询 | 知识获取 |
| **githubm-baidu-poi-detail** | POI 地点搜索与详情 | 商圈/周边设施查询 |
| **githubm-baidu-ai-search** | 百度千帆 AI 搜索（含视频） | 实时信息检索 |
| **githubm-baidu-ip-geolocation** | IP 地址定位 | 用户属地识别 |
| **githubm-baidu-traffic-condition** | 实时路况查询 | 出行导航 |
| **githubm-baidu-region-search** | 行政区划查询 | 地理信息查询 |
| **githubm-baidu-poi-multidim-search** | 多维 POI 自然语言检索 | 综合地点搜索 |
| **githubm-minimax-chat** | MiniMax M2.5 多轮对话 | AI 对话/内容生成 |
| **githubm-minimax-text-to-image** | MiniMax 文生图 | 创意设计 |
| **githubm-minimax-image-to-image** | MiniMax 图生图 | 图像风格转换 |
| **githubm-minimax-image-to-video** | MiniMax 图生视频 | 静态图转动态视频 |
| **githubm-minimax-text-to-video** | MiniMax 文生视频 | 短视频创作 |
| **githubm-minimax-subject-to-video** | 人物主体图片+文本生成视频 | 人物视频生成 |
| **githubm-minimax-tts** | MiniMax 文本转语音 | 有声内容 |
| **githubm-kling-video-generation** | 可灵 Omni 视频生成 | AI 视频创作 |
| **githubm-kling-image-to-video** | 可灵参考图生视频 | 电商视频 |
| **githubm-kling-image-expand** | 可灵图片扩图编辑 | 图片尺寸调整 |
| **githubm-kling-omni-image-generation** | 可灵 Omni 文生图/图生图 | 创意设计 |
| **githubm-sora-video-generation** | Sora 2 高级视频生成 | AI 视频创作 |
| **githubm-image-generation-advanced** | 高级图生图/文生图/多图合成 | 图片生成编辑 |
| **githubm-image-generation-super** | GPT-Image-2 超级版生成 | AI 画图 |
| **githubm-text-to-video** | 文本生成短视频 | 电商营销 |
| **githubm-image-to-video** | Kling 静态图转视频 | 视频创作 |
| **githubm-short-text-tts** | 短文本（≤500字）MP3 合成 | 语音通知/播报 |
| **githubm-long-text-tts** | 超长文本（10万字符）异步 TTS | 有声书/新闻播报 |
| **githubm-short-speech-recognition** | 60秒语音转文字 | 语音输入/指令 |
| **githubm-text-translation** | 百度翻译 200+ 语言 | 多语言翻译 |
| **githubm-accurate-ocr** | 高精度通用文字识别 | 文档数字化 |
| **githubm-id-card-ocr** | 身份证正反面信息识别 | 实名认证 |
| **githubm-id-card-two-factor-auth** | 身份证二要素实名认证 | 身份核验 |
| **githubm-rideshare-receipt-ocr** | 网约车行程单识别 | 财务报销 |
| **githubm-taxi-receipt-ocr** | 出租车票 16 字段识别 | 费用管理 |
| **githubm-bus-ticket-ocr** | 全国汽车票关键字段识别 | 票据管理 |
| **githubm-air-ticket-ocr** | 飞机行程单 24 字段识别 | 差旅报销 |
| **githubm-train-ticket-ocr** | 红/蓝火车票/电子客票识别 | 财务报销 |
| **githubm-train-ticket-query** | 车次/余票/票价查询 | 出行规划 |
| **githubm-face-comparison** | 两张人脸相似度对比 | 身份验证 |
| **githubm-face-recognition** | 人脸库管理+搜索 | 考勤签到 |
| **githubm-object-scene-recognition** | 物体场景标签识别 | 图片内容分析 |
| **githubm-image-understanding** | 图片多维度理解问答 | 图片分析 |
| **githubm-multimodal-llm** | 文心多模态图文混合输入 | 图文分析/拍照解题 |
| **githubm-gemini-image-editing** | Gemini 文本指令图片编辑 | AI 图片编辑 |
| **githubm-wenxin-text-generation** | ERNIE 4.5 流式文本生成 | 内容创作 |
| **githubm-stock-realtime-quote** | 沪深实时行情+K线 | 股票投资 |
| **githubm-currency-exchange-rate** | 200+ 货币实时汇率 | 汇率换算 |
| **githubm-precious-metal-kline** | 贵金属实时行情+K线 | 贵金属投资 |
| **githubm-weather-forecast** | 今日/7天/15天天气预报 | 天气查询 |
| **githubm-company-info-lookup** | 企业工商全维度信息 | 企业尽调 |
| **githubm-company-hiring-data** | 企业招聘概况统计 | 企业调研 |
| **githubm-patent-search** | 企业专利申请查询 | 知识产权管理 |
| **githubm-phone-location-lookup** | 手机号归属地查询 | 风控校验 |
| **githubm-ai-ppt-generator** | 主题自动生成 PPT | 办公汇报 |
| **githubm-document-format-conversion** | 图片/PDF 转 Word/Excel | 文档格式转换 |
| **githubm-web-reader** | URL 网页内容抓取转 Markdown | 网页阅读分析 |
| **githubm-webpage-summarizer** | 网页分析/摘要/问答 | 新闻摘要 |
| **githubm-isbn-lookup** | ISBN 图书信息查询 | 图书管理 |
| **githubm-trending-list** | 9 大平台实时热搜 | 内容创作/舆情 |
| **githubm-vertical-trending-list** | 抖音/小红书垂类热搜 | 热点追踪 |
| **githubm-route-planning** | 驾车/步行/骑行/公交路线规划 | 出行规划 |
| **githubm-lottery-draw-query** | 彩票开奖/历史/奖池查询 | 彩票查询 |
| **githubm-driving-exam-questions** | 驾考科目一/四题库 | 驾考备考 |
| **githubm-realtime-express-tracking** | 快递物流实时查询 | 快递查询 |
| **githubm-vehicle-traffic-restriction** | 全国城市限行查询 | 出行规划 |
| **githubm-sms-verification** | 短信验证码发送+验证 | 身份核验 |
| **githubm-enterprise-three-factor-auth** | 企业三要素验证 | 企业身份核实 |
| **githubm-baidu-seo-keyword-ranking** | SEO 关键词排名 | SEO 监控 |

---

## 十一、能力总览矩阵

| 能力域 | 技能数 | 来源 |
|--------|:------:|------|
| 🛠️ **开发工作流**（Plan/TDD/Review/Branch/Verify）| 14 | Superpowers |
| 🌐 **浏览器自动化** | 2 | BB Browser |
| 🎨 **UI/UX 设计**（品牌/设计系统/样式/横幅/幻灯片）| 7 | UI-UX Pro Max |
| 📈 **ASO & App 增长** | 3 | Gingiris |
| 🔍 **SEO & GEO**（排名/AI引用/Agent运维）| 5 | Gingiris |
| 📊 **竞品分析**（扫描/飞轮/传播链）| 3 | Gingiris |
| 🚀 **产品发布**（GTM/PH Launch/全球出海）| 6 | Gingiris |
| 💼 **B2B & SaaS 增长**（PLG/定价/营销栈）| 6 | Gingiris |
| 🌟 **开源营销 & GitHub Stars** | 4 | Gingiris |
| 👥 **社区运营**（大使/DevRel/社群）| 4 | Gingiris |
| 📝 **内容营销**（博客/社媒蒸馏/README/病毒）| 6 | Gingiris |
| 🤝 **KOL & 用户研究**（拓展/访谈/PMF）| 4 | Gingiris |
| 🧠 **增长策略**（路由器/50手段/飞轮评分）| 4 | Gingiris |
| 📋 **通用营销 Playbooks** | 10 | Gingiris |
| 🤖 **AI Agent 工作流** | 2 | Gingiris |
| 🔄 **VibeCoding 全流程**（初始化→规划→执行→审查→恢复）| 6 | Rlues VibeCoding |
| 🏗️ **工程开发框架**（调研/UI设计/技术评估）| 3 + 12 Agents | CataForge |
| 📑 **SOP 开发框架**（分析/设计/开发/评审/知识库）| 6 | Sopify |
| 🧩 **Hermes 专属领域**（50+ 细分领域专项技能）| 309 | Hermes Skills |
| 📡 **百度 API 系列**（搜索/地图/SEO/IP/天气/百科）| 11 | GitHubM |
| 🎨 **AI 图像/视频生成**（Sora/Kling/MiniMax/文心）| 16 | GitHubM |
| 📄 **OCR 识别**（身份证/票据/车票/通用）| 9 | GitHubM |
| 💹 **金融行情**（股票/汇率/贵金属）| 3 | GitHubM |
| 🏢 **企业信息查询**（工商/招聘/专利）| 3 | GitHubM |
| 🌍 **翻译 & 语音**（翻译/TTS/识别）| 4 | GitHubM |
| 🔥 **热搜 & 生活服务**（热搜/快递/限行/彩票/驾考）| 6 | GitHubM |
| 🎯 **百项实用 API 工具** | 69 | GitHubM |
| 🎨 **设计技能新版**（品牌/设计系统/UI样式/横幅/幻灯片）| 7 | UI-UX Pro Max Skill |

---

## 十二、与本项目的交叉能力分析

| 现有需求 | 可调用的 Skill | 匹配度 |
|---------|---------------|:------:|
| **爬虫开发与调试** | systematic-debugging, bb-browser, cataforge-research | ⭐⭐⭐⭐⭐ |
| **看板 UI 美化** | ui-styling, design, design-system, brand, cataforge-ui-design | ⭐⭐⭐⭐⭐ |
| **新功能实现** | writing-plans, test-driven-development, dispatching-parallel-agents, vibecoding-workflow, cataforge-tech-eval | ⭐⭐⭐⭐⭐ |
| **竞品分析** | gr-competitor, competitor-research-playbook, cataforge-research | ⭐⭐⭐⭐⭐ |
| **SEO 优化（项目官网）** | gingiris-seo-geo, gr-seo-patrol | ⭐⭐⭐⭐ |
| **代码审查** | requesting-code-review, receiving-code-review, sopify-cross-review | ⭐⭐⭐⭐⭐ |
| **用户反馈分析** | gingiris-user-interview, gr-user-interview, cataforge-research | ⭐⭐⭐⭐ |
| **开源项目推广** | gingiris-opensource, gingiris-github-star-growth | ⭐⭐⭐⭐ |
| **README 优化** | gr-readme | ⭐⭐⭐⭐⭐ |
| **全流程开发（需求→设计→编码→审查）** | vibecoding-init → vibecoding-plan → vibecoding-execute → vibecoding-review | ⭐⭐⭐⭐⭐ |
| **方案设计与任务拆分** | sopify-analyze, sopify-design, sopify-develop | ⭐⭐⭐⭐⭐ |
| **知识库管理** | sopify-kb, sopify-templates | ⭐⭐⭐⭐ |
| **技术选型调研** | cataforge-research, cataforge-tech-eval | ⭐⭐⭐⭐⭐ |
| **UI 设计系统搭建** | cataforge-ui-design, ui-styling, design-system | ⭐⭐⭐⭐⭐ |
| **断点恢复（长任务）** | rlues-vibecoding-vibecoding-recovery | ⭐⭐⭐⭐⭐ |
| **百度 API 集成**（搜索/地图/地理编码） | githubm-baidu-search, githubm-baidu-geocoding, githubm-baidu-poi-detail | ⭐⭐⭐⭐⭐ |
| **OCR 识别需求**（身份证/票据/车票） | githubm-id-card-ocr, githubm-train-ticket-ocr, githubm-accurate-ocr | ⭐⭐⭐⭐⭐ |
| **AI 图片/视频生成**（营销素材/封面） | githubm-image-generation-advanced, githubm-text-to-video, githubm-kling-video-generation | ⭐⭐⭐⭐⭐ |
| **翻译需求**（多语言/国际化） | githubm-text-translation | ⭐⭐⭐⭐⭐ |
| **股票/金融行情查询** | githubm-stock-realtime-quote, githubm-currency-exchange-rate | ⭐⭐⭐⭐ |
| **企业信息调研**（竞品公司/招聘/专利） | githubm-company-info-lookup, githubm-company-hiring-data, githubm-patent-search | ⭐⭐⭐⭐ |

---

## 十三、ECC（277 个技能）

> 工程能力全集 — 覆盖 Agent 架构、TDD、代码审查、安全、DevOps、性能优化等全链路工程实践

ECC（Engineering Command Center）来自 [affaan-m/ECC](https://github.com/affaan-m/ECC) 项目，是一套完整的工程 Agent 技能体系。

### 13.1 核心工程技能

| 技能分类 | 技能数 | 代表性技能 | 核心能力 |
|---------|:------:|-----------|---------|
| **Agent 架构与工程** | 15+ | agent-harness-construction, agent-architecture-audit, agent-introspection-debugging, agentic-engineering, agentic-os, autonomous-agent-harness, autonomous-loops | Agent 系统设计、自省调试、自主循环 |
| **测试与质量** | 20+ | test-driven-development, ai-regression-testing, browser-qa, benchmark, benchmark-methodology, benchmark-optimization-loop | TDD 流程、回归测试、基准测试优化 |
| **代码审查与安全** | 15+ | code-review, security-audit, vulnerability-scanning, secrets-detection, dependency-check | 安全审计、漏洞扫描、秘密检测 |
| **架构与设计** | 20+ | architecture-decision-records, api-design, backend-patterns, android-clean-architecture, angular-developer | ADR、API设计、架构模式 |
| **DevOps 与部署** | 20+ | devops-pipeline, dockerfile-generation, kubernetes-config, ci-cd-workflow, infrastructure-as-code | CI/CD、容器化、基础设施即代码 |
| **性能优化** | 10+ | performance-audit, memory-profiling, bundle-optimization, database-query-optimization | 性能审计、内存分析、SQL 优化 |
| **文档与知识管理** | 10+ | documentation-generation, knowledge-base-creation, api-documentation, changelog-generation | 自动文档生成、知识库 |
| **前端工程** | 15+ | frontend-patterns, react-component-architecture, state-management-design, css-architecture, accessibility (a11y) | 前端架构、组件设计、无障碍 |
| **后端工程** | 20+ | backend-patterns, microservice-design, graphql-api-design, rest-api-best-practices, database-schema-design | 微服务、GraphQL、REST、数据库 |
| **AI/ML 工程** | 10+ | ml-pipeline-design, model-evaluation, prompt-engineering, ai-first-engineering | ML 管道、模型评估、Prompt 工程 |
| **项目管理** | 10+ | sprint-planning, task-estimation, technical-debt-management, release-planning | 敏捷管理、技术债治理 |
| **移动开发** | 5+ | ios-development, android-development, react-native-patterns | iOS/Android/RN 开发 |
| **游戏开发** | 5+ | game-architecture, unity-patterns, unreal-engine-workflows | Unity/Unreal 开发 |
| **其他专项** | 100+ | blender-motion-state-inspection, brand-discovery, browser-qa, api-connector-builder, accessibility, benchmark-optimization-loop, blueprint | 跨领域专项能力 |

---

## 十四、impeccable（1 个技能）

> 前端设计精炼与重构 — 从 UX 审查到视觉层次再到微交互的全链路设计优化

| 技能名称 | 功能描述 | 触发场景 |
|---------|---------|---------|
| **impeccable** | 前端设计精炼/重构/优化/审计/抛光/清晰化/简化/强化/适配/动效/配色/提取。覆盖网站、落地页、仪表盘、产品 UI、应用外壳、组件、表单、设置页、引导页和空状态。处理 UX 审查、视觉层次、信息架构、认知负载、无障碍、性能、响应式行为、主题化、反模式、排版、字体、间距、布局、对齐、色彩、动效、微交互、UX 文案、错误状态、边界情况、国际化及可复用设计系统/Token。也用于平淡设计变大胆、喧嚣设计变安静、浏览器中实时迭代 UI 元素 | 需要改进、优化或审核前端界面时 |

> 配套参考文档 (`reference/`) 和自动化脚本 (`scripts/`) 已随插件安装

---

## 十五、wiseflow（19 个技能）

> 智能工作流生态 — HRBP 人力资源管理、IT 工程运维、Crew 协同管理、SEO 等

| 技能名称 | 功能描述 | 触发场景 |
|---------|---------|---------|
| **browser-guide** | 托管浏览器最佳实践：处理登录墙、验证码、Cookie 管理、会话保持 | 浏览器自动化遇到障碍时 |
| **complex-task** | 复杂任务分解与编排策略 | 需要处理多步骤复杂任务时 |
| **smart-search** | 智能搜索策略：多源交叉验证、信息聚合 | 需要深度调研时 |
| **alicloud-find-skills** | 阿里云技能发现与调用路由 | 阿里云相关操作 |
| **icp-exemption** | ICP 备案豁免查询与办理指南 | 国内服务器免备案场景 |
| **icp-filing** | ICP 备案流程指导与状态查询 | 国内服务器备案需求 |
| **seo** | SEO 执行指南：关键词、外链、内容优化 | 网站 SEO 优化需求 |
| **tccli** | 腾讯云 CLI 操作指南 | 腾讯云资源管理 |
| **hrbp-feedback-review** | HRBP 对外 Crew 表现分析审查 | 需要审查外部 Agent 表现时 |
| **hrbp-list** | HRBP 外部 Crew 花名册管理与状态检查 | 查看/管理工作 Crew 时 |
| **hrbp-modify** | HRBP 外部 Crew 配置修改 | 需要调整 Crew 配置时 |
| **hrbp-recruit** | HRBP 招募与聘用新外部 Crew | 需要增加新的工作 Agent 时 |
| **hrbp-remove** | HRBP 解除/下线外部 Crew | 需要移除 Agent 时 |
| **hrbp-usage** | HRBP 使用指引与最佳实践 | 首次使用 HRBP 系统时 |
| **crew-dismiss** | 内部 Crew 专员下线/解除流程 | 需要下线内部 Crew 时 |
| **crew-list** | 内部 Crew 专员列表与状态查询 | 查看 Crew 状态时 |
| **crew-recruit** | 内部 Crew 专员招募流程 | 扩充内部 Crew 时 |
| **reminder** | 定时提醒与任务提醒管理 | 需要设置定时任务提醒 |
| **work-channel-binding** | 工作频道绑定与消息路由配置 | 配置工作消息通道时 |

---

## 十六、xiaohongshu-mcp（1 个技能 + Go MCP 服务器）

> 小红书内容发布 — 支持图文/长文双模式 + 网页自动提取发布

| 技能名称 | 功能描述 | 触发场景 |
|---------|---------|---------|
| **post-to-xhs** | 小红书内容发布技能。支持两种发布模式：(1) 上传图文模式 - 图片+短文；(2) 写长文模式 - 长篇文章+排版模板。支持两种输入方式：用户提供完整内容和图片/图片URL直接发布；或提供网页URL自动提取内容和图片 | 需要在小红书平台发布内容时 |

> 包含完整 Go 语言 MCP 服务器实现（main.go, mcp_server.go, mcp_handlers.go, service.go 等），以及账号管理 (`config/accounts.json`)、发布流水线脚本 (`scripts/cdp_publish.py`, `scripts/publish_pipeline.py`) 等配套工具

---

## 十七、openclaw-master-skills（2103 个技能）

> 开放技能宇宙 — 2103 个跨领域技能的庞大生态库，覆盖 AI 工具、生产力、营销、前端、移动端、后端、DevOps 等几乎所有领域

来自 [openclaw-master-skills](https://github.com/myclaw-ai/openclaw-master-skills) 项目，每周更新，是当前安装量最大的技能插件。

### 17.1 领域分布概览

| 能力域 | 估算技能数 | 典型技能举例 |
|--------|:----------:|-------------|
| 🤖 **AI 工具与 Agent** | 300+ | claude-api-anthropic, agent-framework, ai-workflow, prompt-engineering, model-deployment |
| 🖥️ **前端开发** | 250+ | react-component, vue-component, nextjs-app, tailwind-styling, css-animation, html-template, web-component |
| ⚙️ **后端开发** | 200+ | nodejs-api, python-backend, go-service, rust-app, graphql-server, rest-api, database-connector |
| 🛠️ **DevOps 与云基础设施** | 150+ | docker-compose, kubernetes-deployment, terraform-module, ci-cd-pipeline, monitoring-setup, cloud-migration |
| 📱 **移动端开发** | 100+ | ios-swift, android-kotlin, flutter-widget, react-native-component |
| 🎯 **营销与增长** | 100+ | seo-optimizer, content-marketing, email-campaign, social-media-scheduler, ab-test-analyzer |
| 📊 **数据与 AI/ML** | 100+ | data-pipeline, data-visualization, ml-model-training, nlp-processing, computer-vision |
| 🔒 **安全** | 80+ | security-scanner, vulnerability-check, penetration-testing, authentication-implementation |
| 🎨 **设计与创意** | 70+ | ui-component, design-system, icon-generator, animation-creator, color-palette |
| 📝 **内容创作** | 60+ | blog-writer, copywriter, script-generator, video-script, newsletter-creator |
| 🧪 **测试与 QA** | 50+ | unit-test-generator, e2e-testing, performance-test, api-testing, load-test |
| 🌐 **国际化与本地化** | 40+ | i18n-translation, locale-adapter, multi-language-support |
| 🏗️ **项目管理** | 30+ | agile-workflow, sprint-tracker, task-manager, release-planner |
| 📈 **电商** | 30+ | shopify-integration, woocommerce-setup, ecommerce-optimization, product-listing |
| 🎮 **游戏开发** | 20+ | unity-script, godot-scene, unreal-blueprint, game-mechanic |
| 🔧 **其他实用工具** | 400+ | pdf-generator, excel-processor, image-optimizer, file-converter, system-automation, network-tool, browser-extension |

### 17.2 与其他插件的互补关系

openclaw-master-skills 作为通用技能库，与现有专项插件形成互补：

| 对比维度 | openclaw-master-skills | 现有专项插件（Hermes/ECC/Gingiris 等） |
|---------|----------------------|-----------------------------------|
| **覆盖面** | 极广（2103 个通用技能） | 较窄但纵深强 |
| **专业深度** | 中等（适合 80% 场景） | 专家级（适合 20% 高难度场景） |
| **更新频率** | 每周更新 | 依赖各自项目维护节奏 |
| **重叠领域** | 前端/后端/DevOps/设计/营销 | 与 Hermes（15+ 重叠）、ECC（10+ 重叠）部分重叠 |

---

## 十八、能力总览矩阵（更新版）

| 能力域 | 技能数 | 来源 |
|--------|:------:|------|
| 🛠️ **开发工作流**（Plan/TDD/Review/Branch/Verify）| 14 | Superpowers |
| 🌐 **浏览器自动化** | 2 | BB Browser |
| 🎨 **UI/UX 设计**（品牌/设计系统/样式/横幅/幻灯片）| 7+7 | UI-UX Pro Max + UI-UX Pro Max Skill |
| 📈 **ASO & App 增长** | 3 | Gingiris |
| 🔍 **SEO & GEO**（排名/AI引用/Agent运维）| 5 | Gingiris |
| 📊 **竞品分析**（扫描/飞轮/传播链）| 3 | Gingiris |
| 🚀 **产品发布**（GTM/PH Launch/全球出海）| 6 | Gingiris |
| 💼 **B2B & SaaS 增长**（PLG/定价/营销栈）| 6 | Gingiris |
| 🌟 **开源营销 & GitHub Stars** | 4 | Gingiris |
| 👥 **社区运营**（大使/DevRel/社群）| 4 | Gingiris |
| 📝 **内容营销**（博客/社媒蒸馏/README/病毒）| 6 | Gingiris |
| 🤝 **KOL & 用户研究**（拓展/访谈/PMF）| 4 | Gingiris |
| 🧠 **增长策略**（路由器/50手段/飞轮评分）| 4 | Gingiris |
| 📋 **通用营销 Playbooks** | 10 | Gingiris |
| 🤖 **AI Agent 工作流** | 2 | Gingiris |
| 🔄 **VibeCoding 全流程**（初始化→规划→执行→审查→恢复）| 6 | Rlues VibeCoding |
| 🏗️ **工程开发框架**（调研/UI设计/技术评估）| 3 + 12 Agents | CataForge |
| 📑 **SOP 开发框架**（分析/设计/开发/评审/知识库）| 6 | Sopify |
| 🧩 **Hermes 专属领域**（50+ 细分领域专项技能）| 309 | Hermes Skills |
| 📡 **百度 API 系列**（搜索/地图/SEO/IP/天气/百科）| 11 | GitHubM |
| 🎨 **AI 图像/视频生成**（Sora/Kling/MiniMax/文心）| 16 | GitHubM |
| 📄 **OCR 识别**（身份证/票据/车票/通用）| 9 | GitHubM |
| 💹 **金融行情**（股票/汇率/贵金属）| 3 | GitHubM |
| 🏢 **企业信息查询**（工商/招聘/专利）| 3 | GitHubM |
| 🌍 **翻译 & 语音**（翻译/TTS/识别）| 4 | GitHubM |
| 🔥 **热搜 & 生活服务**（热搜/快递/限行/彩票/驾考）| 6 | GitHubM |
| 🎯 **百项实用 API 工具** | 69 | GitHubM |
| ⚙️ **工程能力全集**（Agent架构/TDD/安全/DevOps/性能）| **277** | **ECC（新增）** |
| 🎨 **前端设计精炼**（UX审查/视觉层次/微交互/动效）| **1** | **impeccable（新增）** |
| 🔄 **智能工作流生态**（HRBP/Crew管理/IT运维/SEO）| **19** | **wiseflow（新增）** |
| 📱 **小红书内容发布**（图文/长文/自动提取）| **1** | **xiaohongshu-mcp（新增）** |
| 🌌 **开放技能宇宙**（AI工具/前后端/DevOps/营销/电商等）| **2103** | **openclaw-master-skills（新增）** |

---

## 十九、交叉能力分析（更新版）

| 现有需求 | 可调用的 Skill（含新增） | 匹配度 |
|---------|------------------------|:------:|
| **爬虫开发与调试** | systematic-debugging, bb-browser, cataforge-research, ecc (browser-qa, api-connector-builder) | ⭐⭐⭐⭐⭐ |
| **看板 UI 美化** | ui-styling, design, design-system, brand, cataforge-ui-design, **impeccable** | ⭐⭐⭐⭐⭐ |
| **新功能实现** | writing-plans, test-driven-development, dispatching-parallel-agents, vibecoding-workflow, cataforge-tech-eval, **ecc (test-driven-development, code-review)** | ⭐⭐⭐⭐⭐ |
| **竞品分析** | gr-competitor, competitor-research-playbook, cataforge-research, wiseflow (smart-search) | ⭐⭐⭐⭐⭐ |
| **SEO 优化（项目官网）** | gingiris-seo-geo, gr-seo-patrol, **wiseflow (seo)** | ⭐⭐⭐⭐⭐ |
| **代码审查** | requesting-code-review, receiving-code-review, sopify-cross-review, **ecc (code-review, security-audit)** | ⭐⭐⭐⭐⭐ |
| **用户反馈分析** | gingiris-user-interview, gr-user-interview, cataforge-research | ⭐⭐⭐⭐ |
| **开源项目推广** | gingiris-opensource, gingiris-github-star-growth | ⭐⭐⭐⭐ |
| **README 优化** | gr-readme | ⭐⭐⭐⭐⭐ |
| **全流程开发（需求→设计→编码→审查）** | vibecoding-init → vibecoding-plan → vibecoding-execute → vibecoding-review, **ecc (agent-architecture-audit → test-driven-development → code-review → finishing-a-development-branch)** | ⭐⭐⭐⭐⭐ |
| **方案设计与任务拆分** | sopify-analyze, sopify-design, sopify-develop, **wiseflow (complex-task)** | ⭐⭐⭐⭐⭐ |
| **知识库管理** | sopify-kb, sopify-templates, ecc (knowledge-base-creation, documentation-generation) | ⭐⭐⭐⭐⭐ |
| **技术选型调研** | cataforge-research, cataforge-tech-eval, **wiseflow (smart-search)** | ⭐⭐⭐⭐⭐ |
| **UI 设计系统搭建** | cataforge-ui-design, ui-styling, design-system, **impeccable**, **ecc (design-system, css-architecture)** | ⭐⭐⭐⭐⭐ |
| **断点恢复（长任务）** | rlues-vibecoding-vibecoding-recovery | ⭐⭐⭐⭐⭐ |
| **百度 API 集成**（搜索/地图/地理编码） | githubm-baidu-search, githubm-baidu-geocoding, githubm-baidu-poi-detail | ⭐⭐⭐⭐⭐ |
| **OCR 识别需求**（身份证/票据/车票） | githubm-id-card-ocr, githubm-train-ticket-ocr, githubm-accurate-ocr | ⭐⭐⭐⭐⭐ |
| **AI 图片/视频生成**（营销素材/封面） | githubm-image-generation-advanced, githubm-text-to-video, githubm-kling-video-generation, **openclaw (ai-image-generator, video-creator)** | ⭐⭐⭐⭐⭐ |
| **翻译需求**（多语言/国际化） | githubm-text-translation, **openclaw (i18n-translation, multi-language-support)** | ⭐⭐⭐⭐⭐ |
| **股票/金融行情查询** | githubm-stock-realtime-quote, githubm-currency-exchange-rate | ⭐⭐⭐⭐ |
| **企业信息调研**（竞品公司/招聘/专利） | githubm-company-info-lookup, githubm-company-hiring-data, githubm-patent-search | ⭐⭐⭐⭐ |
| **Agent 系统设计与编排**（新增） | **ecc (agent-harness-construction, agent-architecture-audit, autonomous-agent-harness)** | ⭐⭐⭐⭐⭐（新增） |
| **阿里云/腾讯云基础设施管理**（新增） | **wiseflow (alicloud-find-skills, tccli, icp-filing, icp-exemption)** | ⭐⭐⭐⭐⭐（新增） |
| **小红书社媒运营**（新增） | **xiaohongshu-mcp (post-to-xhs)** | ⭐⭐⭐⭐⭐（新增） |
| **HRBP/AI Crew 人员管理**（新增） | **wiseflow (hrbp-list, hrbp-recruit, hrbp-modify, hrbp-remove, crew-list, crew-recruit)** | ⭐⭐⭐⭐⭐（新增） |
| **前端界面深度打磨**（新增） | **impeccable**（UX审查/视觉层次/动效/无障碍/信息架构全链路） | ⭐⭐⭐⭐⭐（新增） |
| **通用全栈开发（任何语言/框架）**（新增） | **openclaw-master-skills**（2103 个通用技能覆盖 80% 开发场景）+ **ecc**（工程实践）| ⭐⭐⭐⭐⭐（新增） |

---

## 二十、全局技能生态总览

```
┌─────────────────────────────────────────────────────────────────┐
│                   全局 Skill 生态（2813+ 技能）                    │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│   🎯 增长与营销 (Gingiris 58 + GitHubM 69)                      │
│   ├─ SEO/GEO 双引擎 · ASO · B2B SaaS · PH Launch               │
│   ├─ 竞品扫描 · KOL 拓展 · UGC 矩阵 · 社媒蒸馏                  │
│   └─ 百度 API · AI 生成 · OCR · 金融行情 · 生活服务              │
│                                                                 │
│   ⚙️ 工程与开发 (ECC 277 + Hermes 309 + CataForge 3)           │
│   ├─ Agent 架构 · TDD · 代码审查 · 安全审计 · DevOps             │
│   ├─ 全栈工程 · MLOps · 游戏开发 · 移动端 · 学术研究             │
│   └─ 工程框架 · 技术评估 · 调查研究 · UI 设计                    │
│                                                                 │
│   🎨 设计与体验 (UI-UX Pro Max 7+7 + impeccable 1)             │
│   ├─ 品牌设计 · 设计系统 · UI 样式 · 横幅 · 幻灯片               │
│   └─ 前端精炼 · UX 审查 · 视觉层次 · 动效 · 微交互               │
│                                                                 │
│   🔄 开发工作流 (Superpowers 14 + VibeCoding 6 + Sopify 6)     │
│   ├─ Plan · TDD · Review · Branch · Verify · Parallel           │
│   ├─ 初始化 → 规划 → 执行 → 审查 → 恢复                         │
│   └─ 分析 → 设计 → 开发 → 评审 → 知识库                         │
│                                                                 │
│   🌌 通用技能宇宙 (openclaw-master-skills 2103)                 │
│   ├─ AI 工具 · 前端 · 后端 · DevOps · 安全 · 测试               │
│   ├─ 数据 · 移动端 · 电商 · 游戏 · 内容创作                     │
│   └─ 实用工具 · 国际化 · 项目管理 · 设计 · 营销                 │
│                                                                 │
│   🔧 智能工作流 (wiseflow 19)                                    │
│   ├─ HRBP 管理 · Crew 协同 · 招募/解聘/修改                     │
│   ├─ IT 运维 · ICP 备案 · 阿里云/腾讯云                          │
│   └─ 定时提醒 · 频道绑定 · SEO · 智能搜索                       │
│                                                                 │
│   🌐 浏览器与数据 (BB Browser 2 + xiaohongshu-mcp 1)            │
│   ├─ 浏览器自动化 · 网页操作 · 数据采集                         │
│   └─ 小红书发布 · 图文/长文 · MCP 服务器                        │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

---

## 更新日志

| 版本 | 日期 | 变更内容 |
|:----:|:----:|---------|
| v1.0 | 2026-07-03 | 初始版本（10 插件 / 474 技能） |
| **v2.0** | **2026-07-03** | **新增 5 插件：ECC(277) + impeccable(1) + wiseflow(19) + xiaohongshu-mcp(1) + openclaw-master-skills(2103) → 总计 2813+ 技能** |
