# Lark CLI Skills：飞书/Lark 官方可装 Agent Skills（文档·日历·消息等）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/Larksuite/status/2038789640346624457
- 作者 / 频道：@Larksuite
- 发布时间：2026-03-31 01:25:03 UTC（约 2026-03-31 09:25 CST）

## 要点

- Lark/飞书官方开源 **Lark CLI**，并附带可装 Agent Skills：一键后 Agent 可直接操作日历、群聊、文档等（以仓库 skill 目录为准）。
- 安装入口：`npm install -g @larksuite/cli`；Skills：`npx skills add https://github.com/larksuite/cli -y -g`（或 `npx skills add larksuite/cli`，以 README 为准）。
- 兼容 Claude Code / Codex / Cursor 等；覆盖 Docs / Base / Calendar / Messenger / Mail 等域（博客与 README 列全量）。

## 落地链接（可选）

- 公告帖：https://x.com/Larksuite/status/2038789640346624457
- 仓库：https://github.com/larksuite/cli
- 博客：https://www.larksuite.com/en_us/blog/lark-cli
- skills.sh：https://www.skills.sh/（目录内可见 lark-doc 等）

## 价值判断

- 为什么值得记：垂直协作套件可装 Skills，落地命令清晰；补已入库 Elastic / Vercel / Remotion / anthropics / ECC 等之外的飞书/Lark 办公域。
- 风险 / 待核实：larksuite/cli ★17460（2026-09-26 gh api）；需 OAuth / 权限授权，企数与审计策略自负；Skill 触发质量与飞书/Lark 租户差异待实测。

## 原文摘要（可选）

摘要：@Larksuite 宣布 Lark CLI 开源，强调一装即让 Agent 直连日历/群聊/文档，并给 npm 与 GitHub。

## 与其他条目的关系（可选）

非 Slack/Notion/Linear 等 MCP 条；非 Google Workspace CLI Skills；非已入库 Elastic Agent Skills。
