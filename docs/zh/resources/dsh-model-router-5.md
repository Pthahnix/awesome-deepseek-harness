---
title: "dsh-model-router"
description: "dsh-model-router 是一个 DSH 插件，向 harness 注册一个虚拟模型提供商 model-router：它汇聚用户已添加的所有提供商及其模型（按 model id 严格归并），并在每次 LLM 请求发出时把请求实时路由到该模型当前激活的提供商。配套的设置卡片（设置 → 插件 → 插件配置 → 模型路由）支持按模型对提供商拖拽排序（供后续自动切换使用）与点击切换当前提供商；切换后全局立即生效——下一次发出的该模型请求即走新提供商。"
keywords: "dsh-model-router, developer, plugin, coding, deepseek harness, dsh"
---
# dsh-model-router

> ⭐ **1** · ✅ 活跃 · 插件

| | | | |
|---|---|---|---|
| 类型 | 插件 | 分类 | 开发者工具 |
| 星数 | ⭐ 1 | 状态 | ✅ 活跃 |
| 作者 | [fonlan](https://github.com/fonlan) | 更新时间 | — |

## 一句话介绍

> dsh-model-router 是一个 DSH 插件，向 harness 注册一个虚拟模型提供商 model-router：它汇聚用户已添加的所有提供商及其模型（按 model id 严格归并），并在每次 LLM 请求发出时把请求实时路由到该模型当前激活的提供商。配套的设置卡片（设置 → 插件 → 插件配置 → 模型路由）支持按模型对提供商拖拽排序（供后续自动切换使用）与点击切换当前提供商；切换后全局立即生效——下一次发出的该模型请求即走新提供商。

## 详细介绍

dsh-model-router 是一个 DSH 插件，向 harness 注册一个虚拟模型提供商 model-router：它汇聚用户已添加的所有提供商及其模型（按 model id 严格归并），并在每次 LLM 请求发出时把请求实时路由到该模型当前激活的提供商。配套的设置卡片（设置 → 插件 → 插件配置 → 模型路由）支持按模型对提供商拖拽排序（供后续自动切换使用）与点击切换当前提供商；切换后全局立即生效——下一次发出的该模型请求即走新提供商。

## 🔗 链接

- [GitHub 仓库](https://github.com/fonlan/dsh-model-router)
- [完整 README](https://github.com/fonlan/dsh-model-router#readme)
- [返回dsh-model-router所在分类](../plugins.md)
