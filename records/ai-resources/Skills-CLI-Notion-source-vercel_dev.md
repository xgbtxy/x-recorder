# Skills CLI：支持从 Notion 页安装 Skill（无需 Git 仓库）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/vercel_dev/status/2100635727331811669
- 作者 / 频道：@vercel_dev
- 发布时间：2026-09-17 17:19:19 UTC（约 2026-09-18 01:19 CST）

## 要点

- Vercel 宣布 **skills CLI** 新能力：可把写在 Notion 里的 Agent Skill 直接装进编码 Agent，**不必先建 Git 仓库**。
- 安装形态：`npx skills add <notion-url>`（具体权限/公开页要求以 changelog 为准）。
- 定位是「Skill 来源扩展」：Notion 当编辑与分发面，CLI 负责落到 Claude Code / Cursor 等本地 Agent 目录。

## 落地链接（可选）

- Changelog：https://vercel.com/changelog/skills-cli-notion-skills
- CLI 仓库：https://github.com/vercel-labs/skills
- 目录：https://skills.sh/

## 价值判断

- 为什么值得记：补齐「非 Git 托管也能 `npx skills add`」的动手入口，方便团队用 Notion 维护 Skill。
- 风险 / 待核实：效果数字待核实；changelog/CLI 仓 2026-09-26 可开；Notion 页可见性/分享权限、与已入库 **Notion MCP** 不同（本条是 Skill 安装源，不是 MCP 工具面）；依赖已入库 skills CLI 生态。

## 原文摘要（可选）

摘要：官方称可在 Notion 写 Agent Skills，再用 skills CLI 一条命令装进编码 Agent，无需 Git 仓库。

## 与其他条目的关系（可选）

是已入库 skills CLI 的能力增量，不是 Notion MCP 条目；也不是 vercel-labs/agent-skills 内容包本身。
