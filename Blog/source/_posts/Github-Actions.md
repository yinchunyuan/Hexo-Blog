---
title: Github Actions
date: 2025-08-22 22:49:19
tags:
comments: true
---

2025-8-22 周五 22:49
# Github Actions

## 简介

Github Actions 是 Github 提供的持续集成服务, 用于自动化工作流程。它允许你将工作流程定义在仓库的 `.github/workflows` 目录下的 YAML 文件中, 并使用 Github 提供的虚拟机来执行这些工作流程。


## 工作流程

工作流程是 Github Actions 的基本单元, 它定义了一系列的任务, 这些任务可以自动执行, 例如构建、测试、部署等。

工作流程由事件触发, 例如代码提交、分支合并等。当事件发生时, Github Actions 会自动执行工作流程中的任务。


## 笔记
   来源: [Github Actions 官方文档](https://docs.github.com/en/actions/concepts/workflows-and-actions/workflows)
   1. 工作流是一个可配置的自动化流程
   2. 创建工作流 (创建由推送事件触发的基本工作流) 
   3. Github Actions 使用 YAML 语法来定义工作流, 每个工作流都作为单独的 YAML 文件存储在代码仓库中, 该文件位于 `.github/workflows` 目录中, '.github/workflows' 是两个文件夹, 叠起来了, 这个文件夹不是新建仓库时自动生成的, 需要自己手动创建
