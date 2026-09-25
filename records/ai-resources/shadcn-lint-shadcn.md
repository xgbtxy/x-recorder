# shadcn/lint：面向 Agent 的 Tailwind 设计系统校验器

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/shadcn/status/2099534231114314145
- 作者 / 频道：@shadcn
- 发布时间：2026-09-14 16:22:22 UTC（约 2026-09-15 00:22 CST）

## 要点

- @shadcn 发布 **shadcn/lint**：Agent-first 的 Tailwind / 设计系统 linter——你定义允许的组件、变体与主题规则；Agent 违规时错误信息会说明如何改回合规写法。
- 可动手仓库 `shadcn-ui/lint`；后续帖称已支持 Vue / Svelte（见落地链接）。
- 适合约束 codegen Agent 的 UI 输出；规则覆盖面与误报率 **待核实**。

## 落地链接（可选）

- 仓库：https://github.com/shadcn-ui/lint
- Vue/Svelte 更新帖：https://x.com/shadcn/status/2102408442086556147

## 价值判断

- 为什么值得记：可核作者帖 + 清晰 GitHub，补「Agent×设计系统护栏」工具；非纯营销。
- 风险 / 待核实：★约 2.8k（2026-09-26 页面计数）；与具体 Agent（Cursor/Claude Code 等）集成深度 **待核实**。

## 原文摘要（可选）

摘要：@shadcn 介绍 shadcn/lint，称可让 Agent 在违反设计系统规则时得到可执行的修复说明，并指向 GitHub。

## 与其他条目的关系（可选）

与已入库 UI/设计类 Skill（如 taste-skill、impeccable、ui-ux-pro-max）互补：本条是 **可运行的 lint 工具**，不是提示词 Skill 包。
