# terraform-skill：Terraform / OpenTofu IaC 垂直 Agent Skill

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/antonbabenko/status/2012917839745659170
- 作者 / 频道：@antonbabenko
- 发布时间：2026-01-18 15:59:45 UTC（约 2026-01-18 23:59 CST）

## 要点

- AWS Hero / terraform-aws-modules 作者 Anton Babenko 发布 **terraform-skill**：把 Terraform / OpenTofu 最佳实践（测试、模块、状态、CI/CD、安全扫描等）封装为可装 Agent Skill，宣称结合 HashiCorp MCP 可减少 IaC「幻觉」。
- 覆盖 AWS / Azure / GCP 模式；兼容 Claude Code、Cursor、Copilot、Gemini CLI、OpenCode、Codex 等 Agent Skills 生态。
- 可动手：`npx skills add https://github.com/antonbabenko/terraform-skill`；Claude Code 经 `antonbabenko/agent-plugins` marketplace（勿重复加同名 marketplace）。

## 落地链接（可选）

- 仓库：https://github.com/antonbabenko/terraform-skill

## 价值判断

- 为什么值得记：**新垂直域（IaC / Terraform·OpenTofu）可装 Skills**，作者官号发帖 + `npx skills add` 落地清晰；补已入库营销 / 游戏 / 观测 / dbt 等 Skills 之外的基础设施轴。
- 风险 / 待核实：仓库 ★约 2381（2026-09-26 `gh api`）；效果与生产合规收益 **待核实**；云账号与状态库权限需自控。

## 原文摘要（可选）

摘要：@antonbabenko 介绍 terraform-skill，强调用 HashiCorp MCP + Skill 让 Terraform 回答 grounded，并给出 GitHub 仓库。

## 与其他条目的关系（可选）

非 dbt / Prisma / Azure / Obsidian / Marketing / Elastic 等已入库 Skills；本条是 **Terraform/OpenTofu IaC 垂直包**。非 MCP 单条。
