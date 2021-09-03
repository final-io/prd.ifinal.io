---
formatterOff: "@formatter:off"
title: 门店实施切换计划
subtitle: switch-plan 
summary: switch-plan
categories: [] 
tags: [] 
date: 2021-08-26 14:52:10 +800 
version: 1.0
formatterOn: "@formatter:on"
---

# 门店实施切换计划



## 背景

随着价签系统接入的商家和门店数量增多，价签系统接入的成本体现愈发明显，价徐系统在切换时，实施人员需要在价签系统联相关系统完成大量的配置，并且很容易出现人为的遗漏和操作失误，以及需要相头系统的研发人员在线支持，系统切换效率低下且投入成本较大。

## 目标

门店实施切换计划功能主要是以工作流的方式，给实施人员提供一套标准的系统切换流程，避免在系统切换过程中造成的配置遗漏以及人为的操作失误，主要从以下几个点出发：

* 将系统切换过程的需要配置的选项以**切换清单**的形式呈现，避免切换遗漏。
* 通过系统自助检查切换选项是否正解，避免人为操作出现失误。

## 功能说明

实施切换计划将业务系统称为**应用**，将切换流程称为**模板**，将系统配置称为**配置项**，一次切换计划可能涉及多个应用（系统），关系如下图所示：

![切换计划](http://assets.processon.com/chart_image/6131d12a079129550efc7fae.png)

### 切换应用

研发人员可以在【设置】-【切换应用】菜单下查看、管理已有应用或新增应用。

<iframe id="embed_dom" name="embed_dom" frameborder="0" style="display:block;width:100%; height:600px;" src="../settings/switch-application"></iframe>

应用包含以下属性：

| 属性 | 说明     | 备注 |      |
| ---- | -------- | ---- | ---- |
| 名称 | 应用名称 |      |      |
| 编码 | 应用编码 |      |      |
| 域名 | 应用域名 |      |      |

### 切换项

通过应用列表的【切换项】链接可以跳转到应用的切换项管理页面：

<iframe id="embed_dom" name="embed_dom" frameborder="0" style="display:block;width:100%; height:600px;" src="../settings/switch-application/switch-option"></iframe>

### 切换模板

通过应用列表的【切换模板】链接可以跳转到应用的切换模板管理页面，在这里可以新建切换模板或查看已有切换模板：

<iframe id="embed_dom" name="embed_dom" frameborder="0" style="display:block;width:100%; height:600px;" src="../settings/switch-application/switch-template"></iframe>

通过模板列表的【查看】链接查看查看切换或管理模板中的切换项：

<iframe id="embed_dom" name="embed_dom" frameborder="0" style="display:block;width:100%; height:600px;" src="../settings/switch-application/switch-template/switch-list"></iframe>



### 切换计划

实施人员可以在【工作计划】-【切换实施计划】页面查看、实施已有实施计划可新建实施计划：

<iframe id="embed_dom" name="embed_dom" frameborder="0" style="display:block;width:100%; height:600px;" src="/workflow/schedule/switch-plan/"></iframe>





## 更新日志

| 版本                   | 描述                         | 时间       |
| ---------------------- | ---------------------------- | ---------- |
| 门店实施切换计划-1.0.0 | 门店实施切换计划初稿         | 2021-08-26 |
| 门店实施切换计划-1.0.0 | 门店实施切换计划通用解决方案 | 2021-09-03 |
|                        |                              |            |

