# Cua Driver：开源 Computer-Use 驱动（MCP + Agent Skill）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/trycua/status/2103498682532253734
- 作者 / 频道：@trycua
- 发布时间：2026-09-25 14:55 UTC（约 2026-09-25 22:55 CST）

## 要点

- 宣布 **Cua Driver** 稳定版（帖侧重 Omarchy/Hyprland 原生合成光标与 OS 级 multi-cursor computer use）；开源入口 `github.com/trycua/cua`。
- 可装：本机安装 `cua-driver` 后，用 MCP 挂到 agent：`claude mcp add --transport stdio cua-driver -- cua-driver mcp`；另可用 `cua-driver skills install` 写入 Claude Code / Codex 等 skills 目录（或 ClawHub `@cua/driver`）。
- 定位：给 coding/computer-use agent 可检查与操作本机/远程桌面的驱动层，补「只会改文件、摸不到 GUI」缺口。

## 落地链接（可选）

- 仓库：https://github.com/trycua/cua
- 产品页：https://cua.ai/cua-driver
- Skill 安装文档：https://cua.ai/docs/how-to-guides/driver/install-agent-skill

## 价值判断

- 为什么值得记：开源 computer-use 驱动 + 标准 MCP/Skill 入口，可动手验证。
- 风险 / 待核实：星数/跨平台完整度「待核实」；本机 Accessibility/录屏权限敏感；帖文偏 Omarchy 场景，其他 OS 以文档为准；勿与已入库 OpenClaw 产品本体混淆（本条是 Cua Driver）。

## 原文摘要（可选）

摘要：@trycua 宣布 Cua Driver 稳定版，开源 computer-use 基础，并点名与 Omarchy/Hyprland 协作。

## 与其他条目的关系（可选）

与 OpenClaw / Playwright MCP / Chrome DevTools MCP 相邻但不同：偏 OS 级桌面操控驱动，而非浏览器自动化或 OpenClaw 发行版。
