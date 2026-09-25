# Harbor：Agent eval / RL harness（新文档 + MCP）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-25
- **平台**：X
- **来源（必填）**：https://x.com/alexgshaw/status/2100296774955237438
- 作者 / 频道：@alexgshaw（Harbor / Terminal-Bench 共创）
- 发布时间：2026-09-16 18:52:27 UTC（约 2026-09-17 02:52 CST）

## 要点

- 作者发帖更新 **Harbor 文档**，点名此前未文档化的能力：模拟用户、streaming、regrade trials，并说可把文档/能力交给 coding agent 的 **MCP**。
- Harbor 定位：容器化 Agent 评测与优化 harness（Terminal-Bench 官方相关栈）；安装示例 `uv tool install harbor`，再 `harbor run --dataset … --agent …`。
- 文档站含 quick start、skills、simulate-a-user、regrade、stream 等可动手章节。

## 落地链接（可选）

- 文档：https://docs.harborframework.com/
- 仓库：https://github.com/laude-institute/harbor
- 安装说明：https://docs.harborframework.com/getting-started/installation

## 价值判断

- 为什么值得记：eval harness 线可动手入口，覆盖 Claude Code / Codex 等 agent 评测，非已入库 Omnigent meta-harness。
- 风险 / 待核实：星数/效果待核实；云端并行需第三方 sandbox/账单；帖文偏文档发布，完整 MCP 配置以文档为准。

## 原文摘要（可选）

摘要：Alex Shaw 宣布 Harbor 新文档上线，并提示可用 MCP 给 coding agent。
