<!-- dubline-subs {"title": "Part 5.1: Air Transport App: Visualize 3D Object Movement Over Time", "author": "GISWorld", "files": 3, "updated": "2026-11-06"} -->
# Part 5.1: Air Transport App: Visualize 3D Object Movement Over Time

<img src="4cdc7a/1da8de9f/Part%205.1%20Air%20Transport%20App%20Visualize%203D%20Object%20Movement%20Over%20Time.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=B1zpIloplGQ](https://www.youtube.com/watch?v=B1zpIloplGQ) |
| 发布 | 2024-06-16 |
| 时长 | 40 分 25 秒 |
| 语言 | 英语 |
| 原作者 | [GISWorld](https://www.youtube.com/@gisworld-tech)（@gisworld-tech，7140 订阅） |

## 中文信息

**标题**：【中配】40分钟实战，用QGIS和Cesium实现飞机动态轨迹可视化

**原标题译文**：第 5.1 部分：Air Transport App：可视化 3D 物体随时间的变化运动

在这期视频中，我将带大家完整走一遍如何利用 QGIS 处理地理数据、Blender 编辑 3D 模型，并结合 Cesium.js 实现 3D 物体（飞机）随时间在特定路径上动态移动的可视化效果。这不仅仅是一个简单的模型展示，更是一套涵盖了从底层数据准备、3D 模型预处理到前端代码逻辑实现的全流程实战教学。无论你是想提升 GIS 可视化能力的开发者，还是对 3D 动画感兴趣的爱好者，这期视频都能为你提供非常有价值的实操参考。

通过本期视频的学习，你将掌握以下核心知识点：

首先是关于地理数据的预处理。你将学习如何使用 QGIS 软件中的点对齐几何功能来生成精确的路径点。同时，我还会演示如何利用字段计算器根据距离和角度计算出高度数据，确保生成的路径在三维空间中具有准确的起伏变化。这些步骤是确保后续可视化效果真实准确的基础。

其次是关于 3D 模型的设计与准备。视频中包含了如何使用 Blender 软件对飞机模型进行基础编辑，包括对模型的旋转、镜像以及尺寸调整。最后，你会学到如何将这些模型导出为标准的 glTF 或 GLB 格式，以便顺利接入到 Cesium.js 引擎中。

在核心的代码实现环节，我将详细讲解如何构建 MovingObject 类。这个类的核心逻辑是将物体的位置属性与时间属性建立关联。我会演示如何通过计算总秒数，并建立时间到位置的映射函数，从而驱动飞机模型在路径上平滑移动。此外，为了提升程序性能，我还会分享如何优化数据遍历逻辑，放弃复杂的循环，直接遍历 flightData.features 数组来获取坐标与高度。

最后，视频还会涵盖一些非常关键的工程细节。比如，我将带你识别并解决 UTM 坐标系与 WGS84 地理坐标系导致的显示偏差问题，这是很多初学者容易忽略但又非常影响视觉效果的坑。同时，我还会演示如何通过异步获取 CCM 数据并将 URI 赋值给实体，实现在路径上动态添加可移动模型，并分享如何通过调整相机视角和关闭缩放效果来优化动画的平滑度。

本视频非常适合以下几类人群观看：

如果你是一名开发者，并且正在寻找如何使用 Cesium.js 实现 3D 物体动态轨迹可视化的方案，那么这期视频将为你提供完整的逻辑框架和代码思路。如果你具备基础的 JavaScript 编程能力，并且想要深入了解如何处理复杂的地理空间数据与时间轴的关联逻辑，这期视频的内容将非常契合你的需求。

同时，如果你是一名 GIS 爱好者，已经熟悉 QGIS 的基础操作，但不知道如何将处理好的数据转化为酷炫的 3D 动画效果，那么本视频将教你如何打通 QGIS、Blender 与 Cesium.js 之间的工作流。

看完这期视频后，你将能够独立完成从原始地理数据到动态 3D 可视化的全流程。你不仅能够掌握在 QGIS 中生成路径点和计算高度的技巧，还能学会如何处理 3D 模型并将其转化为可用的可视化资源。更重要的是，你将掌握核心的编程逻辑，能够编写出能够驱动物体在特定路径上随时间移动的代码，并学会处理坐标系偏差等实际开发中的常见问题。通过这 40 分钟的实战教学，你将具备构建高质量、高动态地理空间可视化作品的能力。

原视频：Part 5.1: Air Transport App: Visualize 3D Object Movement Over Time
原作者：GISWorld
发布日期：2024-06-16
视频链接：https://www.youtube.com/watch?v=B1zpIloplGQ

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](4cdc7a/14d0cbc2/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/MBGKA/4cdc7a/14d0cbc2/dubbed.srt) |
| Part 5.1 Air Transport App Visualize 3D Object Movement Over Time - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](4cdc7a/91e93429/Part%205.1%20Air%20Transport%20App%20Visualize%203D%20Object%20Movement%20Over%20Time%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/MBGKA/4cdc7a/91e93429/Part%205.1%20Air%20Transport%20App%20Visualize%203D%20Object%20Movement%20Over%20Time%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| Part 5.1 Air Transport App Visualize 3D Object Movement Over Time - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](4cdc7a/994db9fa/Part%205.1%20Air%20Transport%20App%20Visualize%203D%20Object%20Movement%20Over%20Time%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/MBGKA/4cdc7a/994db9fa/Part%205.1%20Air%20Transport%20App%20Visualize%203D%20Object%20Movement%20Over%20Time%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

In this video, we will discuss the Air Transport App: Visualizing 3D object movement over time.

---

视频内容版权归原作者所有，字幕仅供学习交流。
