---
title: "dsh-run-guard"
description: "核心设计:刹车与油门共用一套状态感知,互不干扰——guard 中断的 turn 以 error 结束,continue 天然不会误推;continue 推进的新 turn 若再次死循环,guard 立刻拦截。闭环自洽。"
keywords: "dsh-run-guard, developer, plugin, coding, deepseek harness, dsh"
---
# dsh-run-guard

> ⭐ **5** · ✅ active · plugin

| | | | |
|---|---|---|---|
| Type | plugin | Category | Developer tools |
| Stars | ⭐ 5 | Status | ✅ active |
| Author | [PrismLean](https://github.com/PrismLean) | Updated | — |

## One-liner

> 核心设计:刹车与油门共用一套状态感知,互不干扰——guard 中断的 turn 以 error 结束,continue 天然不会误推;continue 推进的新 turn 若再次死循环,guard 立刻拦截。闭环自洽。

## About

核心设计:刹车与油门共用一套状态感知,互不干扰——guard 中断的 turn 以 error 结束,continue 天然不会误推;continue 推进的新 turn 若再次死循环,guard 立刻拦截。闭环自洽。

## 🔗 Links

- [GitHub Repository](https://github.com/PrismLean/dsh-run-guard)
- [Full README](https://github.com/PrismLean/dsh-run-guard#readme)
- [Back to the Plugins list](../plugins.md)
