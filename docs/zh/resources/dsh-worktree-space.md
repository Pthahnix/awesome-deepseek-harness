---
title: "dsh-worktree-space"
description: "Worktree Space：将一个可包含多个 Git 仓库的工作区任务放进独立的任务空间目录——参与的每个仓库使用同一个任务分支各开一个 worktree；空间自动注册为 DSH 工作区，会话直接在其中开工，多个任务并行推进、互不干扰。收尾时可合并回各仓库目标分支、移除 worktree，并把 Git 未跟踪的文件归档到指定目录；结束任务时可选把未处理的提交和合并冲突交给 agent 处理。"
keywords: "dsh-worktree-space, developer, plugin, coding, git, multi-agent, deepseek harness, dsh"
---
# dsh-worktree-space

> ⭐ **1** · ✅ 活跃 · 插件

| | | | |
|---|---|---|---|
| 类型 | 插件 | 分类 | 开发者工具 |
| 星数 | ⭐ 1 | 状态 | ✅ 活跃 |
| 作者 | [kangtsang](https://github.com/kangtsang) | 更新时间 | — |

## 一句话介绍

> Worktree Space：将一个可包含多个 Git 仓库的工作区任务放进独立的任务空间目录——参与的每个仓库使用同一个任务分支各开一个 worktree；空间自动注册为 DSH 工作区，会话直接在其中开工，多个任务并行推进、互不干扰。收尾时可合并回各仓库目标分支、移除 worktree，并把 Git 未跟踪的文件归档到指定目录；结束任务时可选把未处理的提交和合并冲突交给 agent 处理。

## 详细介绍

Worktree Space：将一个可包含多个 Git 仓库的工作区任务放进独立的任务空间目录——参与的每个仓库使用同一个任务分支各开一个 worktree；空间自动注册为 DSH 工作区，会话直接在其中开工，多个任务并行推进、互不干扰。收尾时可合并回各仓库目标分支、移除 worktree，并把 Git 未跟踪的文件归档到指定目录；结束任务时可选把未处理的提交和合并冲突交给 agent 处理。

## 🔗 链接

- [GitHub 仓库](https://github.com/kangtsang/dsh-worktree-space)
- [完整 README](https://github.com/kangtsang/dsh-worktree-space#readme)
- [返回dsh-worktree-space所在分类](../plugins.md)
