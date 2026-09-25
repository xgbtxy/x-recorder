# Google Cloud Developer Plugin：把 Cloud Skills + Developer Knowledge MCP 打成可装插件

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/GoogleCloudTech/status/2098121333255135371
- 作者 / 频道：@GoogleCloudTech
- 发布时间：2026-09-10 18:48:01 UTC（约 2026-09-11 02:48 CST）

## 要点

- Google Cloud 宣布面向 AI coding agents 的 **Google Cloud plugins**：按 Agent Plugins 规范打包 Skills + MCP，首发旗舰包 **`google-cloud-developer`**。
- 覆盖 GCP 入门/鉴权、gcloud 安全护栏，并捆绑 **Developer Knowledge MCP**（官方文档检索），降低「技能散装 + 文档过期」成本。
- 可动手入口：仓库 `google/skills`（`npx skills add google/skills` 或 Claude/Codex marketplace 安装 `google-cloud-developer`）；博客含 Antigravity / Claude Code / Codex 安装步骤。星数 **待核实**（公开页可见约 2 万级，以 GitHub 实时为准）。

## 落地链接（可选）

- 博客：https://cloud.google.com/blog/topics/developers-practitioners/introducing-the-google-cloud-developer-plugin-for-ai-coding-agents
- 仓库：https://github.com/google/skills
- Developer Knowledge MCP：https://developers.google.com/knowledge/mcp

## 价值判断

- 为什么值得记：官帖可核 + 可装入口清晰；补「GCP 官方 Agent Plugin 包」轴，不是又一个模型发版。
- 风险 / 待核实：需 Developer Knowledge API key / 计费与权限；插件与单技能目录会持续扩容，以仓库 README 为准；效果数字 **待核实**。

## 原文摘要（可选）

摘要：@GoogleCloudTech 介绍 Google Cloud plugins，用可安装插件包给 coding agent 配上 Cloud 技能与工具。

## 与其他条目的关系（可选）

同厂 Google Agent Skills 生态，但本条是 **`google-cloud-developer` 插件包（Skills+MCP 捆绑）**；勿与已入库 Stitch Skills（设计域）、google-workspace-cli skills（Workspace CLI）、Chrome Modern Web Guidance（Web 平台技能）或 nvidia-verified-agent-skills 混为同一项。
