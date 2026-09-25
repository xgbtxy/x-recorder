# Nemotron 3.5 Lightning：NVIDIA 开源 30B MoE（约 3B 激活）Agent 执行向

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/NVIDIAAI/status/2087162151995629926
- 作者 / 频道：@NVIDIAAI
- 发布时间：2026-08-11 13:00:09 UTC（约 2026-08-11 21:00 CST）

## 要点

- NVIDIA AI 官号发布 **Nemotron 3.5 Lightning**：开源约 30B MoE、宣称约 3B 激活，定位 always-on Agent 的高吞吐专用执行步；自报相对同体量模型最高约 4× 输出速度——速度/效果 **待核实**。
- 线程叙事含 PinchBench 准确率/吞吐对比、NeMo 域适配、以及配套开源路由库 NeMo Switchyard / RL 数据集——配套条目可另开，本条以**模型权重**为主。
- 可动手：HF（`nvidia/NVIDIA-Nemotron-3.5-Lightning-30B-A3B-BF16` / NVFP4）、build.nvidia.com 模型页、NVIDIA 博客。

## 落地链接（可选）

- HF BF16：https://huggingface.co/nvidia/NVIDIA-Nemotron-3.5-Lightning-30B-A3B-BF16
- HF NVFP4：https://huggingface.co/nvidia/NVIDIA-Nemotron-3.5-Lightning-30B-A3B-NVFP4
- 产品页：https://build.nvidia.com/nvidia/nemotron-3-5-lightning-30b-a3b
- 博客：https://blogs.nvidia.com/blog/nemotron-lightning-switchyard-rtx-dgx/

## 价值判断

- 为什么值得记：官号可核的**新开源 Agent 向 MoE 族**（非已入库 Muse-Glimmer / Cosmos-3 / gpt-oss 等），HF 可下；补小激活、高吞吐执行模型入口。
- 风险 / 待核实：HF likes BF16 约 221 / NVFP4 约 435（2026-09-26）；许可以卡页为准；PinchBench 等自报分数 **待核实**；勿收同引擎 serving Day-0 / 第三方量化扩散帖；勿与已入库 NVIDIA-Verified Agent Skills 混淆。

## 原文摘要（可选）

摘要：@NVIDIAAI 宣布 Nemotron 3.5 Lightning（30B MoE / ~3B 激活），强调 Agent 高通量执行与速度叙事。

## 与其他条目的关系（可选）

非 Muse-Glimmer-30B / Cosmos-3 / nvidia-verified-agent-skills；本条是 **Nemotron 3.5 Lightning 开源权重**。非 vLLM/SGLang Day-0。未开 Qwen3.8。
