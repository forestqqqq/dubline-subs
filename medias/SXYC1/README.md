<!-- dubline-subs {"title": "Part 6: how to clamp a 3D object model to the Cesium terrain model", "author": "GISWorld", "files": 3, "updated": "2026-11-06"} -->
# Part 6: how to clamp a 3D object model to the Cesium terrain model

<img src="7c86fa/4f4d6e27/Part%206%20how%20to%20clamp%20a%203D%20object%20model%20to%20the%20Cesium%20terrain%20model.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=t7FW3HxQ7EY](https://www.youtube.com/watch?v=t7FW3HxQ7EY) |
| 发布 | 2024-07-12 |
| 时长 | 27 分 18 秒 |
| 语言 | 英语 |
| 原作者 | [GISWorld](https://www.youtube.com/@gisworld-tech)（@gisworld-tech，7140 订阅） |

## 中文信息

**标题**：【中配】27分钟学会用Cesium把3D模型完美锚定到CCM地形上

**原标题译文**：第6部分：如何将3D物体模型固定到Cesium地形模型上

在这期视频中，我们将深入探讨如何在 Cesium 引擎中实现 3D 物体模型与 CCM 地形模型的完美锚定。在进行 3D 地图开发时，一个非常常见且棘手的问题就是当物体（如汽车、飞机等）在复杂的地理环境中移动时，由于地形起伏的变化，模型往往会出现悬浮在空中或陷入地面的情况。这不仅影响视觉效果，更会破坏整个场景的真实感。本视频将手把手教你如何利用 Cesium 提供的核心 API，通过动态获取地形高度数据，确保这些移动模型在任何时刻都能精准地贴合在地面上。

通过本期教程，你将掌握一系列实用的核心知识点。首先，我们将学习如何使用 Cesium.sampleTerrainDetail 函数。这是一个非常关键的异步 API，能够帮助开发者获取特定经纬度坐标在地形模型上的精确高度。掌握了这个函数，你就拿到了解决模型贴合问题的核心钥匙。其次，视频会详细讲解如何利用 Cesium.Cartographic.fromDegrees 将我们常用的经纬度坐标转换为 Cesium 内部所需的弧度坐标系，这是确保坐标转换准确的基础步骤。

在逻辑实现层面，本视频还会展示如何优化物体控制逻辑。我们将演示如何通过引入动态的 height 和 speed 变量来替代原本死板的固定速度乘数。这种做法能够让物体的移动更加灵活，能够根据实际需求动态调整高度和速度。此外，我们还会涉及到实战中的代码组织技巧，例如在 addMovableEntity 函数中，如何通过 viewer.entities.removeAll 优雅地清除旧有的实体，并根据当前状态动态添加新的模型实体。

视频中还会展示高度数据来源的多样性，包括从数据库、静态文件或者 JSON 文件中获取地形高度数据的方法。更重要的是，我们将演示一套通用的 Y 坐标锚定逻辑，并证明这套逻辑具有极高的兼容性，无论是地面行驶的汽车模型还是在空中飞行的飞机模型，都可以共用同一套高度锚定逻辑，极大地提高了代码的复用率和开发效率。

本视频非常适合正在使用 Cesium 进行 3D 地图开发的开发者，特别是那些正在为 3D 模型与复杂地形贴合问题感到头疼的同学。如果你已经具备基础的 JavaScript 编程知识，并且对 Cesium 的基础 API 有一定的了解，那么这期视频的内容将对你的项目开发提供巨大的帮助。

看完这期视频后，你将能够独立完成以下任务：首先，你能熟练掌握异步获取地形高度的技术路径，解决模型悬浮或穿模的痛点；其次，你能编写出支持多种模型实体的动态切换代码，并实现高度与速度的动态控制；最后，你能构建出一套标准化的模型锚定逻辑，将其应用到各种不同类型的移动物体中，让你的 3D 地图场景更加真实、专业。无论你是想优化现有的项目，还是在规划新的 3D 地图应用，这期视频提供的技术方案都将是你的有力支撑。

原视频：Part 6: how to clamp a 3D object model to the Cesium terrain model
原作者：GISWorld
发布日期：2024-07-12
视频链接：https://www.youtube.com/watch?v=t7FW3HxQ7EY

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| Part 6 how to clamp a 3D object model to the Cesium terrain model - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](7c86fa/5b5ff967/Part%206%20how%20to%20clamp%20a%203D%20object%20model%20to%20the%20Cesium%20terrain%20model%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/SXYC1/7c86fa/5b5ff967/Part%206%20how%20to%20clamp%20a%203D%20object%20model%20to%20the%20Cesium%20terrain%20model%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| Part 6 how to clamp a 3D object model to the Cesium terrain model - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](7c86fa/f6139973/Part%206%20how%20to%20clamp%20a%203D%20object%20model%20to%20the%20Cesium%20terrain%20model%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/SXYC1/7c86fa/f6139973/Part%206%20how%20to%20clamp%20a%203D%20object%20model%20to%20the%20Cesium%20terrain%20model%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](7c86fa/fd3b9a60/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/SXYC1/7c86fa/fd3b9a60/dubbed.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

In this video, we will discuss how to clamp a 3D object model to the Cesium terrain model.

---

视频内容版权归原作者所有，字幕仅供学习交流。
