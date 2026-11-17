<!-- dubline-subs {"title": "DEF CON 34 - CPV - Inside the Guts of Ransomware - Ashley Munoz", "author": "DEFCONConference", "files": 3, "updated": "2026-11-17"} -->
# DEF CON 34 - CPV - Inside the Guts of Ransomware - Ashley Munoz

<img src="e81324/f0f5d6f8/DEF%20CON%2034%20-%20CPV%20-%20Inside%20the%20Guts%20of%20Ransomware%20-%20Ashley%20Munoz.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=8XfVRfUP91Q](https://www.youtube.com/watch?v=8XfVRfUP91Q) |
| 发布 | 2026-11-06 |
| 时长 | 27 分 50 秒 |
| 语言 | 英语 |
| 原作者 | [DEFCONConference](https://www.youtube.com/@DEFCONConference)（@DEFCONConference，约 42 万订阅） |

## 中文信息

**标题**：【中配】勒索软件里藏了什么？手把手教你识别AES、RSA等加密算法

**原标题译文**：DEF CON 34 - CPV - 深入了解勒索软件内部 - Ashley Munoz

这期视频将带你深入探索勒索软件的核心技术逻辑，重点讲解如何通过静态分析、动态分析以及逆向工程技术，精准识别勒索软件中隐藏的各种加密算法。在面对复杂的勒索软件样本时，识别其使用的加密机制是安全专家判断是否能够开发出有效解密工具的关键第一步。本视频将从基础的密码学概念科普开始，逐步深入到复杂的算法辨析与实战案例演示，旨在帮助大家建立起完整的分析思路，从底层原理到实战技巧全方位覆盖。

在观看过程中，你将学到以下核心知识点：

首先是勒索软件常见的混合加密模式。在实际的恶意软件样本中，为了兼顾加密速度和安全性，攻击者通常采用混合加密架构：利用对称加密算法如AES、Salsa20和ChaCha20来处理海量的用户文件，因为这些算法处理速度极快，能够迅速完成大规模数据的加密；而非对称加密算法如RSA和ECC虽然计算速度较慢，但其核心优势在于密钥保护，因此常被用于加密或保护受害者的对称密钥。理解这种配合使用的逻辑是分析勒索软件加密流程的基础，也是判断解密可行性的核心切入点。

其次是针对不同算法的精准识别技巧。针对AES算法，视频将详细讲解如何通过在二进制文件中查找公开的S盒（S-Box）或T表（T-Table）中的特定十六进制常量来进行快速定位。对于Salsa20与ChaCha20这两类结构相似的流加密算法，视频将教你如何通过观察其内部矩阵中expand 32 byte K字符串的排列顺序来准确区分，避免在分析过程中产生混淆。此外，视频还会深入讲解如何利用Windows Crypto API来定位算法。通过在调试过程中监控CryptGenKey等关键API，你可以观察到入栈的算法ID数值，例如识别出6610这一特定数值即对应AES-256算法。同时，视频还会介绍一系列实用的逆向工程工具链，包括Jidra工具、FindCrypt插件、Yara规则以及Crypto Analyzer等，帮助你在实战中更高效地完成算法识别任务。

本视频非常适合恶意软件分析师、应急响应专家、逆向工程爱好者以及对密码学感兴趣的安全研究人员观看。为了获得最佳的学习效果，建议观众具备基础的逆向工程知识，了解基本的密码学概念（如明文、密文、密钥、Nonce、S盒等），并熟悉Jidra或类似的逆向工程工具。无论你是初涉逆向工程的爱好者，还是已经在一线工作的安全从业者，这期视频提供的技术细节都能为你提供极具价值的参考。

看完这期视频后，你将能够掌握识别勒索软件加密算法的标准流程。你不仅能学会利用静态和动态手段快速锁定AES、RSA等算法，还能通过分析算法ID和常量特征来判断勒索软件的技术特征。这些能力将帮助你在应急响应中快速判断是否具备开发解密器的可能性，并能更有效地识别勒索软件家族的技术演变，为后续的防御和溯源工作提供有力支持。通过掌握这些核心技术，你将能够更从容地应对复杂的勒索软件威胁，在复杂的二进制代码中精准剥离出核心的加密逻辑。

原视频：DEF CON 34 - CPV - Inside the Guts of Ransomware - Ashley Munoz
原作者：DEFCONConference
发布日期：2026-11-06
视频链接：https://www.youtube.com/watch?v=8XfVRfUP91Q

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| DEF CON 34 - CPV - Inside the Guts of Ransomware - Ashley Munoz - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](ebbfc6/3c38cace/DEF%20CON%2034%20-%20CPV%20-%20Inside%20the%20Guts%20of%20Ransomware%20-%20Ashley%20Munoz%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/NKBVX/ebbfc6/3c38cace/DEF%20CON%2034%20-%20CPV%20-%20Inside%20the%20Guts%20of%20Ransomware%20-%20Ashley%20Munoz%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](ebbfc6/721bbad6/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/NKBVX/ebbfc6/721bbad6/dubbed.srt) |
| DEF CON 34 - CPV - Inside the Guts of Ransomware - Ashley Munoz - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](ebbfc6/d556de63/DEF%20CON%2034%20-%20CPV%20-%20Inside%20the%20Guts%20of%20Ransomware%20-%20Ashley%20Munoz%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/NKBVX/ebbfc6/d556de63/DEF%20CON%2034%20-%20CPV%20-%20Inside%20the%20Guts%20of%20Ransomware%20-%20Ashley%20Munoz%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

Have you ever wondered how malware analysts identify different encryption algorithms in ransomware samples? In this session, I'll explain the design of some algorithms (such as AES, RSA, ChaCha20, etc.) and show you how to identify them using reverse engineering and debugging techniques, and by using ransomware demos from recent incidents.

---

视频内容版权归原作者所有，字幕仅供学习交流。
