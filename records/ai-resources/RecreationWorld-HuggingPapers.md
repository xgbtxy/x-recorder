# RecreationWorld：混合 Computer-Use Agent 的可验证「复刻」环境与 RecreationBench

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/HuggingPapers/status/2102068609396736180
- 作者 / 频道：@HuggingPapers（社区转、非官宣）
- 发布时间：2026-09-21 16:13:05 UTC（约 2026-09-22 00:13 CST）

## 要点

- 社区日报转介：Qwen 团队开源 **RecreationWorld**——五平台沙盒，让混合 computer-use Agent 在「探索参考应用 → 编码实现 → 视觉/程序验证」循环里复刻真实应用。
- 配套 **RecreationBench**（约 250 道 hold-out 任务，数字 **待核实**），用参考程序与视觉断言打分，而非比源码相似度。
- 可动手入口：GitHub `QwenLM/RecreationWorld`、HF `Qwen/RecreationBench`、站点 recreation-bench.cc（星数/下载 **待核实**）。未见 @Alibaba_Qwen 同链官帖，故标社区转。

## 落地链接（可选）

- 仓库：https://github.com/QwenLM/RecreationWorld
- 数据集：https://huggingface.co/datasets/Qwen/RecreationBench
- 站点：https://recreation-bench.cc/
- 论文：https://arxiv.org/pdf/2609.22000

## 价值判断

- 为什么值得记：可核社区出处 + 官方组织仓/数据集可开；补「GUI+编码+自验证」长程环境轴，优先于纯榜分数营销。
- 风险 / 待核实：来源为 @HuggingPapers 社区转；榜上成本/分数以 README 表为准；跑通五平台依赖与算力成本可能较高。

## 原文摘要（可选）

摘要：@HuggingPapers 称阿里 Qwen 团队在 HF 放出 RecreationWorld，面向混合 computer-use Agent 的五平台可验证复刻环境。

## 与其他条目的关系（可选）

相对已入库 Terminal-Bench / SWE-Serve / Toolathlon / MobileWorld（含在 Qwen Intelligence 条）：本条聚焦 **复刻运行中应用并做程序+视觉验收**，不是终端补丁或手机跨 App 操作榜。非 Qwen3.8 旗舰聊天模型发版帖。
