<!-- dubline-subs {"title": "Part 2: 3D Object Duplication in CesiumJS with the help of QGIS & Blender", "author": "GISWorld", "files": 3, "updated": "2026-11-06"} -->
# Part 2: 3D Object Duplication in CesiumJS with the help of QGIS & Blender

<img src="6948d3/386bf654/Part%202%203D%20Object%20Duplication%20in%20CesiumJS%20with%20the%20help%20of%20QGIS%20%26%20Blender.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=Qi7jrckoAtk](https://www.youtube.com/watch?v=Qi7jrckoAtk) |
| 发布 | 2024-03-18 |
| 时长 | 31 分 19 秒 |
| 语言 | 英语 |
| 原作者 | [GISWorld](https://www.youtube.com/@gisworld-tech)（@gisworld-tech，7140 订阅） |

## 中文信息

**标题**：【中配】31分钟学会用QGIS和Blender在CesiumJS批量克隆3D模型

**原标题译文**：第2部分：借助 QGIS 和 Blender 在 CesiumJS 中进行 3D 物体复制

在这期视频中，我将带大家深入了解如何通过整合 QGIS、Blender 以及 CesiumJS 这三大核心工具，构建一套高效的 3D 模型批量克隆与渲染工作流。很多同学在处理大规模 3D 场景时，往往会遇到手动一个个添加模型效率极低、模型尺寸不统一或者代码结构混乱的问题。本视频的核心主旨就是教大家如何通过标准化的流程，从地理信息提取、模型预处理到前端逻辑编写，实现多个 3D 物体在 CesiumJS 场景中的自动化批量渲染。

通过本视频的学习，你可以掌握以下具体的知识点：

首先是项目的基础架构与安全配置。我会演示如何正确配置 CesiumJS 的访问令牌，并强调如何将 Access Token 放入独立的配置文件中，而不是直接硬编码在主程序里，以此确保项目的安全性。

其次是地理数据的提取与处理。我将演示如何在 QGIS 软件中创建点位数据，并掌握如何将其导出为 GeoJSON 格式。重点在于如何从 GeoJSON 的 feature.geometry.coordinates 字段中准确提取出经纬度信息，为后续在 CesiumJS 中定位模型打下基础。

接着是 3D 模型的预处理环节。我会讲解如何使用 Blender 对原始模型进行优化，包括如何调整模型尺寸（例如统一调整为 4x4 米），并最终导出为 CesiumJS 兼容性最好的 GLB 格式。这是确保模型在 Web 端正确显示且比例准确的关键步骤。

核心的编程逻辑部分，我将详细拆解如何在 CesiumJS 中编写模块化的代码。你会学到如何编写 create_model 函数并将其从外部 JS 文件导入，从而提高代码的复用性。同时，我将演示如何使用 forEach 循环遍历坐标数组，动态地在指定的经纬度位置实例化 3D 模型。

此外，视频还会涵盖实战中经常遇到的技术细节，例如如何通过浏览器控制台的报错信息快速定位并修正模型资源路径问题。最后，我还会分享该流程的扩展性应用，包括如何兼容 CityGML 数据，以及如何将这套逻辑应用于桥梁、灯光、建筑等多种不同类型的模型渲染。

本视频非常适合 GIS 开发人员、前端工程师以及对 3D 可视化感兴趣的爱好者观看。如果你具备基础的 JavaScript 编程知识，并且对 3D 模型的基本概念有所了解，就可以跟着我的步骤快速上手。

看完这期视频后，你将能够独立完成从地理数据采集到 3D 场景渲染的全流程。你不仅能学会如何操作 QGIS 导出数据、如何在 Blender 中规范化模型，更重要的是，你将掌握一套模块化的 CesiumJS 开发思路。通过这套流程，你可以轻松实现成百上千个 3D 物体在网页上的批量渲染，显著提升你的项目开发效率，并能够应对更复杂的城市建模或景观可视化需求。

原视频：Part 2: 3D Object Duplication in CesiumJS with the help of QGIS & Blender
原作者：GISWorld
发布日期：2024-03-18
视频链接：https://www.youtube.com/watch?v=Qi7jrckoAtk

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| Part 2 3D Object Duplication in CesiumJS with the help of QGIS & Blender - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](6948d3/41750a91/Part%202%203D%20Object%20Duplication%20in%20CesiumJS%20with%20the%20help%20of%20QGIS%20%26%20Blender%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/7QJJF/6948d3/41750a91/Part%202%203D%20Object%20Duplication%20in%20CesiumJS%20with%20the%20help%20of%20QGIS%20%26%20Blender%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](6948d3/697e63d9/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/7QJJF/6948d3/697e63d9/dubbed.srt) |
| Part 2 3D Object Duplication in CesiumJS with the help of QGIS & Blender - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](6948d3/887898a1/Part%202%203D%20Object%20Duplication%20in%20CesiumJS%20with%20the%20help%20of%20QGIS%20%26%20Blender%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/7QJJF/6948d3/887898a1/Part%202%203D%20Object%20Duplication%20in%20CesiumJS%20with%20the%20help%20of%20QGIS%20%26%20Blender%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

In this video, we will discuss duplicating single 3D obj in CesiumJS
using QGIS & Blender.

---

视频内容版权归原作者所有，字幕仅供学习交流。
