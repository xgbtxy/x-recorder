# Claude Code 支持 AGENTS.md（无 CLAUDE.md 时回落）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-25
- **平台**：X
- **来源（必填）**：https://x.com/trq212/status/2101009392611278961
- 作者 / 频道：@trq212
- 发布时间：2026-09-18 18:04:08 UTC（约 2026-09-19 02:04 CST）

## 要点

- 宣布 Claude Code **2.1.277** 起支持开放约定 **AGENTS.md**：目录无 `CLAUDE.md` 时自动读取并使用 `AGENTS.md`。
- 可在 `/config` 开关该行为；便于与 Cursor / Codex 等共用同一份 agent 说明，少维护双份指令文件。
- 规格入口：https://agents.md/

## 落地链接（可选）

- 约定说明：https://agents.md/
- 来源帖：https://x.com/trq212/status/2101009392611278961

## 价值判断

- 为什么值得记：Claude Code 社区/宿主侧可立刻动手的配置互通点，降低多 Agent 项目指令分叉；非已入库 /simplify+/batch。
- 风险 / 待核实：作者身份/是否官方雇员未在帖中自证，以版本号与本地 `/config` 实测为准；与 CLAUDE.md 优先级、嵌套目录行为「待核实」。

## 原文摘要（可选）

摘要：称自 2.1.277 起，无 CLAUDE.md 时 Claude Code 会使用 AGENTS.md，并可在 /config 切换。
