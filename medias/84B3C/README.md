<!-- dubline-subs {"title": "Enforcing Safety at Runtime for Systems with Disturbances", "author": "FACTS Lab at Georgia Tech", "files": 3, "updated": "2026-11-14"} -->
# Enforcing Safety at Runtime for Systems with Disturbances

<img src="3587ea/c986d1ad/Enforcing%20Safety%20at%20Runtime%20for%20Systems%20with%20Disturbances.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=6I05WyBQI8A](https://www.youtube.com/watch?v=6I05WyBQI8A) |
| 发布 | 2020-11-10 |
| 时长 | 12 分 54 秒 |
| 语言 | 英语 |
| 原作者 | [FACTS Lab at Georgia Tech](https://www.youtube.com/@factslabatgeorgiatech6699)（@factslabatgeorgiatech6699，29 订阅） |

## 中文信息

**标题**：【中配】12 分钟，用混合单调性给带扰动系统加运行时安全锁

**原标题译文**：为具有扰动的系统提供运行时安全保障

这期视频的核心内容是针对存在仿射扰动的控制系统，提出一种基于混合单调性预测的运行时保证机制。在实际应用中，控制系统往往面临外部扰动或模型不确定性的挑战，如何在保证系统长期安全性的前提下，尽可能维持标称控制性能是一个关键问题。本视频展示的创新方法是构建一种 Active Set Invariance 滤波器，该滤波器能够在允许系统在特定条件下暂时偏离安全集的同时，通过在线计算可达集来确保系统的长期安全性。

通过观看本视频，你可以掌握以下具体的知识点：

首先是关于运行时保证机制的核心逻辑。视频详细介绍了 Active Set Invariance 滤波器的工作原理，即如何在线过滤控制信号。该机制的核心逻辑在于：当系统当前状态处于安全范围内时，控制器输出期望的控制输入以追求最优性能；一旦系统状态接近或进入风险区域，控制器会迅速切换到备用策略或修正当前的控制输入，以确保系统状态始终不进入不安全集合。

其次是关于混合单调系统理论及其在鲁棒可达集计算中的应用。视频讲解了如何将复杂的非确定性系统转化为确定性的辅助嵌入系统。通过分析雅可比矩阵的符号结构，可以快速生成分解函数，进而构建出辅助嵌入系统。利用这些嵌入系统的单条轨迹，可以高效地计算出原始系统在任意扰动策略下的完整鲁棒可达集。这一方法为处理扰动带来的不确定性提供了强有力的数学工具。

此外，视频还涵盖了多个关键的算法细节和理论假设。例如，视频解释了如何利用矩形可达集近似法来处理离散化连续系统的可达性分析，从而简化复杂的优化问题。同时，视频还讨论了关键的安全性假设，例如备用控制器与安全集的互不相交性，以及允许系统在有限时间内处于安全集的吸引域中，只要该区域不与不安全集相交，即可实现前向安全性。

最后，视频通过三车编队这一具体的数值仿真案例，直观地展示了理论的应用效果。在仿真中，你可以清晰地看到洋红色的标称轨迹在受到扰动影响时逐渐偏离安全范围，而经过本视频提出的保证机制处理后的蓝色轨迹，则始终被约束在安全区域内，完美平衡了控制性能与安全性。

本视频非常适合从事自动驾驶、机器人控制或工业过程控制的工程师与研究人员观看。如果你正在设计需要处理模型不确定性及外部扰动的实时控制系统，或者你正在研究如何利用控制障碍函数（CBF）来验证系统的前向不变性，那么这期视频提供的技术路径将对你的研究或工程实践非常有帮助。此外，如果你已经具备基础的控制理论知识，例如了解 Lyapunov 稳定性或控制障碍函数的基本概念，那么本视频深入探讨的混合单调性预测和可达集计算方法将为你提供更高阶的技术支持。

看完这期视频后，你将能够理解如何构建一套完整的运行时保证框架。你不仅能掌握如何通过计算确定性辅助嵌入系统的轨迹来获取鲁棒可达集，还能学会如何设计 Active Set Invariance 滤波器来实时修正控制输入。通过学习视频中的算法逻辑，你可以在自己的控制系统中引入类似的保证机制，确保在复杂的外部扰动环境下，你的系统依然能够稳定、安全地运行，并在保证安全的前提下尽可能保留标称控制轨迹的优良性能。

原视频：Enforcing Safety at Runtime for Systems with Disturbances
原作者：FACTS Lab at Georgia Tech
发布日期：2020-11-10
视频链接：https://www.youtube.com/watch?v=6I05WyBQI8A

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| Enforcing Safety at Runtime for Systems with Disturbances - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](3587ea/2cc52202/Enforcing%20Safety%20at%20Runtime%20for%20Systems%20with%20Disturbances%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/84B3C/3587ea/2cc52202/Enforcing%20Safety%20at%20Runtime%20for%20Systems%20with%20Disturbances%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](3587ea/53daf3f8/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/84B3C/3587ea/53daf3f8/dubbed.srt) |
| Enforcing Safety at Runtime for Systems with Disturbances - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](3587ea/58998a07/Enforcing%20Safety%20at%20Runtime%20for%20Systems%20with%20Disturbances%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/84B3C/3587ea/58998a07/Enforcing%20Safety%20at%20Runtime%20for%20Systems%20with%20Disturbances%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

This video presentation accompanies "Enforcing Safety at Runtime for Systems with Disturbances," to appear at the 59th IEEE Conference on Decision and Control (CDC), 2020.

---

视频内容版权归原作者所有，字幕仅供学习交流。
