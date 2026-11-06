<!-- dubline-subs {"title": "3D Tiles: Point Cloud Filtering", "author": "GISWorld", "files": 3, "updated": "2026-11-06"} -->
# 3D Tiles: Point Cloud Filtering

<img src="340e08/b4baef36/3D%20Tiles%20Point%20Cloud%20Filtering.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=CZSo8lLpy64](https://www.youtube.com/watch?v=CZSo8lLpy64) |
| 发布 | 2024-09-30 |
| 时长 | 32 分 51 秒 |
| 语言 | 英语 |
| 原作者 | [GISWorld](https://www.youtube.com/@gisworld-tech)（@gisworld-tech，7140 订阅） |

## 中文信息

**标题**：【中配】32 分钟实战：在 Cesium 中实现点云数据过滤与样式管理

**原标题译文**：3D Tiles：点云过滤

在这期视频中，我将带大家深入实战，演示如何在 Cesium 引擎中高效处理点云数据。我们将从基础的数据准备开始，一步步完成点云数据的 3D Tiles 转换与可视化，并重点讲解如何构建一套基于分类特征的动态过滤与样式管理系统。为了让大家更直观地看到最终效果，本视频将结合德国 Munsta 城市的 CityGML 建筑模型与点云数据进行融合展示，通过真实的城市场景来验证技术方案的实用性。

通过本期视频的学习，你可以掌握以下核心知识点：
首先是数据集成与基础展示，包括如何通过 Cesium ion (CCM) 上传点云文件并获取相应的 asset IDs，从而将点云数据作为 3D Tiles 在 Cesium 中进行可视化展示。
其次是基础的可见性控制，学习如何利用 tileSetPointCloud.show 属性来精确控制点云数据的显示与隐藏逻辑。
核心技术点在于样式管理与分类过滤。你将学习如何在 StyleManager 中通过特定的分类编号来分配不同的颜色值，例如为树木（编号1）、水体（编号9）以及桥梁（编号13）分别设置对应的视觉样式。
接着是高级过滤逻辑的实现，视频将详细讲解如何使用 showQuery 功能，基于特征分类（feature of classification）来实现点云数据的动态筛选。
最后是前端交互逻辑的闭环，包括如何通过 DOM 事件监听单选按钮的状态，从而动态更新点云的样式和可见性。同时，我还会分享如何编写取消全选逻辑，确保用户在 UI 界面上的操作状态与 3D 模型在场景中的显示状态保持高度一致。

本视频非常适合以下几类观众：
如果你是一名需要处理点云数据的开发者，本视频提供的实战流程将为你提供直接可用的技术参考。
如果你是正在研究 3D Tiles 过滤与样式化技术的 GIS 工程师，视频中关于分类编号映射和 showQuery 的应用将帮助你优化复杂场景下的数据展示效果。
如果你是熟悉基础 JavaScript 且希望学习如何将 UI 交互与 3D 模型状态进行深度绑定的前端开发者，本视频中关于 DOM 事件监听与状态同步的逻辑编写将对你非常有帮助。

看完这期视频后，你将能够独立完成从点云数据上传到 3D Tiles 转换的全流程，并能够在 Cesium 项目中构建出一套完整的点云样式管理系统。你将学会如何通过代码控制不同类型的点云特征，并能够通过简单的 UI 交互让用户自由切换不同分类的数据展示。无论你是想提升现有的 GIS 项目视觉效果，还是在开发复杂的 3D 城市模型，这套实战方案都能为你提供核心的技术支撑。

原视频：3D Tiles: Point Cloud Filtering
原作者：GISWorld
发布日期：2024-09-30
视频链接：https://www.youtube.com/watch?v=CZSo8lLpy64

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| 3D Tiles Point Cloud Filtering - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](340e08/4036e046/3D%20Tiles%20Point%20Cloud%20Filtering%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/BEW55/340e08/4036e046/3D%20Tiles%20Point%20Cloud%20Filtering%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| 3D Tiles Point Cloud Filtering - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](340e08/a4c8397c/3D%20Tiles%20Point%20Cloud%20Filtering%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/BEW55/340e08/a4c8397c/3D%20Tiles%20Point%20Cloud%20Filtering%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](340e08/cedfcc11/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/BEW55/340e08/cedfcc11/dubbed.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

In this video, we will discuss:

---

视频内容版权归原作者所有，字幕仅供学习交流。
