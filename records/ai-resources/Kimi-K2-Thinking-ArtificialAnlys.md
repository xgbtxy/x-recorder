# Kimi K2 Thinking：开源权重推理变体（约 1T / 32B 激活）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/ArtificialAnlys/status/1986541785511043536
- 作者 / 频道：@ArtificialAnlys
- 发布时间：2025-11-07 05:10 CST（UTC+8）

## 要点

- 报道 **MoonshotAI Kimi K2 Thinking**：Kimi K2 家族的推理（thinking）变体，约 1T 总参、约 32B 激活，开源权重可下。
- 帖中强调 agentic / 工具使用向评测（如 τ²-Bench Telecom 等，分数待核实），并相对此前 K2 Instruct 非思考版形成能力差分。
- 落地以 Hugging Face `moonshotai/Kimi-K2-Thinking` 为准；可与 vLLM / SGLang 等自托管路径对照官方文档。

## 落地链接（可选）

- HF：https://huggingface.co/moonshotai/Kimi-K2-Thinking
- 系列说明线索：https://www.kimi.ai/blog/kimi-k2

## 价值判断

- 为什么值得记：可下权重的大规模开源推理模型，批内换「开源模型」角度；未命中避开清单中的具体型号。
- 风险 / 待核实：来源为第三方评测帖；τ² 等分数与「领先开源」表述待核实；HF likes 1715、downloads ~6.5万（2026-09-26 HF api）；许可（含商业条款）与显存门槛以 HF/官方为准。

## 原文摘要（可选）

摘要：Artificial Analysis 称 Moonshot 发布 Kimi K2 Thinking 开源权重推理模型，并给出 agentic 评测观察。

## 与其他条目的关系（可选）

评测名 τ² 已有入库榜单条，本条只收模型权重入口，不另开评测条。非 DeepSeek-V4 / Muse Glimmer 等已避开型号。
