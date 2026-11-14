<!-- dubline-subs {"title": "MPC for pipelined multiprocessor image-based control systems | CDC 2020 presentation", "author": "Sajid Mohamed", "files": 3, "updated": "2026-11-14"} -->
# MPC for pipelined multiprocessor image-based control systems | CDC 2020 presentation

<img src="8a7da4/1347d791/MPC%20for%20pipelined%20multiprocessor%20image-based%20control%20systems%20CDC%202020%20presentation.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=q1OrkSAIabo](https://www.youtube.com/watch?v=q1OrkSAIabo) |
| 发布 | 2020-12-18 |
| 时长 | 12 分 41 秒 |
| 语言 | 英语 |
| 原作者 | [Sajid Mohamed](https://www.youtube.com/@drsajidmohamed)（@drsajidmohamed，18 订阅） |

## 中文信息

**标题**：【中配】50MHz 处理器下，自适应 MPC 仅耗时 6 毫秒

**原标题译文**：用于流水线多处理器图像控制系统的 MPC | CDC 2020 演讲

这期视频深入探讨了在资源受限且工作负载不断变化的流水线多处理器图像控制系统（IBC）中，如何通过自适应预测控制方案来提升控制性能。在自动驾驶等实际应用场景中，视觉感知的处理时间往往不是固定的，而是具有高度可变性的概率分布特征。传统的控制设计往往倾向于针对最坏情况进行配置，这虽然保证了安全性，但往往会导致处理器利用率低下，甚至出现丢帧现象。本视频将带大家了解如何通过动态调整采样周期和处理策略，有效应对感知延迟的波动，从而在有限的硬件资源下实现更优的控制效果。

通过观看本视频，你可以系统性地掌握以下核心知识点：
首先，视频将详细分析图像工作负载的特性，帮助你理解为什么感知处理时间服从概率分布而非固定值，以及这种可变性对系统稳定性的影响。
其次，你将学习到基于输入输出模型（ARX模型）的预测控制基础数学模型。视频重点讲解了如何通过设置延迟项系数为零，在不改变优化问题规模的前提下，巧妙地处理复杂的处理时间延迟问题。
第三，视频涵盖了核心的算法优化技巧，包括如何构建包含输出跟踪误差惩罚与输入偏离稳态目标惩罚的代价函数，并将复杂的二次规划（QP）问题转化为更易于求解的带框约束最小二乘问题。
第四，你将了解到自适应方案的关键参数调节逻辑，包括如何根据感知延迟的变化动态调整ND参数及堆栈更新策略，从而应对不同的工况变化。
最后，视频还会展示具体的工程实践，包括如何考虑帧间依赖关系、系统非线性以及变量约束等实际工程需求，并提供在50MHz处理器上仅耗时6毫秒的实测数据支撑。

本视频非常适合以下人群观看：
如果你是从事嵌入式系统设计与优化的研究人员或工程师，本视频提供的低功耗、高效率的MPC实现方案将对你的工程实践极具参考价值。
如果你是关注自动驾驶、机器人视觉控制或工业过程控制的学术工作者，视频中关于自适应预测控制的理论推导和实验对比结果将为你提供重要的科研思路。
如果你是一名正在寻找如何在资源受限环境下解决实时控制问题的开发者，本视频展示的将二次规划问题转化为最小二乘问题的技巧，将直接帮助你优化算法的运行效率。
此外，如果你已经具备基础的自动控制理论知识，例如熟悉MPC（模型预测控制）和LQR（线性二次调节器）的基本概念，那么本视频将帮助你更进一步地理解这些理论如何在复杂的流水线多处理器架构中落地。

看完这期视频后，你将能够：
理解并分析图像处理任务在流水线架构中的延迟波动特征，能够识别出传统最坏情况设计在实际应用中的局限性。
掌握将复杂的控制优化问题转化为带框约束最小二乘问题的数学变换方法，掌握处理时间延迟的参数化技巧。
学会设计能够应对感知延迟变化的自适应策略，能够根据不同的工况动态调整控制参数。
掌握在低频处理器（如50MHz）上部署高性能MPC算法的工程经验，能够通过优化算法复杂度在满足实时性要求的同时，获得优于传统LQR控制的控制性能。
最后，你将能够理解如何综合考虑帧间依赖、系统非线性及变量约束，构建出更贴近实际工程需求的自动驾驶横向控制系统。

原视频：MPC for pipelined multiprocessor image-based control systems | CDC 2020 presentation
原作者：Sajid Mohamed
发布日期：2020-12-18
视频链接：https://www.youtube.com/watch?v=q1OrkSAIabo

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| MPC for pipelined multiprocessor image-based control systems CDC 2020 presentation - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](8a7da4/0fa081fb/MPC%20for%20pipelined%20multiprocessor%20image-based%20control%20systems%20CDC%202020%20presentation%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/56ZC3/8a7da4/0fa081fb/MPC%20for%20pipelined%20multiprocessor%20image-based%20control%20systems%20CDC%202020%20presentation%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| MPC for pipelined multiprocessor image-based control systems CDC 2020 presentation - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](8a7da4/185d2f07/MPC%20for%20pipelined%20multiprocessor%20image-based%20control%20systems%20CDC%202020%20presentation%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/56ZC3/8a7da4/185d2f07/MPC%20for%20pipelined%20multiprocessor%20image-based%20control%20systems%20CDC%202020%20presentation%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](8a7da4/6697285a/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/56ZC3/8a7da4/6697285a/dubbed.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

This video is the presentation of the following paper:
Sajid Mohamed, Nilay Saraf, Daniele Bernardini, Dip Goswami, Twan Basten, and Alberto Bemporad, "Adaptive predictive control for pipelined multiprocessor image-based control systems considering workload variations," In IEEE 59th Conference on Decision and Control (CDC), 2020.

---

视频内容版权归原作者所有，字幕仅供学习交流。
