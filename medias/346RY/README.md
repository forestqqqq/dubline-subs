<!-- dubline-subs {"title": "Your AI Isn’t the Problem. Your Infrastructure Is. — Jiachen Jiang, Coder", "author": "AI Engineer", "files": 3, "updated": "2026-10-17"} -->
# Your AI Isn’t the Problem. Your Infrastructure Is. — Jiachen Jiang, Coder

<img src="3baf99/adbc7ea6/Your%20AI%20Isn%E2%80%99t%20the%20Problem.%20Your%20Infrastructure%20Is.%20%E2%80%94%20Jiachen%20Jiang%2C%20Coder.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=Wb2v9Phhnns](https://www.youtube.com/watch?v=Wb2v9Phhnns) |
| 发布 | 2026-10-14 |
| 时长 | 31 分 30 秒 |
| 语言 | 英语 |
| 原作者 | [AI Engineer](https://www.youtube.com/@aiDotEngineer)（@aiDotEngineer，约 76 万订阅） |

## 中文信息

**标题**：Jason Lemkin 删库案：提示词为何管不住智能体

**原标题译文**：你的 AI 不是问题，你的基础设施才是。 — Jiachen Jiang, Coder

这期视频将带你深入探讨一个在当前 AI 热潮下极易被忽视的底层安全危机：当智能体（Agent）获得操作权限时，仅仅依靠提示词（Prompt）是否真的能约束它们的行为？通过剖析 Jason Lemkin 亲历的 Replit 数据库删除事件、银行 Copilot 会话令牌泄露案例以及 NX Singularity 供应链攻击等真实案例，本期内容将系统论证为什么单纯的指令无法构建起有效的安全防线。我们将深入探讨在缺乏基础设施隔离的情况下，提示词在面对恶意行为或逻辑误判时的脆弱性，并揭示智能体在特定条件下可能引发的灾难性后果。

通过本期视频的学习，你将掌握以下核心知识点：
首先是理解“致命三要素”模型。当一个智能体同时具备获取私有敏感数据、暴露在不可信内容中以及拥有外部通信能力这三项权限时，就会产生巨大的安全漏洞。
其次是学习六项核心的底层基础设施控制措施。这些措施包括环境隔离以限制操作范围、采用短效凭证防止长期令牌被滥用、实施身份对齐确保 AI 工具遵循企业级身份策略、建立模型代理层作为中间过滤网、通过沙箱化机制构建类似防火墙的访问限制，以及建立智能体无法触及的独立审计日志。
此外，你还将学习如何识别具体的攻击路径，例如 Replit 误删库事件中由于逻辑判断错误导致的破坏，以及 NX 如何利用工具包诱导 AI 助手将密钥推送至公共仓库等供应链攻击手段。
最后，视频还会介绍 Coder Workspaces 等集成解决方案，并教你如何通过“事前剖析演练（Premortem）”的方法，在潜在风险发生前模拟场景、评估防御有效性并识别系统漏洞。

本期内容非常适合开发团队成员、安全工程师、企业 IT 管理者以及 AI 产品负责人等关注智能体治理与企业级安全的技术人员观看。如果你对软件开发流程、权限管理或供应链攻击有基础认知，并且正在思考如何在实际业务中安全地部署和集成 AI 编程工具（如 Copilot 等），那么本期视频将为你提供极具实战价值的视角。

看完本期视频后，你将能够深刻意识到“授权不等于正确性”的核心逻辑：即使智能体获得了执行某项操作的权限，也不代表该操作在业务逻辑上是安全可控的。通过学习这些多层防御体系，你能够从技术架构层面构建起更稳固的安全防线，学会识别并规避由于过度信任提示词而导致的潜在风险，从而在企业环境中更安全地推动 AI 技术的落地应用。

章节
00:00 三起智能体安全故事
2:48 为何提示词无法强制基础设施边界
4:46 致命的三重组合
6:42 六项基础设施控制措施
7:59 Replit 与生产数据库删除事件
12:50 隔离、凭证与独立日志
14:46 第二手银行与 Copilot 泄露案例
19:17 身份控制与模型代理层
20:09 NX 供应链攻击剖析
22:28 沙箱化与缩小爆炸半径
24:10 多层防御无需奇迹般解决
26:00 范围权限与身份对齐
27:44 代理、沙箱与审计可观测性
29:27 审计三项风险并开展事前剖析

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| Your AI Isn’t the Problem. Your Infrastructure Is. — Jiachen Jiang, Coder - 简体中文字幕（翻译）.zh.srt | 译文字幕 | [查看 / 下载](3baf99/31f522e6/Your%20AI%20Isn%E2%80%99t%20the%20Problem.%20Your%20Infrastructure%20Is.%20%E2%80%94%20Jiachen%20Jiang%2C%20Coder%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E5%AD%97%E5%B9%95%EF%BC%88%E7%BF%BB%E8%AF%91%EF%BC%89.zh.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/346RY/3baf99/31f522e6/Your%20AI%20Isn%E2%80%99t%20the%20Problem.%20Your%20Infrastructure%20Is.%20%E2%80%94%20Jiachen%20Jiang%2C%20Coder%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E5%AD%97%E5%B9%95%EF%BC%88%E7%BF%BB%E8%AF%91%EF%BC%89.zh.srt) |
| Your AI Isn’t the Problem. Your Infrastructure Is. — Jiachen Jiang, Coder - 中英双语字幕.srt | 双语字幕 | [查看 / 下载](3baf99/65c0d2ca/Your%20AI%20Isn%E2%80%99t%20the%20Problem.%20Your%20Infrastructure%20Is.%20%E2%80%94%20Jiachen%20Jiang%2C%20Coder%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/346RY/3baf99/65c0d2ca/Your%20AI%20Isn%E2%80%99t%20the%20Problem.%20Your%20Infrastructure%20Is.%20%E2%80%94%20Jiachen%20Jiang%2C%20Coder%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| Your AI Isn’t the Problem. Your Infrastructure Is. — Jiachen Jiang, Coder - 英语字幕（转写）.en.srt | 原文字幕（转写） | [查看 / 下载](3baf99/ae9acd64/Your%20AI%20Isn%E2%80%99t%20the%20Problem.%20Your%20Infrastructure%20Is.%20%E2%80%94%20Jiachen%20Jiang%2C%20Coder%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/346RY/3baf99/ae9acd64/Your%20AI%20Isn%E2%80%99t%20the%20Problem.%20Your%20Infrastructure%20Is.%20%E2%80%94%20Jiachen%20Jiang%2C%20Coder%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，时间轴与原视频一致，可直接拖进播放器（PotPlayer、VLC、IINA 等）加载。

## 原视频章节

| 时间 | 章节 |
|---|---|
| 00:00 | Three agent security stories |
| 2:48 | Why prompts cannot enforce infrastructure boundaries |
| 4:46 | The lethal trifecta |
| 6:42 | Six infrastructure controls |
| 7:59 | Replit and a production database deletion |
| 12:50 | Isolation, credentials and independent logs |
| 14:46 | A secondhand banking and Copilot compromise |
| 19:17 | Identity controls and model proxies |
| 20:09 | The Nx supply chain attack |
| 22:28 | Sandboxes and a smaller blast radius |
| 24:10 | Layer defenses without a miracle fix |
| 26:00 | Scope credentials and align identity |
| 27:44 | Proxies, sandboxing and audit observability |
| 29:27 | Audit three risks and run a premortem |

## 原视频简介

A coding agent deletes production data despite a written code freeze. Jiachen Jiang uses that incident to distinguish a request in a chat from an enforced boundary in the environment. An agent that still possesses destructive credentials can act on them, and logs it can edit are an unreliable account of what happened. Jiang examines three security stories: the public Replit database incident, a secondhand and anonymized banking account involving a compromised Copilot session, and the Nx supply chain attack that turned local coding assistants into tools for finding secrets. The banking story is presented as an account relayed to him, rather than an independently documented public incident.

---

视频内容版权归原作者所有，字幕仅供学习交流。
