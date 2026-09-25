# Cultivar：Pinecone 开源的 Agent Skills / Docs 评测 CLI

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/pinecone/status/2101325527457968417
- 作者 / 频道：@pinecone
- 发布时间：2026-09-19 15:00:21 UTC（约 2026-09-19 23:00 CST）

## 要点

- Pinecone 宣布 **Cultivar**（Agent Skills / Docs 评测库）新版可用：在沙箱里测 agent 对 Skill 与文档的执行质量，并可用 @typesafeai 的 **Jev** 做二值判分。
- 可动手入口：GitHub `pinecone-io/cultivar`；PyPI `cultivar`；README 给出 `npx skills add https://github.com/pinecone-io/cultivar --skill cultivar`，也可直接装 CLI（如 `uv tool install cultivar`）跑本地/远程（Modal）评测。
- 官帖称用 Jev 相对 Claude 做 grading 有约 19× 速度、38× 成本优势（效果与星数 **待核实**）。

## 落地链接（可选）

- 仓库：https://github.com/pinecone-io/cultivar
- PyPI：https://pypi.org/project/cultivar/
- 同帖跟帖装仓说明：https://x.com/pinecone/status/2101325532398858263

## 价值判断

- 为什么值得记：可核官帖 + 可装 Skill/CLI 的 **Skills 评测工具**，比纯营销更可动手；与「只会装 Skill」条目形成评测侧互补。
- 风险 / 待核实：GitHub ★ 约 41（此前 gh api；当前限流未复核）；Jev 加速/成本数字为厂商口径 **待核实**；远程跑依赖 Modal 等外部沙箱账号。

## 原文摘要（可选）

摘要：@pinecone 称 Cultivar 新版可用，可用 Jev 在 Modal 沙箱里评估 agent 对 docs/Skill 的表现，并给出相对 Claude grading 的速度与成本对比。

## 与其他条目的关系（可选）

相对已入库 **VQ-bench（Pinecone）**：本条是 **Agent Skills/Docs 评测 CLI**，不是向量量化框架。相对已入库 **Decision Index 0.1**（拿 Jev 当对照轴）：本条是 **评测 harness**，可选用 Jev 当 grader，不是决策模型排行榜。
