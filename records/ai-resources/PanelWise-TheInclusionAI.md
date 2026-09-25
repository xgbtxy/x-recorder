# PanelWise：inclusionAI 开源多模型融合引擎（eval / 状态机双拓扑）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/TheInclusionAI/status/2091851247259443627
- 作者 / 频道：@TheInclusionAI
- 发布时间：2026-08-24 11:32:56 UTC（约 2026-08-24 19:32 CST）

## 要点

- inclusionAI 官号开源 **PanelWise**：把同一任务交给可配置「模型评审团」，融合互补判断，宣称可让廉价模型组合接近更强单模（效果 **待核实**）。
- 仓库提供两种执行拓扑：`--eval`（独立完整作答 → 评估 → 综合，偏调研问答）与 `--no-eval`（独立下一步提议 → 协调动作 → 共享可观察状态，偏编码等有状态任务）。
- 可动手：`panelwise run "..."`（Python 3.10+，Apache-2.0）；可自接 ChatClient / Executor。

## 落地链接（可选）

- 仓库：https://github.com/inclusionAI/PanelWise

## 价值判断

- 为什么值得记：可核官帖 + 可 clone 的开源引擎；轴心是「多模型聚合 / 深研与有状态任务拓扑」，补 Agent 编排工具而非再收一张榜单。
- 风险 / 待核实：推文偏概念演示，成本/延迟/胜率需自测；星数 **待核实**；与商业 multi-agent 产品边界需读 README。

## 原文摘要（可选）

摘要：@TheInclusionAI 发布 PanelWise，强调多模型互补融合，并给出 GitHub 仓库链接。

## 与其他条目的关系（可选）

同厂商已入库 Ling / Ming / LLaDA 等模型条；本条是 **编排/融合工具**，产品轴清晰可并存。非 DeepSeek Harness（禁开）或纯 serving 发版帖。
