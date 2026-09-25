# gpt-oss：OpenAI 开源权重推理模型（120B / 20B）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/ArtificialAnlys/status/1952887733803991070
- 作者 / 频道：@ArtificialAnlys
- 发布时间：2025-08-06 08:21 CST（UTC+8）

## 要点

- 第三方评测账号汇总：**OpenAI gpt-oss-120b** 与 **gpt-oss-20b** 开源权重已发布（Apache 2.0 线索见官网/HF）；MoE 结构，原生 MXFP4 等部署友好格式，可自托管。
- 帖中给出独立 Intelligence Index 等对比数字（效果与榜单待核实）；强调 120B 可在单卡级场景部署的体积线索。
- 可动手入口：Hugging Face `openai/gpt-oss-120b`（及 20B）权重页；OpenAI 介绍文 `introducing-gpt-oss` 可作官方背景核对。

## 落地链接（可选）

- HF 120B：https://huggingface.co/openai/gpt-oss-120b
- 官网介绍：https://openai.com/index/introducing-gpt-oss/
- 模型卡线索：https://openai.com/index/gpt-oss-model-card/

## 价值判断

- 为什么值得记：美国实验室可下权重开源推理模型，补开源模型面；未在已避开清单（非 DeepSeek-V4 / Gemma 4 等）。
- 风险 / 待核实：来源帖为第三方评测而非 @OpenAI 官宣帖；榜单分数与「最强美系开源」表述待核实；HF likes 5305、downloads ~462万（gpt-oss-120b，2026-09-26 HF api）；Harmony 响应格式与本地栈兼容以官方文档为准。

## 原文摘要（可选）

摘要：Artificial Analysis 称 OpenAI 已开源 gpt-oss-120b/20b，并发布独立评测对比与部署体积观察。

## 与其他条目的关系（可选）

非 Claude Opus 5.5 闭源产品条；与已入库 llama.cpp 运行时条目互补（模型权重 vs 推理引擎）。若后续补到 OpenAI 官方 status，可替换来源字段。
