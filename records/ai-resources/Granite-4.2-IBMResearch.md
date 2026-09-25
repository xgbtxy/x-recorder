# Granite 4.2：IBM 开源企业 Agent 向稠密推理族（3B/8B/30B）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/IBMResearch/status/2092304349665833410
- 作者 / 频道：@IBMResearch
- 发布时间：2026-08-25 17:33:24 UTC（约 2026-08-26 01:33 CST）

## 要点

- IBM Research 官号发布 **Granite 4.2**：开源稠密推理族，规格含 **3B / 8B / 30B**，定位企业 agentic 工作流（原生推理、工具调用、规划与自纠）——效果与可靠性 **待核实**。
- 许可宣称 **Apache 2.0**；配套还有 Granite Speech 5.0 Turbo CTC 等语音侧发布——**本条只记语言/推理权重族**，语音侧勿再拆小步迭代条。
- 可动手：HF `ibm-granite/granite-4.2-{3b,8b,30b}`、IBM Research 博客、Granite 文档；Ollama 亦有镜像入口（非本条必收）。

## 落地链接（可选）

- HF 8B：https://huggingface.co/ibm-granite/granite-4.2-8b
- HF 3B：https://huggingface.co/ibm-granite/granite-4.2-3b
- HF 30B：https://huggingface.co/ibm-granite/granite-4.2-30b
- 博客：https://research.ibm.com/blog/introducing-granite-4-2
- 文档：https://www.ibm.com/granite/docs/models/granite4-2

## 价值判断

- 为什么值得记：官号可核的**新开源企业 Agent 推理族**（非已入库 Command A+ / North Mini / Muse 等），HF 可下；补 IBM Granite 4.2 入口。
- 风险 / 待核实：HF likes 约 97（3B）/ 83（8B）/ 125（30B）（2026-09-26）；跑分、长上下文与工具调用实测 **待核实**；勿收 vLLM/SGLang Day-0 或第三方量化扩散帖。

## 原文摘要（可选）

摘要：@IBMResearch 宣布 Granite 4.2 开源族，强调原生推理与企业 agent 工具使用叙事。

## 与其他条目的关系（可选）

非 Command-A-Plus / North-Mini-Code（Cohere）/ Muse-Glimmer / Nemotron-3.5-Lightning。本条是 **IBM Granite 4.2 语言推理权重**。同厂 Speech 5.0 勿再拆。未开 Qwen3.8 / jina-v5-text。
