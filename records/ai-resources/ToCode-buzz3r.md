# ToCode：把二进制导出成源码形态给 Agent

- 状态：已核
- 分类：ai-resources（兼 security-tools）
- 主目录：`records/ai-resources/`（README 索引兼列 security-tools）
- 记录日期：2026-09-25
- **来源 X（必填）**：https://x.com/buzz3r_/status/2063486884806832200
- 作者：@buzz3r_
- 推文时间：2026-06-07 05:03:05 UTC（约 2026-06-07 13:03 CST）

## 关键点

- Agent 逆向思路：导出为源码形态，便于本地推理。
- 目标是构建可查询的二进制 oracle，而不是只做一次性反编译。
- 讨论语境常与 ASC / Agent 友好逆向一起出现（参见 `records/security-tools/ASC-root-narrative-MGAldys4.md`、`reverse-skill-bigaiguy.md`）。

## 落地链接（可选）

- 仓库：https://github.com/buzzer-re/ToCode（注意拼写是 **ToCode**，不是 ToCo）

## 价值判断

- 为什么值得记：AI 资源 × 逆向交叉点清晰；支持 IDA Pro / radare2 / angr / Binary Ninja 等（以 README 为准）。
- 风险 / 待核实：先读 README 确认适用目标格式与成熟度；星数以仓库页为准（抽查约 38★）。

## 原文摘要（可选）

在 ASC/Agent 逆向讨论线程中被引用的项目帖；本条以该 status 链接为唯一来源。
