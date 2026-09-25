# SWE-Serve：NVIDIA 的推理服务工程 Agent 评测（53 任务）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/JiantaoJ/status/2102885056327090418
- 作者 / 频道：@JiantaoJ（NVIDIA）
- 发布时间：2026-09-23 22:17:21 UTC（约 2026-09-24 06:17 CST）

## 要点

- NVIDIA 研究员发布 **SWE-Serve**：从 SGLang 已合并改动抽出来的推理服务工程任务集，问的是 Agent 能不能改推理引擎并让服务真正跑起来。
- 官方仓 `NVIDIA/swe-serve` README 写明 53 个任务（GPU/CPU 都有），附排行榜与论文。任务在仓里，可克隆。
- 运行说明依赖已入库的 Harbor 作为执行器。本条记的是这套任务集，不是 Harbor 本体。

## 落地链接（可选）

- 仓库：https://github.com/NVIDIA/swe-serve
- 排行榜：https://research.nvidia.com/benchmarks/swe-serve
- 博客：https://developer.nvidia.com/blog/how-swe-serve-exposes-the-gap-between-local-tests-and-live-serving/
- 论文：https://arxiv.org/abs/2609.26777

## 价值判断

- 为什么值得记：新的、可下载的软件工程向评测任务集，场景是推理服务而不是通用 SWE-bench 题。
- 风险 / 待核实：NVIDIA/swe-serve ★15（2026-09-26 gh api）。榜上分数与「在线服务测试拉低通过率」等效果待核实。GPU 任务要 H100 级机器；完整跑通成本不低。执行器钉的是 Harbor 某个 git 版本，环境以 README 为准。

## 原文摘要（可选）

摘要：作者称 SWE-Serve 用 SGLang 真实工程改动做成任务，并指出在线服务测试和只跑本地测试结果不一样。

## 与其他条目的关系（可选）

避开 SWE-Bench Pro V2、Terminal-Bench、mini-SWE-agent 本体。与已入库 Harbor harness 的关系：本榜用 Harbor 跑任务，不要并成同一条。
