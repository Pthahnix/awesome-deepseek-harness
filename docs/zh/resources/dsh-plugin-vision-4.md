---
title: "dsh-plugin-vision"
description: "给 DeepSeek Harness增加视觉能力的插件：新增 analyze_image 工具，让 DSH 能读取并分析本地图片内容（截图、图表、照片、文档、UI 界面等），并把分析结果以文本形式返回给模型。DSH 自带的 read_image 工具依赖主对话模型本身声明支持 image 输入模态（比如 DeepSeek 的 deepseek-chat / deepseek-reasoner 都是纯文本模型），因此在这些模型上无法直接\"看图\"。  本插件通过可配置的 OpenAI 兼容视觉模型 API（OpenAI、Qwen/通义、GLM/智谱、Moonshot、Ollama、vLLM 等）独立完成图片理解，把图片转成文本分析结果交回模型。这样即使主模型是纯文本模型，DSH 也具备视觉能力。"
keywords: "dsh-plugin-vision, ui, plugin, coding, multimodal, deepseek harness, dsh"
---
# dsh-plugin-vision

> ⭐ **1** · ✅ 活跃 · 插件

| | | | |
|---|---|---|---|
| 类型 | 插件 | 分类 | 界面与体验 |
| 星数 | ⭐ 1 | 状态 | ✅ 活跃 |
| 作者 | [Wyatt5341](https://github.com/Wyatt5341) | 更新时间 | — |

## 一句话介绍

> 给 DeepSeek Harness增加视觉能力的插件：新增 analyze_image 工具，让 DSH 能读取并分析本地图片内容（截图、图表、照片、文档、UI 界面等），并把分析结果以文本形式返回给模型。DSH 自带的 read_image 工具依赖主对话模型本身声明支持 image 输入模态（比如 DeepSeek 的 deepseek-chat / deepseek-reasoner 都是纯文本模型），因此在这些模型上无法直接"看图"。  本插件通过可配置的 OpenAI 兼容视觉模型 API（OpenAI、Qwen/通义、GLM/智谱、Moonshot、Ollama、vLLM 等）独立完成图片理解，把图片转成文本分析结果交回模型。这样即使主模型是纯文本模型，DSH 也具备视觉能力。

## 详细介绍

给 DeepSeek Harness增加视觉能力的插件：新增 analyze_image 工具，让 DSH 能读取并分析本地图片内容（截图、图表、照片、文档、UI 界面等），并把分析结果以文本形式返回给模型。DSH 自带的 read_image 工具依赖主对话模型本身声明支持 image 输入模态（比如 DeepSeek 的 deepseek-chat / deepseek-reasoner 都是纯文本模型），因此在这些模型上无法直接"看图"。  本插件通过可配置的 OpenAI 兼容视觉模型 API（OpenAI、Qwen/通义、GLM/智谱、Moonshot、Ollama、vLLM 等）独立完成图片理解，把图片转成文本分析结果交回模型。这样即使主模型是纯文本模型，DSH 也具备视觉能力。

## 🔗 链接

- [GitHub 仓库](https://github.com/Wyatt5341/dsh-plugin-vision)
- [完整 README](https://github.com/Wyatt5341/dsh-plugin-vision#readme)
- [返回dsh-plugin-vision所在分类](../plugins.md)
