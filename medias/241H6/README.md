<!-- dubline-subs {"title": "2-Langchain Series-Building Chatbot Using Paid And Open Source LLM's using Langchain And Ollama", "author": "Krish Naik", "files": 3, "updated": "2026-11-13"} -->
# 2-Langchain Series-Building Chatbot Using Paid And Open Source LLM's using Langchain And Ollama

<img src="6349da/93d310a7/2-Langchain%20Series-Building%20Chatbot%20Using%20Paid%20And%20Open%20Source%20LLM%27s%20using%20Langchain%20And%20Ollama.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=5CJA1Hbutqc](https://www.youtube.com/watch?v=5CJA1Hbutqc) |
| 发布 | 2024-04-01 |
| 时长 | 27 分 0 秒 |
| 语言 | 英语 |
| 原作者 | [Krish Naik](https://www.youtube.com/@krishnaik06)（@krishnaik06，约 153 万订阅） |

## 中文信息

**标题**：【中配】一套代码，OpenAI 和 Ollama 本地模型无缝切换

**原标题译文**：2-Langchain 系列-使用 Langchain 和 Ollama 构建基于付费和开源 LLM 的聊天机器人

本期视频的核心内容是带大家实操如何利用 Langchain 框架，在同一套代码逻辑下实现 OpenAI 付费模型与 Ollama 本地开源模型的无缝切换。很多开发者在构建 AI 应用时，往往会面临选择难题：是追求 OpenAI 强大的推理能力，还是为了数据隐私和成本考虑使用本地部署的开源模型？本视频通过一个完整的项目演示，展示了如何通过简单的配置调整，让你的应用程序能够灵活地在两种模式之间自由切换。此外，我们还会结合 Streamlit 框架快速搭建出一个交互式的聊天机器人界面，并引入 LangSmith 系统来实时监控每一条请求的成本和详细轨迹。

通过观看本期视频，你可以掌握以下具体的知识点：

首先是基础的开发环境搭建与依赖管理。我们将学习如何使用 Python 虚拟环境来隔离项目依赖，确保开发环境的整洁。你会学到如何通过 pip install -r requirements.txt 命令快速安装 Langchain_community 等核心模块，并学会如何处理常见的环境报错。

其次是核心框架的配置与链式结构构建。视频将详细讲解如何通过环境变量来配置 OpenAI API Key 以及 LangSmith 的项目名称，这是实现自动化追踪和成本监控的关键步骤。在代码层面，我们将深入剖析 Langchain 的核心逻辑，学习如何利用 ChatPromptTemplate 定义提示词模板，配合 ChatOpenAI 或本地模型实例，并使用 StringOutputParser 来解析最终的输出内容，从而构建出通用的链式结构。

接着是本地模型的部署与集成。我们将演示如何安装并运行 Ollama 服务，通过命令行指令 ollama run 快速下载并运行 Llama 2、Gemma、Code Llama 或 Mistral 等多种主流开源模型。你会看到如何将代码中的 chat_openai 调用替换为 Ollama 接口，并实测不同架构模型在相同提示词下的响应能力差异。

最后是前端界面开发与监控分析。我们将使用 Streamlit 框架快速将后端逻辑转化为可视化的聊天界面，通过运行 streamlit run local_llama.py 启动应用。同时，视频还会展示如何利用 LangSmith 进行全方位的代码追踪，包括查看请求日志、分析 Token 消耗情况以及监控每一笔请求的成本支出。

本视频非常适合以下人群观看：

如果你是一名具备基础 Python 基础的开发者，正处于从零开始构建大语言模型应用的初期阶段，这期视频将为你提供非常实用的工程实践经验。特别是如果你在纠结该选付费 API 还是本地模型，或者你想学习如何优雅地兼容两种方案，本视频提供的架构思路将非常有帮助。此外，对于对 Langchain 框架感兴趣、想要快速上手 Streamlit 制作 Demo 界面，或者对 Ollama 本地部署模型有技术探索欲望的技术人员来说，这期视频提供的全流程演示将是极佳的学习素材。

看完这期视频后，你将能够独立完成以下操作：

首先，你能熟练掌握在 Python 环境中配置和管理 AI 项目的依赖，确保开发流程标准化。其次，你能独立编写出基于 Langchain 框架的通用对话链，能够根据需求灵活切换不同的模型后端，无论是调用 OpenAI 的 GPT-3.5-Turbo 还是调用本地运行的 Gemma 模型。

原视频：2-Langchain Series-Building Chatbot Using Paid And Open Source LLM's using Langchain And Ollama
原作者：Krish Naik
发布日期：2024-04-01
视频链接：https://www.youtube.com/watch?v=5CJA1Hbutqc

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| 2-Langchain Series-Building Chatbot Using Paid And Open Source LLM's using Langchain And Ollama - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](6349da/08227074/2-Langchain%20Series-Building%20Chatbot%20Using%20Paid%20And%20Open%20Source%20LLM%27s%20using%20Langchain%20And%20Ollama%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/241H6/6349da/08227074/2-Langchain%20Series-Building%20Chatbot%20Using%20Paid%20And%20Open%20Source%20LLM%27s%20using%20Langchain%20And%20Ollama%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](6349da/5de7a48a/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/241H6/6349da/5de7a48a/dubbed.srt) |
| 2-Langchain Series-Building Chatbot Using Paid And Open Source LLM's using Langchain And Ollama - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](6349da/6f39a8e7/2-Langchain%20Series-Building%20Chatbot%20Using%20Paid%20And%20Open%20Source%20LLM%27s%20using%20Langchain%20And%20Ollama%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/241H6/6349da/6f39a8e7/2-Langchain%20Series-Building%20Chatbot%20Using%20Paid%20And%20Open%20Source%20LLM%27s%20using%20Langchain%20And%20Ollama%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

Welcome to the Langchain tutorials, in this video we will be building langchain chatbot projects with the help of AOpen AI and open ource llms models ussing ollama
github code: https://github.com/krishnaik06/Updated-Langchain
---------------------------------------------------------------------------------------------
Support me by joining membership so that I can upload these kind of videos
https://www.youtube.com/channel/UCNU_lfiiWBdtULKOw6X0Dig/join
-----------------------------------------------------------------------------------
►LLM Fine Tuning Playlist: https://www.youtube.com/watch?v=Vg3dS-NLUT4&list=PLZoTAELRMXVN9VbAx5I2VvloTtYmlApe3
►AWS Bedrock Playlist: https://www.youtube.com/watch?v=2maPaQutcWs&list=PLZoTAELRMXVP8-wzKPtrRST3jNCprvMZj
►Llamindex Playlist: https://www.youtube.…

---

视频内容版权归原作者所有，字幕仅供学习交流。
