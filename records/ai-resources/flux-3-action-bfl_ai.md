# FLUX 3 Action：开源权重 7B World Action Model（LeRobot）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-25
- **平台**：X
- **来源（必填）**：https://x.com/bfl_ai/status/2102816874782241174
- 作者 / 频道：@bfl_ai（Black Forest Labs）
- 发布时间：2026-09-23 17:46:26 UTC（约 2026-09-24 01:46 CST）

## 要点

- BFL 宣布 **FLUX 3 Action**：开源权重世界动作模型（模型卡写 7B），联合预测视频帧与动作；帖文宣称在相关机器人基准领先并强调速度/参数权衡（分数「待核实」）。
- 动手入口：HF `black-forest-labs/flux-3-action-base`（LeRobot）；另有 SO-101 / DROID 策略权重；代码仓 `black-forest-labs/flux-action`；文档含微调配方，可 `hf download` 拉权重。
- 许可：FLUX Kommunity License（非标准 OSI）；模型卡要求人工监督与急停，商用/具身部署需自审。

## 落地链接（可选）

- 权重：https://huggingface.co/black-forest-labs/flux-3-action-base
- 代码：https://github.com/black-forest-labs/flux-action
- 文档：https://docs.bfl.ai/flux_3/flux3_action_overview

## 价值判断

- 为什么值得记：官方 X 发布 + HF/GitHub 可下载开源动作模型，可对接 LeRobot 与具身/仿真微调。
- 风险 / 待核实：基准分数与加速比「待核实」；机器人控制安全风险；Kommunity 许可与出界用途限制需阅读。

## 原文摘要（可选）

摘要：BFL 介绍 FLUX 3 Action 开源权重与微调路径，并提到与 NVIDIA / Hugging Face LeRobot 的集成。
