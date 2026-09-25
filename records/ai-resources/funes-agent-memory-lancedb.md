# funes：本地 Agent 会话记忆（Claude Code / Codex / pi / Hermes）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-25
- **平台**：X
- **来源（必填）**：https://x.com/lancedb/status/2102079650839306613
- 作者 / 频道：@lancedb（转述 Hugging Face 博客；作者 @ariG23498 / @loldedxd）
- 发布时间：2026-09-21 16:56:58 UTC（约 2026-09-22 00:56 CST）

## 要点

- 帖文介绍 Hugging Face **funes**：把 Claude Code、Codex、pi、Hermes 等历史会话索引进本地 Lance 数据集，向 agent 暴露 `recall` / `get`（可选 `ask`）。
- 安装：`curl -fsSL https://huggingface.co/buckets/huggingface/funes/resolve/install.sh | sh`，再 `funes add codex`（或 `claude` / `pi` / `hermes`）建索引并注册工具/钩子。
- 强调本地默认、索引路径无 LLM 摘要；可选 TruffleHog 脱敏与 `funes push` 前扫描。

## 落地链接（可选）

- 博客：https://huggingface.co/blog/ariG23498/funes-lance
- 安装桶：https://huggingface.co/buckets/huggingface/funes

## 价值判断

- 为什么值得记：直接可装的跨编码 Agent「会话记忆」层，补 Claude Code / Codex 技能与工具缺口，非已入库网安逆向 skill。
- 风险 / 待核实：来源为 LanceDB 转发 HF 博客，非 funes 作者首发帖；星数/效果「待核实」；会话痕迹含敏感路径/密钥，需本地审权限。

## 原文摘要（可选）

摘要：LanceDB 推荐 funes 博客，强调本地 Lance 索引 + recall/get，不在 ingest 时用 LLM 摘要 traces。
