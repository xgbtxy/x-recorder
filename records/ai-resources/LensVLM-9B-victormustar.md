# LensVLM-9B：Apple 开源「压缩页图→按需展开」长文档 VLM

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-25
- **平台**：X
- **来源（必填）**：https://x.com/victormustar/status/2102824162511503669
- 作者 / 频道：@victormustar（报道 Apple HF 上架）
- 发布时间：2026-09-23 18:15:23 UTC（约 2026-09-24 02:15 CST）

## 要点

- 帖文指向 Apple 在 Hugging Face 上架的 **LensVLM-9B**（基于 Qwen3.5-9B）：把长文档压成小页图省 token，再只展开与问题相关的页面全文。
- 动手入口：HF 权重 `apple/LensVLM-9B`；代码 `https://github.com/apple-aiml-research/ml-lensvlm`（`pip install -e .` 后 `python scripts/run_demo.py --model apple/LensVLM-9B`）。
- 论文 arXiv:2605.07019；许可为 Apple ML Research Model License（非宽松 OSI，商用需自审）。

## 落地链接（可选）

- 模型：https://huggingface.co/apple/LensVLM-9B
- 代码：https://github.com/apple-aiml-research/ml-lensvlm

## 价值判断

- 为什么值得记：新开源模型 release 帖带直达下载与推理脚本，补长上下文/文档 Agent 工具链。
- 风险 / 待核实：来源为第三方报道帖非 Apple 官方账号；星数/效果「待核实」；Apple 许可条款需本地阅读。

## 原文摘要（可选）

摘要：Victor 提示 Apple 在 HF 放出基于 Qwen3.5-9B 的 LensVLM，用页图压缩 + 按需展开降低长文档 token。
