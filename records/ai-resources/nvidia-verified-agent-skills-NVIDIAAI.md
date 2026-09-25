# NVIDIA-Verified Agent Skills：可 `npx skills add` 的官方 Skill 目录

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/NVIDIAAI/status/2087887993025843391
- 作者 / 频道：@NVIDIAAI
- 发布时间：2026-08-13 21:04 CST（UTC+8）

## 关键点

- NVIDIA 官方 Agent Skills 目录，面向 Claude Code / Codex / Cursor 等兼容 Agent Skills 规范的客户端。
- 安装入口：`npx skills add nvidia/skills`（可再 `--skill` / `--agent` 精选与定向）。
- 文档强调「Verified」流程：编目、扫描、签名（`skill.oms.sig`）、Skill Card；覆盖 CUDA / cuOpt / RAG / Omniverse 等产品工作流。
- 同账号后续帖有 SkillEvaluator 基准宣传数字，一律标待核实。

## 落地链接（可选）

- 仓库 / 官网 / 文档：https://github.com/nvidia/skills ；https://docs.nvidia.com/skills ；https://skills.sh/

## 价值判断

- 为什么值得记：可一行安装的官方 Skill 包，直接对接现有 coding agent / skills CLI 生态。
- 风险 / 待核实：帖中「300+ skills / 30+ products」及后续基准提升百分点均未采信；签名校验与各 Agent 兼容度需本地试装。

## 原文摘要（可选）

摘要：@NVIDIAAI 称 Cursor 等开发者可用 300+ NVIDIA skills，覆盖 30+ 产品。

## 与其他条目的关系（可选）

与已入库 `skills CLI`（rauchg）互补：本条是 NVIDIA 官方 skill 目录，而非 CLI 本体。
