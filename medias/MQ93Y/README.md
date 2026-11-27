<!-- dubline-subs {"title": "[REBASE'26] The Last Mile of Certified Programming", "author": "ACM SIGPLAN", "files": 2, "updated": "2026-11-27"} -->
# [REBASE'26] The Last Mile of Certified Programming

<img src="0890c1/046002d2/%5BREBASE%2726%5D%20The%20Last%20Mile%20of%20Certified%20Programming.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=ERemvvBxlxo](https://www.youtube.com/watch?v=ERemvvBxlxo) |
| 发布 | 2026-11-16 |
| 时长 | 38 分 0 秒 |
| 语言 | 英语 |
| 原作者 | [ACM SIGPLAN](https://www.youtube.com/@acmsigplan)（@acmsigplan，约 1 万订阅） |

## 中文信息

**标题**：【中配】38分钟带你搞懂：如何用认证编程生成无漏洞的C语言库

**原标题译文**：[REBASE26] 认证编程的最后一公里

在当今软件工程领域，内存安全漏洞和未定义行为依然是导致系统崩溃和安全风险的主要原因。传统的软件验证往往是在程序开发完成后，通过测试或静态分析来寻找漏洞，这种做法本质上是在事后补救。本期视频将带大家深入探讨一种全新的范式：认证编程（Certified Programming）。通过认证编程，我们不再仅仅是寻找漏洞，而是通过构造能够同时表达程序规范和正确性证明的语言来编写程序，从而从源头上确保代码的正确性。视频的核心内容围绕 Crane 项目展开，这是一个旨在将 Rocq 语言编写的经证明正确的代码，转化为生产环境可读、内存安全且高性能的 C 语言库的提取系统。

通过本期视频的学习，你可以掌握以下核心知识点：首先是认证编程与传统软件验证的本质区别，理解如何通过形式化证明来弥补传统测试和防御性编程的不足。其次是深入了解 Crane 系统处理复杂逻辑的核心技术，包括如何通过 CPS 转换和去函数化技术实现递归循环化，从而有效避免 C 语言中常见的栈溢出问题。此外，视频还会详细讲解零开销抽象映射的实现，即如何将 Rocq 的归纳类型映射为 Variant，将多态映射为模板，并将类型类映射为 Concept。对于高级开发者来说，视频中关于交互树（Interaction Trees）的处理方式也非常关键，它展示了如何在纯函数式语言中处理 IO、状态和并发等副作用。最后，视频还会探讨工业界的实际落地挑战，例如如何在保持正确性的前提下，通过 Wrapper 包装来兼容现有的库接口。

本视频非常适合软件工程领域的安全研究人员、形式化验证从业者，以及对 Rust、C 语言底层内存管理和高性能系统编程感兴趣的开发者。如果你在研究 AI Agent 如何降低形式化验证成本，或者在思考如何将函数式编程的思想应用于工业级 C 代码生成，这期视频提供的技术路径和工业案例将为你提供极具价值的参考。

看完本期视频后，你将能够清晰地理解认证编程的逻辑框架，掌握从 Rocq 到 C 的代码提取全流程。你将学会如何利用递归循环化和零开销抽象等技术手段，将高阶的函数式编程概念转化为高性能的底层代码。更重要的是，通过学习 Crane 项目在扫雷、魔方求解器以及彭博公司微服务中的实际应用案例，你将能够理解如何平衡性能、可读性与正确性，并掌握在实际工程中构建无漏洞 C 语言库的思路。无论你是希望提升底层编程的安全水平，还是在探索形式化验证的前沿技术，这期视频都将为你提供从理论到实践的全面指导。

原视频：[REBASE'26] The Last Mile of Certified Programming
原作者：ACM SIGPLAN
发布日期：2026-11-16
视频链接：https://www.youtube.com/watch?v=ERemvvBxlxo

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| [REBASE'26] The Last Mile of Certified Programming - 英语字幕.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](0890c1/5609f1b9/%5BREBASE%2726%5D%20The%20Last%20Mile%20of%20Certified%20Programming%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/MQ93Y/0890c1/5609f1b9/%5BREBASE%2726%5D%20The%20Last%20Mile%20of%20Certified%20Programming%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95.en.srt) |
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](0890c1/fc4775a9/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/MQ93Y/0890c1/fc4775a9/dubbed.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

The Last Mile of Certified Programming (Video, REBASE 2026)
Joomy Korkut
(Bloomberg)

---

视频内容版权归原作者所有，字幕仅供学习交流。
