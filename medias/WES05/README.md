<!-- dubline-subs {"title": "From Vibes to Production: Evaluating and Shipping AI Agents That Work 101 — Laurie Voss, Arize AI", "author": "AI Engineer", "files": 3, "updated": "2026-10-19"} -->
# From Vibes to Production: Evaluating and Shipping AI Agents That Work 101 — Laurie Voss, Arize AI

<img src="c0c2d4/5fff10aa/From%20Vibes%20to%20Production%20Evaluating%20and%20Shipping%20AI%20Agents%20That%20Work%20101%20%E2%80%94%20Laurie%20Voss%2C%20Arize%20AI.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=qZj7sqmidqA](https://www.youtube.com/watch?v=qZj7sqmidqA) |
| 发布 | 2026-10-05 |
| 时长 | 1 小时 51 分 26 秒 |
| 语言 | 英语 |
| 原作者 | [AI Engineer](https://www.youtube.com/@aiDotEngineer)（@aiDotEngineer，约 76 万订阅） |

## 中文信息

**标题**：从感性到数据：用 1 小时实战拆解 AI Agent 的生产级评估体系

**原标题译文**：从氛围到生产：评估并交付可用的 AI Agents 入门教程 —— Laurie Voss, Arize AI

很多开发者在构建 AI Agent 时，往往容易陷入一种“感觉”驱动的开发陷阱：即通过不断手动调整提示词，直到看到几次正确的输出就认为产品可以上线。然而，这种基于感性的调试模式在面对复杂的生产环境时，往往会导致系统不可预测、难以维护且难以进行大规模迭代。本期视频将带你彻底告别“凭感觉”的盲目摸索，通过实战演示手把手教你构建一套完整的评估驱动开发（EDD）体系。我们将深入探讨如何建立多层级的自动化评估流程，利用数据追踪和量化指标来确保 AI Agent 在生产环境中具备高度的可预测性和稳定性。

在这一期视频中，你将掌握以下核心知识点：
首先是关于追踪与可见性的构建。通过学习 OpenTelemetry 标准以及 Arize AX 等工具链，你可以学会如何记录 Agent 的完整执行路径，从而精准捕捉到诸如“静默失败”或文件写入错误等隐藏在复杂逻辑中的故障。
其次是建立多层级的评估体系，即所谓的“瑞士奶酪模型”。你将学到如何通过叠加确定性代码检查（如验证 JSON 格式、股票代码匹配）、LLM 作为裁判的语义评判以及人工审核等多重防线，来确保系统的稳健性。
第三是核心指标的深度拆解。在涉及实时搜索等复杂场景时，我们将重点讨论如何区分“准确性”与“忠实度”，确保 Agent 的输出基于提供的上下文信息而非模型幻觉。同时，你还将学习如何识别并消除 LLM 在担任裁判时可能产生的长度、位置及置信度等系统性偏差，并通过构建包含人工标注的黄金数据集来校验评估器的可靠性。
最后是闭环迭代与优化策略。你会学到如何将失败案例聚类成测试集，利用编程 Agent 根据具体的错误解释自动重写提示词或工具定义，并掌握正确的优化优先级：即优先保障数据质量，其次是提示词工程（如 Few-shot、清晰指令），最后才是模型选择与超参数调优。

本视频非常适合正在开发 AI Agent 或复杂 LLM 应用的工程师，他们可以通过学习构建起一套标准化的评估流程；同时也适合需要建立自动化测试和评估体系的 AI 产品经理或 QA 工程师。通过这期课程的学习，你将能够从感性的试错转向数据驱动的工程化思维，能够独立搭建出一套包含追踪、多层过滤、自动反馈在内的生产级评估体系。看完视频后，你将具备从零构建自动化测试流程的能力，能够量化评估 Agent 的表现，并在面对复杂业务需求时，通过数据驱动的方法快速迭代提示词和工具定义，最终打造出稳定可靠的生产级 AI 应用。

章节
0:00 工作坊概览与 Notebook 设置
7:31 追踪、评估与感知的局限性
11:21 代码、LLM 与人工评估
14:27 Agent 失败与判定有效方案
17:18 能力评测与回归测试
21:19 配置 Claude Agent SDK
28:47 构建并追踪金融分析师 Agent
36:26 生成多样化的测试查询
38:54 阅读追踪数据并定义成功标准
45:31 分类失败原因并确定优先级
49:16 编写确定性代码检查
58:14 拒绝所有报告的正确性判断器
62:11 具备搜索上下文的忠实度评估
66:25 编写自定义可操作性准则
77:35 聚焦评估器与生产环境标准
80:00 对比 LLM 裁判与人工标注
86:25 精确率、召回率与裁判偏差
90:27 将失败案例转化为评估数据集
92:39 利用解释信息改进提示词
95:24 通过受控实验比较变更效果

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| From Vibes to Production Evaluating and Shipping AI Agents That Work 101 — Laurie Voss, Arize AI - 简体中文字幕（翻译）.zh.srt | 译文字幕 | [查看 / 下载](c0c2d4/4ee228cb/From%20Vibes%20to%20Production%20Evaluating%20and%20Shipping%20AI%20Agents%20That%20Work%20101%20%E2%80%94%20Laurie%20Voss%2C%20Arize%20AI%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E5%AD%97%E5%B9%95%EF%BC%88%E7%BF%BB%E8%AF%91%EF%BC%89.zh.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/WES05/c0c2d4/4ee228cb/From%20Vibes%20to%20Production%20Evaluating%20and%20Shipping%20AI%20Agents%20That%20Work%20101%20%E2%80%94%20Laurie%20Voss%2C%20Arize%20AI%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E5%AD%97%E5%B9%95%EF%BC%88%E7%BF%BB%E8%AF%91%EF%BC%89.zh.srt) |
| From Vibes to Production Evaluating and Shipping AI Agents That Work 101 — Laurie Voss, Arize AI - 中英双语字幕.srt | 双语字幕 | [查看 / 下载](c0c2d4/73a99bd8/From%20Vibes%20to%20Production%20Evaluating%20and%20Shipping%20AI%20Agents%20That%20Work%20101%20%E2%80%94%20Laurie%20Voss%2C%20Arize%20AI%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/WES05/c0c2d4/73a99bd8/From%20Vibes%20to%20Production%20Evaluating%20and%20Shipping%20AI%20Agents%20That%20Work%20101%20%E2%80%94%20Laurie%20Voss%2C%20Arize%20AI%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| From Vibes to Production Evaluating and Shipping AI Agents That Work 101 — Laurie Voss, Arize AI - 英语字幕（转写）.en.srt | 原文字幕（转写） | [查看 / 下载](c0c2d4/d53da070/From%20Vibes%20to%20Production%20Evaluating%20and%20Shipping%20AI%20Agents%20That%20Work%20101%20%E2%80%94%20Laurie%20Voss%2C%20Arize%20AI%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/WES05/c0c2d4/d53da070/From%20Vibes%20to%20Production%20Evaluating%20and%20Shipping%20AI%20Agents%20That%20Work%20101%20%E2%80%94%20Laurie%20Voss%2C%20Arize%20AI%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，时间轴与原视频一致，可直接拖进播放器（PotPlayer、VLC、IINA 等）加载。

## 原视频章节

| 时间 | 章节 |
|---|---|
| 0:00 | Workshop overview and notebook setup |
| 7:31 | Traces, evals, and the limits of vibes |
| 11:21 | Code, LLM, and human evaluations |
| 14:27 | Agent failures and grading valid solutions |
| 17:18 | Capability and regression evals |
| 21:19 | Instrumenting the Claude Agent SDK |
| 28:47 | Building and tracing the financial analyst |
| 36:26 | Generating diverse test queries |
| 38:54 | Reading traces and defining success |
| 45:31 | Categorizing failures and choosing priorities |
| 49:16 | Writing a deterministic ticker check |
| 58:14 | A correctness judge that rejects every report |
| 62:11 | Faithfulness with the research context |
| 66:25 | Writing a custom actionability rubric |
| 77:35 | Focused evaluators and production criteria |
| 80:00 | Comparing judges with human annotations |
| 86:25 | Precision, recall, and judge biases |
| 90:27 | Turning failures into evaluation datasets |
| 92:39 | Using explanations to improve prompts |
| 95:24 | Comparing changes with controlled experiments |

## 原视频简介

An LLM correctness judge rejects all 13 reports from a financial analysis agent. Laurie Voss examines why: the agent used live web research, while the judge graded from its own knowledge without that research context. Supplying the collected sources to a faithfulness evaluator produces a more useful split of six faithful reports and seven unfaithful ones. The notebook builds the agent with the Claude Agent SDK and instruments it with OpenTelemetry and OpenInference to send traces to Arize AX. Reading those traces exposes failed file writes, missing report content, and excessive web searches. A deterministic ticker check adds a cheap first layer of evaluation.

---

视频内容版权归原作者所有，字幕仅供学习交流。
