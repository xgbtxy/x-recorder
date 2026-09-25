# LFM2.5-2.6B：Liquid AI 端侧开源权重 Agent 小模型

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/liquidai/status/2084640701669613906
- 作者 / 频道：@liquidai
- 发布时间：2026-08-04 14:00:48 UTC（约 2026-08-04 22:00 CST）

## 要点

- Liquid AI 官方发布 **LFM2.5-2.6B**：宣传为可端侧运行的 agentic 小模型（规划、工具调用、多步任务；数据不出设备等叙事以原文为准）。
- 帖内规格线索：约 34T 预训练 token、混合架构、128K 上下文；许可称 **LFM2 open-weight license**（以模型卡为准）；并给出若干基准对比数字（效果待核实）。
- 可动手：Hugging Face `LiquidAI/LFM2.5-2.6B` 权重；官方博客有部署说明；社区路径含 Transformers / vLLM / llama.cpp / SGLang 等（以各自文档为准）。

## 落地链接（可选）

- 公告帖：https://x.com/liquidai/status/2084640701669613906
- 权重：https://huggingface.co/LiquidAI/LFM2.5-2.6B
- 博客：https://www.liquid.ai/blog/lfm2-5-2-6b
- HF 组织：https://huggingface.co/LiquidAI

## 价值判断

- 为什么值得记：官方可核的端侧/小参数开源权重，补已入库大模型族之外的 on-device Agent 口味；HF 可下。
- 风险 / 待核实：跑分对比、许可商用边界、真实端侧延迟/功耗待核实；HF likes 780、downloads ~9.2万（LiquidAI/LFM2.5-2.6B，2026-09-26 HF api 复核）；跑分/许可/端侧实测效果待核实。

## 原文摘要（可选）

摘要：@liquidai 宣布 LFM2.5-2.6B 开源权重，强调端侧 agent 能力与若干基准领先宣传。

## 与其他条目的关系（可选）

非 Gemma 4 / Ministral / Muse 等已入库小模型条。SGLang 等引擎的「Day-0 支持 LFM」帖勿再拆开引擎扩散条。
