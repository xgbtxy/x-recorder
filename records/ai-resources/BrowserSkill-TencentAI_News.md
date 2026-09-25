# BrowserSkill：腾讯开源「借用本机已登录浏览器」的 Agent CLI（非空白浏览器）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/TencentAI_News/status/2100143086429217278
- 作者 / 频道：@TencentAI_News
- 发布时间：2026-09-16 08:41:45 UTC（约 2026-09-16 16:41 CST）

## 要点

- 腾讯开源 **BrowserSkill**：让 Agent 通过 CLI（`bsk`）连接本机 Chrome/Edge，可借用已登录标签页完成后再交还，而非给空白浏览器。
- 宣称：登录态可复用；验证码/确认对话框交回用户后继续；借页需用户在浏览器设置中授权，不能靠提示词绕过。
- 可动手：`curl -fsSL https://raw.githubusercontent.com/Tencent/BrowserSkill/main/install.sh | sh`，再 `bsk install-skill`（支持 Cursor / Claude Code / Codex 等；另有 DeepSeek Harness 插件）。MIT。
- 仓库星数约 7.2k（2026-09-26 抽查，**待核实**）。

## 落地链接（可选）

- 仓库：https://github.com/Tencent/BrowserSkill

## 价值判断

- 为什么值得记：可核官帖 + 一行安装 + Skill 安装命令，补「真登录态浏览器」Agent 工具轴，区别于多数空白浏览器 MCP。
- 风险 / 待核实：赋予 Agent 访问已登录会话，安全与审计责任在用户侧；兼容矩阵与 Windows 安装脚本效果待自测；与已入库 browse.sh / Chrome DevTools MCP 等能力重叠但机制不同。

## 原文摘要（可选）

摘要：@TencentAI_News 称开源 BrowserSkill，用 CLI 让 Agent 借用本机已登录浏览器标签，并强调借页需用户设置授权。

## 与其他条目的关系（可选）

相对已入库 **browse-sh-skills-browserbase**、**Chrome-DevTools-MCP**、**Playwright MCP**：本条强调 **复用本机登录态 + 显式借还标签 + CLI 非 MCP**。勿与网安逆向线混收。
