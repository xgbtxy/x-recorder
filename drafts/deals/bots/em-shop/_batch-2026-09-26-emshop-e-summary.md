# 批次 emshop-e 摘要 · EM 风格价目店铺（2026-09-26）

提案人：小弟·TG  
统一前缀：**`[低价·bot·价目]`**  
目录：`drafts/deals/bots/em-shop/`  
约束：未写 `records/`、未 git push、未发帖/试单/对 bot·客服发交易消息、未 VIP 转发；**未** SSH dig / Telethon / 碰 session / 2FA。

## 本批交审（2）

| # | 文件 | Bot | 价目可见性 | 主出处 |
|---|------|-----|------------|--------|
| 1 | `bot-taynikstore-catalog.md` | `@taynikstore_bot`（客服 `@taynik_sup`） | 公开站 `/api/products` 多品 `$`/`₽` + 首页横幅 4.99$ | https://taynik.store/ + `/api/products`（辅 `/product/15` 等） |
| 2 | `bot-storeluma-market-rub.md` | `@storeluma_bot`（客服 `@salesluma`；旁路 `@vpnluma_bot`） | 公开论坛卢布多品表 + 频道 VPN 70 ₽ | mipped Luma 帖；辅 `storeluma/45,55,57` |

> **宁缺**：可核、≥2 行标价、店铺 bot（非纯人工）且未撞库者本批 2 条；未硬凑第 3 条。

## 同目录并行（不叠交）

| 文件 / 状态 | 说明 |
|-------------|------|
| `bot-jeroaccounts-support-menu.md` | 仍在草稿；msgid 公开未检出；**本批不改不覆盖** |
| emshop-d 已交并入库 `Substor` / `SubscriptionDotCheap` | **不重写** |
| EM-Q / emshop-c 等已入库 nevakeystore / aboutshop / Veriyfer / Cp669912 等 | **不重写** |
| `records/other/em-shop/` 全量已入库 | **不重写** |

## 跳过

| 对象 | 原因 |
|------|------|
| RichAI / Canvora / crassus / AIVerseX / Pixora / geminiprosub / Shop_Ayham / ver_pixel / NovaStore / UPE / Veriyfer / Cp669912 / nevakeystore / aboutshop / Substor / SubscriptionDotCheap | 已入库或并行已交 |
| `@Gemini_shop_robot` / Warzone / AiSubShop / storeBatman / 既有 `records/other/bot-*.md` | 总目录已有 |
| `@Qamify_bot` `@ZinoShopbot` `@NyStoreOfficialBot` `@Paglu_*` `@AIXpress_Bot` `@gemini_subscribe_bot` | Gemini 同质单品闪购跳过 |
| `@Chatgpt_storebot`（Dazai） / `@SellzivoBot` | og 空壳或公开预览无价帖（与 d 批同判） |
| `@GemPeakBot` / gempeak.ir / `@GptPlusEshtrakiBot` | 价目多但下单主入口人工号 |
| `tuzifaka.net` / `@babywinwin` | 站有 ¥ 多品，入口为**人工客服**非店铺 bot |
| `kikiai.store` / `@KiKi_love888` | 站/频道有品类，成交为**人工 DM**；首页 curl 几乎无公开价表 |
| `@vacklink` | 频道有 $ 促销，联系 Discord/WhatsApp，**无店铺 bot** |
| `@shopgojobot` | bot 可开但 og 无价；公开频道/价表未检出（空壳口径） |
| `@StorePremiumAccounts_bot` / `PremiumAccountsStore` | 公开窗为 IG/Netflix/工具交付回执，**非 AI/CapCut 同型价目店** |
| `@shompol_bot` / `t.me/shompoldigitalbot` | 论坛仅 2 行价；`shompoldigitalbot` 为 11 粉小频道「оп」，bot 身份弱，**宁缺** |
| `@larpshopAI_bot` | og 有品类，**无公开频道/站内数字价表** |
| `@ArianaProToolsBot` / arianaprotools.com | 站有 AFN 价 + bot 可开，但多品 CTA 偏 WhatsApp、部分 SKU 页 404；本批已有 Taynik/Luma，**不凑第 3** |
| `goplus.pro` / `mfatools` | 同前批：无互证 bot 或仅人工 DM |
| Jero | 不编造 msgid；保留原草稿 |

## 排查范围（公开源）

- WebSearch：STOCK/PRICELIST；mipped Luma/Shompol；taynik.store；arianaprotools；vacklink；kikiai；tuzifaka
- 公开预览：`storeluma`、`vacklink`、`kikiai999`、`PremiumAccountsStore`、`capcut4u`、`Farm_DeFi` 等
- 公开网页/API：https://taynik.store/ + `/api/products` + `/product/*`；mipped Luma 帖；https://arianaprotools.com/product/*；tuzifaka / kikiai 抽样
- curl 核 bot/客服 og（taynikstore / taynik_sup / storeluma / salesluma / vpnluma / ArianaProTools / shopgojo / shompol* 等）；**未**入群、**未**对 bot 下单

## 风险口径

观察 ≠ 推荐购买。价目远低于官方、成品号/продление、无 гарантии 档、仿冒客服、论坛价与店内实时价可能漂移、跑路等已写入各稿。

## 文件清单

- 新建：`bot-taynikstore-catalog.md`、`bot-storeluma-market-rub.md`
- 本摘要：`_batch-2026-09-26-emshop-e-summary.md`
- 未改：`bot-jeroaccounts-support-menu.md`
