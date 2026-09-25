# 批次 emshop-d 摘要 · EM 风格价目店铺（2026-09-26）

提案人：小弟·TG  
统一前缀：**`[低价·bot·价目]`**  
目录：`drafts/deals/bots/em-shop/`  
约束：未写 `records/`、未 git push、未发帖/试单/对 bot·客服发交易消息、未 VIP 转发；**未** SSH dig / Telethon / 碰 session / 2FA。

## 本批交审（2）

| # | 文件 | Bot | 价目可见性 | 主出处 |
|---|------|-----|------------|--------|
| 1 | `bot-substore-market-rub.md` | `@Substor_bot`（下单观察 `@SubStore01`；话术 `@SubStore`） | 公开频道卢布多品总表 + Cursor 三档 | `SubStore_market/944,1097,1087`（辅 986） |
| 2 | `bot-subscriptiondotcheap-catalog.md` | `@SubscriptionDotCheap_bot`（客服 `@Kevillionaire`） | 公开站 `/products/*` 多品 From $ | https://subscription.cheap/ + 代表性商品页 |

> **宁缺**：可核、≥2 行标价、店铺 bot（非纯人工）且未撞库者本批 2 条；未硬凑第 3 条。

## 同目录并行（不叠交）

| 文件 / 状态 | 说明 |
|-------------|------|
| `bot-jeroaccounts-support-menu.md` | 仍在草稿；msgid 公开未检出；**本批不改不覆盖** |
| EM-Q 已交并入库 `nevakeystore` / `chatgpt_aboutshop` | **不重写** |
| `records/other/em-shop/` 已入库 RichAI / Canvora / crassus / AIVerseX / Pixora / geminiprosub / Shop_Ayham / ver_pixel / NovaStore / UPE / Veriyfer / Cp669912 等 | **不重写** |

## 跳过

| 对象 | 原因 |
|------|------|
| RichAI / Canvora / crassus / AIVerseX / Pixora / geminiprosub / Shop_Ayham / ver_pixel / NovaStore / UPE / Veriyfer / Cp669912 / nevakeystore / aboutshop | 已入库或并行已交 |
| `@Gemini_shop_robot` / Warzone / AiSubShop / storeBatman / 既有 `records/other/bot-*.md` | 总目录已有 |
| `@Qamify_bot` `@ZinoShopbot` `@NyStoreOfficialBot` `@Paglu_*` `@AIXpress_Bot` `@gemini_subscribe_bot` | Gemini 同质单品闪购跳过 |
| `@Chatgpt_storebot`（Dazai） | bot/客服 og 可开，**关联频道公开预览几乎无帖、无核验价表** |
| `@GemPeakBot` / gempeak.ir | 价目多但下单主入口人工 `@GemPeakSup`（与 EM-Q 同判） |
| `@GptPlusEshtrakiBot` / 仅人工波斯语号 | 同「仅人工号」口径 |
| `@SellzivoBot` / `@sellzivo` | 频道公开预览 0 帖 |
| `@MedicAccounts_bot` | 有 Amboss $ 价，**医学生工具垂直店**，非本专项 AI/CapCut 同型 |
| `@VIPresellerPanel_Bot` | 仅见 GitHub README 捆绑价，**无公开 TG 价目帖/站内目录可核链** |
| `goplus.pro` | 站有 ¥ 表，**页内未挂可核 @bot**（`@goplus_bot` og「Plusik」未互证） |
| `mfatools` / `@mfatool` | 公开有 Canva $ 帖，入口为 **人工 DM** 非店铺 bot 菜单 |
| Jero | 不编造 msgid；保留原草稿 |

## 排查范围（公开源）

- WebSearch：STOCK/PRICELIST/代充价目；subscription.cheap；波斯语 تومان 店；SubStore
- 公开预览：`SubStore_market`（含 before= 翻页）、`Cheap_UltraGptCursor`、`gemini12pro_channel`、`gemini_rev`、`sellzivo`、`DazaiGPT`、`Uptodate_accounts`、`mfatools` 等
- 公开网页：https://subscription.cheap/ 及 `/products/*`；https://goplus.pro/；https://gempeak.ir/shop/
- curl 核 bot/客服 og（Substor / SubscriptionDotCheap / Dazai / Sellzivo / GemPeak 等）；**未**入群、**未**对 bot 下单

## 风险口径

观察 ≠ 推荐购买。价目远低于官方、成品号/预激活、代付绑号、仿冒客服、人工 DM 成交、跑路等已写入各稿。

## 文件清单

- 新建：`bot-substore-market-rub.md`、`bot-subscriptiondotcheap-catalog.md`
- 本摘要：`_batch-2026-09-26-emshop-d-summary.md`
- 未改：`bot-jeroaccounts-support-menu.md`
