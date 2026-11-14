<!-- dubline-subs {"title": "Creating a Custom Ansible Lookup Plugin in Python for Reading a File", "author": "Luca Berton", "files": 3, "updated": "2026-11-13"} -->
# Creating a Custom Ansible Lookup Plugin in Python for Reading a File

<img src="c762bd/26d1775c/Creating%20a%20Custom%20Ansible%20Lookup%20Plugin%20in%20Python%20for%20Reading%20a%20File.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=iyjXouFfD1M](https://www.youtube.com/watch?v=iyjXouFfD1M) |
| 发布 | 2023-11-08 |
| 时长 | 9 分 6 秒 |
| 语言 | 英语 |
| 原作者 | [Luca Berton](https://www.youtube.com/@BertonLuca)（@BertonLuca，6210 订阅） |

## 中文信息

**标题**：【中配】只需40行Python代码，手搓一个自定义Ansible lookup插件

**原标题译文**：使用 Python 创建用于读取文件的自定义 Ansible Lookup 插件

在这期视频中，我们将深入探讨 Ansible 的扩展机制，带你通过最基础的 Python 代码实战，亲手打造一个自定义的 Ansible lookup 插件。很多自动化工程师在处理复杂的运维任务时，往往会遇到现有的内置插件无法满足特定需求的情况，比如需要从特定的文件路径读取动态内容，或者需要对接特殊的 API 接口。Lookup 插件正是解决这类问题的核心工具，它能够在执行 playbook 的过程中动态地获取数据。本视频将从基础概念出发，手把手教你如何编写一个名为 file_read 的自定义插件，让你的 Ansible 自动化流程能够灵活地读取外部文件内容并将其集成到任务流中。

通过本期视频的学习，你将掌握以下核心知识点：

首先，你将深入理解 Lookup 插件的核心作用。你会明白它如何在 playbook 执行过程中作为数据源，去获取数据库、API 或外部文件中的动态信息，从而为后续的任务提供必要的变量支持。

其次，我们将详细讲解插件开发的规范要求。一个合格的 Ansible 插件必须包含明确的元数据，包括插件名称、作者、版本以及功能描述。这些信息不仅是代码的注释，更是 Ansible 与插件之间交互的重要 API 规范，确保插件能够被系统正确识别和调用。

在核心代码实现方面，视频将重点演示继承机制的应用。你会学习到如何通过继承 Ansible 内置的 LookupBase 类，并正确实现 run 函数，这是符合 Ansible 开发规范的关键步骤。同时，我们将深入剖析插件的返回值要求，明确 Lookup 插件必须返回一个列表格式的数据，这是确保数据正确传递到 playbook 中的基础。

此外，视频还会涵盖多个关键的库函数与工程实践。我们将演示如何利用 Ansible 内置的 findFileInSearchPath 函数来准确定位文件路径，并学习如何使用 try-catch 块捕获运行中的错误。通过抛出 AnsibleError 或 ParseError，你可以更高效地定位问题并进行调试。同时，我们还会讲解如何通过指定 verbosity 参数来控制调试信息的显示程度，以及了解 Ansible 如何自动编译 Python 插件生成 .pyc 文件，从而优化后续执行的速度。

本视频非常适合以下人群观看：首先是想要突破现有工具限制、扩展 Ansible 功能的自动化工程师，如果你经常在寻找特定的数据源但发现官方插件不够用，这期内容将为你提供全新的思路。其次是具备基础 Python 编程能力的用户，只要你会基本的 Python 语法，就能轻松跟上视频中的代码编写节奏。最后，如果你是希望系统性学习如何开发自定义 Ansible 插件的开发者，本视频提供的从基础代码编写到在终端实际运行并验证输出结果的完整流程，将是你从零到一的实战指南。

看完这期视频后，你将能够独立完成从零开始的自定义插件开发。你不仅能掌握如何编写出符合规范的 Python 插件代码，还能学会如何在真实的 ansible-playbook 环境中调用并测试这些插件。通过在终端实际运行代码并验证输出结果的实战演示，你将具备将自定义逻辑融入自动化运维流程的能力，让你的 Ansible 工具箱变得更加强大和个性化。

原视频：Creating a Custom Ansible Lookup Plugin in Python for Reading a File
原作者：Luca Berton
发布日期：2023-11-08
视频链接：https://www.youtube.com/watch?v=iyjXouFfD1M

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| Creating a Custom Ansible Lookup Plugin in Python for Reading a File - 简体中文+拉丁语双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](c762bd/291ca673/Creating%20a%20Custom%20Ansible%20Lookup%20Plugin%20in%20Python%20for%20Reading%20a%20File%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%2B%E6%8B%89%E4%B8%81%E8%AF%AD%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/7VJB9/c762bd/291ca673/Creating%20a%20Custom%20Ansible%20Lookup%20Plugin%20in%20Python%20for%20Reading%20a%20File%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%2B%E6%8B%89%E4%B8%81%E8%AF%AD%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| Creating a Custom Ansible Lookup Plugin in Python for Reading a File - 拉丁语字幕（转写）.la.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](c762bd/b0652f18/Creating%20a%20Custom%20Ansible%20Lookup%20Plugin%20in%20Python%20for%20Reading%20a%20File%20-%20%E6%8B%89%E4%B8%81%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.la.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/7VJB9/c762bd/b0652f18/Creating%20a%20Custom%20Ansible%20Lookup%20Plugin%20in%20Python%20for%20Reading%20a%20File%20-%20%E6%8B%89%E4%B8%81%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.la.srt) |
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](c762bd/f8db60e3/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/7VJB9/c762bd/f8db60e3/dubbed.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

Extending Ansible’s Capabilities with a Custom File Retrieval Python Lookup Plugin.
https://www.ansiblepilot.com/articles/creating-a-custom-ansible-lookup-plugin-in-python-for-reading-a-file/

---

视频内容版权归原作者所有，字幕仅供学习交流。
