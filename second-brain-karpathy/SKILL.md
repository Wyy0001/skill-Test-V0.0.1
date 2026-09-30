---
name: second-brain-karpathy
description: |
  当用户想用 AI（尤其 Claude）搭建持久化的个人知识系统/第二大脑、用 Obsidian 作本地存储并用 Claude 作顶层大脑、通过深度采访生成 CLAUDE.md、或厌倦了每次会话都重新对齐上下文时调用。不适用于纯代码生成、一次性问答、或不需要长期记忆的轻量任务。
metadata:
  cangjie.generated-by: cangjie-tools v2.5.0
  cangjie.variant: single
  cangjie.bundle-id: bundle.second-brain-karpathy
  cangjie.capability-count: 5
  cangjie.entrypoint-count: 1
---
# 卡帕西 LLM Wiki：用 Obsidian + Claude 构建第二大脑 — 全书能力入口

## 触发与不触发

**适用**：与本书能力域相关的咨询与任务（见下方路由表的意图列）。
**不适用**：
- 纯代码生成 / 一次性问答（本技能不替代通用编程助手）。
- 不需要长期记忆的轻量任务。
- 企业级知识库 / 团队协作 wiki（本方法面向个人单用户）。
- 具体 AI 编程技巧（如 Cursor 用法）。

## 核心原则（常驻速览，概览类问题读到这里即可回答）

1. 别用 AI 写代码；用它构建一个会持续累积、多年后可能超越你的第二大脑。
2. 停止把 AI 当严重失忆的伴侣每天重新喂背景、对齐颗粒度——给它一个持久记忆层。
3. 用 Obsidian 作本地存储、Claude 作顶层大脑，二者通过文件夹链接形成可检索知识库。
4. 通过一次一问的深度灵魂采访把你自己（目标/习惯/项目）载入第二大脑，产出 CLAUDE.md。
5. 每天往文件夹里丢思考、知识和新闻，让 Claude 自动归档，长期复利。

## 能力路由（先读本表，按意图加载 1 张能力卡）

| 用户意图 | 先读 | 补读/备注 |
|---|---|---|
| 我想让AI记住我；每次都要重新解释背景好烦；怎么让AI有长期记忆；AI为什么总忘记之前说的 | references/capabilities/stop-context-realignment.md | references/capabilities/setup-obsidian-claude.md、references/capabilities/soul-interview-claude-md.md |
| 怎么用Obsidian和Claude搭第二大脑；Claude怎么连Obsidian；第二大脑文件夹怎么建；Claude Projects怎么用 | references/capabilities/setup-obsidian-claude.md | references/capabilities/soul-interview-claude-md.md、references/capabilities/daily-ingestion.md |
| 怎么让Claude真正懂我；CLAUDE.md怎么生成；让AI深度采访我；怎么把我的习惯写进AI | references/capabilities/soul-interview-claude-md.md | references/capabilities/daily-ingestion.md、references/capabilities/stop-context-realignment.md |
| 第二大脑怎么日常维护；每天往Claude里放什么；怎么让AI自动整理我的笔记；知识库怎么持续更新 | references/capabilities/daily-ingestion.md | references/capabilities/setup-obsidian-claude.md、references/capabilities/long-term-evolution.md |
| 第二大脑长期有什么用；坚持用AI笔记值得吗；AI能替我进化吗 | references/capabilities/long-term-evolution.md | references/capabilities/daily-ingestion.md |

**非能力类查询**：
- 书名/作者/章节/整书概览 → references/overview.md
- 术语解释 → references/glossary.md
- 决策规则速查（不需要原文依据时） → references/cheatsheet.md
- 完整意图与关键词索引（本表未覆盖的意图先查这里） → references/capability-index.md

## 加载规则

- 每次任务先读本文件，再按路由表加载 **1** 张能力卡；任务明确跨域时最多加载 2 张。
- 概览/书名类问题不加载能力卡，用「核心原则」与 overview.md 回答。
- 路由表与 capability-index.md 都无法命中的意图，明确告知超出本书范围，不要硬套。

## 边界与判停

- 用户只想要一次性答案，不打算建立长期知识系统。
- 用户没有本地 Obsidian / Claude 访问条件。
- 涉及敏感隐私且用户不愿写入本地文件夹时，先停下确认。
