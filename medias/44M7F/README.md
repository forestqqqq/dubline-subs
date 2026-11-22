<!-- dubline-subs {"title": "MLFlow Crash Course: MLOps in Python", "author": "NeuralNine", "files": 3, "updated": "2026-11-21"} -->
# MLFlow Crash Course: MLOps in Python

<img src="3547f9/fec253cf/MLFlow%20Crash%20Course%20MLOps%20in%20Python.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=4FgAKzM_uYM](https://www.youtube.com/watch?v=4FgAKzM_uYM) |
| 发布 | 2026-05-25 |
| 时长 | 42 分 9 秒 |
| 语言 | 英语 |
| 原作者 | [NeuralNine](https://www.youtube.com/@NeuralNine)（@NeuralNine，约 49 万订阅） |

## 中文信息

**标题**：【中配】本地部署 MLflow 一键开启 OpenAI、LangChain 及 PyTorch 追踪

**原标题译文**：MLFlow 速成课程：Python 中的 MLOps

这期视频将带你深入了解开源 MLOps 平台 MLflow 的核心功能。通过实战演示，我们将全面展示如何构建一个本地化的工程平台，实现从生成式 AI 到经典机器学习的全流程统一追踪、评估与版本管理。无论你是正在开发大模型应用，还是在处理传统的深度学习模型，本视频都能为你提供一套完整的工程化实践方案。

在视频中，你将学到以下具体知识点：

首先是基础环境的搭建与配置。我们将演示如何使用 UV 包管理器初始化环境，配置 .env 密钥文件，并成功启动运行在 5000 端口的 MLflow 后端服务。

其次是生成式 AI 的工程化能力。通过调用 mlflow.openai.autolog()、mlflow.langchain.autolog() 以及 mlflow.mistral.autolog() 等函数，你可以一键开启对 OpenAI、LangChain 和 Mistral 等模型的自动追踪，实时查看包括 P99 延迟在内的关键指标。

在模型评估方面，视频展示了如何利用 scorer 装饰器配合 gen_ai.evaluate 函数，将正确性指标与语言风格、简洁性等业务规则相结合，实现对智能体输出的多维度评分。

关于提示词管理，我们将演示如何使用双花括号语法定义变量并创建版本，支持提示词模板的对比与差异视图管理。同时，视频还会讲解如何配置 AI 网关来实现在多模型之间的负载均衡与故障转移，显著提升系统的可用性。

在服务部署上，你将看到如何利用 invoke 装饰器将智能体逻辑封装为异步 FastAPI 端点，并结合 Git 版本追踪来启动服务。

针对经典机器学习，视频演示了如何利用 sklearn.autolog 自动记录 Iris 数据集训练过程中的指标、参数及模型制品。同时，我们将展示如何结合 Optuna 库与 MLflow 的日志可视化功能，高效筛选超参数组合并实现最佳模型的自动化注册。

最后是深度学习的监控与优化。视频将演示如何开启 PyTorch 的系统级资源监控，实时追踪 CPU、GPU、内存占用情况，并独立记录损失函数和准确率曲线。此外，我们还会讲解检查点保存机制，帮助开发者识别过拟合现象，并支持在训练中断后快速恢复。

本视频非常适合以下人群观看：

如果你已经掌握了 Python 编程基础，并且具备 LangChain 或 PyTorch 的基础使用经验，那么这期视频将帮助你从单纯的写代码转向真正的工程化落地。

如果你是一名机器学习工程师，正在构建生成式 AI 应用，并且面临模型调试困难、监控缺失或提示词管理混乱的问题，本视频提供的自动化追踪和评估工具将极大提升你的开发效率。

如果你是负责团队项目的工程师，希望将现有的经典机器学习或深度学习项目纳入规范的工程化流程，实现模型版本管理和超参数调优的标准化，本视频提供的全流程演示将为你提供清晰的参考路径。

章节
0:00 Intro
1:07 Environment Setup
6:11 Tracing
11:45 Evaluation
18:20 Prompt Templates
22:20 AI Gateways
25:42 Agent Servers
29:30 Scikit-Learn MLOps
33:20 Hyperparameter Tuning
37:17 PyTorch MLOps
41:20 Outro

原视频：MLFlow Crash Course: MLOps in Python
原作者：NeuralNine
发布日期：2026-05-25
视频链接：https://www.youtube.com/watch?v=4FgAKzM_uYM

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| MLFlow Crash Course MLOps in Python - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](58cfde/4a150bca/MLFlow%20Crash%20Course%20MLOps%20in%20Python%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/44M7F/58cfde/4a150bca/MLFlow%20Crash%20Course%20MLOps%20in%20Python%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| MLFlow Crash Course MLOps in Python - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](58cfde/ba6c7033/MLFlow%20Crash%20Course%20MLOps%20in%20Python%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/44M7F/58cfde/ba6c7033/MLFlow%20Crash%20Course%20MLOps%20in%20Python%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](58cfde/f106e698/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/44M7F/58cfde/f106e698/dubbed.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频章节

| 时间 | 章节 |
|---|---|
| 0:00 | Intro |
| 1:07 | Environment Setup |
| 6:11 | Tracing |
| 11:45 | Evaluation |
| 18:20 | Prompt Templates |
| 22:20 | AI Gateways |
| 25:42 | Agent Servers |
| 29:30 | Scikit-Learn MLOps |
| 33:20 | Hyperparameter Tuning |
| 37:17 | PyTorch MLOps |
| 41:20 | Outro |

## 原视频简介

💻️ Need some help with a project or some consulting? Contact me here: https://www.neuralnine.com/services

---

视频内容版权归原作者所有，字幕仅供学习交流。
