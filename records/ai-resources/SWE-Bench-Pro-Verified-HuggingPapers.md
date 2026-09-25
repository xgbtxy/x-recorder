# SWE-Bench Pro Verified：OpenCompass 核实版软件工程 Agent 评测集

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/HuggingPapers/status/2098142214450782282
- 作者 / 频道：@HuggingPapers（社区转、非官宣）
- 发布时间：2026-09-10 20:11:00 UTC（约 2026-09-11 04:11 CST）

## 要点

- HuggingPapers 转介 OpenCompass 发布的 **SWE-Bench Pro Verified**：对 SWE-Bench Pro 做核实与去噪，缓解 reward hacking / 题目质量问题，并称据此重测后前沿模型分数显著低于先前报道（数字 **待核实**）。
- 可动手入口：Hugging Face 数据集 `opencompass/SWEBench-Pro-Verified`；评测基础设施见 `open-compass/AgentCompass`（EMNLP 2026 相关）。下载量/星数 **待核实**。

## 落地链接（可选）

- 数据集：https://huggingface.co/datasets/opencompass/SWEBench-Pro-Verified
- 评测仓：https://github.com/open-compass/AgentCompass
- 论文页（arXiv）：https://arxiv.org/html/2609.08149

## 价值判断

- 为什么值得记：可下载核实版题集 + 开源评测基建，补「SWE-Bench Pro 可信度校准」轴。
- 风险 / 待核实：来源为社区转帖非 OpenCompass 官号；与 Scale 官方 Pro V2 题集关系需对照说明，分数不可直接横比；效果数字 **待核实**。

## 原文摘要（可选）

摘要：@HuggingPapers 称 OpenCompass 放出 SWE-Bench Pro 核实版，修复奖励作弊与题目质量问题后，前沿模型成绩更低。

## 与其他条目的关系（可选）

与已入库 **SWE-Bench Pro V2（@scale_AI）** 同属软件工程 Agent 评测，但本条是 **OpenCompass 核实/去噪版题集与 AgentCompass 基建**，不是 Scale 刷新的公开 split；社区转、非官宣。
