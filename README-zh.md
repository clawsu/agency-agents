# 🎭 机构：准备改变您工作流程的AI专家

> **一个完整的AI机构触手可及** - 从前端巫师到Reddit社区忍者，从趣味注入者到现实检验者。每个代理都是具有个性、流程和可交付成果的专业专家。

[![GitHub stars](https://img.shields.io/github/stars/msitarzewski/agency-agents?style=social)](https://github.com/msitarzewski/agency-agents)
[![许可证: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![欢迎PR](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://makeapullrequest.com)
[![赞助](https://img.shields.io/badge/Sponsor-%E2%9D%A4-pink?logo=github)](https://github.com/sponsors/msitarzewski)

---

## 🚀 这是什么？

诞生于Reddit讨论帖和数月的迭代，**The Agency**是一个精心打造的AI代理个性集合。每个代理都是：

- **🎯 专业化**: 在各自领域拥有深厚专业知识（不是通用提示模板）
- **🧠 个性驱动**: 独特的声音、沟通方式和处理方法
- **📋 交付成果导向**: 真实的代码、流程和可衡量的结果
- **✅ 生产就绪**: 经过实战考验的工作流程和成功指标

**想象一下**: 组建您的梦想团队，只不过他们是永不睡眠、从不抱怨、总能交付的AI专家。

---

## ⚡ 快速开始

### 选项1：与Claude Code一起使用（推荐）

```bash
# 将代理复制到您的Claude Code目录
cp -r agency-agents/* ~/.claude/agents/

# 现在在您的Claude Code会话中激活任何代理：
# "嘿Claude，激活前端开发者模式并帮助我构建一个React组件"
```

### 选项2：作为参考使用

每个代理文件包含：
- 身份和个性特征
- 核心使命和工作流程
- 带有代码示例的技术交付成果
- 成功指标和沟通风格

浏览下面的代理，复制/调整您需要的那些！

### 选项3：与其他工具一起使用（Cursor、Aider、Windsurf、Gemini CLI、OpenCode）

```bash
# 步骤1 -- 为所有支持的工具生成集成文件
./scripts/convert.sh

# 步骤2 -- 交互式安装（自动检测您已安装的工具）
./scripts/install.sh

# 或直接针对特定工具
./scripts/install.sh --tool cursor
./scripts/install.sh --tool copilot
./scripts/install.sh --tool aider
./scripts/install.sh --tool windsurf
```

有关详细信息，请参阅下面的[多工具集成](#-multi-tool-integrations)部分。

---

## 🎨 机构名单

### 💻 工程部

一次提交构建未来。

| 代理 | 专长 | 使用场景 |
|-------|-----------|-------------|
| 🎨 [前端开发者](engineering/engineering-frontend-developer.md) | React/Vue/Angular、UI实现、性能 | 现代Web应用、像素完美的UI、核心网页指标优化 |
| 🏗️ [后端架构师](engineering/engineering-backend-architect.md) | API设计、数据库架构、可扩展性 | 服务器端系统、微服务、云基础设施 |
| 📱 [移动应用构建者](engineering/engineering-mobile-app-builder.md) | iOS/Android、React Native、Flutter | 原生和跨平台移动应用 |
| 🤖 [AI工程师](engineering/engineering-ai-engineer.md) | 机器学习模型、部署、AI集成 | 机器学习功能、数据管道、AI驱动应用 |
| 🚀 [DevOps自动化专家](engineering/engineering-devops-automator.md) | CI/CD、基础设施自动化、云运维 | 管道开发、部署自动化、监控 |
| ⚡ [快速原型制作师](engineering/engineering-rapid-prototyper.md) | 快速POC开发、MVP | 快速概念验证、黑客松项目、快速迭代 |
| 💎 [高级开发者](engineering/engineering-senior-developer.md) | Laravel/Livewire、高级模式 | 复杂实现、架构决策 |
| 🔒 [安全工程师](engineering/engineering-security-engineer.md) | 威胁建模、安全代码审查、安全架构 | 应用安全、漏洞评估、安全CI/CD |
| ⚡ [自主优化架构师](engineering/engineering-autonomous-optimization-architect.md) | LLM路由、成本优化、影子测试 | 需要智能API选择和成本护栏的自主系统 |
| 🔩 [嵌入式固件工程师](engineering/engineering-embedded-firmware-engineer.md) | 裸机、RTOS、ESP32/STM32/Nordic固件 | 生产级嵌入式系统和IoT设备 |
| 🚨 [事件响应指挥官](engineering/engineering-incident-response-commander.md) | 事件管理、事后分析、值班 | 管理生产事件和构建事件响应准备 |
| ⛓️ [Solidity智能合约工程师](engineering/engineering-solidity-smart-contract-engineer.md) | EVM合约、gas优化、DeFi | 安全、gas优化的智能合约和DeFi协议 |
| 📚 [技术文档作者](engineering/engineering-technical-writer.md) | 开发者文档、API参考、教程 | 清晰、准确的技术文档 |
| 🎯 [威胁检测工程师](engineering/engineering-threat-detection-engineer.md) | SIEM规则、威胁搜寻、ATT&CK映射 | 构建检测层和威胁搜寻 |
| 💬 [微信小程序开发者](engineering/engineering-wechat-mini-program-developer.md) | 微信生态、小程序、支付集成 | 为微信生态系统构建高性能应用 |
| 👁️ [代码审查者](engineering/engineering-code-reviewer.md) | 建设性代码审查、安全性、可维护性 | PR审查、代码质量门限、通过审查进行指导 |
| 🗄️ [数据库优化师](engineering/engineering-database-optimizer.md) | 模式设计、查询优化、索引策略 | PostgreSQL/MySQL调优、慢查询调试、迁移规划 |
| 🌿 [Git工作流大师](engineering/engineering-git-workflow-master.md) | 分支策略、约定式提交、高级Git | Git工作流设计、历史清理、CI友好的分支管理 |
| 🏛️ [软件架构师](engineering/engineering-software-architect.md) | 系统设计、DDD、架构模式、权衡分析 | 架构决策、领域建模、系统演进策略 |
| 🛡️ [SRE](engineering/engineering-sre.md) | SLO、错误预算、可观测性、混沌工程 | 生产可靠性、减少繁琐工作、容量规划 |
| 🧬 [AI数据修复工程师](engineering/engineering-ai-data-remediation-engineer.md) | 自愈管道、隔离SLM、语义聚类 | 以零数据损失大规模修复损坏的数据 |
| 🔧 [数据工程师](engineering/engineering-data-engineer.md) | 数据管道、湖仓架构、ETL/ELT | 构建可靠的数据基础设施和数据仓库 |
| 🔗 [飞书集成开发者](engineering/engineering-feishu-integration-developer.md) | 飞书/Lark开放平台、机器人、工作流 | 为飞书生态系统构建集成 |

### 🎨 设计部
使其美观、易用、令人愉悦。

| Agent | Specialty | When to Use |
|-------|-----------|-------------|
| 🎯 [UI Designer](design/design-ui-designer.md) | 视觉设计、组件库、设计系统 | 界面创建、品牌一致性、组件设计 |
| 🔍 [UX Researcher](design/design-ux-researcher.md) | 用户测试、行为分析、研究 | 了解用户、可用性测试、设计洞察 |
| 🏛️ [UX Architect](design/design-ux-architect.md) | 技术架构、CSS系统、实现 | 开发友好的基础、实施指导 |
| 🎭 [Brand Guardian](design/design-brand-guardian.md) | 品牌身份、一致性、定位 | 品牌策略、身份开发、指南 |
| 📖 [Visual Storyteller](design/design-visual-storyteller.md) | 视觉叙事、多媒体内容 | 引人入胜的视觉故事、品牌叙事 |
| ✨ [Whimsy Injector](design/design-whimsy-injector.md) | 个性、愉悦、有趣的交互 | 增加乐趣、微交互、彩蛋、品牌个性 |
| 📷 [Image Prompt Engineer](design/design-image-prompt-engineer.md) | AI图像生成提示、摄影 | Midjourney、DALL-E、Stable Diffusion的摄影提示 |
| 🌈 [Inclusive Visuals Specialist](design/design-inclusive-visuals-specialist.md) | 代表性、偏见缓解、真实图像 | 生成文化准确的AI图像和视频 |

### 💰 付费媒体事业部

将广告支出转化为可衡量的业务成果。

| Agent | Specialty | When to Use |
| --- | --- | --- |
| 💰 [PPC Campaign Strategist](paid-media/paid-media-ppc-strategist.md) | Google/Amazon/微软广告、账户架构、竞价 | 账户构建、预算分配、扩展、性能诊断 |
| 🔍 [Search Query Analyst](paid-media/paid-media-search-query-analyst.md) | 搜索词分析、否定关键词、意图映射 | 查询审核、消除浪费支出、关键词发现 |
| 📋 [Paid Media Auditor](paid-media/paid-media-auditor.md) | 200+点账户审核、竞争分析 | 账户接管、季度审查、竞争提案 |
| 📡 [Tracking & Measurement Specialist](paid-media/paid-media-tracking-specialist.md) | GTM、GA4、转化跟踪、CAPI | 新实施、跟踪审核、平台迁移 |
| ✍️ [Ad Creative Strategist](paid-media/paid-media-creative-strategist.md) | RSA文案、Meta创意、Performance Max资产 | 创意发布、测试计划、广告疲劳刷新 |
| 📺 [Programmatic & Display Buyer](paid-media/paid-media-programmatic-buyer.md) | GDN、DSP、合作伙伴媒体、ABM展示 | 展示规划、合作伙伴拓展、ABM计划 |
| 📱 [Paid Social Strategist](paid-media/paid-media-paid-social-strategist.md) | Meta、LinkedIn、TikTok、跨平台社交 | 社交广告计划、平台选择、受众策略 |

### 💼 销售事业部

通过技巧而非CRM琐事将销售线索转化为收入。

| Agent | Specialty | When to Use |
|-------|-----------|-------------|
| 🎯 [Outbound Strategist](sales/sales-outbound-strategist.md) | 基于信号的潜在客户开发、多渠道序列、ICP定位 | 通过研究驱动的拓展建立销售线索，而非数量 |
| 🔍 [Discovery Coach](sales/sales-discovery-coach.md) | SPIN、Gap Selling、Sandler—问题设计和通话结构 | 准备发现电话、评估机会、培训代表 |
| ♟️ [Deal Strategist](sales/sales-deal-strategist.md) | MEDDPICC资格、竞争定位、获胜计划 | 交易评分、暴露销售线索风险、构建获胜策略 |
| 🛠️ [Sales Engineer](sales/sales-engineer.md) | 技术演示、POC范围、竞争战斗卡 | 售前技术胜利、演示准备、竞争定位 |
| 🏹 [Proposal Strategist](sales/sales-proposal-strategist.md) | RFP响应、获胜主题、叙事结构 | 编写具有说服力而非仅合规的提案 |
| 📊 [Pipeline Analyst](sales/sales-pipeline-analyst.md) | 预测、销售健康状况、交易速度、RevOps | 销售线索审查、预测准确性、收入运营 |
| 🗺️ [Account Strategist](sales/sales-account-strategist.md) | 扩展策略、QBR、利益相关者映射 | 售后扩展、账户规划、NRR增长 |
| 🏋️ [Sales Coach](sales/sales-coach.md) | 代表发展、通话培训、销售线索审查促进 | 通过结构化培训使每个代表和每笔交易更好 |

### 📢 营销事业部

一次一个真实的互动，增长您的受众。

| Agent | Specialty | When to Use |
|-------|-----------|-------------|
| 🚀 [Growth Hacker](marketing/marketing-growth-hacker.md) | 快速用户获取、病毒循环、实验 | 爆炸性增长、用户获取、转化优化 |
| 📝 [Content Creator](marketing/marketing-content-creator.md) | 多平台内容、编辑日历 | 内容策略、文案、品牌叙事 |
| 🐦 [Twitter Engager](marketing/marketing-twitter-engager.md) | 实时互动、思想领导力 | Twitter策略、LinkedIn活动、专业社交 |
| 📱 [TikTok Strategist](marketing/marketing-tiktok-strategist.md) | 病毒内容、算法优化 | TikTok增长、病毒内容、Z世代/千禧一代受众 |
| 📸 [Instagram Curator](marketing/marketing-instagram-curator.md) | 视觉叙事、社区建设 | Instagram策略、美学发展、视觉内容 |
| 🤝 [Reddit Community Builder](marketing/marketing-reddit-community-builder.md) | 真实互动、价值驱动内容 | Reddit策略、社区信任、真实营销 |
| 📱 [App Store Optimizer](marketing/marketing-app-store-optimizer.md) | ASO、转化优化、可发现性 | 应用营销、商店优化、应用增长 |
| 🌐 [Social Media Strategist](marketing/marketing-social-media-strategist.md) | 跨平台策略、活动 | 整体社交策略、多平台活动 |
| 📕 [Xiaohongshu Specialist](marketing/marketing-xiaohongshu-specialist.md) | 生活方式内容、趋势驱动策略 | 小红书增长、美学叙事、Z世代受众 |
| 💬 [WeChat Official Account Manager](marketing/marketing-wechat-official-account.md) | 订阅者互动、内容营销 | 微信公众号策略、社区建设、转化优化 |
| 🧠 [Zhihu Strategist](marketing/marketing-zhihu-strategist.md) | 思想领导力、知识驱动互动 | 知乎权威建设、问答策略、潜在客户生成 |
| 🇨🇳 [Baidu SEO Specialist](marketing/marketing-baidu-seo-specialist.md) | 百度优化、中国SEO、ICP合规 | 在百度排名并接触中国搜索市场 |
| 🎬 [Bilibili Content Strategist](marketing/marketing-bilibili-content-strategist.md) | B站算法、弹幕文化、UP主增长 | 通过以社区为中心的内容在哔哩哔哩建立受众 |
| 🎠 [Carousel Growth Engine](marketing/marketing-carousel-growth-engine.md) | TikTok/Instagram轮播、自主发布 | 生成和发布病毒性轮播内容 |
| 💼 [LinkedIn Content Creator](marketing/marketing-linkedin-content-creator.md) | 个人品牌、思想领导力、专业内容 | LinkedIn增长、专业受众建设、B2B内容 |
| 🛒 [China E-Commerce Operator](marketing/marketing-china-ecommerce-operator.md) | 淘宝、天猫、拼多多、直播电商 | 运营中国多平台电商 |
| 🎥 [Kuaishou Strategist](marketing/marketing-kuaishou-strategist.md) | 快手、老铁社区、草根增长 | 在下沉市场建立真实受众 |
| 🔍 [SEO Specialist](marketing/marketing-seo-specialist.md) | 技术SEO、内容策略、链接建设 | 推动可持续的有机搜索增长 |
| 📘 [Book Co-Author](marketing/marketing-book-co-author.md) | 思想领导力书籍、代笔、出版 | 创始人和专家的战略书籍合作 |
| 🌏 [Cross-Border E-Commerce Specialist](marketing/marketing-cross-border-ecommerce.md) | 亚马逊、Shopee、Lazada、跨境履约 | 全渠道跨境电商策略 |
| 🎵 [Douyin Strategist](marketing/marketing-douyin-strategist.md) | 抖音平台、短视频营销、算法 | 在中国领先短视频平台增长受众 |
| 🎙️ [Livestream Commerce Coach](marketing/marketing-livestream-commerce-coach.md) | 主播培训、直播间优化、转化 | 建立高性能直播电商运营 |
| 🎧 [Podcast Strategist](marketing/marketing-podcast-strategist.md) | 播客内容策略、平台优化 | 中国播客市场策略和运营 |
| 🔒 [Private Domain Operator](marketing/marketing-private-domain-operator.md) | 企业微信、私域流量、社区运营 | 构建企业微信私域生态系统 |
| 🎬 [Short-Video Editing Coach](marketing/marketing-short-video-editing-coach.md) | 后期制作、编辑工作流、平台规格 | 实用短视频编辑培训和优化 |
| 🔥 [Weibo Strategist](marketing/marketing-weibo-strategist.md) | 微博、热门话题、粉丝互动 | 全方位微博运营和增长 |
| 🎯 [Sprint Prioritizer](product/product-sprint-prioritizer.md) | 敏捷规划、功能优先级 | 冲刺规划、资源分配、待办事项管理 |
| 🔍 [Trend Researcher](product/product-trend-researcher.md) | 市场情报、竞争分析 | 市场研究、机会评估、趋势识别 |
| 💬 [Feedback Synthesizer](product/product-feedback-synthesizer.md) | 用户反馈分析、洞察提取 | 反馈分析、用户洞察、产品优先级 |
| 🧠 [Behavioral Nudge Engine](product/product-behavioral-nudge-engine.md) | 行为心理学、助推设计、参与度 | 通过行为科学最大化用户动机 |

| 🧭 [Product Manager](product/product-manager.md) | 全生命周期产品所有权 | 发现、PRD、路线图规划、GTM、结果测量 |

### 🎬 项目管理事业部

让列车准时运行（且在预算内）。

| Agent | Specialty | When to Use |
|-------|-----------|-------------|
| 🎬 [Studio Producer](project-management/project-management-studio-producer.md) | 高层次编排、投资组合管理 | 多项目监督、战略对齐、资源分配 |
| 🐑 [Project Shepherd](project-management/project-management-project-shepherd.md) | 跨职能协调、时间线管理 | 端到端项目协调、利益相关者管理 |
| ⚙️ [Studio Operations](project-management/project-management-studio-operations.md) | 日常效率、流程优化 | 运营卓越、团队支持、生产力 |
| 🧪 [Experiment Tracker](project-management/project-management-experiment-tracker.md) | A/B测试、假设验证 | 实验管理、数据驱动决策、测试 |
| 👔 [Senior Project Manager](project-management/project-manager-senior.md) | 现实范围界定、任务转换 | 将规格转换为任务、范围管理 |
| 📋 [Jira Workflow Steward](project-management/project-management-jira-workflow-steward.md) | Git工作流、分支策略、可追溯性 | 强制执行Jira链接的Git纪律和交付 |
### 🧪 测试部门

破坏事物，这样用户就不必了。

| 代理 | 专业领域 | 何时使用 |
|-------|-----------|-------------|
| 📸 [证据收集器](testing/testing-evidence-collector.md) | 基于截图的QA，视觉证明 | UI测试，视觉验证，错误文档 |
| 🔍 [现实检查器](testing/testing-reality-checker.md) | 基于证据的认证，质量关卡 | 生产就绪度，质量批准，发布认证 |
| 📊 [测试结果分析器](testing/testing-test-results-analyzer.md) | 测试评估，指标分析 | 测试输出分析，质量洞察，覆盖率报告 |
| ⚡ [性能基准测试器](testing/testing-performance-benchmarker.md) | 性能测试，优化 | 速度测试，负载测试，性能调优 |
| 🔌 [API测试器](testing/testing-api-tester.md) | API验证，集成测试 | API测试，端点验证，集成QA |
| 🛠️ [工具评估器](testing/testing-tool-evaluator.md) | 技术评估，工具选择 | 评估工具，软件推荐，技术决策 |
| 🔄 [工作流程优化器](testing/testing-workflow-optimizer.md) | 流程分析，工作流程改进 | 流程优化，效率提升，自动化机会 |
| ♿ [可访问性审计师](testing/testing-accessibility-auditor.md) | WCAG审计，辅助技术测试 | 可访问性合规，屏幕阅读器测试，包容性设计验证 |

### 🛟 支持部门

运作的支柱。

| 代理 | 专业领域 | 何时使用 |
|-------|-----------|-------------|
| 💬 [支持响应器](support/support-support-responder.md) | 客户服务，问题解决 | 客户支持，用户体验，支持运营 |
| 📊 [分析报告器](support/support-analytics-reporter.md) | 数据分析，仪表板，洞察 | 商业智能，KPI跟踪，数据可视化 |
| 💰 [财务跟踪器](support/support-finance-tracker.md) | 财务规划，预算管理 | 财务分析，现金流，业务绩效 |
| 🏗️ [基础设施维护器](support/support-infrastructure-maintainer.md) | 系统可靠性，性能优化 | 基础设施管理，系统运营，监控 |
| ⚖️ [法律合规检查器](support/support-legal-compliance-checker.md) | 合规，法规，法律审查 | 法律合规，监管要求，风险管理 |
| 📑 [执行摘要生成器](support/support-executive-summary-generator.md) | C级管理层沟通，战略摘要 | 执行报告，战略沟通，决策支持 |

### 🥽 空间计算部门

构建沉浸式未来。

| 代理 | 专业领域 | 何时使用 |
|-------|-----------|-------------|
| 🏗️ [XR界面架构师](spatial-computing/xr-interface-architect.md) | 空间交互设计，沉浸式UX | AR/VR/XR界面设计，空间计算UX |
| 💻 [macOS空间/Metal工程师](spatial-computing/macos-spatial-metal-engineer.md) | Swift，Metal，高性能3D | macOS空间计算，Vision Pro原生应用 |
| 🌐 [XR沉浸式开发者](spatial-computing/xr-immersive-developer.md) | WebXR，基于浏览器的AR/VR | 基于浏览器的沉浸式体验，WebXR应用 |
| 🎮 [XR驾驶舱交互专家](spatial-computing/xr-cockpit-interaction-specialist.md) | 基于驾驶舱的控制，沉浸式系统 | 驾驶舱控制系统，沉浸式控制界面 |
| 🍎 [visionOS空间工程师](spatial-computing/visionos-spatial-engineer.md) | Apple Vision Pro开发 | Vision Pro应用，空间计算体验 |
| 🔌 [终端集成专家](spatial-computing/terminal-integration-specialist.md) | 终端集成，命令行工具 | CLI工具，终端工作流，开发者工具 |

### 🎯 专业部门

不落窠臼的独特专家。

| 代理 | 专业领域 | 何时使用 |
|-------|-----------|-------------|
| 🎭 [代理协调器](specialized/agents-orchestrator.md) | 多代理协调，工作流管理 | 需要多代理协调的复杂项目 |
| 🔍 [LSP/索引工程师](specialized/lsp-index-engineer.md) | 语言服务器协议，代码智能 | 代码智能系统，LSP实现，语义索引 |
| 📥 [销售数据提取代理](specialized/sales-data-extraction-agent.md) | Excel监控，销售指标提取 | 销售数据摄取，MTD/YTD/年终指标 |
| 📈 [数据整合代理](specialized/data-consolidation-agent.md) | 销售数据聚合，仪表板报告 | 区域摘要，代表表现，管道快照 |
| 📬 [报告分发代理](specialized/report-distribution-agent.md) | 自动报告分发 | 基于区域的报告分发，定时发送 |
| 🔐 [代理身份与信任架构师](specialized/agentic-identity-trust.md) | 代理身份，认证，信任验证 | 多代理身份系统，代理授权，审计跟踪 |
| 🔗 [身份图操作员](specialized/identity-graph-operator.md) | 多代理系统的共享身份解析 | 实体去重，合并建议，跨代理身份一致性 |
| 💸 [应付账款代理](specialized/accounts-payable-agent.md) | 支付处理，供应商管理，审计 | 跨加密货币，法定货币，稳定币的自主支付执行 |
| 🛡️ [区块链安全审计师](specialized/blockchain-security-auditor.md) | 智能合约审计，漏洞分析 | 在部署前发现合约中的漏洞 |
| 📋 [合规审计师](specialized/compliance-auditor.md) | SOC 2，ISO 27001，HIPAA，PCI-DSS | 指导组织完成合规认证 |
| 🌍 [文化智能战略家](specialized/specialized-cultural-intelligence-strategist.md) | 全球UX，代表性，文化排斥 | 确保软件在不同文化中产生共鸣 |
| 🗣️ [开发者倡导者](specialized/specialized-developer-advocate.md) | 社区建设，DX，开发者内容 | 连接产品和开发者社区 |
| 🔬 [模型QA专家](specialized/specialized-model-qa.md) | ML审计，功能分析，可解释性 | 机器学习模型的端到端QA |
| 🗃️ [ZK管理员](specialized/zk-steward.md) | 知识管理，Zettelkasten，笔记 | 构建连接的、经验证的知识库 |
| 🔌 [MCP构建器](specialized/specialized-mcp-builder.md) | 模型上下文协议服务器，AI代理工具 | 构建扩展AI代理能力的MCP服务器 |
| 📄 [文档生成器](specialized/specialized-document-generator.md) | 从代码生成PDF，PPTX，DOCX，XLSX | 专业文档创建，报告，数据可视化 |
| ⚙️ [自动化治理架构师](specialized/automation-governance-architect.md) | 自动化治理，n8n，工作流审计 | 评估和大规模治理业务自动化 |
| 📚 [企业培训设计师](specialized/corporate-training-designer.md) | 企业培训，课程开发 | 设计培训系统和学习计划 |
| 🏛️ [政府数字售前顾问](specialized/government-digital-presales-consultant.md) | 中国ToG售前，数字化转型 | 政府数字化转型提案和投标 |
| ⚕️ [医疗营销合规](specialized/healthcare-marketing-compliance.md) | 中国医疗广告合规 | 医疗营销监管合规 |
| 🎯 [招聘专家](specialized/recruitment-specialist.md) | 人才获取，招聘运营 | 招聘策略，寻源和招聘流程 |
| 🎓 [留学顾问](specialized/study-abroad-advisor.md) | 国际教育，申请规划 | 美国英国加拿大澳大利亚留学规划 |
| 🔗 [供应链战略家](specialized/supply-chain-strategist.md) | 供应链管理，采购策略 | 供应链优化和采购规划 |
| 🗺️ [工作流架构师](specialized/specialized-workflow-architect.md) | 工作流发现，映射和规范 | 在编写代码前映射系统中的每条路径 |

### 🎮 游戏开发部门

构建跨越所有主要引擎的世界、系统和体验。

#### 跨引擎代理（引擎无关）

| 代理 | 专业领域 | 何时使用 |
|-------|-----------|-------------|
| 🎯 [游戏设计师](game-development/game-designer.md) | 系统设计，GDD编写，经济平衡，游戏循环 | 设计游戏机制，进度系统，编写设计文档 |
| 🗺️ [关卡设计师](game-development/level-designer.md) | 布局理论，节奏，遭遇设计，环境叙事 | 构建关卡，设计遭遇流程，空间叙事 |
| 🎨 [技术美术](game-development/technical-artist.md) | 着色器，VFX，LOD管道，艺术到引擎优化 | 连接艺术和工程，着色器编写，性能安全的资源管道 |
| 🔊 [游戏音频工程师](game-development/game-audio-engineer.md) | FMOD/Wwise，自适应音乐，空间音频，音频预算 | 交互式音频系统，动态音乐，音频性能 |
| 📖 [叙事设计师](game-development/narrative-designer.md) | 故事系统，分支对话，架构构建 | 编写分支叙事，实现对话系统，世界背景 |

#### Unity

| 代理 | 专业领域 | 何时使用 |
|-------|-----------|-------------|
| 🏗️ [Unity架构师](game-development/unity/unity-architect.md) | ScriptableObjects，数据驱动模块化，DOTS/ECS | 大规模Unity项目，数据驱动系统设计，ECS性能工作 |
| ✨ [Unity着色器图艺术家](game-development/unity/unity-shader-graph-artist.md) | 着色器图，HLSL，URP/HDRP，渲染器功能 | 自定义Unity材质，VFX着色器，后处理通道 |
| 🌐 [Unity多人工程师](game-development/unity/unity-multiplayer-engineer.md) | GameObjects的网络代码，Unity Relay/Lobby，服务器权威，预测 | 在线Unity游戏，客户端预测，Unity游戏服务集成 |
| 🛠️ [Unity编辑器工具开发者](game-development/unity/unity-editor-tool-developer.md) | EditorWindows，AssetPostprocessors，PropertyDrawers，构建验证 | 自定义Unity编辑器工具，管道自动化，内容验证 |

#### 虚幻引擎

| 代理 | 专业领域 | 何时使用 |
|-------|-----------|-------------|
| ⚙️ [Unreal Systems Engineer](game-development/unreal-engine/unreal-systems-engineer.md) | C++/Blueprint混合, GAS, Nanite限制, 内存管理 | 复杂的Unreal游戏系统, Gameplay Ability System, 引擎级C++ |
| 🎨 [Unreal Technical Artist](game-development/unreal-engine/unreal-technical-artist.md) | 材质编辑器, Niagara, PCG, Substrate | Unreal材质, Niagara VFX, 程序化内容生成 |
| 🌐 [Unreal Multiplayer Architect](game-development/unreal-engine/unreal-multiplayer-architect.md) | Actor复制, GameMode/GameState层次结构, 专用服务器 | Unreal在线游戏, 复制图, 服务器权威的Unreal |
| 🗺️ [Unreal World Builder](game-development/unreal-engine/unreal-world-builder.md) | World Partition, Landscape, HLOD, LWC | 大型开放世界Unreal关卡, 流式传输系统, 大规模地形 |

#### Godot

| Agent | Specialty | When to Use |
|-------|-----------|-------------|
| 📜 [Godot Gameplay Scripter](game-development/godot/godot-gameplay-scripter.md) | GDScript 2.0, 信号, 组合, 静态类型 | Godot游戏系统, 场景组合, 性能敏感的GDScript |
| 🌐 [Godot Multiplayer Engineer](game-development/godot/godot-multiplayer-engineer.md) | MultiplayerAPI, ENet/WebRTC, RPC, 权威模型 | 在线Godot游戏, 场景复制, 服务器权威的Godot |
| ✨ [Godot Shader Developer](game-development/godot/godot-shader-developer.md) | Godot着色语言, VisualShader, RenderingDevice | 自定义Godot材质, 2D/3D效果, 后处理, 计算着色器 |

#### Blender

| Agent | Specialty | When to Use |
|-------|-----------|-------------|
| 🧩 [Blender Addon Engineer](game-development/blender/blender-addon-engineer.md) | Blender Python (`bpy`), 自定义操作符/面板, 资产验证器, 导出器, 管道自动化 | 构建Blender插件, 资产准备工具, 导出工作流, 和DCC管道自动化 |

#### Roblox Studio

| Agent | Specialty | When to Use |
|-------|-----------|-------------|
| ⚙️ [Roblox Systems Scripter](game-development/roblox-studio/roblox-systems-scripter.md) | Luau, RemoteEvents/Functions, DataStore, 服务器权威模块架构 | 构建安全的Roblox游戏系统, 客户端-服务器通信, 数据持久化 |
| 🎯 [Roblox Experience Designer](game-development/roblox-studio/roblox-experience-designer.md) | 参与循环, 货币化, D1/D7留存, 上游流程 | 设计Roblox游戏循环, 游戏通行证, 每日奖励, 玩家留存 |
| 👗 [Roblox Avatar Creator](game-development/roblox-studio/roblox-avatar-creator.md) | UGC管道, 配件绑定, 创作者市场提交 | Roblox UGC项目, HumanoidDescription自定义, 体验内Avatar商店 |

---

## 🎯 真实世界用例

### 场景1: 构建创业公司MVP

**您的团队**:
1. 🎨 **前端开发人员** - 构建React应用
2. 🏗️ **后端架构师** - 设计API和数据库
3. 🚀 **增长黑客** - 规划用户获取
4. ⚡ **快速原型师** - 快速迭代周期
5. 🔍 **现实检查员** - 确保发布前质量

**结果**: 在每个阶段拥有专业知识，更快地发布产品。

---

### 场景2: 营销活动启动

**您的团队**:
1. 📝 **内容创作者** - 开发活动内容
2. 🐦 **Twitter互动专员** - Twitter策略和执行
3. 📸 **Instagram策展人** - 视觉内容和故事
4. 🤝 **Reddit社区建设者** - 真实社区参与
5. 📊 **分析报告员** - 跟踪和优化性能

**结果**: 具有平台专业知识的多渠道协调活动。

---

### 场景3: 企业级功能开发

**您的团队**:
1. 👔 **高级项目经理** - 范围和任务规划
2. 💎 **高级开发人员** - 复杂实现
3. 🎨 **UI设计师** - 设计系统和组件
4. 🧪 **实验跟踪器** - A/B测试规划
5. 📸 **证据收集员** - 质量验证
6. 🔍 **现实检查员** - 生产就绪检查

**结果**: 具有质量检查和文档的企业级交付。

---

### 场景5: 付费媒体账户接管

**您的团队**:

1. 📋 **付费媒体审计员** - 全面账户评估
2. 📡 **跟踪与测量专家** - 验证转化跟踪准确性
3. 💰 **PPC活动策略师** - 重新设计账户架构
4. 🔍 **搜索查询分析师** - 清除搜索词浪费的支出
5. ✍️ **广告创意策略师** - 刷新所有广告文案和扩展
6. 📊 **分析报告员** (支持部门) - 构建报告仪表板

**结果**: 系统性账户接管，跟踪已验证，浪费已消除，结构已优化，创意已刷新 - 所有这些都在前30天内完成。

---

### 场景4: 完整机构产品发现

**您的团队**: 所有8个部门并行执行单一任务。

查看 **[Nexus空间发现练习](examples/nexus-spatial-discovery.md)** - 一个完整示例，其中8个代理（产品趋势研究员、后端架构师、品牌守护者、增长黑客、支持响应者、UX研究员、项目牧羊人和XR界面架构师）同时部署，以评估软件机会并制定统一的产品计划，涵盖市场验证、技术架构、品牌战略、上市策略、支持系统、UX研究、项目执行和空间UI设计。

**结果**: 在单一会议中生成的全面、跨职能产品蓝图。[更多示例](examples/)。

---

## 🤝 贡献

我们欢迎贡献！以下是可以提供帮助的方式:
### 添加新代理

1. Fork 仓库
2. 在适当的类别中创建新的代理文件
3. 遵循代理模板结构：
   - 包含名称、描述、颜色的前置元数据
   - 身份与记忆部分
   - 核心任务
   - 关键规则（特定领域）
   - 带示例的技术交付成果
   - 工作流程
   - 成功指标
4. 提交包含你的代理的PR

### 改进现有代理

- 添加真实案例
- 增强代码示例
- 更新成功指标
- 改进工作流程

### 分享你的成功故事

你是否成功使用了这些代理？在[讨论区](https://github.com/msitarzewski/agency-agents/discussions)分享你的故事！

---

## 📖 代理设计理念

每个代理都设计有：

1. **🎭 强烈个性**：不是通用模板，而是真实的角色和声音
2. **📋 明确的交付成果**：具体的输出，而非模糊的指导
3. **✅ 成功指标**：可衡量的成果和质量标准
4. **🔄 经过验证的工作流程**：有效的分步流程
5. **💡 学习记忆**：模式识别和持续改进

---

## 🎁 有什么特别之处？

### 与通用AI提示不同：
- ❌ 通用"扮演开发者"的提示
- ✅ 具有个性化和流程的深度专业化

### 与提示库不同：
- ❌ 一次性提示集合
- ✅ 具有工作流程和交付成果的综合代理系统

### 与AI工具不同：
- ❌ 无法自定义的黑盒工具
- ✅ 透明、可分叉、可适应的代理个性

---

## 🎨 代理个性亮点

> "我不只是测试你的代码 - 我默认会找到3-5个问题，并且要求每件事都有视觉证明。"
>
> -- **证据收集者**（测试部门）

> "你不在Reddit上做营销 - 你正在成为一个有价值的社区成员，恰好代表一个品牌。"
>
> -- **Reddit社区建设者**（营销部门）

> "每个趣味元素必须具有功能性或情感目的。设计增强而非分散注意力的愉悦体验。"
>
> -- **奇思注入者**（设计部门）

> "让我添加一个庆祝动画，将任务完成焦虑减少40%"
>
> -- **奇思注入者**（在UX评审期间）

---

## 📊 统计数据

- 🎭 **144个专业化代理**分布在12个部门
- 📝 **10,000+行**个性、流程和代码示例
- ⏱️ **数月迭代**来自真实世界使用
- 🌟 **经过实战检验**在生产环境中
- 💬 **50+请求**在Reddit发布后12小时内

---

## 🔌 多工具集成

The Agency 原生支持 Claude Code，并提供转换和安装脚本，让你可以在所有主要的代理编程工具中使用相同的代理。

### 支持的工具

- **[Claude Code](https://claude.ai/code)** — 原生 `.md` 代理，无需转换 → `~/.claude/agents/`
- **[GitHub Copilot](https://github.com/copilot)** — 原生 `.md` 代理，无需转换 → `~/.github/agents/` + `~/.copilot/agents/`
- **[Antigravity](https://github.com/google-gemini/antigravity)** — 每个代理的 `SKILL.md` → `~/.gemini/antigravity/skills/`
- **[Gemini CLI](https://github.com/google-gemini/gemini-cli)** — 扩展 + `SKILL.md` 文件 → `~/.gemini/extensions/agency-agents/`
- **[OpenCode](https://opencode.ai)** — `.md` 代理文件 → `.opencode/agents/`
- **[Cursor](https://cursor.sh)** — `.mdc` 规则文件 → `.cursor/rules/`
- **[Aider](https://aider.chat)** — 单个 `CONVENTIONS.md` → `./CONVENTIONS.md`
- **[Windsurf](https://codeium.com/windsurf)** — 单个 `.windsurfrules` → `./.windsurfrules`
- **[OpenClaw](https://github.com/openclaw/openclaw)** — 每个代理的 `SOUL.md` + `AGENTS.md` + `IDENTITY.md`
- **[Qwen Code](https://github.com/QwenLM/qwen-code)** — `.md` 子代理文件 → `~/.qwen/agents/`

---

### ⚡ 快速安装

**步骤 1 -- 生成集成文件：**
```bash
./scripts/convert.sh
```

**步骤 2 -- 安装（交互式，自动检测您的工具）：**
```bash
./scripts/install.sh
```

安装程序会扫描您系统中已安装的工具，显示一个复选框界面，让您精确选择要安装的内容：

```
  +------------------------------------------------+
  |   代理工具 -- 工具安装程序                     |
  +------------------------------------------------+

  系统扫描：[*] = 在此机器上检测到

  [x]  1)  [*]  Claude Code     (claude.ai/code)
  [x]  2)  [*]  Copilot         (~/.github + ~/.copilot)
  [x]  3)  [*]  Antigravity     (~/.gemini/antigravity)
  [ ]  4)  [ ]  Gemini CLI      (gemini 扩展)
  [ ]  5)  [ ]  OpenCode        (opencode.ai)
  [ ]  6)  [ ]  OpenClaw        (~/.openclaw)
  [x]  7)  [*]  Cursor          (.cursor/rules)
  [ ]  8)  [ ]  Aider           (CONVENTIONS.md)
  [ ]  9)  [ ]  Windsurf        (.windsurfrules)
  [ ] 10)  [ ]  Qwen Code       (~/.qwen/agents)

  [1-10] 切换   [a] 全部   [n] 无   [d] 已检测
  [Enter] 安装   [q] 退出
```

**或直接安装特定工具：**
```bash
./scripts/install.sh --tool cursor
./scripts/install.sh --tool opencode
./scripts/install.sh --tool openclaw
./scripts/install.sh --tool antigravity
```

**非交互式（CI/脚本）：**
```bash
./scripts/install.sh --no-interactive --tool all
```

---

### 特定工具说明

<details>
<summary><strong>Claude Code</strong></summary>

代理直接从仓库复制到 `~/.claude/agents/` -- 无需转换。

```bash
./scripts/install.sh --tool claude-code
```

然后在 Claude Code 中激活：
```
使用前端开发人员代理来审查此组件。
```

详细信息请参见 [integrations/claude-code/README.md](integrations/claude-code/README.md)。
</details>

<details>
<summary><strong>GitHub Copilot</strong></summary>

代理直接从仓库复制到 `~/.github/agents/` 和 `~/.copilot/agents/` -- 无需转换。

```bash
./scripts/install.sh --tool copilot
```

然后在 GitHub Copilot 中激活：
```
使用前端开发人员代理来审查此组件。
```

详细信息请参见 [integrations/github-copilot/README.md](integrations/github-copilot/README.md)。
</details>

<details>
<summary><strong>Antigravity (Gemini)</strong></summary>

每个代理都成为 `~/.gemini/antigravity/skills/agency-<slug>/` 中的一个技能。

```bash
./scripts/install.sh --tool antigravity
```
在 Gemini 中使用 Antigravity 激活：
```
@agency-frontend-developer review this React component
```

详细信息请参阅 [integrations/antigravity/README.md](integrations/antigravity/README.md)。
</details>

<details>
<summary><strong>Gemini CLI</strong></summary>

安装为 Gemini CLI 扩展，每个代理一个技能外加一个清单。
在全新克隆时，运行安装程序前先生成 Gemini 扩展文件。

```bash
./scripts/convert.sh --tool gemini-cli
./scripts/install.sh --tool gemini-cli
```

详细信息请参阅 [integrations/gemini-cli/README.md](integrations/gemini-cli/README.md)。
</details>

<details>
<summary><strong>OpenCode</strong></summary>

代理被放置在项目根目录的 `.opencode/agents/` 中（项目范围）。

```bash
cd /your/project
/path/to/agency-agents/scripts/install.sh --tool opencode
```

或全局安装：
```bash
mkdir -p ~/.config/opencode/agents
cp integrations/opencode/agents/*.md ~/.config/opencode/agents/
```

在 OpenCode 中激活：
```
@backend-architect design this API.
```

详细信息请参阅 [integrations/opencode/README.md](integrations/opencode/README.md)。
</details>

<details>
<summary><strong>Cursor</strong></summary>

每个代理成为项目中 `.cursor/rules/` 下的一个 `.mdc` 规则文件。

```bash
cd /your/project
/path/to/agency-agents/scripts/install.sh --tool cursor
```

当 Cursor 在项目中检测到规则时会自动应用。明确引用它们：
```
使用 @security-engineer 规则来审查此代码。
```

详细信息请参阅 [integrations/cursor/README.md](integrations/cursor/README.md)。
</details>

<details>
<summary><strong>Aider</strong></summary>

所有代理都被编译成一个单一的 `CONVENTIONS.md` 文件，Aider 会自动读取。

```bash
cd /your/project
/path/to/agency-agents/scripts/install.sh --tool aider
```

然后在 Aider 会话中引用代理：
```
使用前端开发人员代理来重构此组件。
```

详细信息请参阅 [integrations/aider/README.md](integrations/aider/README.md)。
</details>

<details>
<summary><strong>Windsurf</strong></summary>

所有代理都被编译到项目根目录下的 `.windsurfrules` 中。

```bash
cd /your/project
/path/to/agency-agents/scripts/install.sh --tool windsurf
```

在 Windsurf 的 Cascade 中引用代理：
```
使用现实检查代理来验证这是否已准备好投入生产。
```

详细信息请参阅 [integrations/windsurf/README.md](integrations/windsurf/README.md)。
</details>
<details>
<summary><strong>OpenClaw</strong></summary>

每个代理都会成为一个工作区，在 `~/.openclaw/agency-agents/` 目录下包含 `SOUL.md`、`AGENTS.md` 和 `IDENTITY.md`。

```bash
./scripts/install.sh --tool openclaw
```

代理通过 `agentId` 在 OpenClaw 会话中注册并可用。

详细信息请参阅 [integrations/openclaw/README.md](integrations/openclaw/README.md)。

</details>

<details>
<summary><strong>Qwen Code</strong></summary>

SubAgents 安装在项目根目录的 `.qwen/agents/` 中（项目范围）。

```bash
# 转换并安装（从项目根目录运行）
cd /your/project
./scripts/convert.sh --tool qwen
./scripts/install.sh --tool qwen
```

**在 Qwen Code 中的使用：**
- 按名称引用：`使用 frontend-developer 代理来审查此组件`
- 或让 Qwen 根据任务上下文自动委派
- 在交互模式下通过 `/agents` 命令管理

> 📚 [Qwen SubAgents 文档](https://qwenlm.github.io/qwen-code-docs/en/users/features/sub-agents/)

</details>

---

### 更改后重新生成

当你添加新代理或编辑现有代理时，重新生成所有集成文件：

```bash
./scripts/convert.sh        # 重新生成所有
./scripts/convert.sh --tool cursor   # 仅重新生成一个工具
```

---

## 🗺️ 路线图

- [ ] 交互式代理选择器网页工具
- [x] 多代理工作流示例 -- 参见 [examples/](examples/)
- [x] 多工具集成脚本（Claude Code、GitHub Copilot、Antigravity、Gemini CLI、OpenCode、OpenClaw、Cursor、Aider、Windsurf、Qwen Code）
- [ ] 代理设计视频教程
- [ ] 社区代理市场
- [ ] 项目匹配的代理"性格测试"
- [ ] "每周代理"展示系列

---

## 🌐 社区翻译与本地化

社区维护的翻译和区域适配。这些是独立维护的 -- 请查看每个仓库的覆盖范围和版本兼容性。

| 语言 | 维护者 | 链接 | 备注 |
|----------|-----------|------|-------|
| 🇨🇳 简体中文 (zh-CN) | [@jnMetaCode](https://github.com/jnMetaCode) | [agency-agents-zh](https://github.com/jnMetaCode/agency-agents-zh) | 100 个已翻译的代理 + 9 个中国市场原创 |
| 🇨🇳 简体中文 (zh-CN) | [@dsclca12](https://github.com/dsclca12) | [agent-teams](https://github.com/dsclca12/agent-teams) | 独立翻译，包含 Bilibili、微信、小红书本地化 |

想要添加翻译？请提交一个 issue，我们会在这里链接它。

---

## 🔗 相关资源

- [awesome-openclaw-agents](https://github.com/mergisi/awesome-openclaw-agents) — 社区维护的 OpenClaw 代理集合（源自此仓库）

---

## 📜 许可证

MIT 许可证 - 可以自由、商业或个人使用。欢迎署名但非必需。

---

## 🙏 致谢

从一个关于 AI 代理专业化的 Reddit 帖子开始，已经发展成为一个了不起的项目 — **12个分部的147个代理**，得到了来自世界各地的贡献者社区的支持。此仓库中的每个代理都存在，因为有人足够关心去编写、测试和分享它。

感谢每一位提交 PR、提出问题、发起讨论，或者只是尝试了一个代理并告诉我们什么有效的用户 — 谢谢你们。正是因为你们，The Agency 才能不断变得更好。

---

## 💬 社区

- **GitHub 讨论**: [分享你的成功故事](https://github.com/msitarzewski/agency-agents/discussions)
- **问题**: [报告错误或请求功能](https://github.com/msitarzewski/agency-agents/issues)
- **Reddit**: 在 r/ClaudeAI 加入对话
- **Twitter/X**: 使用 #TheAgency 分享
## 🚀 开始

1. **浏览**上面的代理，为您找到所需的专业人士
2. **复制**代理到 `~/.claude/agents/` 以实现与Claude Code的集成
3. **激活**代理，在您的Claude对话中引用它们
4. **定制**代理的性格和工作流程，以满足您的特定需求
5. **分享**您的成果，并为社区做出贡献

---

<div align="center">

**🎭 The Agency: 您的AI梦之队正在等待 🎭**

[⭐ Star this repo](https://github.com/msitarzewski/agency-agents) • [🍴 Fork it](https://github.com/msitarzewski/agency-agents/fork) • [🐛 Report an issue](https://github.com/msitarzewski/agency-agents/issues) • [❤️ Sponsor](https://github.com/sponsors/msitarzewski)

由社区用心制作，为社区服务

</div>