# Pi：Earendil 开源 coding agent harness（npm 可装）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/badlogicgames/status/2100248057413558600
- 作者 / 频道：@badlogicgames（Mario Zechner）
- 发布时间：2026-09-16 23:38 CST（UTC+8）

## 关键点

- Mario 预告 **Pi 3.14**：定位为「just a new harness」——极简、可扩展的终端 coding agent 运行时。
- 可动手落地：网站 https://pi.dev/ ；仓库 https://github.com/earendil-works/pi ；CLI 包 `@earendil-works/pi-coding-agent`（npm 可查，示例 `npm i -g @earendil-works/pi-coding-agent`，以 README 为准）。
- 能力面：read / bash / edit / write 等工具、多模型、可自扩展；文档强调默认无内置强权限沙箱，生产环境需自行容器化。
- 与已入库 OpenClaw 有渊源（历史上曾作为其最小 agent），但本条记 **独立 Pi harness / CLI**，勿与 OpenClaw 发行版混为一条。

## 落地链接（可选）

- 官网 / 文档：https://pi.dev/ ；https://pi.dev/docs/latest
- 仓库：https://github.com/earendil-works/pi
- npm：https://www.npmjs.com/package/@earendil-works/pi-coding-agent

## 价值判断

- 为什么值得记：开源、可 npm 安装的最小 harness，便于对照 OpenCode / Crush 等重量级 TUI agent。
- 风险 / 待核实：帖文本身极短（预告口径）；星数约 109324（earendil-works/pi，2026-09-26 核）；默认无沙箱——本地跑需注意权限。

## 原文摘要（可选）

摘要：@badlogicgames 预告「pi 3.14，下周五，只是一个新 harness」。

## 与其他条目的关系（可选）

开源 agent harness；非 mini-SWE / Cline / Crush / Goose / OpenCode / Cua；与 OpenClaw 相关但条目独立。
