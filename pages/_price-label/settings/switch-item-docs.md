---
formatterOff: "@formatter:off"
title: 切换配置清单
subtitle: switch_item_docs 
summary: switch_item_docs
categories: [] 
tags: [] 
date: 2021-08-26 13:49:24 +800 
version: 1.0
formatterOn: "@formatter:on"
---

# 切换配置清单

## 概述

切换配置清单为系统中的多个配置项，每一项或多项配置共同组织成一个最小配置单元。

## 切换配置条目

**切换条目**为价签系统中一条切换配置项，即配置的最小操作单元或最小操作单元的组合。

| 属性     | 描述                           | 是否非空 | 说明             |
| -------- | ------------------------------ | -------- | ---------------- |
| 名称     | 切换配置的名称                 | Y        |                  |
| 模块     | 配置所属模块：电子｜纸质｜磅秤 | Y        | 至少一种，可多种 |
| 描述     | 切换配置功能描述               | Y        |                  |
| 状态     | 配置条目的状态：启有｜禁用     | Y        | 默认启用         |
| 配置页面 | 配置操作页面路径               | N        | 相对路径         |
| 是否     | 配置是否可能跳过               | N        |                  |
|          |                                |          |                  |



## 切换配置清单

切换配置清单以列表的形式展示系统中的**切换配置条目**。

![切换配置清单](switch-item-list.png)



## 新增/修改配置条目

在切换配置清单列表的右上角，通过按钮<button class="btn btn-round btn-sm btn-primary" data-toggle="modal" data-target="#addSwitchPlan"><i class="material-icons">add_task</i></button>
进行配置条目的新增，或通过配置清单的操作“修改”对已有配置条目进行修改。

交互方式：Model框



![保存配置条目](save-switch-item.png)

