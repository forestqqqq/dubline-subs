<!-- dubline-subs {"title": "How to Get Your Data Ready for AI Agents (Docs, PDFs, Websites)", "author": "Dave Ebbelaar", "files": 3, "updated": "2026-11-23"} -->
# How to Get Your Data Ready for AI Agents (Docs, PDFs, Websites)

<img src="97717d/44f1e15b/How%20to%20Get%20Your%20Data%20Ready%20for%20AI%20Agents%20%28Docs%2C%20PDFs%2C%20Websites%29.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=9lBTS5dM27c](https://www.youtube.com/watch?v=9lBTS5dM27c) |
| 发布 | 2025-02-13 |
| 时长 | 25 分 0 秒 |
| 语言 | 英语 |
| 原作者 | [Dave Ebbelaar](https://www.youtube.com/@daveebbelaar)（@daveebbelaar，约 31 万订阅） |

## 中文信息

**标题**：【中配】25 分钟学会构建 AI 智能体知识系统的数据流水线

**原标题译文**：如何为 AI Agents 准备数据（文档、PDF、网站）

在构建 AI 智能体（AI Agents）的过程中，如何让模型精准获取并理解海量的私有知识是核心挑战之一。很多初学者往往只关注最后的检索环节，却忽略了最关键的前置环节：高质量的数据处理流水线。本期视频将带你深度拆解构建 AI 智能体知识系统的完整工程流程，从多源文档的提取、逻辑分块、向量嵌入，一直到向量数据库的存储与最终的检索应用，全方位展示一套生产级的知识系统是如何搭建出来的。

通过本期视频的学习，你将掌握构建知识系统五个核心步骤的实操方法：提取、解析、分块、嵌入和检索。首先，我们将重点介绍 Docling 工具的使用，它能够将 PDF、PowerPoint、Docx 以及网页等多种格式的文档统一转换为 Docling Document 模型，特别是在处理复杂表格和生成高质量 Markdown 输出方面具有显著优势。接着，视频将演示如何处理网页数据，包括通过解析 sitemap.xml 获取全站 URL，并利用 convertAll 方法进行批量内容提取的技术细节。

在数据处理的核心环节，我们将深入讲解混合分块（Hybrid Chunking）技术。这种技术能够根据文档的逻辑组件进行智能拆分，并同时兼顾嵌入模型的最大输入限制，确保分块内容既符合语义逻辑又符合技术规范。此外，你还将学习如何利用 Pydantic 模型定义结构化数据，确保每一条数据都包含文本内容、向量信息以及文件名、页码等关键元数据。在存储环节，我们将演示如何利用 LanceDB 的 add 函数实现自动化向量嵌入，在插入数据的同时完成向量化处理，极大简化了工程复杂度。最后，视频将展示如何通过设置查询类型和限制返回数量进行精准检索，并利用 Streamlit 框架快速构建出一个交互式聊天应用，实现用户提问后自动检索上下文并流式传输给用户的完整问答系统。

本视频非常适合 AI 工程师、软件开发者，以及任何想要构建生产级 AI 应用的程序员观看。如果你具备基础的 Python 编程能力，并且对 AI 智能体的基本概念有所了解，那么这期视频将为你提供极具价值的工程实践参考。

看完本期视频后，你将能够独立完成从原始数据到可检索知识库的全流程建设。你不仅能学会使用 Docling 处理多格式文档，还能掌握网页数据的自动化抓取技巧，学会如何利用混合分块策略优化数据质量，并能够熟练运用 Pydantic 和 LanceDB 构建结构化的向量数据库。最终，你将具备从零开始搭建一套完整的 RAG（检索增强生成）应用的能力，能够通过 Streamlit 快速原型化你的 AI 智能体项目，让你的 AI 应用拥有更精准、更丰富的知识支撑。

原视频：How to Get Your Data Ready for AI Agents (Docs, PDFs, Websites)
原作者：Dave Ebbelaar
发布日期：2025-02-13
视频链接：https://www.youtube.com/watch?v=9lBTS5dM27c

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| How to Get Your Data Ready for AI Agents (Docs, PDFs, Websites) - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](7d1a4b/04d11823/How%20to%20Get%20Your%20Data%20Ready%20for%20AI%20Agents%20%28Docs%2C%20PDFs%2C%20Websites%29%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/R3D6C/7d1a4b/04d11823/How%20to%20Get%20Your%20Data%20Ready%20for%20AI%20Agents%20%28Docs%2C%20PDFs%2C%20Websites%29%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| How to Get Your Data Ready for AI Agents (Docs, PDFs, Websites) - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](7d1a4b/72409f79/How%20to%20Get%20Your%20Data%20Ready%20for%20AI%20Agents%20%28Docs%2C%20PDFs%2C%20Websites%29%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/R3D6C/7d1a4b/72409f79/How%20to%20Get%20Your%20Data%20Ready%20for%20AI%20Agents%20%28Docs%2C%20PDFs%2C%20Websites%29%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](7d1a4b/83764c2e/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/R3D6C/7d1a4b/83764c2e/dubbed.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频章节

| 时间 | 章节 |
|---|---|
| 0:45 | Building an Extraction Pipeline |
| 2:15 | Document Conversion Basics |
| 6:12 | HTML Extraction Techniques |
| 9:10 | Chunking Data for AI |
| 14:22 | Storing in Vector Databases |
| 19:51 | Searching the Vector Database |
| 22:16 | Creating an Interactive Application |

## 原视频简介

Want to start freelancing? Let me help: https://academy.datalumina.com/freelance
Want to learn real AI Engineering? Go here: https://academy.datalumina.com/accelerator

---

视频内容版权归原作者所有，字幕仅供学习交流。
