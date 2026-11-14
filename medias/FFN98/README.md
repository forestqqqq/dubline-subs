<!-- dubline-subs {"title": "Talk - All-in-one: Certifiable Optimal Distributed Kalman Filter under Unknown Correlations", "author": "Eduardo Sebastián Rodríguez", "files": 3, "updated": "2026-11-14"} -->
# Talk - All-in-one: Certifiable Optimal Distributed Kalman Filter under Unknown Correlations

<img src="8fb4d5/0bbeeb53/Talk%20-%20All-in-one%20Certifiable%20Optimal%20Distributed%20Kalman%20Filter%20under%20Unknown%20Correlations.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=_c95pvdmsXA](https://www.youtube.com/watch?v=_c95pvdmsXA) |
| 发布 | 2021-11-04 |
| 时长 | 11 分 43 秒 |
| 原作者 | [Eduardo Sebastián Rodríguez](https://www.youtube.com/@eduardosebastianrodriguez531)（@eduardosebastianrodriguez531，4 订阅） |

## 中文信息

**标题**：【中配】11 分钟：用凸松弛 + 秩验证重构未知相关性下的最优滤波

**原标题译文**：Talk - All-in-one: 未知相关性下的可证明最优分布式 Kalman Filter

在现代智能电网、无人机协同控制以及物联网等大规模网络系统中，状态估计是确保系统稳定运行的核心技术。然而，随着网络规模的扩大，传统的集中式滤波器往往面临通信带宽受限和单点故障等局限性，因此采用分布式滤波方案成为了必然选择。但在实际应用中，分布式滤波器面临一个巨大的技术瓶颈：由于每个节点无法获取全网的所有信息，传统的分布式共同滤波器往往难以达到均方误差意义下的最优性。此外，现有的扩散共同滤波器通常陷入两难境地，要么必须预先放弃最优性，要么就面临无法求解的NP hard优化问题。

本期视频将深入解析CodEKF算法，这是针对上述难题提出的创新解决方案。该算法的核心思路在于通过凸松弛与秩验证的认证机制，在传感器相关性未知的复杂环境下，实现可证明的最优分布式卡尔曼滤波估计。视频将带你从基础理论出发，逐步剖析CodEKF如何突破传统分布式滤波器的技术限制。

通过观看本视频，你将掌握以下核心知识点：
首先，你将深入理解状态估计在分布式系统中的挑战。我们将探讨奥法蒂证明的传统分布式共同滤波器无法达到最优性的理论基础，并分析为什么在未知相关性下，传统的估计值融合方法无法保证最优性。
其次，视频将详细拆解CodEKF的算法逻辑。你将学习到如何利用凸松弛求解非凸优化问题，并重点掌握其核心的认证过程：即通过检查松弛解的秩是否为1，以及其迹是否等于误差协方差最小特征值倒数，来判断该解是否成功重构了原始的非凸最优解。
第三，我们将从几何直观的角度解释估计值融合的步骤。视频将介绍如何利用外接Löwner-John椭球这一几何工具，在未知相关性下包围多面体交集，从而实现对融合结果的有效近似。
最后，你将了解到CodEKF算法的优越特性，包括其具备的全局渐近稳定性、完全分布式架构、低通信负担以及无需对角化的便捷性。同时，视频还会展示实验数据，证明在高度噪声和稀疏传感器配置的极端场景下，CodEKF的性能显著优于其他先进分布式滤波器，且在实验中达到了96%和93%的最优性满足概率。

本视频非常适合从事状态估计、滤波算法研究的科研人员与工程师，以及关注分布式系统、智能电网、无人机协同控制等领域的专业人士。如果你具备凸优化和矩阵分析的基础知识，本视频将为你提供极具价值的理论支撑和算法实践参考。

看完本视频后，你将能够清晰掌握CodEKF算法的数学推导过程与几何直观，理解如何在分布式架构下处理非凸优化问题。你将具备在实际工程中应用凸松弛与秩验证策略的能力，能够在面对未知传感器相关性的复杂环境时，构建出具备可证明最优性的分布式滤波系统，从而显著提升在高度噪声环境下的估计精度。

原视频：Talk - All-in-one: Certifiable Optimal Distributed Kalman Filter under Unknown Correlations
原作者：Eduardo Sebastián Rodríguez
发布日期：2021-11-04
视频链接：https://www.youtube.com/watch?v=_c95pvdmsXA

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| Talk - All-in-one Certifiable Optimal Distributed Kalman Filter under Unknown Correlations - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](8fb4d5/244672f4/Talk%20-%20All-in-one%20Certifiable%20Optimal%20Distributed%20Kalman%20Filter%20under%20Unknown%20Correlations%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/FFN98/8fb4d5/244672f4/Talk%20-%20All-in-one%20Certifiable%20Optimal%20Distributed%20Kalman%20Filter%20under%20Unknown%20Correlations%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| Talk - All-in-one Certifiable Optimal Distributed Kalman Filter under Unknown Correlations - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](8fb4d5/8e218ac2/Talk%20-%20All-in-one%20Certifiable%20Optimal%20Distributed%20Kalman%20Filter%20under%20Unknown%20Correlations%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/FFN98/8fb4d5/8e218ac2/Talk%20-%20All-in-one%20Certifiable%20Optimal%20Distributed%20Kalman%20Filter%20under%20Unknown%20Correlations%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](8fb4d5/cccbe4a0/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/FFN98/8fb4d5/cccbe4a0/dubbed.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

This is the talk given at 2021 IEEE Conference on Decision and Control about our work "All-in-one: Certifiable Optimal Distributed Kalman Filter under Unknown Correlations"

---

视频内容版权归原作者所有，字幕仅供学习交流。
