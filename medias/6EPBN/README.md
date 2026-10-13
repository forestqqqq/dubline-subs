<!-- dubline-subs {"title": "Stanford CME295 Transformers & LLMs | Autumn 2026 | Lecture 1 - Transformers", "author": "Stanford Online", "files": 3, "updated": "2026-10-13"} -->
# Stanford CME295 Transformers & LLMs | Autumn 2026 | Lecture 1 - Transformers

<img src="ff2527/e3fe94a1/Stanford%20CME295%20Transformers%20%26%20LLMs%20Autumn%202026%20Lecture%201%20-%20Transformers.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=114i2Kz-LZA](https://www.youtube.com/watch?v=114i2Kz-LZA) |
| 发布 | 2026-09-28 |
| 时长 | 1 小时 44 分 28 秒 |
| 语言 | 英语 |
| 原作者 | [Stanford Online](https://www.youtube.com/@stanfordonline)（@stanfordonline，约 130 万订阅） |

## 中文信息

**标题**：斯坦福大学LLM课程第一讲：从Word2Vec到Transformer全解析

**原标题译文**：斯坦福 CME295 Transformers & LLMs | 2026秋季 | 第1讲 - Transformers

本期视频带你走进斯坦福大学 Transformer 与大语言模型（LLM）课程的第一讲。这不仅是一次技术的复盘，更是一次从基础到核心架构的系统性演进之旅。课程将带领你回顾人工智能领域关键的技术里程碑，深入剖析从早期的词向量、循环神经网络到现代 Transformer 架构的核心逻辑。通过本节课的学习，你可以建立起清晰的技术脉络，深刻理解当前大模型之所以能够产生强大能力的底层技术支撑。

在这一讲中，你将掌握以下核心知识点：
首先是关于分词技术（Tokenization）的深度对比。我们将探讨词级、字符级以及子词级别（如 BPE算法）的不同实现方式，并重点分析子词级别如何在平衡序列长度与保留语义表达之间取得最优平衡。
接着，课程将剖析 Word2Vec 的局限性。虽然它通过预测上下文获取语义向量，但在处理多义词、忽略词序以及适应新内容方面存在明显短板。随后我们将对比 RNN 与 LSTM，分析它们在处理长距离依赖时的困难以及面临的梯度消失问题，从而理解为什么我们需要更高效的架构。
核心部分将聚焦于注意力机制（Attention）与自注意力（Self-attention）。你将深入学习 Query（查询）、Key（键）和 Value（值）这三个核心概念的逻辑关系：Query用于寻找内容，Key作为匹配依据，而Value提供实际信息。通过计算Q与K的相似度对V进行加权，模型能够建立到过去所有标记的直接连接。
此外，课程还会详细讲解 Transformer 的关键组件，包括利用不同频率的三角函数来注入位置信息的“位置嵌入”，用于解决自注意力机制导致的词序丢失问题；多头注意力（Multi-head Attention）如何并行学习不同特征；以及前馈神经网络在非线性变换中的作用。最后，我们还会讨论 Masking 等核心技巧，确保模型在训练过程中不会获取未来的信息。

本视频非常适合以下人群观看：
如果你是从事人工智能领域的研究人员或个人项目开发者，这门课程将为你提供扎实的底层原理支撑；如果你是希望提升 AI 素养的职场人士，通过系统学习这些基础架构，能帮助你更专业地理解当前大模型技术的逻辑。只要你已经具备了线性代数（矩阵运算）以及基础的机器学习知识（如损失函数、神经网络、嵌入等），本课程的内容将对你极具启发性。

观看完本期视频后，你将能够清晰地解释 Transformer 架构中各个组件的功能，理解从简单词向量到复杂大模型的技术演进逻辑。你不仅能掌握 BPE 等关键算法的原理，还能深刻理解自注意力机制中的数学逻辑与工程技巧。这些知识将帮助你在面对复杂的 AI 模型时，不再仅仅停留在调用接口层面，而是能够从底层架构出发，去思考和分析模型的运作机理。

章节
00:00:00 欢迎
00:03:43 与去年版本的区别
00:05:01 课程安排
00:12:42 时间线
00:16:56 分词
00:37:27 Word2vec (CBOW, Skip-gram)
00:48:26 RNN, LSTM
00:55:18 注意力机制
00:57:16 自注意力机制
00:59:54 Query, key, value
01:09:35 Transformer 架构
01:12:19 输入
01:16:27 Transformer 编码器
01:18:19 Transformer 解码器
01:22:16 计算技巧
01:27:35 端到端示例

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| Stanford CME295 Transformers & LLMs Autumn 2026 Lecture 1 - Transformers - 英语字幕（转写）.en.srt | 原文字幕（转写） | [查看 / 下载](ff2527/0348c60d/Stanford%20CME295%20Transformers%20%26%20LLMs%20Autumn%202026%20Lecture%201%20-%20Transformers%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/6EPBN/ff2527/0348c60d/Stanford%20CME295%20Transformers%20%26%20LLMs%20Autumn%202026%20Lecture%201%20-%20Transformers%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| Stanford CME295 Transformers & LLMs Autumn 2026 Lecture 1 - Transformers - 简体中文字幕（翻译）.zh.srt | 译文字幕 | [查看 / 下载](ff2527/4993923f/Stanford%20CME295%20Transformers%20%26%20LLMs%20Autumn%202026%20Lecture%201%20-%20Transformers%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E5%AD%97%E5%B9%95%EF%BC%88%E7%BF%BB%E8%AF%91%EF%BC%89.zh.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/6EPBN/ff2527/4993923f/Stanford%20CME295%20Transformers%20%26%20LLMs%20Autumn%202026%20Lecture%201%20-%20Transformers%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E5%AD%97%E5%B9%95%EF%BC%88%E7%BF%BB%E8%AF%91%EF%BC%89.zh.srt) |
| Stanford CME295 Transformers & LLMs Autumn 2026 Lecture 1 - Transformers - 中英双语字幕.srt | 双语字幕 | [查看 / 下载](ff2527/d6059766/Stanford%20CME295%20Transformers%20%26%20LLMs%20Autumn%202026%20Lecture%201%20-%20Transformers%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/6EPBN/ff2527/d6059766/Stanford%20CME295%20Transformers%20%26%20LLMs%20Autumn%202026%20Lecture%201%20-%20Transformers%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，时间轴与原视频一致，可直接拖进播放器（PotPlayer、VLC、IINA 等）加载。

## 原视频章节

| 时间 | 章节 |
|---|---|
| 00:00:00 | Welcome |
| 00:03:43 | Difference from last year’s edition |
| 00:05:01 | Class logistics |
| 00:12:42 | Timeline |
| 00:16:56 | Tokenization |
| 00:37:27 | Word2vec (CBOW, Skip-gram) |
| 00:48:26 | RNN, LSTM |
| 00:55:18 | Attention |
| 00:57:16 | Self-attention mechanism |
| 00:59:54 | Query, key, value |
| 01:09:35 | Transformer architecture |
| 01:12:19 | Input |
| 01:16:27 | Transformer Encoder |
| 01:18:19 | Transformer Decoder |
| 01:22:16 | Computational tricks |
| 01:27:35 | End-to-end example |

## 原视频简介

For more information about Stanford’s graduate programs, visit: https://online.stanford.edu/graduate-education

---

视频内容版权归原作者所有，字幕仅供学习交流。
