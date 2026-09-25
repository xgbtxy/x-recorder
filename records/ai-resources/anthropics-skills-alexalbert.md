# anthropics/skills：Anthropic 官方 Agent Skills 示例与文档技能包

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/alexalbert__/status/1978877498411880550
- 作者 / 频道：@alexalbert__（Anthropic）
- 发布时间：2025-10-16 17:35:36 UTC（约 2025-10-17 01:35 CST）

## 要点

- **anthropics/skills**：Anthropic 公开的 Agent Skills 仓库，含文档类（PDF/DOCX/PPTX/XLSX 等）与示例技能（如 frontend-design、skill-creator）。
- 安装路径：Claude Code 可用 `/plugin marketplace add anthropics/skills` 再装 plugin；skills.sh 亦收录，可用 `npx skills add anthropics/skills`（以 README / 目录页为准）。
- 公告帖说明 Skills 可在 claude.ai、Claude Code 与 API 按需加载专用能力。

## 落地链接（可选）

- 仓库：https://github.com/anthropics/skills
- 目录：https://www.skills.sh/anthropics/skills
- 工程博文：https://www.anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills
- 产品说明：https://claude.com/blog/skills

## 价值判断

- 为什么值得记：官方可核对的 Skill 内容包入口，覆盖文档处理与示例工作流，skills.sh / 仓库均可开。
- 风险 / 待核实：
  - **代码执行**：文档/示例技能可含脚本，Agent 可能在本机或沙箱执行代码。
  - **权限与外连**：按技能说明可能触达文件系统、依赖与外部服务；只从可信源安装并先审 SKILL.md。
  - 星数约 178190（anthropics/skills，2026-09-26 核）；效果数字仍待核实；与 Claude Marketplace 插件列表条目互补而非同一封装入口。

## 原文摘要（可选）

摘要：Alex Albert 宣布在 claude.ai、Claude Code 与 API 引入 Skills，把专用知识打成可按需加载的可复用能力。

## 与其他条目的关系（可选）

**非** skills-cli / Notion 源 CLI 本体；**非**已入库 claude-marketplace 产品页条目的替代。本条记的是可装的 **anthropics/skills 内容包**（官方示例与 document-skills）。
