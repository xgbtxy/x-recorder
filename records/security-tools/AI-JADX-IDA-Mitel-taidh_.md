# 案例：Claude + MCP 搭配 JADX / IDA 做补丁与根因分析

- 状态：已核（write-up 可打开；仅作 Agent+JADX/IDA 工作流案例索引，不收录 PoC）
- 分类：security-tools（兼 ai-resources）
- 记录日期：2026-09-25
- **来源 X（必填）**：https://x.com/taidh_/status/2072863860625989984
- 作者：@taidh_
- 推文时间：2026-07-03 02:03:50 UTC（约 2026-07-03 10:03 CST）

## 关键点

- 作者分享用 Claude（经 MCP）作为逆向助手，配合 **JADX** 与 **IDA Pro** 分析 Mitel MiCollab 相关 CVE 的补丁与根因。
- 价值在「Agent + 传统逆向工具链」的可复现工作流记录，不是新漏洞 PoC；文中指向完整 write-up。
- 与 JADX-AI-MCP / ASC 条目互补：本条是实战案例入口，前两者是工具入口。

## 落地链接（可选）

- Write-up：https://sec.vnpt.vn/2026/06/AI-Assisted-Mitel-CVE-Analysis-Claude-MCP-JADX-andamp-IDA-Pro

## 价值判断

- 为什么值得记：直接对应本轮关键词「jadx / Agent reverse」，可供对照 Agent 辅助静态分析怎么接到 JADX/IDA。
- 风险 / 待核实：效果为作者自述；write-up 是否持续可访问需抽查。只记公开方法叙述，不收录利用步骤。

## 原文摘要（可选）

作者称用 Claude via MCP 配合 JADX 与 IDA 做 Mitel CVE 分析效果不错，并给出完整文章链接。
