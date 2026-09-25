# MiniMax H3：开源权重多模态视频（含原生立体声）生成底座

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/MiniMax_AI/status/2099381310733328784
- 作者 / 频道：@MiniMax_AI
- 发布时间：2026-09-14 06:14:43 UTC（约 2026-09-14 14:14 CST）

## 要点

- @MiniMax_AI 官帖确认 **MiniMax H3** 已开源权重并推动社区加速：面向视频生成，宣称支持原生立体声音频与多模态参考控制（能力边界 **待核实**）。
- 帖内盘点 FastH3 / Sol-H3 / VDN / PDD Acc-LoRA / LightX2V 等社区蒸馏与加速线；完整系统中 Context-IR / Regenerate-2K 等模块仍可能走官方 API（以仓库说明为准，**待核实**）。
- 可动手入口：Hugging Face `MiniMaxAI/MiniMax-H3`、GitHub `MiniMax-AI/MiniMax-H3`（含 prompt skill / `npx skills add` 指引见仓库）。

## 落地链接（可选）

- 模型：https://huggingface.co/MiniMaxAI/MiniMax-H3
- 仓库：https://github.com/MiniMax-AI/MiniMax-H3
- 新闻稿：https://www.minimax.io/news/minimax-h3-open-source

## 价值判断

- 为什么值得记：官号可核 + HF/GitHub 可下载，补 MiniMax 视频开源轴；相对纯生态营销帖有明确权重入口。
- 风险 / 待核实：本帖偏「开源后生态进展」而非首发公告；本地可复现范围（Base vs 全链路 2K）与显存需求 **待核实**；HF likes 约 5672、GitHub ★约 9208（2026-09-26）；延迟待核实。勿与同引擎 Day-0/量化或 SGLang 发版帖另开产品条。

## 原文摘要（可选）

摘要：@MiniMax_AI 总结 H3 开源后社区在蒸馏、稀疏注意力与 ComfyUI LoRA 等方面的加速进展，并强调开放权重与共建。

## 与其他条目的关系（可选）

相对已入库 **MiniMax-M3 / MiniMax Code CLI**：本条是 **视频/音频多模态生成（H3）**，不是文本旗舰 M3，也不是 Code CLI 编程 Agent；生态加速帖中的 SGLang/vLLM 等仅作推理后端提及，不另开 serving 发版条。
