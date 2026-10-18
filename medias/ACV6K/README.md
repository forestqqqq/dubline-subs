<!-- dubline-subs {"title": "Rebuilding CI for AI-Scale Commit Volume — Gautam Korlam, Sonar", "author": "AI Engineer", "files": 3, "updated": "2026-10-17"} -->
# Rebuilding CI for AI-Scale Commit Volume — Gautam Korlam, Sonar

<img src="bc4354/241ab182/Rebuilding%20CI%20for%20AI-Scale%20Commit%20Volume%20%E2%80%94%20Gautam%20Korlam%2C%20Sonar.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=7b9tov5Uc5s](https://www.youtube.com/watch?v=7b9tov5Uc5s) |
| 发布 | 2026-10-14 |
| 时长 | 19 分 18 秒 |
| 语言 | 英语 |
| 原作者 | [AI Engineer](https://www.youtube.com/@aiDotEngineer)（@aiDotEngineer，约 76 万订阅） |

## 中文信息

**标题**：AI 代码生成让 CI 队列彻底崩盘了怎么办

**原标题译文**：为 AI 规模的提交量重构 CI —— Gautam Korlam, Sonar

随着 AI 编程智能体的爆发式应用，开发者在生成代码时的效率得到了极大提升，但这也带来了一个意想不到的工程挑战：当大量的 AI 生成代码涌入系统时，传统的 CI/CD 流水线往往会因为无法承受高频并发提交而陷入严重的串行瓶颈。本期视频将深入探讨这一现象，分析当智能体生成的 PR 数量呈指数级增长时，如何避免合并队列崩溃，并提供一套完整的工程化解决方案来重构你的构建系统。

通过这期内容的学习，你可以掌握以下核心知识点：首先是识别 AI 时代特有的基础设施压力，包括由于高频并行提交导致的构建超时、测试失败频繁重试以及严重的队列积压问题；其次是深入了解如何利用缓存技术和分片并行构建（例如参考 Rust 构建系统的优化案例及 NextTest 框架），来显著降低重复构建的成本并降低交叉污染的风险；再者，视频将详细讲解如何实施基于风险的合并策略，通过自动识别低风险或内部变更来加速流程，同时将昂贵的合规检查前置到流水线前端而非依赖末端的过滤；最后，你还将学到严谨的审计与安全机制，包括禁止智能体自我批准、建立提示词工程师与代码作者分离的双人复核制度，以及记录完整的审计轨迹（涵盖会话记录和人工干预证据），确保所有操作都有明确的命名标识和可追溯的修复闭环。

这期视频特别适合以下人群观看：如果你是一名负责 CI/CD 流水线设计与优化的 DevOps 工程师，本视频提供的分片构建和缓存优化策略将直接帮助你解决高并发下的系统稳定性问题；如果你是正在开发 AI 编程助手或计划将其集成到企业级工作流中的软件工程师，通过学习如何处理智能体带来的合规挑战和审计要求，你可以构建出更符合工业标准的工具链；此外，对于需要在大规模代码提交环境下平衡效率与安全、负责公司内部合规审计的科技公司管理者来说，视频中提到的 HIPAA 和 DORA 等标准相关的合规策略也将提供极具价值的实操参考。

看完本期视频后，你将能够从技术和管理两个维度应对 AI 带来的工程冲击。在技术层面，你将掌握如何通过分片并行、缓存优化等手段提升构建效率，让你的 CI 系统在面对海量 PR 时依然稳如磐石；在流程治理层面，你将学会建立一套完整的审计体系，确保每一行由智能体生成的代码都能在可追溯的范围内进行管理。无论你是想解决当前的系统崩溃问题，还是在为未来的 AI 协作工作流做前瞻性布局，这期内容都将为你提供从技术架构到合规规范的全方位指导，帮助你构建出一个既高效又安全的现代化软件生产工厂。

章节
00:00 编程智能体将瓶颈转移至持续集成
1:13 SubmitQueue 与合并前组合测试
2:53 为人类速度设计的队列为何失效
5:24 软件工厂下的重复修复循环
7:08 CI 失败带来的反馈成本
8:11 增量构建、缓存与并行工作优化
10:16 持续通过 CI 后的政策强制执行
13:28 基于风险的合并与审批策略
15:21 测试过的提交、覆盖例外与审计证据

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| Rebuilding CI for AI-Scale Commit Volume — Gautam Korlam, Sonar - 英语字幕（转写）.en.srt | 原文字幕（转写） | [查看 / 下载](bc4354/288cac71/Rebuilding%20CI%20for%20AI-Scale%20Commit%20Volume%20%E2%80%94%20Gautam%20Korlam%2C%20Sonar%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/ACV6K/bc4354/288cac71/Rebuilding%20CI%20for%20AI-Scale%20Commit%20Volume%20%E2%80%94%20Gautam%20Korlam%2C%20Sonar%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| Rebuilding CI for AI-Scale Commit Volume — Gautam Korlam, Sonar - 简体中文字幕（翻译）.zh.srt | 译文字幕 | [查看 / 下载](bc4354/3ba1573d/Rebuilding%20CI%20for%20AI-Scale%20Commit%20Volume%20%E2%80%94%20Gautam%20Korlam%2C%20Sonar%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E5%AD%97%E5%B9%95%EF%BC%88%E7%BF%BB%E8%AF%91%EF%BC%89.zh.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/ACV6K/bc4354/3ba1573d/Rebuilding%20CI%20for%20AI-Scale%20Commit%20Volume%20%E2%80%94%20Gautam%20Korlam%2C%20Sonar%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E5%AD%97%E5%B9%95%EF%BC%88%E7%BF%BB%E8%AF%91%EF%BC%89.zh.srt) |
| Rebuilding CI for AI-Scale Commit Volume — Gautam Korlam, Sonar - 中英双语字幕.srt | 双语字幕 | [查看 / 下载](bc4354/8049e1ea/Rebuilding%20CI%20for%20AI-Scale%20Commit%20Volume%20%E2%80%94%20Gautam%20Korlam%2C%20Sonar%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/ACV6K/bc4354/8049e1ea/Rebuilding%20CI%20for%20AI-Scale%20Commit%20Volume%20%E2%80%94%20Gautam%20Korlam%2C%20Sonar%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，时间轴与原视频一致，可直接拖进播放器（PotPlayer、VLC、IINA 等）加载。

## 原视频章节

| 时间 | 章节 |
|---|---|
| 00:00 | Coding agents move the bottleneck into CI |
| 1:13 | SubmitQueue and testing combinations before merge |
| 2:53 | Queues built for human speed |
| 5:24 | The software factory and repeated repair loops |
| 7:08 | CI failures and the feedback cost |
| 8:11 | Incremental builds, caching and parallel work |
| 10:16 | Enforcing policy beyond passing CI |
| 13:28 | Risk based merge and approval policies |
| 15:21 | Tested commits, overrides and audit evidence |

## 原视频简介

A coding agent can produce changes faster than the queues that test, review and merge them. Gautam Korlam examines that mismatch through his work on Uber's SubmitQueue and Gitar, now part of Sonar. A merge queue keeps the main branch healthy by testing combinations of changes before they land, but a process designed for human arrival rates can become a bottleneck when agents create many pull requests at once. Faster code generation shifts the constraint to failed builds, repeated repairs, review and approvals. Korlam argues that the engineering system around the agent must change alongside the agent itself.

---

视频内容版权归原作者所有，字幕仅供学习交流。
