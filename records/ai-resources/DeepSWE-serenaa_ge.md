# DeepSWE：原创长程工程任务的 Coding Agent 评测轴

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/serenaa_ge/status/2059308218564890875
- 作者 / 频道：@serenaa_ge（Datacurve）
- 发布时间：2026-05-26 16:18:34 UTC（约 2026-05-27 00:18 CST）

## 要点

- 发布 **DeepSWE**：面向 coding agent 的长程软件工程基准——**113** 题、跨 **91** 个活跃仓库、5 语言（TS/Go/Python/JS/Rust）；任务为**原创撰写**而非从已合并 PR 挖掘，降低污染与「背答案」风险。
- 强调短/自然提示 + **行为向手写 verifier**（相对 SWE-Bench Pro 审计中的误判率自称更低，**具体数字待核实**）；统一 harness 为 `mini-swe-agent`。
- 可动手：GitHub `datacurve-ai/deep-swe`、站点与博客、可自跑 agent。

## 落地链接（可选）

- 公告帖：https://x.com/serenaa_ge/status/2059308218564890875
- 仓库：https://github.com/datacurve-ai/deep-swe
- 站点：https://deepswe.datacurve.ai/
- 博客：https://deepswe.datacurve.ai/blog/deepswe
- 论文 HTML：https://arxiv.org/html/2607.07946

## 价值判断

- 为什么值得记：新评测轴——**抗污染、原创长程 SWE**，与已入库 SWE-Bench Pro V2 / Terminal-Bench / τ2 / BFCL / VQ / MLPerf / MentalHealth / MCPMark / MLE-bench / GameDevBench 不重复。
- 风险 / 待核实：仓库 ★约 1753（2026-09-26 `gh api`）；公开榜面分数与 SWE-Bench Pro 对照仍待核对；固定 harness 可能低估「原生产品脚手架」；仅覆盖 ≥500★ 开源仓与五语言。

## 原文摘要（可选）

摘要：@serenaa_ge 宣布 DeepSWE——用原创长程工程任务拉开公开榜面上「看起来接近」的 frontier coding agent 差距。

## 与其他条目的关系（可选）

非 SWE-Bench Pro V2 / Terminal-Bench 4.0 / Harbor / mini-SWE-agent 条目本身；本条是 **评测集**，mini-swe-agent 仅作统一跑法提及。
