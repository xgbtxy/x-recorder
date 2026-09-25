# apktool-mcp-server：用 MCP 把 Apktool 交给 Agent

- 状态：已核（仓库可打开）
- 分类：security-tools（兼 ai-resources）
- 记录日期：2026-09-25
- **来源 X（必填）**：https://x.com/zinja_coder/status/1923636620420350411
- 作者：@zinja_coder（Jafar Pathan）
- 推文时间：2025-05-17 07:08:04 UTC（约 2025-05-17 15:08 CST）

## 关键点

- 开源 **apktool-mcp-server**：把 Apktool 能力封装成 MCP，让 Claude 等 Agent 做 APK 解包、清单/smali 查看与重建等工作流。
- 本帖是作者演示：用该 MCP 完成 Android CTF Level 1（「Solving … using Vibes」），仓库直链给出。
- 与同作者 JADX-AI-MCP / jadx-mcp-server 同属「Zin 逆向 MCP 套件」；本条专记 apktool 线。另有第三方转发帖（如 @DanKornas）可不另立，除非带新能力说明。

## 落地链接（可选）

- 仓库：https://github.com/zinja-coder/apktool-mcp-server

## 价值判断

- 为什么值得记：直接对应关键词 apktool / Agent reverse；作者原帖可核，仓库可打开。
- 风险 / 待核实：星数与能力边界以 README 为准；CTF 演示不等于生产审计完备。只记公开入口，不写利用或绕过步骤。

## 原文摘要（可选）

作者展示用 APKTool MCP Server 解 Android CTF Level 1，并给出 GitHub 链接。
