# MLPerf Training v6.1：首个 LLM 后训练（Agentic RL）基准

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/MLCommons/status/2103137660885774720
- 作者 / 频道：@MLCommons
- 发布时间：2026-09-24 15:01:07 UTC（约 2026-09-24 23:01 CST）

## 要点

- MLCommons 宣布 **MLPerf Training v6.1** 加入套件里第一个 LLM 后训练基准：用 agentic RL 让大开源权重模型修真实软件，按质量（帖称 pass@4）而不只按吞吐打分。
- 说明页给出任务代码目录 `mlcommons/training` 下的 `llm_post_training`。
- 这是训练/后训练基准的新任务定义，不是已入库的 SWE-Bench Pro、Terminal-Bench 或 τ2-bench。

## 落地链接（可选）

- 说明：https://mlcommons.org/2026/09/mlperf-training-llm-post-training/
- 代码：https://github.com/mlcommons/training/tree/master/llm_post_training

## 价值判断

- 为什么值得记：公开基准组织的新任务，代码目录可打开，补「评测」而不是再收一个厂商 MCP。
- 风险 / 待核实：mlcommons/training 整仓 ★1772（2026-09-26 gh api；非本任务单独仓）。帖中的模型规模、pass@4 与提交成绩待核实。MLPerf 提交流程重，不等于随手能跑的小数据集。

## 原文摘要（可选）

摘要：MLCommons 称 Training v6.1 新增 LLM 后训练基准，用 agentic RL 修软件，并按质量打分。

## 与其他条目的关系（可选）

同账号另有 Inference v6.1 成绩帖，本条只收后训练任务。非 SWE-Bench Pro V2 / Harbor / mini-SWE-agent。
