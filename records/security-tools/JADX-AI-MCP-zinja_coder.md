# JADX-AI-MCP：给 JADX 接 MCP，让 Agent 读实时反编译上下文

- 状态：已核（仓库可打开，约 2.8k★）
- 分类：security-tools（兼 ai-resources）
- 记录日期：2026-09-25
- **来源 X（必填）**：https://x.com/zinja_coder/status/2085396884273914160
- 作者：@zinja_coder（Jafar Pathan）
- 推文时间：2026-08-06 16:05:36 UTC（约 2026-08-07 00:05 CST）

## 关键点

- 开源插件 **JADX-AI-MCP**（帖称 v6.4.1）：把 JADX 反编译 GUI 的当前类/方法/资源等上下文，通过 MCP 暴露给 Claude 等 LLM 客户端。
- 定位：Android 逆向时让 Agent「看见」正在看的 JADX 视图，而不是盲猜命令；与 ASC「替代 Jadx MCP」叙事互补（本条目是原 Jadx MCP 路线）。
- 同作者还有配套 `jadx-mcp-server`、`apktool-mcp-server`（安卓逆向 MCP 套件的一部分，另帖另立）。

## 落地链接（可选）

- 仓库：https://github.com/zinja-coder/jadx-ai-mcp
- 配套 MCP server：https://github.com/zinja-coder/jadx-mcp-server

## 价值判断

- 为什么值得记：关键词 jadx + Agent 的高频公开入口；作者原帖可核，仓库可打开。
- 风险 / 待核实：远程绑定 MCP 时 README 有明文无鉴权警告，需本机/授权环境使用；星数与下载量以 GitHub/Release 为准。只记公开入口，不写利用步骤。

## 原文摘要（可选）

作者官宣 JADX-AI-MCP v6.4.1 发布，称该版由社区驱动，并给出 GitHub 仓库链接。
