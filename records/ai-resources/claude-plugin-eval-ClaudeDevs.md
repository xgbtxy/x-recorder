# claude plugin eval：对 Claude Code 插件/技能做有无对照评测

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/ClaudeDevs/status/2098500999656923145
- 作者 / 频道：@ClaudeDevs
- 发布时间：2026-09-11 19:56:41 UTC（约 2026-09-12 03:56 CST）

## 要点

- @ClaudeDevs 官宣 Claude Code 新能力 **`claude plugin eval`**：为插件或 skill 写测试用例，在隔离会话中分别「带插件」与「不带插件」跑同一批 case，打分后对比差异。
- 用途是回答「这个插件/技能到底有没有用、哪里还要改」，可把阈值设为 CI 门槛（文档称低于阈值可非零退出，细节 **待核实**）。
- 可动手入口：官方 Plugin Evals 文档；会话内迭代也可配合 skill-creator 工作流（见文档交叉引用）。

## 落地链接（可选）

- 文档：https://code.claude.com/docs/en/plugin-evals
- 插件总览：https://code.claude.com/docs/en/plugins

## 价值判断

- 为什么值得记：官帖可核 + 文档可点开；补「技能/插件效果评测」动手工具，不是纯营销榜单。
- 风险 / 待核实：grader 设计、用例编写成本、与 skill-creator 评测格式是否互通以文档为准；仅覆盖 Claude Code 插件生态。

## 原文摘要（可选）

摘要：@ClaudeDevs 发布 `claude plugin eval`，可对插件/技能做有无对照评测并看差异。

## 与其他条目的关系（可选）

同厂 Claude Code 工具轴，但本条是 **插件/技能评测 CLI**；勿与同批「ant apply」（平台资源 IaC）混为同一项。非已入库 SkillsBench / State of agent skills 等横向评测或目录帖。
