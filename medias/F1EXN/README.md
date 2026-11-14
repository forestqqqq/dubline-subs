<!-- dubline-subs {"title": "Hybrid Search RAG With Langchain And Pinecone Vector DB", "author": "Krish Naik", "files": 3, "updated": "2026-11-13"} -->
# Hybrid Search RAG With Langchain And Pinecone Vector DB

<img src="4f6d30/05488eda/Hybrid%20Search%20RAG%20With%20Langchain%20And%20Pinecone%20Vector%20DB.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=CK0ExcCWDP4](https://www.youtube.com/watch?v=CK0ExcCWDP4) |
| 发布 | 2024-07-16 |
| 时长 | 42 分 35 秒 |
| 语言 | 英语 |
| 原作者 | [Krish Naik](https://www.youtube.com/@krishnaik06)（@krishnaik06，约 153 万订阅） |

## 中文信息

**标题**：【中配】42 分钟：用 Langchain+Pinecone 搞懂混合搜索原理

**原标题译文**：使用 Langchain 和 Pinecone 向量数据库实现混合搜索 RAG

这期视频将带你深入探索大模型应用开发中至关重要的检索技术。我们将聚焦于如何利用 Langchain 框架和 Pinecone 向量数据库构建一套高效的混合搜索系统。在构建检索增强生成（RAG）应用的过程中，单纯依赖语义向量搜索往往难以处理某些精确的关键词匹配，而传统的关键词搜索又缺乏对上下文语义的理解。本视频的核心目标就是演示如何通过结合稠密向量语义搜索与稀疏关键词搜索，并应用倒数排名融合（RRF）算法，来显著提升检索系统的准确性与召回率。

通过本视频的学习，你将掌握以下核心知识点：

首先，你将深入理解混合搜索的基本原理。我们将对比两种核心搜索机制的差异：稠密向量搜索利用 NLP 技术将文本转化为高维向量，用于捕捉语义上的相似度；而稀疏向量搜索则利用 TFIDF、词袋模型等技术将文本转化为矩阵，用于实现精准的关键词匹配。

其次，我们将详细讲解倒数排名融合（RRF）算法。这是合并两组不同排序结果的核心理论，我们将学习其计算公式，即通过 1/(k + rank1) 和 1/(k + rank2) 的加权和来平衡不同维度的检索结果。同时，你还将学会如何通过调整关键词搜索与语义搜索的权重比例，例如 70% 对 30% 的比例分配，来针对不同业务场景优化最终的排名顺序。

在实操层面，本视频将手把手带你完成项目的搭建。你将学习如何配置 Pinecone 索引以支持点积度量标准，从而实现同时处理稀疏值与稠密向量的检索。我们将演示如何调用 Hugging Face 的 sentence-transformers/all-MiniLM-L6-v2 模型来生成 384 维的稠密向量，并配合 BM25 编码器来处理文本生成稀疏矩阵。此外，我们还会利用 Langchain 提供的现成 Pinecone Hybrid Search 检索器类，大幅简化复杂的混合查询任务代码。

最后，我们将通过真实的旅行记录数据进行实测验证。视频将展示系统在面对不同类型的查询时，例如关于特定年份或地点的复杂提问时，如何通过混合搜索提供更全面的召回能力。此外，视频还会简要提及图知识搜索的概念，说明 Neo4j 等数据库在整合结构化信息、关键词及语义搜索方面的潜力。

本视频非常适合以下人群观看：如果你是正在构建 RAG 应用的技术人员或开发者，希望解决检索精度不足的痛点，这期内容将为你提供实战级的技术支持。如果你是 AI 领域的学习者，希望从底层原理到代码实现全面掌握混合搜索的细节，本视频也能为你提供清晰的知识框架。此外，如果你已经熟悉 Python 基础和 Langchain 的基本操作，但需要掌握更高级的检索策略来优化你的 AI 项目，那么这期视频将是你的进阶必修课。

看完本视频后，你将能够独立完成从原理理解到代码实现的完整流程。你不仅能清晰解释混合搜索背后的数学逻辑和技术原理，还能熟练操作 Pinecone 和 Langchain 相关的 API，在自己的项目中配置出支持双度量标准的索引，并能够根据实际需求灵活调整 RRF 权重。通过掌握这些核心技术，你将能够构建出比单一向量检索更强大、更精准的检索系统，显著提升 AI 应用在处理复杂查询时的表现。

原视频：Hybrid Search RAG With Langchain And Pinecone Vector DB
原作者：Krish Naik
发布日期：2024-07-16
视频链接：https://www.youtube.com/watch?v=CK0ExcCWDP4

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| Hybrid Search RAG With Langchain And Pinecone Vector DB - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](4f6d30/78793860/Hybrid%20Search%20RAG%20With%20Langchain%20And%20Pinecone%20Vector%20DB%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/F1EXN/4f6d30/78793860/Hybrid%20Search%20RAG%20With%20Langchain%20And%20Pinecone%20Vector%20DB%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](4f6d30/b47b577e/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/F1EXN/4f6d30/b47b577e/dubbed.srt) |
| Hybrid Search RAG With Langchain And Pinecone Vector DB - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](4f6d30/e4db5925/Hybrid%20Search%20RAG%20With%20Langchain%20And%20Pinecone%20Vector%20DB%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/F1EXN/4f6d30/e4db5925/Hybrid%20Search%20RAG%20With%20Langchain%20And%20Pinecone%20Vector%20DB%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

Hybrid search typically refers to a search approach that combines multiple search methodologies or technologies to provide more comprehensive and accurate results. In the context of information retrieval, hybrid search often involves blending traditional keyword-based searching with more advanced techniques such as natural language processing (NLP), semantic search, and machine learning.

---

视频内容版权归原作者所有，字幕仅供学习交流。
