# Terminal-Bench 4.0：持续演进的终端 Agent 基准（Harbor Hub 数据集）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/terminalbench/status/2093593947654533349
- 作者 / 频道：@terminalbench
- 发布时间：2026-08-29 06:57:48 UTC（约 2026-08-29 14:57 CST）

## 要点

- 官方账号宣布 **Terminal-Bench 4.0** 发布；定位为持续更新的终端 Agent 能力基准（continuous benchmark）。
- 任务集托管在 Harbor Hub（`terminal-bench/terminal-bench`），可用 Harbor 运行：`uv tool install 'harbor[modal]'` 后 `harbor run -d terminal-bench/terminal-bench@latest …`。
- 仓库：`harbor-framework/terminal-bench`；站点 https://www.tbench.ai/ 。相对已入库的 **Harbor harness 文档帖**，本条记的是 **基准数据集/版本发布本身**。

## 落地链接（可选）

- 仓库：https://github.com/harbor-framework/terminal-bench
- 站点：https://www.tbench.ai/
- Harbor Hub 数据集：https://hub.harborframework.com/datasets/terminal-bench/terminal-bench

## 价值判断

- 为什么值得记：可下载/可跑的 Agent 评测任务集新版本，落地路径清晰。
- 风险 / 待核实：星数约 773（harbor-framework/terminal-bench，2026-09-26 核）；跑评测依赖 Harbor/沙箱与可选 Modal 账单；效果数字以官方 leaderboard 为准，不采信转述分数。

## 原文摘要（可选）

摘要：@terminalbench 短帖宣布 Terminal-Bench 4.0 上线。

## 与其他条目的关系（可选）

参照已核 `harbor-docs-mcp-alexgshaw`（harness）；本条为 TB 4.0 基准发布，非同仓重复。
