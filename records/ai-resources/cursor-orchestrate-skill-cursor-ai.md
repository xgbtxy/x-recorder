# Cursor `/orchestrate`：递归派生多 Agent 的官方 Skill

- 状态：已核（落地链抽查可开；宣传数字以原文/文档为准）
- 分类：ai-resources
- 记录日期：2026-09-25
- **来源 X（必填）**：https://x.com/cursor_ai/status/2052432778743210127
- 作者：@cursor_ai
- 推文时间：2026-05-08 00:58 CST（UTC+8）

## 要点

- 推出 `/orchestrate` skill：借 Cursor SDK 递归 spawn Agent 处理复杂任务。
- 官方自述内部用途：自动检索内部 skills、压低后端冷启动（具体数字见风险项）。
- 使用前提：当前 Cursor 版本暴露该 slash skill，并具备 SDK/多 Agent 能力。
- 可与普通 Agent Skills 组合：编排层 + 领域 skill。

## 落地链接（可选）

- 仓库 / 官网 / 文档：https://cursor.com/docs/skills ；https://cursor.com/changelog

## 价值判断

- 为什么值得记：官方多 Agent 编排入口，比散装 prompt 更接近可复用工作流。
- 风险 / 待核实：帖中「token 降约 20%」「冷启动降约 80%」为宣传数字，待核实；计费与权限需实测。

## 原文摘要（可选）

Cursor 介绍 `/orchestrate` skill，称可递归拉起 Agent 攻坚大任务，并列举两项内部效果数据。
