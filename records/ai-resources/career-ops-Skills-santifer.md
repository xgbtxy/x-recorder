# career-ops：本地优先的求职筛选 Agent Skill 包

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/santifer/status/2041403685696053741
- 作者 / 频道：@santifer
- 发布时间：2026-04-07 06:32:20 UTC（约 2026-04-07 14:32 CST）

## 要点

- **career-ops**：作者为自用求职场景开源的本地 Agent 工作流，扫描/评估岗位并给出结构化报告，强调「不代投、不替你发简历」。
- 可装入口：`npx skills add career-ops-hq/career-ops`（skills.sh 目录可见）；仓库另有引导安装 `npx @santifer/career-ops init`。
- Skill 定义在 `.agents/skills/career-ops/SKILL.md`，面向 Claude Code / Cursor 等兼容宿主。
- 站点与文档：career-ops.org；仓已迁至 `career-ops-hq/career-ops`（历史 `santifer/career-ops` 仍指向同帖）。

## 落地链接（可选）

- 仓库：https://github.com/career-ops-hq/career-ops
- 目录：https://www.skills.sh/career-ops-hq/career-ops
- 站点：https://career-ops.org/
- 故事页：https://santifer.io/career-ops-system

## 价值判断

- 为什么值得记：有明确 `npx skills add` 的第三方 Skill 包，对准可动手的求职筛选，而非空口号。
- 风险 / 待核实：星数约 72760（career-ops-hq/career-ops，2026-09-26 核）；「HIRED」计数仍待核实；岗位数据源与本地模型效果待自测；勿与自动投递灰产混淆（项目自称不代投）。

## 原文摘要（可选）

摘要：作者称工具为自己求职而建并开源，两日内破万星，链到 GitHub。

## 与其他条目的关系（可选）

非已入库 **skills-cli-rauchg** / Notion 源能力增量，而是可被 skills CLI 安装的**内容包**；也非 Claude Marketplace / mattpocock/skills 工程向合集。
