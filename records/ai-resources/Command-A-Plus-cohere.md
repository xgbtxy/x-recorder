# Command A+：Cohere 开源 MoE（218B-A25B）企业 Agent 模型

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/cohere/status/2057120818551734589
- 作者 / 频道：@cohere
- 发布时间：2026-05-20 15:26:37 UTC（约 2026-05-20 23:26 CST）

## 要点

- Cohere 发布 **Command A+**（`command-a-plus-05-2026`）：稀疏 MoE，约 **218B 总参 / 25B 激活**；宣传面向推理、多模态、多语、工具调用等企业 Agent 负载。
- 许可称 **Apache 2.0**；博客写 128K 输入、文本+图像输入、48 语等（规格以模型卡为准）；强调低比特量化与尽量少卡部署。
- 可动手：Hugging Face 权重（BF16 / FP8 / W4A4 等）；博客写支持 vLLM、Transformers；另有 Model Vault / API（托管非本批重点）。

## 落地链接（可选）

- 公告帖：https://x.com/cohere/status/2057120818551734589
- 博客：https://cohere.com/blog/command-a-plus
- HF（例）：https://huggingface.co/CohereLabs/command-a-plus-05-2026-bf16
- 文档：https://docs.cohere.com/docs/command-a-plus

## 价值判断

- 为什么值得记：官方开源权重的新模型族（非已入库 gpt-oss / DeepSeek / Qwen 等），HF 可下，企业 Agent 口味清晰。
- 风险 / 待核实：HF likes 145、downloads ~4.1万（command-a-plus-05-2026-bf16，2026-09-26 HF api）；τ²/Terminal-Bench 等博客数字与最低硬件/量化损失待核实；X 帖极短，细节以博客/模型卡为准。

## 原文摘要（可选）

摘要：@cohere 宣布 Command A+ 开源，强调强性能与尽量少硬件可跑。

## 与其他条目的关系（可选）

非 gpt-oss / DeepSeek-V4 / Mistral 3；评测对比中出现的 τ2 / Terminal-Bench 已另有条目，勿因同数字再开引擎或榜单扩散条。
