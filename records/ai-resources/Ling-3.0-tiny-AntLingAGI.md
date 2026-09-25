# Ling-3.0-tiny：蚂蚁 Ling 端侧混合推理小 MoE（开源权重）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/AntLingAGI/status/2085432364189335884
- 作者 / 频道：@AntLingAGI
- 发布时间：2026-08-06 18:26:35 UTC（约 2026-08-07 02:26 CST）

## 要点

- Ant Ling 宣布 **Ling-3.0-tiny**：约 **7.9B 总参 / 1.3B 激活** 的原生混合推理 MoE，面向真实任务、数学、指令跟随与资源敏感部署。
- 后续已放出 BF16 / FP8 / INT4 等开源权重（以 HF 卡片为准）；可动手入口为 Hugging Face `inclusionAI/Ling-3.0-tiny`（及 GGUF 等衍生，星数/下载 **待核实**）。
- 产品轴是 **端侧/小算力 tiny**，与已入库 flash-Fin（金融）/ flash-VL（多模态）清晰区分。

## 落地链接（可选）

- 模型：https://huggingface.co/inclusionAI/Ling-3.0-tiny
- 组织页：https://huggingface.co/inclusionAI

## 价值判断

- 为什么值得记：可核官帖 + HF 权重；补齐 Ling-3.0 家族「tiny 端侧」缺口，便于对照 flash 域增强变体。
- 风险 / 待核实：Intelligence/Agentic 指数与手机侧延迟数字以 Artificial Analysis / 官方后续帖为准；许可与商用条款以模型卡为准；发帖偏早但仓库此前未入库。

## 原文摘要（可选）

摘要：@AntLingAGI 发布 Ling-3.0-tiny（7.9B/1.3B 激活）混合推理小 MoE，强调少算力多智能。

## 与其他条目的关系（可选）

已入库 **Ling-3.0-flash-Fin**、**Ling-3.0-flash-VL** 同属 Ling-3.0；本条是 **tiny 端侧通用推理**，用关系节区分规模与场景，勿与 Fin/VL 合并。非 Qwen3.8 / MiniCPM5 等他厂小模。
