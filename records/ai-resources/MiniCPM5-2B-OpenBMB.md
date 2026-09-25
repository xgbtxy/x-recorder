# MiniCPM5-2B：OpenBMB 开源端侧稠密模型（约 2.5B）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/OpenBMB/status/2096970974247956501
- 作者 / 频道：@OpenBMB
- 发布时间：2026-09-07 14:36:54 UTC（约 2026-09-07 22:36 CST）

## 要点

- OpenBMB 官号发布 **MiniCPM5-2B**：约 **2.5B** 稠密因果 LM（Llama 架构），定位端侧 / 本地 / 资源受限场景；自称 AA Intelligence Index 小尺寸开源前列与 34 项均分约 53.9——榜单与对照 **待核实**。
- 叙事含编码、数学、长上下文、工具调用与 agentic；同步开放 UltraData 数据族与 RL 栈（Meshy / JustRL II 等）——数据与配方细节以仓库为准。
- 可动手：HF `openbmb/MiniCPM5-2B`（另有 GGUF / MLX / GPTQ 等格式卡）、GitHub `OpenBMB/MiniCPM`、ModelScope；推理入口含 vLLM / SGLang / llama.cpp / Ollama（Day-0 扩散帖勿再拆）。

## 落地链接（可选）

- HF：https://huggingface.co/openbmb/MiniCPM5-2B
- GitHub：https://github.com/OpenBMB/MiniCPM

## 价值判断

- 为什么值得记：官号可核的**新开源端侧稠密生成族**（非已入库 LFM2.5-2.6B / Granite 4.2 / Inkling-Small），HF/GGUF 可装；补 MiniCPM5 系列入口。
- 风险 / 待核实：HF likes 约 1686、downloads 约 66 万；GitHub MiniCPM 仓 ★约 11273（2026-09-26）；自报榜分与 agent 实测 **待核实**；勿收第三方量化/引擎 Day-0 扩散帖。

## 原文摘要（可选）

摘要：@OpenBMB 宣布 MiniCPM5-2B 开源，强调端侧智能密度，并开放数据与 RL 栈。

## 与其他条目的关系（可选）

非 **LFM2.5-2.6B** / **Granite-4.2** / **Inkling-Small** / **Nex-N2.5**。同厂联动的 **Atria Dawn Preview**（744B MoE agentic）为本批另一候选，产品轴不同（端侧稠密 vs 长程 Agent MoE）。未开 Qwen3.8 / jina-v5-text / Granite Speech。
