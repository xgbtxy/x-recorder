# TensorRT Model Connect：HF 模型两命令上 TensorRT（开源预览）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/NVIDIAAI/status/2089750360869233059
- 作者 / 频道：@NVIDIAAI
- 发布时间：2026-08-18 16:24:46 UTC（约 2026-08-19 00:24 CST）

## 要点

- NVIDIA 宣布 **TensorRT Model Connect** 公共预览：将支持的 Hugging Face 模型经约两命令打到端到端 TensorRT 推理，宣称无需中间 ONNX 导出，产物可用原生 C++ API 运行（能力边界 **待核实**）。
- 仓库开源；官帖称项目大量由 Codex agents 在人审下完成实现/调优/测试/文档。
- 可动手入口：GitHub 仓库 + 官方 quick-start 文档（`trtmc build` / `trtmc run` 等）。

## 落地链接（可选）

- 仓库：https://github.com/NVIDIA/TensorRT-Model-Connect
- 快速上手：https://nvidia.github.io/TensorRT-Model-Connect/getting-started/quick-start/

## 价值判断

- 为什么值得记：可核官帖 + 开源仓库/文档，属于可动手的 **AI 推理工程工具**，非纯营销。
- 风险 / 待核实：星数/支持模型列表以仓库为准（抽查约两百星量级，**待核实**）；Public Preview；与已有 TensorRT / CUDA 生态条目是工具链互补而非重复发版帖。

## 原文摘要（可选）

摘要：@NVIDIAAI 介绍 TensorRT Model Connect 公共预览，强调 HF→TensorRT 两命令路径并给出 GitHub。

## 与其他条目的关系（可选）

已入库 **CUDA Rust**、**transformers GGUF Metal**、**vLLM** 等偏运行时/内核；本条是 **HF→TensorRT 打包连接器**。非 Nemotron 模型发版，亦非 serving 小版本 changelog。
