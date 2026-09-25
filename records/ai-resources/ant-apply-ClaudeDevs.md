# ant apply：用仓库文件声明并同步 Claude Managed Agents 资源

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/ClaudeDevs/status/2095651107645145538
- 作者 / 频道：@ClaudeDevs
- 发布时间：2026-09-03 23:12:14 UTC（约 2026-09-04 07:12 CST）

## 要点

- Anthropic 官方开发者账号宣布：`ant` CLI 新增 **`ant apply`**，可把 Claude Managed Agent 的 environments、agents、skills、memory stores、deployments 写成仓库内文件，再与平台 API 资源双向同步。
- 面向「Agent 平台资源即代码」：本地/CI 用同一套声明文件创建或更新远端资源，并跟踪 ID/版本（官文提到 lock 文件机制，细节 **待核实**）。
- 可动手入口：官方文档页（见落地链接）；需已安装可用的 `ant` CLI（版本门槛 **待核实**）。

## 落地链接（可选）

- 文档：https://platform.claude.com/docs/en/cli-sdks-libraries/cli/apply

## 价值判断

- 为什么值得记：官帖可核 + 文档可点开；补「Claude 平台资源 IaC / 部署同步」轴，不是又一个模型发版。
- 风险 / 待核实：Managed Agents 配额与计费、`ant` 最低版本、lock 文件与 CI 示例以官方文档为准；面向 Claude 平台生态，非通用跨厂商 harness。

## 原文摘要（可选）

摘要：@ClaudeDevs 宣布 `ant apply`，可用仓库文件声明 Managed Agent 环境/技能/记忆库等并用 CLI 与 API 同步。

## 与其他条目的关系（可选）

同厂 Claude 开发者工具轴，但本条是 **平台资源声明/同步（ant apply）**；勿与同批「claude plugin eval」（插件/技能评测 CLI）或 Claude Design/Docs 产物能力混为同一项。非已入库 Agents API（OpenAI）或各类第三方 Agent Skills 目录。
