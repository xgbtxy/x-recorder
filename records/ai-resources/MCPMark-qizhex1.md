# MCPMark：面向真实 MCP 使用的压力测试评测集

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/qizhex1/status/1960029790305763567
- 作者 / 频道：@qizhex1
- 发布时间：2025-08-25 17:21:32 UTC（约 2025-08-26 01:21 CST）

## 要点

- 作者宣布 **MCPMark**（与 @EvalSysOrg、@lobehub 合作）：用专家构造任务压力测试模型/Agent 在综合 MCP 场景下的工具使用。
- 帖称约 127 条高质量样本；覆盖 Notion、GitHub、Filesystem、Playwright（浏览器）、Postgres 等 MCP 环境；并给出初步 Pass@1 区间（数字待核实）。
- 可动手入口：网站与开源仓（可跑评测），不是纯营销长文。

## 落地链接（可选）

- 网站：https://mcpmark.ai/
- 仓库：https://github.com/eval-sys/mcpmark
- 论文线索：https://arxiv.org/abs/2509.24002 （与后续论文帖 status/1973374660919324795 同源，本条以发布帖为准）

## 价值判断

- 为什么值得记：可跑的 MCP 专用评测，补「工具调用/CRUD 闭环」维度，和纯 SWE/终端榜不同。
- 风险 / 待核实：Pass@1 与题量以站点/论文为准；eval-sys/mcpmark ★462（2026-09-26 gh api）；部分任务依赖外部 MCP/凭证，复现成本不低。

## 原文摘要（可选）

摘要：介绍 MCPMark 压力测试基准，给出任务规模、覆盖 MCP 类型与初步模型分数区间，并预告线程展开。

## 与其他条目的关系（可选）

- **非** SWE-Bench Pro V2 / mini-SWE-agent（软件工程补丁），**非** Terminal-Bench（终端操作），**非** τ2/τ³-bench（客户服务对话），**非** Harbor harness（评测脚手架/文档 MCP），**非** VQ-bench / SWE-Serve / MLPerf / MentalHealthBench / FineWeb / Stack / SmolDataEnvs。
- MCPMark 聚焦 **跨真实 MCP 服务器的综合工具使用与 CRUD 闭环**；若与 Harbor 同用，Harbor 是 harness，MCPMark 是任务集——可并列、勿合并。
