# [TG] 公开优质频道候选（待小弟审计）

- 状态：候选
- 记录日期：2026-09-25
- 平台：Telegram
- 说明：仅调研公开频道；**不加入、不发帖、不建群**。链接均可网页预览核对。
- 排查备注：未收录 `@vxunderground`（恶意样本库，合规风险高）、`@cvebird`（推送噪声大且含 exploit/PoC 向内容）、`@GithubRedTeam`（偏后渗透/免杀，拿不准先不进初筛）。

| # | 频道 | 链接 | 方向 | 一句话价值 | 风险 |
|---|------|------|------|------------|------|
| 1 | HackGit `@hackgit` | https://t.me/hackgit | security-tools | 面向安全从业者的公开聚合（攻防/红队/BugBounty/OSINT 等），适合扫可入库工具线索 | 含 Malware Research 向内容，入库时只记公开工具名与官方入口 |
| 2 | Offensive OSINT `@offensiveosint` | https://t.me/offensiveosint | security-tools / other | 高频推送可点开的 OSINT 工具与链接（已核公开预览活跃），线索密度高 | 个别帖涉及社工/侦察手法，摘要只保留工具入口 |
| 3 | Agentic AI Coding `@ai_codin` | https://t.me/ai_codin | ai-resources | Claude / Cursor / Codex 等 Agent 编程动态日更，约 2.6 万订阅，贴合 x-recorder 的 AI 资源线 | 资讯向，需筛有落地链接的帖 |
| 4 | 网络安全笔记 `@tsecrecord` | https://t.me/tsecrecord | security-tools / ai-resources | 中文向「网安 + AI」笔记频道，约 7.9k 订阅，便于补中文圈线索 | 内容深浅不一，需逐条核出处 |
| 5 | sing-box 通知 `@yapnc` | https://t.me/yapnc | vpn-proxy | SagerNet/sing-box 官方文档列出的通知频道，发布开源代理平台更新 | 官方通知为主，订阅源/第三方节点另议 |
| 备选 | mihomo 通知 `@clashmeta` | https://t.me/clashmeta | vpn-proxy | MetaCubeX/mihomo（Clash Meta）官方通知频道，约 1.7 万订阅 | 同为官方发布；与 yapnc 二选一盯即可 |

## 建议盯法（待你拍板）

1. 初筛通过后，我每周从已批频道公开预览里抽 3–5 条可入库线索，按 `templates/record.md` 写短草稿（平台标 Telegram，带来源消息链接；若同源有 X 再补 X）。
2. 草稿只回传给你审计，GitHub 上传仍由你执行。
3. 若阿言另有指定频道，优先覆盖指定清单。
