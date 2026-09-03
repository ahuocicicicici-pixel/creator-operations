# Creator Operations

中文 | [English](README.en.md)

一套面向达人调研、建联准备与项目执行的 AI 辅助工作台。

[体验个人演示版](https://ops.mccoco.xyz/) · [查看完整作品案例](https://mccoco.xyz/portfolio)

![已脱敏的 Creator Operations 达人推荐流程](https://mccoco.xyz/portfolio/assets/projects/outreach/flow/recommendation-live.png)

## 为什么做这个产品

达人运营的信息通常散落在表格、邮箱和个人经验里。项目数量增加后，团队很容易丢失上下文、重复调研，并花费大量时间确认下一步该做什么。

我把自己在海外红人营销中使用的运营方法，整理成一条连贯的产品工作流：

1. 解析项目 Brief，召回相关达人。
2. 调研达人近期公开内容，形成推荐依据。
3. 生成个性化建联草稿，交由人工审核。
4. 从邮件回复中提取报价与交付条件。
5. 展示待跟进事项、项目阻塞点与建议动作。

## 我的职责

我定义了业务规则、产品范围和交互方式，并独立完成个人演示版的前端、API、工作流与部署。

这个项目把达人营销判断、产品设计和技术实现结合在一起。它的目标不是替代人的决策，而是在运营做决定之前提供更完整的上下文。

## 产品流程

### 达人推荐

![已脱敏的达人推荐界面](https://mccoco.xyz/portfolio/assets/projects/outreach/flow/recommendation-live.png)

从结构化达人库中召回候选人，并整理审核推荐所需的依据。

### 建联准备

![已脱敏的建联草稿界面](https://mccoco.xyz/portfolio/assets/projects/outreach/flow/draft-redacted.png)

生成带有达人上下文的草稿，供运营审核，并支持按时区规划发送。

### 回复解析

![已脱敏的邮件回复解析界面](https://mccoco.xyz/portfolio/assets/projects/outreach/flow/reply-parse-redacted.png)

把非结构化回复整理成可审核的商务条件与明确的下一步动作。

### 执行可见性

显示工作卡在哪里，并让调研、沟通与交付上下文保持连接。

## 系统边界

个人演示版主要使用 React、TypeScript、Python API、PostgreSQL、Redis 与容器化服务。AI 辅助的召回和草稿生成与人工审核、批准保持分离。

这是公开的产品展示仓库，不是生产源码仓库。仓库不包含客户记录、达人联系方式数据库、邮件正文、凭据、部署配置或专有工作流实现。

## 体验与反馈

- 产品演示：[ops.mccoco.xyz](https://ops.mccoco.xyz/)
- 个人作品集：[mccoco.xyz/portfolio](https://mccoco.xyz/portfolio)
- 问题与建议：可以通过本仓库的 Issues 提交

Copyright © 2026 Mark Shi. All rights reserved.
