# Dynamo AIPerf：NVIDIA 开源生成式推理压测 / 流量回放工具

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/NVIDIAAI/status/2101077927408623623
- 作者 / 频道：@NVIDIAAI
- 发布时间：2026-09-18 22:36:28 UTC（约 2026-09-19 06:36 CST）

## 要点

- NVIDIA AI 官号推广 **Dynamo AIPerf**：面向生成式推理端点的综合压测工具，宣称可测 TTFT / ITL / 延迟 / 吞吐，并用可重复的真实流量模式做规模化评估。
- 属 Dynamo 生态的**评测 / 基准工具**，不是又一个推理引擎发版；可对接常见 inference 方案做对照——具体支持矩阵 **待核实**。
- 可动手：GitHub `ai-dynamo/aiperf`（Apache-2.0）+ NVIDIA 开发者博客；含教程与指标参考文档。

## 落地链接（可选）

- 仓库：https://github.com/ai-dynamo/aiperf
- 博客：https://developer.nvidia.com/blog/benchmarking-llm-inference-at-scale-with-aiperf/
- 帖内短链：https://nvda.ws/4hdIeGd

## 价值判断

- 为什么值得记：可核官号 + 高星开源压测入口，补「怎么测 serving」工具缺口；与本批 megakernel serving/训练条目可对照使用。
- 风险 / 待核实：仓库 ★约 722（2026-09-26 `api.github.com`）；指标与流量回放对标声明 **待核实**；需自备被测端点与 GPU/集群环境。

## 原文摘要（可选）

摘要：@NVIDIAAI 称端点可用后应用 Dynamo AIPerf 在规模下测量 TTFT/ITL/延迟/吞吐并回放真实流量，指向博客。

## 与其他条目的关系（可选）

非 vLLM / SGLang / LMDeploy / Ollama / EXO / llama.cpp **发版帖**；本条是 **压测工具**。可与本批 **Cohere Megakernel** 等 serving 实现对照测速，但条目本身不是引擎。非已入库 MLPerf Training 榜单条目。
