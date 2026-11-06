<!-- dubline-subs {"title": "3D Tiles: CityGML Conversion, Styling & Filtering", "author": "GISWorld", "files": 3, "updated": "2026-11-06"} -->
# 3D Tiles: CityGML Conversion, Styling & Filtering

<img src="d1a139/82265e61/3D%20Tiles%20CityGML%20Conversion%2C%20Styling%20%26%20Filtering.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=-d98-qy3FAE](https://www.youtube.com/watch?v=-d98-qy3FAE) |
| 发布 | 2024-08-20 |
| 时长 | 41 分 18 秒 |
| 语言 | 英语 |
| 原作者 | [GISWorld](https://www.youtube.com/@gisworld-tech)（@gisworld-tech，7140 订阅） |

## 中文信息

**标题**：【中配】41分钟实操：把CityGML城市数据转成3D Tiles

**原标题译文**：3D Tiles：CityGML 转换、样式设置与过滤

在这期视频中，我将带大家深入了解如何处理复杂的城市空间数据，并实操演示如何将 CityGML 城市数据高效转换为 3D Tiles 格式。CityGML 作为一种遵循 OGC 标准的 XML 格式，能够非常详尽地描述城市结构的几何信息、拓扑关系以及丰富的属性信息。然而，在实际的 Web 端 3D 地图开发中，直接加载复杂的 CityGML 数据往往面临性能挑战，因此将其转换为更适合流式加载的 3D Tiles 格式是至关重要的第一步。本视频不仅涵盖了从数据转换到模型加载的全流程，更核心的内容在于如何通过编写样式代码和逻辑管理，对生成的 3D Tiles 模型进行精细的属性过滤与视觉样式化处理。

通过本视频的学习，你可以掌握以下具体的知识点：首先是数据处理基础，包括如何利用 Cesium Ion 工具将原始的 CityGML 数据转换为 3D Tiles 格式，为后续的渲染打下基础。其次是核心的样式化逻辑，你会学习如何利用 Cesium3DTilesStyle 条件，根据建筑的高度、屋顶类型等特定属性，为模型赋予不同的颜色或视觉效果。在代码架构方面，我将演示如何引入 TileStyleManager 类来集中管理样式，通过这种重构方式显著提高代码的整洁度与可维护性，避免样式逻辑与业务逻辑耦合。此外，视频还会展示如何引入 chroma-js 库来动态生成颜色列表，从而处理复杂的样式映射需求。最后，你还将学习如何利用 map 函数处理 features 数组，根据索引生成对应的颜色和数值，并结合点击事件监听器（EventListener）实现前端 UI 按钮与 3D 场景样式之间的动态交互切换。

本视频非常适合正在使用 Cesium 进行 3D 地图开发或城市建模的开发者观看。无论你是正在处理大规模城市数据，还是希望在 3D 场景中实现更丰富的交互视觉效果，这期实操教程都能为你提供实用的技术路径。在观看之前，建议你具备基础的 JavaScript 编程知识，并且对 Webpack 配置基础以及基本的 3D Tiles 概念有一定的了解。

看完本视频后，你将能够独立完成从 CityGML 城市数据到 3D Tiles 模型的转换全过程。你不仅能够掌握基础的数据转换流程，还能学会如何编写高质量的样式管理代码，通过属性过滤实现复杂的视觉表现。通过学习视频中的 TileStyleManager 架构和 chroma-js 动态配色方案，你可以在自己的项目中构建出更具交互性、更美观的城市 3D 模型展示界面，并能够通过简单的 UI 交互快速切换不同的数据表现模式。

原视频：3D Tiles: CityGML Conversion, Styling & Filtering
原作者：GISWorld
发布日期：2024-08-20
视频链接：https://www.youtube.com/watch?v=-d98-qy3FAE

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](d1a139/421e7f0d/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/S1GV2/d1a139/421e7f0d/dubbed.srt) |
| 3D Tiles CityGML Conversion, Styling & Filtering - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](d1a139/54f705ee/3D%20Tiles%20CityGML%20Conversion%2C%20Styling%20%26%20Filtering%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/S1GV2/d1a139/54f705ee/3D%20Tiles%20CityGML%20Conversion%2C%20Styling%20%26%20Filtering%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| 3D Tiles CityGML Conversion, Styling & Filtering - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](d1a139/697dd348/3D%20Tiles%20CityGML%20Conversion%2C%20Styling%20%26%20Filtering%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/S1GV2/d1a139/697dd348/3D%20Tiles%20CityGML%20Conversion%2C%20Styling%20%26%20Filtering%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

In this video, we will discuss:

---

视频内容版权归原作者所有，字幕仅供学习交流。
