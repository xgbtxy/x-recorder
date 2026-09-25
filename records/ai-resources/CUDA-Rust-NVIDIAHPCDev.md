# CUDA Rust：用 Rust 原生写 GPU Kernel（cuda-oxide + cutile-rs）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/NVIDIAHPCDev/status/2100261772355907936
- 作者 / 频道：@NVIDIAHPCDev
- 发布时间：2026-09-16 16:33:22 UTC（约 2026-09-17 00:33 CST）

## 要点

- NVIDIA HPC 开发者号发布 **CUDA Rust**：可在 Rust 中直接编写 GPU kernel，而不仅是从 Rust 启动 CUDA。
- 两条路径：`cuda-oxide`（SIMT → PTX）、`cutile-rs`（稳定 Rust 上的 Tile 编程）；宣称可在编译期捕获别名等问题。
- 可动手：技术博客 + NVlabs 开源仓；面向内核/推理算子开发者。成熟度与生产可用性 **待核实**。

## 落地链接（可选）

- 博客：https://developer.nvidia.com/blog/introducing-cuda-rust-two-tracks-for-writing-gpu-kernels/
- cuda-oxide：https://github.com/NVlabs/cuda-oxide
- cutile-rs：https://github.com/NVlabs/cutile-rs

## 价值判断

- 为什么值得记：可核官帖 + 双仓开源，补 AI/系统侧「算子与 Kernel 工程」工具轴。
- 风险 / 待核实：cuda-oxide ★约 3.6k、cutile-rs ★约 1.0k（2026-09-26）；实验性 API 可能变动。

## 原文摘要（可选）

摘要：@NVIDIAHPCDev 介绍 CUDA Rust 双轨方案（cuda-oxide / cutile-rs），并给出技术博客链接。

## 与其他条目的关系（可选）

相对已入库 Nemotron/AIPerf 等 NVIDIA 模型或评测：本条是 **GPU 编程语言/编译工具链**，不是新基础模型。同账号另有较早的 CUDA MCP Server 帖，产品轴不同，未在本批展开。
