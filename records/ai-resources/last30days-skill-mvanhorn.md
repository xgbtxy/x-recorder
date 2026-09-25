# last30days：跨平台「近 30 天舆情/人物」Agent Skill（含 Codex）

- 状态：已核（仓库可开；星数/效果待核实）
- 分类：ai-resources
- 记录日期：2026-09-25
- **来源 X（必填）**：https://x.com/mvanhorn/status/2092629365045559547
- 作者：@mvanhorn
- 推文时间：2026-08-26 15:04:54 UTC（约 2026-08-26 23:04 CST）

## 关键点

- 作者长文《Every Grok Bot Hack I Know》中自荐并链出其开源 skill：`mvanhorn/last30days-skill`（文中亦提及星数，统一「待核实」）。
- Skill 并行检索 Reddit / X / YouTube / HN / Polymarket / GitHub 等，按真实互动打分后汇总「近况」简报；README 提供 Claude Code 市场安装，以及 `npx skills add mvanhorn/last30days-skill`（写明适用于 Codex、Cursor、Copilot、Gemini CLI、OpenClaw 等 Agent Skills 宿主）。
- 零配置可用部分源；X/YouTube 等需自备 key 或会话。

## 落地链接（可选）

- 仓库：https://github.com/mvanhorn/last30days-skill
- Skill 规格：仓库内 `skills/last30days/SKILL.md`
- 标准说明：https://agentskills.io

## 价值判断

- 为什么值得记：同时覆盖 agent skills / Claude Code skill / Codex skill / OpenClaw 安装路径，可直接 `npx skills add` 动手。
- 风险 / 待核实：来源帖主叙事是 Grok Bot 技巧长文，last30days 为文中自荐项目而非单独发布帖；星数、榜单徽章「待核实」；多平台抓取涉及账号/ToS/密钥管理。

## 原文摘要（可选）

摘要：X Article 讲 Grok Bot 个人工作流；正文点名自建 last30days（并给出 GitHub），可装进 bot 做研究向 skill。
