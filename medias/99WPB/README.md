<!-- dubline-subs {"title": "Deploying modern software architecture - the ASML case study (keynote at ICSA 2026)", "author": "International Conference on Software Architecture", "files": 3, "updated": "2026-11-22"} -->
# Deploying modern software architecture - the ASML case study (keynote at ICSA 2026)

<img src="b3a59e/ced10580/Deploying%20modern%20software%20architecture%20-%20the%20ASML%20case%20study%20%28keynote%20at%20ICSA%202026%29.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=EPV5WGY5h2U](https://www.youtube.com/watch?v=EPV5WGY5h2U) |
| 发布 | 2026-07-28 |
| 时长 | 43 分 3 秒 |
| 语言 | 英语 |
| 原作者 | [International Conference on Software Architecture](https://www.youtube.com/@IEEEICSA)（@IEEEICSA，142 订阅） |

## 中文信息

**标题**：【中配】ASML 光刻机软件架构：如何解耦百吨级设备的致命复杂度

**原标题译文**：部署现代软件架构 - ASML 案例研究 (ICSA 2026 主旨演讲)

这期视频将带你深入剖析全球半导体制造领域的巅峰设备——ASML光刻机的软件架构演进之路。面对重达百吨、包含二十万个零件的极端复杂设备，如何在纳米级的精度要求下，同时应对热变形、地震等环境干扰，并确保软件逻辑的鲁棒性？ASML通过引入基于领域驱动设计（DDD）的DCA（数据、控制与算法）分层架构，成功破解了单体架构带来的圈复杂度爆炸危机。我们将跟随ASML首席架构师的视角，揭开这些精密机器背后的软件工程艺术，探讨如何通过架构解耦来应对工业级系统的致命复杂度。

通过本期视频的学习，你可以掌握以下核心知识点：

首先是DCA分层架构的深度解析。视频将详细介绍ASML如何将复杂的系统拆分为三个核心层级：顶层的响应式有限状态机（Coco）负责事件驱动的控制逻辑，中间层保持无状态的原子算法以支持独立的测试与形式化验证，而底层则利用自研的C代码生成器来处理复杂的数据结构与坐标操作。这种分层策略不仅提升了系统的可维护性，还为跨平台软件复用奠定了基础。

其次是关于工业系统一致性与可预测性的深度思考。我们将分析半导体制造客户的核心诉求，探讨在面对旧工艺坚守者与混合系统升级者时，厂商如何平衡新功能迭代与系统稳定性。视频将揭示软件逻辑变更带来的风险，特别是那些未经充分预警的Bug修复或行为突变，如何引发生产中断，以及厂商在面对客户防御性优化时的应对策略。

最后是保障生产连续性的工程实践。视频将介绍ASML如何利用数字孪生模拟技术，在变更实施前至少提前六个月甚至一年进行预警和评估。通过在虚拟环境中模拟变更影响，并利用配置开关保留旧逻辑，确保在不中断客户生产流程的前提下完成系统升级，从而保障晶圆厂的良率与利润。

本期视频非常适合以下人群观看：

如果你是半导体制造或高端工业设备领域的软件架构师与工程师，这期视频将为你提供极具参考价值的工业级架构设计案例。如果你负责高价值、高可靠性的嵌入式系统或实时控制系统，视频中关于如何处理复杂状态机和算法解耦的经验将对你的项目极具启发。此外，对于关注领域驱动设计（DDD）在复杂工业场景落地实践的专业人员，或者需要在新功能迭代与旧系统兼容性之间寻找平衡的技术决策者，这期视频提供的深度技术剖析将帮助你更好地理解如何构建稳健的工业软件生态。

看完这期视频后，你将能够理解ASML如何通过架构手段解决软件复杂度爆炸问题，掌握DCA分层架构的核心逻辑，并学会如何通过数字孪生和提前预警机制来管理工业软件中的风险点。通过学习这些工业界的顶尖实践，你将能够更清晰地构建高可靠性的软件系统，并在处理复杂业务逻辑时，具备更强的架构设计思维和风险控制能力。

原视频：Deploying modern software architecture - the ASML case study (keynote at ICSA 2026)
原作者：International Conference on Software Architecture
发布日期：2026-07-28
视频链接：https://www.youtube.com/watch?v=EPV5WGY5h2U

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| Deploying modern software architecture - the ASML case study (keynote at ICSA 2026) - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](a8e1f5/946d3967/Deploying%20modern%20software%20architecture%20-%20the%20ASML%20case%20study%20%28keynote%20at%20ICSA%202026%29%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/99WPB/a8e1f5/946d3967/Deploying%20modern%20software%20architecture%20-%20the%20ASML%20case%20study%20%28keynote%20at%20ICSA%202026%29%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| Deploying modern software architecture - the ASML case study (keynote at ICSA 2026) - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](a8e1f5/de74ebcd/Deploying%20modern%20software%20architecture%20-%20the%20ASML%20case%20study%20%28keynote%20at%20ICSA%202026%29%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/99WPB/a8e1f5/de74ebcd/Deploying%20modern%20software%20architecture%20-%20the%20ASML%20case%20study%20%28keynote%20at%20ICSA%202026%29%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](a8e1f5/f1643e55/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/99WPB/a8e1f5/f1643e55/dubbed.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

This is the keynote by Lewis Binns (ASML) at the 23rd edition of the IEEE International Conference on Software Architecture (ICSA 2026), held in Amsterdam, The Netherlands.

---

视频内容版权归原作者所有，字幕仅供学习交流。
