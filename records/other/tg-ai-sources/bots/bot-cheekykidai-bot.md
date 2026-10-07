# CheekyKid Store

- 状态：**已下架（REJECTED，2026-10-08：店方频道卖 Claude API token，另卖含邮箱/密码/2FA 的 JSON Codex 登录凭证）**
- 审核：2026-10-03 仅公开预览核对。
- 记录日期：2026-10-03
- 提案人：小弟·TG群bot
- **Bot 用户名**：`@CheekyKidAI_bot`
- **发现于哪个群组**：频道 Da Anh Đen（`@ChuBeThatTha`，https://t.me/ChuBeThatTha）。这是频道，不是群。非转发帖 https://t.me/ChuBeThatTha/124 、https://t.me/ChuBeThatTha/137 、https://t.me/ChuBeThatTha/138 正文点名本 bot。简介里的 `@CheekyKidAI` 是另一个联系人，不是本 bot，不建联系人档。已登录账号于 2026-10-03 曾 Start 本 bot；本批没有再打开客户端。
- **售卖内容**：启动页标题 CheekyKid Store。文案只写用 /start 开始购买，更新看 `t.me/ChuBeThatTha`，支持 `@nthai1702`。没有商品表。频道转发帖的来源名是 CheekyKid Store，和本 bot 的显示名相同，但那些帖是转发，不是启动页价目。
- **公开价格（如有）**：启动页 https://t.me/CheekyKidAI_bot 没有数字价。转发自 CheekyKid Store 的 https://t.me/ChuBeThatTha/128（2026-09-02 18:13 上海，`$0.24`）、/130（2026-09-04 04:01 上海，`$0.24`）、/133（2026-09-06 04:46 上海，`$0.16`）不当 2026-10 现价。客户端菜单价不写。
- **来源消息链接**：https://t.me/ChuBeThatTha/138
- **风险**：买卖 bot。转发库存价不能当成启动页或 10 月现价。可能是账号或会员转售。不立 em-shop。观察不等于推荐。

> 观察不等于推荐；只读，不发消息、不下单、不试购。

## 公开页实见（2026-10-03 curl）

- https://t.me/CheekyKidAI_bot HTTP 200
- og:title：`CheekyKid Store`
- tgme_page_extra：`@CheekyKidAI_bot`
- 简介原文：`Use /start to begin shopping.` / `Updates & Announcements: t.me/ChuBeThatTha` / `Support: @nthai1702`
- 有 Start Bot 按钮。无价格。
- 对照：https://t.me/CheekyKidAI 的 og:title 是 `Telegram: Contact @CheekyKidAI`。那是联系人，不是本 bot。

## 去重

- `records/` 与 `drafts/tg-ai-sources/`、`drafts/deals/tg-catalog/` 没有 `@CheekyKidAI_bot` 的已有档。不建第二份，也不给 `@CheekyKidAI` 建档。频道档：`drafts/tg-ai-sources/groups/group-chubethattha.md`。

## ⛔ 下架（老大 2026-10-08）

- 店方频道 @ChuBeThatTha 原帖（老大 10-08 `chk.sh` embed 复核原帖，均非转发；时间为上海）：
  - https://t.me/ChuBeThatTha/39（2026-07-15 17:42）价目长帖一行「🏷️  API Token Claude chỉ từ 39k (Full model Claude Opus, Sonet, Haiku)」
  - https://t.me/ChuBeThatTha/131（2026-09-05 20:56）「ChatGPT Free đã Ver Phone Codex … 4K 💵 | 0.15💰 / 3K5 💵 | 0.14💰」「Định dạng : JSON CODEX (Trong Json có chứa email, pass, 2fa)」，另附 JSON Codex 自动登录工具（链接不收录）
- 同运营依据：频道简介点名 `@ChuBeChamChi_bot`；`@ChuBeChamChi_bot`、`@CheekyKidAI_bot` 启动页都把更新指向 t.me/ChuBeThatTha，支持同为 `@nthai1702`；/124、/137、/138 正文并列两 bot。
- 卖 JSON 登录凭证 + API token，整店下架（两个 bot + 频道）。线索：小弟·便宜店 已入库店 API 额度排查（2026-10-08）；/131 由老大补。
