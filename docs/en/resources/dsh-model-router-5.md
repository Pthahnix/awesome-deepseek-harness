---
title: "dsh-model-router"
description: "dsh-model-router 是一个 DSH 插件，向 harness 注册一个虚拟模型提供商 model-router：它汇聚用户已添加的所有提供商及其模型（按 model id 严格归并），并在每次 LLM 请求发出时把请求实时路由到该模型当前激活的提供商。配套的设置卡片（设置 → 插件 → 插件配置 → 模型路由）支持按模型对提供商拖拽排序（供后续自动切换使用）与点击切换当前提供商；切换后全局立即生效——下一次发出的该模型请求即走新提供商。"
keywords: "dsh-model-router, developer, plugin, coding, deepseek harness, dsh"
---
# dsh-model-router

> ⭐ **1** · ✅ active · plugin

| | | | |
|---|---|---|---|
| Type | plugin | Category | Developer tools |
| Stars | ⭐ 1 | Status | ✅ active |
| Author | [fonlan](https://github.com/fonlan) | Updated | — |

## One-liner

> dsh-model-router 是一个 DSH 插件，向 harness 注册一个虚拟模型提供商 model-router：它汇聚用户已添加的所有提供商及其模型（按 model id 严格归并），并在每次 LLM 请求发出时把请求实时路由到该模型当前激活的提供商。配套的设置卡片（设置 → 插件 → 插件配置 → 模型路由）支持按模型对提供商拖拽排序（供后续自动切换使用）与点击切换当前提供商；切换后全局立即生效——下一次发出的该模型请求即走新提供商。

## About

dsh-model-router 是一个 DSH 插件，向 harness 注册一个虚拟模型提供商 model-router：它汇聚用户已添加的所有提供商及其模型（按 model id 严格归并），并在每次 LLM 请求发出时把请求实时路由到该模型当前激活的提供商。配套的设置卡片（设置 → 插件 → 插件配置 → 模型路由）支持按模型对提供商拖拽排序（供后续自动切换使用）与点击切换当前提供商；切换后全局立即生效——下一次发出的该模型请求即走新提供商。

## 🔗 Links

- [GitHub Repository](https://github.com/fonlan/dsh-model-router)
- [Full README](https://github.com/fonlan/dsh-model-router#readme)
- [Back to the Plugins list](../plugins.md)
