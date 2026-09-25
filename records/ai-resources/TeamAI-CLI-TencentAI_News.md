# TeamAI-CLI：腾讯开源「团队知识 → 多 Agent 共用手册」CLI

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/TencentAI_News/status/2102991196788490264
- 作者 / 频道：@TencentAI_News
- 发布时间：2026-09-24 05:19:07 UTC（约 2026-09-24 13:19 CST）

## 要点

- 腾讯官号跟进开源 **TeamAI-CLI**：把团队 skills / rules / docs / MCP / hooks 收成 **一个 git 仓库**，让 Claude Code、Codex、Cursor、OpenCode、CodeBuddy、WorkBuddy 以及本周新增的 **Kiro、GitHub Copilot、Oh My Pi** 等从同一本手册开工。
- 机制（开源帖摘要）：MR 合入后 hook 推到各人下次会话；learnings 按真实使用累积置信度，强弱分流；本周补充「按角色/项目 scoped」的 rules/agents/mcp/hooks，以及 learnings 独立分支。
- 可动手入口：GitHub `Tencent/teamai-cli`（星数 **待核实**，抓取时约 5k）。欢迎 PR 扩展未覆盖 Agent。

## 落地链接（可选）

- 仓库：https://github.com/Tencent/teamai-cli

## 价值判断

- 为什么值得记：官帖 + 高星开源仓；轴是「团队级 Agent 知识/技能治理」，不是又一款聊天模型。
- 风险 / 待核实：星数/采用面 **待核实**；各宿主 Agent 的实际对接深度以 README 为准；与纯单机 Skill 包不同，偏组织协作。

## 原文摘要（可选）

摘要：@TencentAI_News 称 TeamAI 开源两周后手册已覆盖更多 Agent（含 Kiro/Copilot/Oh My Pi），并指向 github.com/Tencent/teamai-cli。

## 与其他条目的关系（可选）

同源开源官宣另有 2026-09-07 帖 https://x.com/TencentAI_News/status/2096876836898865165；本条用近两周跟进帖作出处。勿与已入库各类单店 Agent Skill / MCP 目录混为同一项：本条是 **多 Agent 共用的 git 手册 + 置信度学习**。
