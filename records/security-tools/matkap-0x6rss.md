# Matkap：用 JADX MCP 辅助挖恶意 Telegram bot 的开源面板

- 状态：已核
- 分类：security-tools
- 记录日期：2026-09-25
- **来源 X（必填）**：https://x.com/0x6rss/status/2092295504533012775
- 作者：@0x6rss
- 推文时间：2026-08-25 16:58:15 UTC（约 2026-08-26 00:58 CST）

## 关键点

- 作者开源 **Matkap**（帖称 weaponized web 版）：面向威胁狩猎 / 恶意软件分析的面板，聚焦滥用 Telegram bot 作 C2 的线索汇聚。
- 与网安关键词相关的一点：帖内称可结合 **JADX MCP** 从 Android 恶意样本侧抽取 bot token / chat ID 等指标（只记能力标签，不写抽取步骤）。
- 同帖还提到对接 urlscan / ThreatFox / ZoomEye / MalwareBazaar 等公开情报源做汇聚。

## 落地链接（可选）

- 仓库：https://github.com/0x6rss/matkap（作者同名账号仓库，页面可开；帖正文未贴直链，以作者官宣帖 + 同名仓核对）

## 价值判断

- 为什么值得记：JADX MCP × Android 恶意分析工作流入口；有可核 X 出处与可打开仓库。
- 风险 / 待核实：帖未直接贴 GitHub URL，落地仓按作者/项目名核对；「weaponized」宣传口径需保持入口索引，不转载利用细节。

## 原文摘要（可选）

作者宣布 Matkap Web 版开源，介绍恶意 Telegram bot 狩猎面板能力，并点到 JADX MCP 用于 Android 样本侧指标提取。
