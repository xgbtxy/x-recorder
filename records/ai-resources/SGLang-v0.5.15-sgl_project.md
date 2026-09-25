# SGLang v0.5.15：高吞吐开源 LLM/多模态推理服务引擎发版

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/sgl_project/status/2075721488456654861
- 作者 / 频道：@sgl_project
- 发布时间：2026-07-10 23:19:02 UTC（约 2026-07-11 07:19 CST）

## 要点

- LMSYS 旗下 **SGLang** 官方账号发布 **v0.5.15**：面向 LLM / 多模态的高吞吐开源 serving 框架（结构化生成、Radix 前缀缓存、OpenAI 兼容 API 等，细节以文档为准）。
- 本版亮点（帖内宣称，待核实）：Breakable CUDA Graph 成默认 capture 路径、内置 web search、MLA 模型 decode context parallelism、FlashInfer MoE all-to-all，以及对若干新模型的 day-0/增强支持。
- 可动手：`pip` / Docker（`lmsysorg/sglang`）/ `python -m sglang.launch_server`；文档与 cookbook 有可复制配方。

## 落地链接（可选）

- 公告帖：https://x.com/sgl_project/status/2075721488456654861
- 仓库：https://github.com/sgl-project/sglang
- 文档：https://docs.sglang.io/
- 站点：https://sglang.io

## 价值判断

- 为什么值得记：本地/集群开源推理引擎缺口（records 已有 vLLM / llama.cpp / Ollama / EXO，尚无 SGLang 本条）；官方账号可核发版帖，GitHub + 文档可动手。
- 风险 / 待核实：吞吐数字（如 tok/s/user）、硬件组合与 breaking defaults 待核实；sgl-project/sglang ★36433（2026-09-26 gh api）；Release v0.5.15 可开；同引擎后续发版/扩散帖勿重复开条。

## 原文摘要（可选）

摘要：@sgl_project 宣布 SGLang v0.5.15，列举 BCG 默认化、web search、DCP、MoE 路径与新模型支持，并贴出部分 launch 命令。

## 与其他条目的关系（可选）

互补 vLLM（GPU serving）与 llama.cpp/Ollama（本机）；非已入库模型权重条。帖内点名的 Qwen-Image / DeepSeek-V4 / GLM 等勿因「引擎 day-0 支持」再拆开模型扩散条（模型已有或另条）。
