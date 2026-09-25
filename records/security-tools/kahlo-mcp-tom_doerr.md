# kahlo-mcp：面向 Android AI Agent 的 Frida MCP Server

- 状态：已核
- 分类：security-tools（兼 ai-resources）
- 记录日期：2026-09-25
- **来源 X（必填）**：https://x.com/tom_doerr/status/2035619264120467536
- 作者：@tom_doerr（分享）
- 推文时间：2026-03-22 07:27:07 UTC（约 2026-03-22 15:27 CST）

## 关键点

- 公开 **kahlo-mcp**（FuzzySecurity）：把 Frida 能力封装成 MCP，供 Android 场景下的 AI Agent 调用。
- 与已入库 JADX-AI-MCP / apktool-mcp-server / frida-ssl-bypass 等互补：本条专记 Frida MCP server 入口。
- 只记仓库与定位，不写 hook / 绕过步骤。

## 落地链接（可选）

- 仓库：https://github.com/FuzzySecurity/kahlo-mcp

## 价值判断

- 为什么值得记：直接命中 Frida + MCP + Android Agent；出处与仓库均可核。
- 风险 / 待核实：双刃动态插桩能力；维护状态/星数以 README 为准；仅作公开索引。

## 原文摘要（可选）

@tom_doerr 分享「Frida MCP server for Android AI agents」并给出 kahlo-mcp 仓库链接。
