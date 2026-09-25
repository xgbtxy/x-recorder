# LFM2.5-VL-3B：Liquid AI 开源轻量视觉-语言模型

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/liquidai/status/2087539876929441983
- 作者 / 频道：@liquidai
- 发布时间：2026-08-12 14:01:05 UTC（约 2026-08-12 22:01 CST）

## 要点

- Liquid AI 官号发布 **LFM2.5-VL-3B**：轻量 VLM，宣称面向屏幕/文档/物理世界理解，含坐标 grounding、读字读图、图文工具调用——效果 **待核实**。
- 架构线索：基于已入库 **LFM2.5-2.6B** 基座 + SigLIP2 约 400M NaFlex 视觉编码器；给出 ScreenSpot / RealWorldQA / TextVQA 等对比数字——分数 **待核实**。
- 可动手：HF `LiquidAI/LFM2.5-VL-3B`、官方博客。

## 落地链接（可选）

- HF：https://huggingface.co/LiquidAI/LFM2.5-VL-3B
- 博客：https://www.liquid.ai/blog/lfm2-5-vl-3b

## 价值判断

- 为什么值得记：官号可核的**同厂视觉产品轴**（相对已入库文本小模型 LFM2.5-2.6B），HF 可下；补端侧/轻量 VLM 入口。
- 风险 / 待核实：HF likes 约 213（2026-09-26）；许可以卡页为准；自报基准 **待核实**；勿收引擎 Day-0 扩散帖。

## 原文摘要（可选）

摘要：@liquidai 宣布 LFM2.5-VL-3B，强调屏幕/文档理解与工具调用，并给出若干相对同量级模型的对比数字。

## 与其他条目的关系（可选）

同厂已入库 **LFM2.5-2.6B**（文本/端侧 Agent 小模型）；本条是 **VL/多模态产品轴**，勿与基座文本条合并或再拆小步迭代。非 InternVL-U / LensVLM-9B / Gemma-4 / NeoMME。未开 Qwen3.8 / jina-v5-text。
