# Google Workspace CLI（gws）：人类 + Agent，附带 40+ Agent Skills

- 状态：候选
- 分类：ai-resources
- 记录日期：2026-09-25
- **来源 X（必填）**：https://x.com/addyosmani/status/2029372736267805081
- 作者：@addyosmani
- 推文时间：2026-03-05 01:45:38 UTC（约 2026-03-05 09:45 CST）

## 要点

- Addy Osmani 介绍 `googleworkspace/cli`（命令名 `gws`）：一个 CLI 覆盖 Drive/Gmail/Calendar 等 Workspace API，面向人类与 AI agent。
- 仓库自述包含 **40+ agent skills**；运行时按 Google Discovery Service 动态生成命令面，JSON 结构化输出，方便 agent 调用。
- 安装：GitHub Releases 二进制 / `npm i -g @googleworkspace/cli` / Homebrew 等；需自备 GCP OAuth。

## 落地链接（可选）

- 仓库：https://github.com/googleworkspace/cli
- npm：https://www.npmjs.com/package/@googleworkspace/cli

## 价值判断

- 为什么值得记：可下载可跑的「agent skills」打包资源，把 Workspace 操作变成 agent 可调用技能。
- 风险 / 待核实：README 写明非 Google 官方支持产品；星数「待核实」；OAuth/GCP 配置有门槛；API 面仍在活跃开发，可能有破坏性变更。

## 原文摘要（可选）

摘要：宣布 Google Workspace CLI，链到 GitHub，强调为人类和 agent 构建，并称含 40+ agent skills。
