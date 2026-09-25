# Supabase Agent Skills：可 `npx skills add` 的官方 Skill 包

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/supabase/status/2014375032261156943
- 作者 / 频道：@supabase
- 发布时间：2026-01-23 00:30 CST（UTC+8）

## 关键点

- Supabase 发布面向 AI coding agent 的 Agent Skills（含 Postgres Best Practices 等），遵循 agentskills.io 开放格式。
- 安装：`npx skills add supabase/agent-skills`；也可按 skill 安装（如 `--skill supabase` / `--skill supabase-postgres-best-practices`）。
- 仓库声称兼容 Claude Code、Cursor、GitHub Copilot、Cline 等 18+ agent（兼容列表与数字待核实）。
- 技能侧重：先查当前文档、RLS/安全清单、CLI/`--help` 与 Supabase MCP 排障、schema 变更工作流（开发库，非生产直连）。

## 落地链接（可选）

- 仓库 / 官网 / 文档：https://github.com/supabase/agent-skills ；https://supabase.com/docs/guides/getting-started/ai-skills ；https://supabase.com/blog/supabase-agent-skills

## 价值判断

- 为什么值得记：一行命令可装的官方 Skill，直接提升 Agent 写 Supabase/Postgres 的可落地性。
- 风险 / 待核实：帖中效果表述；评测表准确率数字（博客内）待核实；勿把 MCP 指到生产库。

## 原文摘要（可选）

摘要：宣布一系列聚焦 Postgres Best Practices 的 Agent Skills，并指向 supabase.com 博客试用入口。
