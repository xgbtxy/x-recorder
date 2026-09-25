# T3MP3ST：把现有 Coding Agent 接成授权红队 harness

- 状态：候选
- 分类：security-tools（兼 ai-resources）
- 记录日期：2026-09-25
- **来源 X（必填）**：https://x.com/elder_plinius/status/2073579120135664102
- 作者：@elder_plinius
- 推文时间：（fxtwitter 可见；约 2026-07 前后发帖）

## 关键点

- 开源 AGPL-3.0 项目：把 Claude Code / Codex / Hermes 等已有 Coding Agent 套上进攻安全 harness（自称「harness of harnesses」）。
- 覆盖面宣传：Web/API、网络侦察、白盒源码审计、CTF、部分 DeFi 复现、嵌入式/IoT 等；提供 War Room UI、CLI、HTTP API，以及 `security_recon` MCP。
- 作者贴出可复算基准叙事：XBEN / Cybench / CVE-Zero；仓库侧强调 `npm run verify-claims` 从提交产物重算。
- 明确写 Authorized use only；后渗透类驱动（如 metasploit / hydra）在文档中称需人工批准门控。

## 落地链接（可选）

- 仓库：https://github.com/elder-plinius/T3MP3ST

## 价值判断

- 为什么值得记：公开「Agent + 进攻安全编排」入口，和库内 ASC / reverse-skill 同属 AI×安全工具线，可跟进 harness / MCP / 基准复现方法。
- 风险 / 待核实：基准数字与「swarm 已可用」叙事需以 README 状态表 + `verify-claims` 为准；部分算子/领域在文档中仍标 experimental / roadmap；仅记公开入口，不收录利用步骤。

## 原文摘要（可选）

官宣帖：介绍 T3MP3ST，指向 GitHub，强调把现有 coding agent 变成 full-stack red team，并罗列基准与授权免责声明。
