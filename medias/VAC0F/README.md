<!-- dubline-subs {"title": "NSDI '26 - Managing Congestion Control Heterogeneity on the Internet with Approximate Performance...", "author": "USENIX", "files": 3, "updated": "2026-11-20"} -->
# NSDI '26 - Managing Congestion Control Heterogeneity on the Internet with Approximate Performance...

<img src="c9084d/d3391759/NSDI%20%2726%20-%20Managing%20Congestion%20Control%20Heterogeneity%20on%20the%20Internet%20with%20Approximate%20Performance.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=41NN8Wlckos](https://www.youtube.com/watch?v=41NN8Wlckos) |
| 发布 | 2026-06-01 |
| 时长 | 15 分 50 秒 |
| 语言 | 英语 |
| 原作者 | [USENIX](https://www.youtube.com/@UsenixOrg)（@UsenixOrg，约 4 万订阅） |

## 中文信息

**标题**：【中配】1个BBR流能拿走16个Cubic流的40%带宽？揭秘互联网不公平的真相

**原标题译文**：NSDI 26 - 通过近似性能管理互联网上的拥塞控制异构性...

在当今复杂的互联网环境中，不同类型的网络流量往往运行在不同的拥塞控制算法之上。然而，正是这种算法的多样性，导致了网络中普遍存在的“不公平”现象。本期视频将带大家深入揭秘互联网底层网络中，不同算法如何相互竞争，以及为什么有时候一个BBR流竟然能拿走多达16个Cubic流的40%带宽。我们将通过技术视角剖析这一现象背后的核心逻辑，并介绍学术界和工业界最新的解决方案。

通过本期视频的学习，你将掌握以下核心知识点：

首先，我们将深入探讨互联网拥塞控制算法（CCA）的异构性问题。目前网络中广泛存在Cubic、BBR以及Vegas等多种算法，它们分别对应不同的应用场景，如视频流传输或静态资产加载。由于这些算法在追求吞吐量与延迟权衡（Throughput-Delay Trade-off）时采取了不同的策略，导致它们在共享链路时会产生严重的竞争不公。

其次，视频将阐述从单纯追求带宽公平性到追求性能隔离的核心逻辑转变。传统的公平调度往往难以兼顾不同算法的特殊需求，而性能隔离的目标是让每一个流，无论它使用哪种算法，都能在不受竞争对手干扰的情况下，实现其所需的理想权衡点。

接着，我们将详细介绍视频的核心技术点：基于近似性能隔离理念的新型多队列AQM算法Santa。你将了解到Santa的核心思路是如何通过聚类思想来减少干扰的。它不需要为每一个流都分配独立的队列，而是将追求相似权衡需求的流归类到相同的队列中。

此外，视频还会展示Santa算法的具体实现细节。包括它如何通过推断流的特征，并利用动态洗牌机制来优化队列分配。系统会观察新流在队列中的缓冲区占用和带宽消耗，识别出激进的流和温顺的流，并定期将其重新分配到合适的队列中。同时，视频还会介绍Santa如何在P4可编程交换机上进行部署，利用驻留时间作为带宽消耗的代理，在数据平面执行队列分配，并在控制平面执行洗牌决策。

最后，我们将通过实验数据来验证算法的有效性。视频将展示Santa在不同算法组合下的性能表现，并提供关于队列数量与隔离效果之间的连续体分析。你会看到Santa的性能如何处于FIFO（无隔离）与FQ（完美隔离）之间，并理解随着队列数量增加，隔离效果如何逐渐接近FQ。

本期视频非常适合网络工程、计算机网络研究领域的学生或从业者观看。如果你是对拥塞控制算法（CCA）、主动队列管理（AQM）或网络公平性感兴趣的开发者，或者需要了解P4可编程交换机在网络流量管理中实际应用场景的工程师，本期内容将为你提供极具价值的深度技术参考。

看完本期视频后，你将能够清晰地理解互联网流量竞争中的不公平真相，掌握从算法异构性到性能隔离的技术演进逻辑。你将学会如何分析不同算法在网络中的行为特征，并深入理解Santa算法如何通过聚类和动态洗牌机制解决复杂网络环境下的公平性难题。通过学习，你将具备从学术理论到P4可编程交换机实践层面的综合知识，能够更专业地评估和优化网络流量管理策略。

原视频：NSDI '26 - Managing Congestion Control Heterogeneity on the Internet with Approximate Performance...
原作者：USENIX
发布日期：2026-06-01
视频链接：https://www.youtube.com/watch?v=41NN8Wlckos

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](c9084d/19f307c8/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/VAC0F/c9084d/19f307c8/dubbed.srt) |
| NSDI '26 - Managing Congestion Control Heterogeneity on the Internet with Approximate Performance - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](c9084d/29b37373/NSDI%20%2726%20-%20Managing%20Congestion%20Control%20Heterogeneity%20on%20the%20Internet%20with%20Approximate%20Performance%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/VAC0F/c9084d/29b37373/NSDI%20%2726%20-%20Managing%20Congestion%20Control%20Heterogeneity%20on%20the%20Internet%20with%20Approximate%20Performance%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| NSDI '26 - Managing Congestion Control Heterogeneity on the Internet with Approximate Performance - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](c9084d/ce5cf3e3/NSDI%20%2726%20-%20Managing%20Congestion%20Control%20Heterogeneity%20on%20the%20Internet%20with%20Approximate%20Performance%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/VAC0F/c9084d/ce5cf3e3/NSDI%20%2726%20-%20Managing%20Congestion%20Control%20Heterogeneity%20on%20the%20Internet%20with%20Approximate%20Performance%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

Managing Congestion Control Heterogeneity on the Internet with Approximate Performance Isolation

---

视频内容版权归原作者所有，字幕仅供学习交流。
