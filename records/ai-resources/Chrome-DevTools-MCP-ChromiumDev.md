# Chrome DevTools MCP：给 Coding Agent 的浏览器调试/性能入口

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/ChromiumDev/status/1970505063064825994
- 作者 / 频道：@ChromiumDev
- 发布时间：2025-09-23 15:06 UTC（约 2025-09-23 23:06 CST）

## 要点

- Chrome 官方公测 **Chrome DevTools MCP**，让 Cursor/Claude 等 coding agent 直接连上 Chrome DevTools：性能 trace、DOM 检查、实时调试。
- 本地可装入口：`npx chrome-devtools-mcp@latest`（亦见官方博客配置示例）；仓库 `ChromeDevTools/chrome-devtools-mcp`。
- 与已入库 Playwright MCP 不同：偏 DevTools 调试/性能洞察，而非通用浏览器自动化库包装。
- 同日社区转发帖：https://x.com/addyosmani/status/1970503277621256263（功能点更细，非本条主来源）。

## 落地链接（可选）

- 仓库：https://github.com/ChromeDevTools/chrome-devtools-mcp
- 博客：https://developer.chrome.com/blog/chrome-devtools-mcp
- npm 用法（文档）：`npx chrome-devtools-mcp@latest`

## 价值判断

- 为什么值得记：官方可装 MCP，补「agent 看不见页面真实运行态」缺口，落地命令清晰。
- 风险 / 待核实：星数/效果「待核实」；公测能力面会变；控制本机 Chrome 有安全边界，需本地审权限。

## 原文摘要（可选）

摘要：ChromiumDev 宣布 Chrome DevTools MCP 公测，agent 可跑性能 trace、检查 DOM、做实时调试。
