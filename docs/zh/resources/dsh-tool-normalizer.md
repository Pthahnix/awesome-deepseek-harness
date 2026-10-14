---
title: "dsh-tool-normalizer"
description: "Every failed tool call costs a full model round-trip: the error comes back, the model re-reads the entire conversation context, and tries again. In a large workspace that retry resubmits ~180k input tokens — so a ~5% tool failure rate quietly inflates your tok"
keywords: "dsh-tool-normalizer, memory, plugin, coding, context, ui, deepseek harness, dsh"
---
# dsh-tool-normalizer

> ⭐ **8** · ✅ 活跃 · 插件

| | | | |
|---|---|---|---|
| 类型 | 插件 | 分类 | 记忆与上下文 |
| 星数 | ⭐ 8 | 状态 | ✅ 活跃 |
| 作者 | [merenguesL](https://github.com/merenguesL) | 更新时间 | — |

## 一句话介绍

> Every failed tool call costs a full model round-trip: the error comes back, the model re-reads the entire conversation context, and tries again. In a large workspace that retry resubmits ~180k input tokens — so a ~5% tool failure rate quietly inflates your tok

## 详细介绍

Every failed tool call costs a full model round-trip: the error comes back, the model re-reads the entire conversation context, and tries again. In a large workspace that retry resubmits ~180k input tokens — so a ~5% tool failure rate quietly inflates your tok

## 🔗 链接

- [GitHub 仓库](https://github.com/merenguesL/dsh-tool-normalizer)
- [完整 README](https://github.com/merenguesL/dsh-tool-normalizer#readme)
- [返回dsh-tool-normalizer所在分类](../plugins.md)
