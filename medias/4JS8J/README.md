<!-- dubline-subs {"title": "Cesium Entity: Integrating 2D and 3D Data with REST APIs", "author": "GISWorld", "files": 3, "updated": "2026-11-06"} -->
# Cesium Entity: Integrating 2D and 3D Data with REST APIs

<img src="f0b338/c909a325/Cesium%20Entity%20Integrating%202D%20and%203D%20Data%20with%20REST%20APIs.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=HdBdTTbAkY8](https://www.youtube.com/watch?v=HdBdTTbAkY8) |
| 发布 | 2024-10-22 |
| 时长 | 44 分 38 秒 |
| 语言 | 英语 |
| 原作者 | [GISWorld](https://www.youtube.com/@gisworld-tech)（@gisworld-tech，7140 订阅） |

## 中文信息

**标题**：【中配】44 分钟实战：通过 REST API 将 QGIS 数据动态同步到 Cesium

**原标题译文**：Cesium Entity：通过 REST APIs 集成 2D 和 3D 数据

在这期视频中，我将带大家深入实战，演示如何通过 REST API 将在 QGIS 中编辑的 2D 和 3D 地理空间数据，实现动态同步到 Cesium 场景中。这不仅是一个简单的模型展示，更是一套完整的技术闭环：从后端数据库的数据获取，到前端的几何属性映射，再到复杂的 3D 地形锚定，最后到前端页面的实时更新逻辑。通过这 44 分钟的实战教学，你将掌握从数据源到可视化呈现的全流程技术栈。

在具体的知识点学习上，本视频涵盖了以下核心技术内容：
首先，我们将学习如何利用 Axios 库发起异步请求，从基于 PostgreSQL 数据库构建的 OGC 标准 API 端点获取地理空间数据。这是数据流转的第一步，确保你能正确处理复杂的地理信息请求。
其次，视频详细讲解了如何利用 viewer.entities.add 方法，将 API 返回的各种几何数据、高度信息以及材质属性精准地映射到 Cesium 场景中。
针对 3D 场景中常见的坐标对齐问题，我将演示如何通过 sampleTerrain 函数，将经纬度坐标转换为准确的笛卡尔坐标，从而确保点位实体能够完美地锚定在 Cesium Terrain 地形上，避免模型悬浮或沉入地表。
在资源加载方面，我们将学习如何根据 API 返回的特定属性（例如 usage 字段）动态选择并加载对应的 GLB 模型资源。通过这种方式，你可以根据数据内容自动切换不同的 3D 模型，如树木、汽车等。
此外，视频还会深入讲解数据更新的逻辑处理。我们将通过布尔变量判断当前的同步状态，决定是移除旧有的实体还是直接缩放新实体，从而确保 Web 端的数据与 QGIS 的修改保持高度一致。
最后，为了保证系统的稳定性，我还会演示如何建立完整的错误处理机制，通过 catch 函数捕获并打印 API 请求中的错误信息，帮助你在开发过程中快速定位问题。

这期视频非常适合 Web GIS 开发者、Cesium 工程师，以及任何需要处理 2D/3D 数据同步、追求高精度地理空间可视化技术的 GIS 技术人员观看。如果你正在构建复杂的数字孪生项目，或者在为如何高效同步 QGIS 数据到 Web 端而苦恼，这期视频提供的实战方案将非常有帮助。

在观看视频之前，建议你具备基础的 JavaScript 编程能力，了解 Axios 发送网络请求的基本原理，并且对 Cesium 的基础 API 以及基本的地理空间坐标概念有所了解。

看完这期视频后，你将能够独立完成从数据获取到模型展示的完整链路。你不仅能学会如何通过 REST API 获取地理空间数据，还能掌握如何在 Cesium 中实现复杂的模型映射与地形锚定。更重要的是，你可以将这套成熟的方案作为通用包，集成到你自己的 Web 应用或软件中，快速实现 QGIS 数据到 Web 端实时同步的完整闭环。无论你是想优化现有的数据流转逻辑，还是想在项目中加入动态的 3D 模型加载功能，这期视频提供的实战经验都能为你提供核心的技术支持。

原视频：Cesium Entity: Integrating 2D and 3D Data with REST APIs
原作者：GISWorld
发布日期：2024-10-22
视频链接：https://www.youtube.com/watch?v=HdBdTTbAkY8

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](f0b338/5ad3a73f/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/4JS8J/f0b338/5ad3a73f/dubbed.srt) |
| Cesium Entity Integrating 2D and 3D Data with REST APIs - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](f0b338/8d8659e1/Cesium%20Entity%20Integrating%202D%20and%203D%20Data%20with%20REST%20APIs%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/4JS8J/f0b338/8d8659e1/Cesium%20Entity%20Integrating%202D%20and%203D%20Data%20with%20REST%20APIs%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| Cesium Entity Integrating 2D and 3D Data with REST APIs - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](f0b338/98928a24/Cesium%20Entity%20Integrating%202D%20and%203D%20Data%20with%20REST%20APIs%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/4JS8J/f0b338/98928a24/Cesium%20Entity%20Integrating%202D%20and%203D%20Data%20with%20REST%20APIs%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

In this video, we will discuss:

---

视频内容版权归原作者所有，字幕仅供学习交流。
