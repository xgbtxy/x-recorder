# BFCL V4 Agentic：Berkeley 函数调用 / Agent 工具评测（Web Search · Memory · Format）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/shishirpatil_/status/1946020561626546176
- 作者 / 频道：@shishirpatil_
- 发布时间：2025-07-18 01:33:51 UTC（约 2025-07-18 09:33 CST）

## 要点

- Berkeley Function-Calling Leaderboard 进入 **V4 Agentic**：在真实 Agent 设定下评测 tool-calling，含 **Web Search（多跳+故障恢复）**、**Memory**、**Format Sensitivity**。
- Web Search 轨故意注入 503/429/403 等常见访问错误，观察模型是否静默失败或可恢复（细节见系列博客）。
- 可动手：排行榜站点、HF 数据集、Gorilla 仓库 PR/代码；三篇技术博客可复现评测设定。

## 落地链接（可选）

- 公告帖：https://x.com/shishirpatil_/status/1946020561626546176
- 排行榜：https://gorilla.cs.berkeley.edu/leaderboard.html
- 博客（Web Search）：https://gorilla.cs.berkeley.edu/blogs/15_bfcl_v4_web_search.html
- 博客（Memory）：https://gorilla.cs.berkeley.edu/blogs/16_bfcl_v4_memory.html
- 博客（Format）：https://gorilla.cs.berkeley.edu/blogs/17_bfcl_v4_prompt_variation.html
- 代码 PR：https://github.com/ShishirPatil/gorilla/pull/1019

## 价值判断

- 为什么值得记：可复现的工具调用/Agent 评测基准，官方 X + 开源码；补已入库 SWE-Bench Pro / Terminal-Bench / τ2 / MCPMark 等之外的 function-calling 轴。
- 风险 / 待核实：ShishirPatil/gorilla ★13044（2026-09-26 gh api；整仓）；PR #1019 可开；当前榜名次与 Web Search 外部 API 复现波动待核实。

## 原文摘要（可选）

摘要：@shishirpatil_ 在 ICML 2025 语境下宣布 BFCL V4 Agentic，列 Web Search / Memory / Format 三轨并给博客与 PR。

## 与其他条目的关系（可选）

非 SWE-Bench Pro V2 / Terminal-Bench / τ2-bench / MCPMark / MLPerf / MentalHealthBench / VQ-bench / SWE-Serve。
