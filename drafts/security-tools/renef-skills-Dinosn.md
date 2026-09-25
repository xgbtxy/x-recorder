# renef-skills：Android ARM64 动态插桩 Agent Skill（renef.io）

- 状态：候选
- 分类：security-tools（兼 ai-resources）
- 记录日期：2026-09-25
- **来源 X（必填）**：https://x.com/Dinosn/status/2070800787542864054
- 作者：@Dinosn
- 推文时间：2026-06-27 09:25:56 UTC（约 2026-06-27 17:25 CST）

## 关键点

- 公开 **renef-skills**：给 Claude Code / OpenCode 用的 Agent Skill，用于操作 [renef.io](http://renef.io) 做 Android ARM64 动态插桩相关工作流。
- 帖内能力标签含 hook native/Java、内存补丁、syscall 追踪，以及与 Frida / GameGuardian 脚本迁移相关的表述（**只记标签，不写绕过或脚本细节**）。
- 与已入库 frida-ssl-bypass / Beerus 等互补：本条是 renef 平台上的 Skill 入口。

## 落地链接（可选）

- 仓库：https://github.com/vichhka-git/renef-skills
- 平台：http://renef.io

## 价值判断

- 为什么值得记：命中 Frida / Agent reverse / @Dinosn；仓库可开。
- 风险 / 待核实：双刃工具（含 pinning/root 相关宣传）；仅入口索引，禁止当教程或 PoC 转载。renef 平台本身需另核可信度。

## 原文摘要（可选）

@Dinosn 介绍用于操作 renef.io 的 Agent Skill，并给出 GitHub 仓库链接。
