# North Small Translate：Cohere 开源机器翻译 MoE（218B-A25B）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/cohere/status/2098081558087270736
- 作者 / 频道：@cohere
- 发布时间：2026-09-10 16:09:58 UTC（约 2026-09-11 00:09 CST）

## 要点

- Cohere 官号发布 **North Small Translate**：专向机器翻译的开源权重 MoE，约 **218B 总参 / 25B 激活**，自称覆盖 **50+** 语种——WMT26 等自报分数 **待核实**。
- 模型卡写清：CC BY-NC 4.0（研究/非商用）+ Acceptable Use；上下文约 **16K in / 16K out**；提供 BF16 / FP8 / NVFP4 等量化卡页——商用需另谈许可。
- 可动手：HF `CohereLabs/North-Small-Translate-1.0`、Cohere 博客与文档、HF Space 试用；部署叙事含 Transformers / vLLM（同引擎 Day-0 扩散帖勿再拆）。

## 落地链接（可选）

- HF：https://huggingface.co/CohereLabs/North-Small-Translate-1.0
- 博客：https://cohere.com/blog/north-small-translate

## 价值判断

- 为什么值得记：官号可核的**新开源翻译专用族**（非通用 Command / North Code），HF 可下；补 Cohere North 系列的翻译产品轴。
- 风险 / 待核实：HF likes 约 53（2026-09-26）；WMT26/长文翻译自报、最低硬件与量化损失 **待核实**；非商用许可限制落地场景。

## 原文摘要（可选）

摘要：@cohere 从 Transformer 起源谈起，宣布 North Small Translate 开源机器翻译模型。

## 与其他条目的关系（可选）

同厂已入库 **Command-A-Plus**（企业 Agent 通用 MoE）与 **North-Mini-Code**（agentic coding MoE）；本条是 **North 族翻译专用轴**，勿与 Code / Command A+ 权重混淆。非 Qwen3.5 / GLM / Gemma 通用翻译用法帖。未开 Qwen3.8 / jina-v5-text / Granite Speech。
