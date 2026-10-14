---
title: "dsh-tool-normalizer"
description: "Every failed tool call costs a full model round-trip: the error comes back, the model re-reads the entire conversation context, and tries again. In a large workspace that retry resubmits ~180k input tokens — so a ~5% tool failure rate quietly inflates your tok"
keywords: "dsh-tool-normalizer, memory, plugin, coding, context, ui, deepseek harness, dsh"
---
# dsh-tool-normalizer

> ⭐ **8** · ✅ active · plugin

| | | | |
|---|---|---|---|
| Type | plugin | Category | Memory & context |
| Stars | ⭐ 8 | Status | ✅ active |
| Author | [merenguesL](https://github.com/merenguesL) | Updated | — |

## One-liner

> Every failed tool call costs a full model round-trip: the error comes back, the model re-reads the entire conversation context, and tries again. In a large workspace that retry resubmits ~180k input tokens — so a ~5% tool failure rate quietly inflates your tok

## About

Every failed tool call costs a full model round-trip: the error comes back, the model re-reads the entire conversation context, and tries again. In a large workspace that retry resubmits ~180k input tokens — so a ~5% tool failure rate quietly inflates your tok

## 🔗 Links

- [GitHub Repository](https://github.com/merenguesL/dsh-tool-normalizer)
- [Full README](https://github.com/merenguesL/dsh-tool-normalizer#readme)
- [Back to the Plugins list](../plugins.md)
