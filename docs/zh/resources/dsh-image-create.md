---
title: "dsh-image-create"
description: "核心思想：在 DSH 里直接生图，不离开对话。插件通过宿主进程安全代理 OpenAI 兼容的图像生成接口（/images/generations 文生图、/images/edits 图生图），在侧边栏提供三栏生图工作台；同时把 generate_image 工具注册给 Agent——在对话框里让模型直接生图，结果自动进入面板历史。"
keywords: "dsh-image-create, ui, plugin, coding, multi-agent, multimodal, deepseek harness, dsh"
---
# dsh-image-create

> ⭐ **1** · ✅ 活跃 · 插件

| | | | |
|---|---|---|---|
| 类型 | 插件 | 分类 | 界面与体验 |
| 星数 | ⭐ 1 | 状态 | ✅ 活跃 |
| 作者 | [xiaoyuink](https://github.com/xiaoyuink) | 更新时间 | — |

## 一句话介绍

> 核心思想：在 DSH 里直接生图，不离开对话。插件通过宿主进程安全代理 OpenAI 兼容的图像生成接口（/images/generations 文生图、/images/edits 图生图），在侧边栏提供三栏生图工作台；同时把 generate_image 工具注册给 Agent——在对话框里让模型直接生图，结果自动进入面板历史。

## 详细介绍

核心思想：在 DSH 里直接生图，不离开对话。插件通过宿主进程安全代理 OpenAI 兼容的图像生成接口（/images/generations 文生图、/images/edits 图生图），在侧边栏提供三栏生图工作台；同时把 generate_image 工具注册给 Agent——在对话框里让模型直接生图，结果自动进入面板历史。

## 🔗 链接

- [GitHub 仓库](https://github.com/xiaoyuink/dsh-image-create)
- [完整 README](https://github.com/xiaoyuink/dsh-image-create#readme)
- [返回dsh-image-create所在分类](../plugins.md)
