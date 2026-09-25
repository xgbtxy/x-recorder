# Modern Web Guidance：把现代 Web 最佳实践注入 Coding Agent 的可装 Skills

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/ChromiumDev/status/2101020485123490045
- 作者 / 频道：@ChromiumDev
- 发布时间：2026-09-16 18:30:00 UTC（约 2026-09-17 02:30 CST）

## 要点

- Chrome 团队推广 **Modern Web Guidance**：一组把 Web 平台最佳实践与浏览器兼容数据喂给 coding agent 的 Skills；官帖称安装量破 **1 万**（数字 **待核实**）。
- 建议与 **Chrome DevTools for agents** 联用：先审计性能/可访问性，再按现代 Web 模式改代码。
- 可动手入口：`npx modern-web-guidance@latest install`；或 `npx skills add GoogleChrome/modern-web-guidance`；亦支持 Claude Code / Copilot / Antigravity 插件安装。仓星 **待核实**。

## 落地链接（可选）

- 文档：https://developer.chrome.com/docs/modern-web-guidance
- 仓库：https://github.com/GoogleChrome/modern-web-guidance
- Skills 安装：`npx skills add GoogleChrome/modern-web-guidance`

## 价值判断

- 为什么值得记：官方可装 Web Skills，直接对准「Agent 写出过时前端」痛点；安装命令与文档齐全。
- 风险 / 待核实：安装量/星数以官方与 GitHub 实时为准；技能覆盖面随 Baseline 目标变化；需本地 Agent 支持 Skills/插件。

## 原文摘要（可选）

摘要：@ChromiumDev 称 Modern Web Guidance 已有逾万安装，并建议与 Chrome DevTools for agents 搭配使用。

## 与其他条目的关系（可选）

同账号生态但能力轴不同：已入库 **Chrome DevTools MCP** 是调试/性能工具面；本条是 **现代 Web 编码指导 Skills**。勿与 Stitch Skills（设计）或 Google Cloud Developer Plugin（GCP）合并。
