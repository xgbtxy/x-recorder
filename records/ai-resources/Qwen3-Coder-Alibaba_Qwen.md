# Qwen3-Coder：开源 Agentic 代码模型 + Qwen Code CLI

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/Alibaba_Qwen/status/1947766835023335516
- 作者 / 频道：@Alibaba_Qwen
- 发布时间：2025-07-23 05:12 CST（UTC+8）

## 要点

- 官方发布 **Qwen3-Coder-480B-A35B-Instruct**：480B MoE（约 35B 激活），原生约 256K 上下文并可外推到约 1M；面向 agentic coding，宣称在开源模型中于 SWE-bench Verified 等基准靠前（效果待核实）。
- 同步开源命令行 **Qwen Code**（由 Gemini Code 分支定制提示与函数调用协议），用于本地/工作流里驱动该模型做 agentic coding。
- 权重与博客可开：Hugging Face 模型页与 Qwen 博客成套入口，可下载权重，非纯 API 营销。

## 落地链接（可选）

- 模型：https://huggingface.co/Qwen/Qwen3-Coder-480B-A35B-Instruct
- 博客：https://qwenlm.github.io/blog/qwen3-coder/
- 仓库线索：https://github.com/QwenLM/Qwen3-Coder
- Chat：https://chat.qwen.ai/

## 价值判断

- 为什么值得记：可下权重的开源 coding/agent 模型 + 可装 CLI，符合「开源模型 / 可动手」优先；与已入库 Qwen-Image-2.1 图像线不同。
- 风险 / 待核实：SWE-bench 等分数、本地显存与推理栈兼容度待核实；HF likes 1373、downloads ~3.5万（2026-09-26 HF api）；QwenLM/Qwen3-Coder ★16843（gh api）；大 MoE 权重体积与合规许可以 HF/仓库为准。

## 原文摘要（可选）

摘要：官方称 Qwen3-Coder 开源发布，并附带 Qwen Code CLI，强调 agentic coding 与 SWE-bench Verified 表现。

## 与其他条目的关系（可选）

非 DeepSeek-V4 / Gemma 4 / Muse Glimmer 等已避开清单；非 Qwen-Image 图像权重条。本条为代码 Agent 开源模型入口。
