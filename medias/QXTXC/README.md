<!-- dubline-subs {"title": "[ISSTA'26] Finding the Bugs Users Would Find: From Sapienz to Autonomous Agents", "author": "ACM SIGPLAN", "files": 2, "updated": "2026-11-27"} -->
# [ISSTA'26] Finding the Bugs Users Would Find: From Sapienz to Autonomous Agents

<img src="220882/5308efb9/%5BISSTA%2726%5D%20Finding%20the%20Bugs%20Users%20Would%20Find%20From%20Sapienz%20to%20Autonomous%20Agents.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=ozSr9dzYawM](https://www.youtube.com/watch?v=ozSr9dzYawM) |
| 发布 | 2026-11-16 |
| 时长 | 45 分 46 秒 |
| 语言 | 英语 |
| 原作者 | [ACM SIGPLAN](https://www.youtube.com/@acmsigplan)（@acmsigplan，约 1 万订阅） |

## 中文信息

**标题**：【中配】每天跑250万次测试，Meta靠这套系统守住Facebook和WhatsApp

**原标题译文**：[ISSTA26] 寻找用户会发现的 Bug：从 Sapienz 到自主智能体

这期视频将带你深度解析 Meta 如何构建并运行一套极其强大的自动化测试与修复系统，支撑起 Facebook、Instagram 和 WhatsApp 等全球顶级应用的稳定性。我们将重点围绕 Sapienz 系统从最初的学术研究原型到最终在 Meta 工业级生产环境大规模部署的完整演进历程展开。视频不仅展示了 Meta 是如何通过多目标优化和动机基因模拟人类行为来生成高质量测试路径的，还详细拆解了如何将测试验证工作从发布后的阶段提前到持续集成（CI）甚至代码审查阶段，也就是所谓的向左移策略。更重要的是，视频最后将带你进入智能体（Agents）时代，看 Meta 如何引入智能体来解决自动化测试中最核心的判定标准问题，并构建起从发现崩溃到自动修复的完整闭环。

通过观看本期视频，你可以获取到以下核心知识点：

首先是关于 Sapienz 系统核心架构的理解。你会了解到该系统如何利用遗传算法在最大化测试覆盖率和故障演进的同时，通过最小化测试序列长度来确保崩溃的可重现性。此外，视频还会解释动机基因（MotifGene）的概念，即如何通过模拟真实人类的操作行为来生成更具代表性的自动化测试路径，从而提高测试的有效性。

其次是关于信号增强与隐私保护的技术细节。视频将展示如何将 Sapienz 的动态分析与 Infer 静态分析工具相结合，通过信号增强技术提高报告的准确性，并获取更细粒度的根因分析。同时，你还能了解到这一引擎是如何演进并扩展到 PrivacyCat 系统中，用于预防潜在的隐私泄露事件。

第三是关于自动化修复系统 SetFix 的深度解析。你将学习到 SetFix 是如何从发现崩溃出发，通过撤销差异、基于模板的修复以及在抽象语法树（AST）上进行变异等多种策略，自动生成并筛选出高质量的修复补丁。

最后是关于智能体（Agent）在软件工程中的变革性应用。视频将详细讲解智能体如何解决自动化测试中难以判断行为是否正确的判定标准问题，并介绍智能体在自我审查、独立代码审查、落地决策以及驱动端到端应用等四个核心关卡中的具体职责。

本期视频非常适合软件测试工程师、自动化测试研究人员以及软件质量保障（QA）从业者观看。如果你是一名对自动化修复（Auto-repair）技术感兴趣的开发者，或者正在研究如何将智能体（Agents）应用于软件工程领域，这期视频提供的工业级实战案例将为你提供极具价值的参考。此外，对于需要了解大规模工业级 CI 流程中如何处理崩溃问题、如何保障每月数百个应用稳定发布的网络技术人员来说，视频中提到的每天运行约 250 万次测试、每周发现约 2000 个唯一崩溃的真实数据指标，将为你提供极具震撼力的技术视野。

看完这期视频后，你将能够掌握 Meta 处理大规模应用崩溃的核心逻辑，理解多目标优化在自动化测试中的应用原理，并能够清晰地勾勒出从自动化测试发现问题到利用智能体进行自动修复的完整技术链路。无论你是希望提升现有测试流程效率的从业者，还是追求前沿技术突破的开发者，这期视频都能为你提供从学术理论到工业落地的高质量技术干货。

原视频：[ISSTA'26] Finding the Bugs Users Would Find: From Sapienz to Autonomous Agents
原作者：ACM SIGPLAN
发布日期：2026-11-16
视频链接：https://www.youtube.com/watch?v=ozSr9dzYawM

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| [ISSTA'26] Finding the Bugs Users Would Find From Sapienz to Autonomous Agents - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](220882/55bd704f/%5BISSTA%2726%5D%20Finding%20the%20Bugs%20Users%20Would%20Find%20From%20Sapienz%20to%20Autonomous%20Agents%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/QXTXC/220882/55bd704f/%5BISSTA%2726%5D%20Finding%20the%20Bugs%20Users%20Would%20Find%20From%20Sapienz%20to%20Autonomous%20Agents%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](220882/702566a4/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/QXTXC/220882/702566a4/dubbed.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

Finding the Bugs Users Would Find: From Sapienz to Autonomous Agents (Keynote) (Video, ISSTA 2026)
Ke Mao
(Meta, UK)

---

视频内容版权归原作者所有，字幕仅供学习交流。
