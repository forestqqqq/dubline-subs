<!-- dubline-subs {"title": "MobiSys 2019 - SpecEye: Towards Pervasive and Privacy-Preserving Screen Exposure Detection in Daily", "author": "ACM SIGMOBILE ONLINE", "files": 3, "updated": "2026-11-23"} -->
# MobiSys 2019 - SpecEye: Towards Pervasive and Privacy-Preserving Screen Exposure Detection in Daily

<img src="d2b53c/aef0dedf/MobiSys%202019%20-%20SpecEye%20Towards%20Pervasive%20and%20Privacy-Preserving%20Screen%20Exposure%20Detection%20in%20Daily.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=z4zGpzIGLUw](https://www.youtube.com/watch?v=z4zGpzIGLUw) |
| 发布 | 2019-08-14 |
| 时长 | 18 分 52 秒 |
| 语言 | 英语 |
| 原作者 | [ACM SIGMOBILE ONLINE](https://www.youtube.com/@acmsigmobileonline4068)（@acmsigmobileonline4068，2330 订阅） |

## 中文信息

**标题**：【中配】成本不到10美元，用光伏效应实现全天候屏幕暴露监测

**原标题译文**：MobiSys 2019 - SpecEye: 迈向日常生活中普遍且保护隐私的屏幕暴露检测

在数字化时代，我们几乎每天都会长时间面对各类电子屏幕，无论是工作中的电脑、社交媒体上的手机，还是娱乐时的电视和游戏机。然而，长期的屏幕暴露往往会带来一系列健康问题，包括视力下降、注意力分散甚至可能诱发注意力缺陷障碍等问题。现有的屏幕时间统计工具大多存在局限性：要么是基于软件层面的统计，无法涵盖所有设备的使用情况；要么是依赖可穿戴摄像头进行视觉识别，这不仅带来了巨大的隐私泄露风险，还对设备的计算能力提出了极高要求。为了解决这些痛点，本期视频将带大家深入了解一种名为 SpecEye 的创新方案。这是一款成本极低、高度保护隐私的可穿戴设备，它摒弃了复杂的图像识别，而是巧妙地利用物理学中的光伏效应来实现全天候的屏幕暴露监测。

通过观看本期视频，你可以系统地掌握以下核心知识点：

首先是核心物理原理。视频将详细讲解什么是光伏效应（Photovoltaic Effect），以及 PN 结在接收光线时如何产生电荷和电流。不同类型的屏幕在发光时具有独特的蓝色波段光谱特征，SpecEye 正是利用这一特征，通过测量传感器产生的电流变化来判断用户是否正在面对屏幕。

其次是极简的硬件架构设计。你会了解到该设备如何通过极低成本的组件实现功能。硬件包含带蓝牙功能的 SOC 微控制器、从 RGB LED 中提取的 PN 结、太阳能电池以及锂电池。整个设备的重量仅为 50 克，尺寸仅为 30x32x8 毫米，且整套硬件成本控制在 10 美元以下。这种设计思路展示了如何在保证功能性的前提下，最大限度地降低硬件门槛并保护用户隐私。

在软件算法层面，视频展示了如何处理传感器获取的原始数据。系统通过对电压和充放电时间的建模，提取出关键的放电信号特征。随后，利用两层级联的 SVM（支持向量机）树状结构进行屏幕特征识别。这种算法模型能够有效地从复杂的环境光中剥离出屏幕特征，确保监测的准确性。

最后，视频还会展示详实的实验验证数据。研究团队在 51 个不同尺寸（从 3.5 英寸到 70 英寸）的显示屏以及 43 个不同的真实生活地点进行了测试，结果显示系统准确率超过 98%。此外，视频还会展示 30 天的纵向研究数据，以及软件如何提供实时光照强度反馈，并自动将屏幕暴露分类为电视、游戏或手机等不同类型。

本期视频非常适合以下人群观看：如果你是计算机视觉研究者，想要寻找非视觉识别类的创新监测方案；如果你是可穿戴设备开发者，对低功耗、低成本的传感器集成感兴趣；或者你是一名健康监测技术爱好者，希望找到更科学的方法来控制屏幕成瘾，甚至如果你是对隐私保护技术感兴趣的研究者，本视频提供的“非图像识别”思路将为你提供极大的启发。

在观看过程中，你只需要具备基础的物理知识（如光伏效应和 PN 结的基本概念）、基本的机器学习概念（如 SVM 算法的基本逻辑）以及基础的硬件开发常识即可轻松上手。看完本期视频后，你将能够理解如何通过跨学科的知识融合，利用物理规律解决复杂的工程问题。你将掌握从硬件传感器选型、物理信号建模到机器学习分类的完整技术链路，并能够理解如何构建一个既高效又尊重用户隐私的健康监测系统。这不仅是一次技术原理的科普，更是一次关于如何用极简设计解决复杂问题的思维碰撞。

原视频：MobiSys 2019 - SpecEye: Towards Pervasive and Privacy-Preserving Screen Exposure Detection in Daily
原作者：ACM SIGMOBILE ONLINE
发布日期：2019-08-14
视频链接：https://www.youtube.com/watch?v=z4zGpzIGLUw

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](2963f9/a9312134/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/Q01S3/2963f9/a9312134/dubbed.srt) |
| MobiSys 2019 - SpecEye Towards Pervasive and Privacy-Preserving Screen Exposure Detection in Daily - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](2963f9/bf7550ea/MobiSys%202019%20-%20SpecEye%20Towards%20Pervasive%20and%20Privacy-Preserving%20Screen%20Exposure%20Detection%20in%20Daily%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/Q01S3/2963f9/bf7550ea/MobiSys%202019%20-%20SpecEye%20Towards%20Pervasive%20and%20Privacy-Preserving%20Screen%20Exposure%20Detection%20in%20Daily%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| MobiSys 2019 - SpecEye Towards Pervasive and Privacy-Preserving Screen Exposure Detection in Daily - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](2963f9/db29634d/MobiSys%202019%20-%20SpecEye%20Towards%20Pervasive%20and%20Privacy-Preserving%20Screen%20Exposure%20Detection%20in%20Daily%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/Q01S3/2963f9/db29634d/MobiSys%202019%20-%20SpecEye%20Towards%20Pervasive%20and%20Privacy-Preserving%20Screen%20Exposure%20Detection%20in%20Daily%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

Presented at MobiSys 2019

---

视频内容版权归原作者所有，字幕仅供学习交流。
