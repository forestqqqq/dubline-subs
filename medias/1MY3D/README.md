<!-- dubline-subs {"title": "Guardrails with LangChain: A Complete Crash Course for Building Safe AI Agents", "author": "Krish Naik", "files": 3, "updated": "2026-11-13"} -->
# Guardrails with LangChain: A Complete Crash Course for Building Safe AI Agents

<img src="057eb1/af177a8b/Guardrails%20with%20LangChain%20A%20Complete%20Crash%20Course%20for%20Building%20Safe%20AI%20Agents.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=ruiLq0OzjkI](https://www.youtube.com/watch?v=ruiLq0OzjkI) |
| 发布 | 2026-03-05 |
| 时长 | 38 分 15 秒 |
| 语言 | 英语 |
| 原作者 | [Krish Naik](https://www.youtube.com/@krishnaik06)（@krishnaik06，约 153 万订阅） |

## 中文信息

**标题**：【中配】38 分钟详解：用 LangChain 给 AI Agent 加安全锁

**原标题译文**：使用 LangChain 构建安全 AI Agent 的完整速成课程

在构建基于大语言模型的 AI Agent 时，安全性始终是开发者面临的首要挑战。如果智能体在与用户交互过程中泄露了敏感的个人身份信息，或者生成了包含恶意代码、有害言论的内容，不仅会损害品牌声誉，还可能面临严重的法律风险。本期视频将带大家深入系统地学习如何在 LangChain 框架中为 AI Agent 构建全方位的安全护栏。我们将从基础概念出发，对比不同防护技术的优劣，并手把手演示如何通过多种技术手段构建起一道坚固的防线，确保你的智能体在复杂的生产环境中能够安全可靠地运行。

通过这期视频的学习，你将掌握以下核心知识点：

首先，我们将深入探讨 AI Agent 护栏的核心逻辑。视频将对比确定性方法与模型评估方法的差异。确定性方法基于关键词匹配等规则算法，虽然运行成本极低且速度快，但在处理复杂的语义理解时往往力不从心。相比之下，模型方法利用大语言模型来评估语义，虽然存在一定的调用成本和延迟，但在识别隐晦的有害信息方面具有显著优势。

其次，我们将学习如何利用 LangChain 内置的 PII 检测中间件。这一功能可以自动识别并脱敏电子邮件、信用卡号、IP 地址、MAC 地址以及 API 密钥等敏感信息。掌握这一技能，可以有效防止用户在输入过程中不经意间泄露隐私，也能防止智能体在输出中暴露内部敏感数据。

接着，视频将展示如何引入人机交互（HITL）中间件。通过 Checkpoint 机制，我们可以在工作流的关键节点设置暂停点，等待人工审核后再继续执行。配合 resume 命令，你可以精确控制哪些高风险操作必须经过人类批准，从而在自动化与安全性之间找到完美的平衡。

此外，我们将深入讲解自定义钩子的实现逻辑。通过继承 AgentMiddleware 类并实现特定的逻辑，你可以创建 before_agent 钩子和 after_agent 钩子。before_agent 钩子可以在 LLM 调用之前拦截危险请求，从而有效节省不必要的 Token 消耗；而 after_agent 钩子则可以在生成最终响应后进行二次验证或修改，确保输出内容符合安全规范。为了平衡安全性与经济性，我们还会探讨如何结合廉价的小模型来进行高效的后处理。

最后，视频将演示多层防护体系的构建方法。我们将展示如何按顺序堆叠多种中间件，例如将内容过滤（content filter）与 PII 过滤结合使用。通过一个真实的医疗聊天机器人实战案例，我们将验证这些输入过滤与输出安全策略在实际业务场景中的表现。

本视频非常适合正在开发或使用 LangChain 构建 AI Agent 的开发者观看。无论你是希望确保智能体输入输出安全性的产品经理或技术负责人，还是希望深入了解如何防止隐私泄露和有害内容生成的技术人员，这期视频都能为你提供实用的技术指导。只要你具备基础的 Python 编程知识以及一定的 LLM 应用经验，就能跟随视频中的步骤，掌握构建安全护栏的核心技术。

看完本视频后，你将能够独立在 LangChain 项目中部署多层安全防护体系。你不仅能学会如何识别并拦截恶意关键词（如 hack、malware 等），还能掌握如何通过代码实现自动化的隐私脱敏、基于语义的风险评估以及关键节点的审批流。通过掌握这些技术，你将能够构建出更加稳健、合规且具备工业级安全标准的 AI Agent 应用，让你的智能体在处理敏感数据和复杂交互时更加从容。

原视频：Guardrails with LangChain: A Complete Crash Course for Building Safe AI Agents
原作者：Krish Naik
发布日期：2026-03-05
视频链接：https://www.youtube.com/watch?v=ruiLq0OzjkI

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](057eb1/068178f4/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/1MY3D/057eb1/068178f4/dubbed.srt) |
| Guardrails with LangChain A Complete Crash Course for Building Safe AI Agents - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](057eb1/3e97a699/Guardrails%20with%20LangChain%20A%20Complete%20Crash%20Course%20for%20Building%20Safe%20AI%20Agents%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/1MY3D/057eb1/3e97a699/Guardrails%20with%20LangChain%20A%20Complete%20Crash%20Course%20for%20Building%20Safe%20AI%20Agents%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| Guardrails with LangChain A Complete Crash Course for Building Safe AI Agents - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](057eb1/6eba784e/Guardrails%20with%20LangChain%20A%20Complete%20Crash%20Course%20for%20Building%20Safe%20AI%20Agents%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/1MY3D/057eb1/6eba784e/Guardrails%20with%20LangChain%20A%20Complete%20Crash%20Course%20for%20Building%20Safe%20AI%20Agents%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

Check out the detailed blog with code: https://krishcnaik.substack.com/p/guardrails-with-langchain-a-complete?r=6ah1nv&utm_campaign=post&utm_medium=web&triedRedirect=true

---

视频内容版权归原作者所有，字幕仅供学习交流。
