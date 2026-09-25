# 批次 emshop-f 摘要 · EM 风格价目店铺（2026-09-26）

提案人：小弟·TG  
统一前缀：**`[低价·bot·价目]`**  
目录：`drafts/deals/bots/em-shop/`  
约束：未写 `records/`、未 git push、未发帖/试单/对 bot·客服发交易消息、未 VIP 转发；**未** SSH dig / Telethon / 碰 session / 2FA；**未**碰私密群翻帖。

## 本批交审（2）

| # | 文件 | Bot | 价目可见性 | 主出处 |
|---|------|-----|------------|--------|
| 1 | `bot-zykoland-catalog.md` | `@ZykoLand_bot`（频道 `@ZykoLand`） | 公开论坛卢布多品表 + 频道 $ 询盘/补货 msgid | mipped ZykoLand 帖；辅 `ZykoLand/392,395,403,407,393,411` |
| 2 | `bot-premium-shop-rub.md` | `@Premium_Shop_bot`（客服 `@MegaSEmka`） | 公开论坛卢布多品（ChatGPT/Claude/MS 等） | mipped Premium Shop 帖 |

> **宁缺**：可核、≥2 行标价、店铺 bot（非纯人工）且未撞库者本批 2 条；未硬凑第 3 条。

## 同目录并行（不叠交）

| 文件 / 状态 | 说明 |
|-------------|------|
| `bot-jeroaccounts-support-menu.md` | 仍在草稿；msgid 公开未检出；**本批不改不覆盖** |
| emshop-e 已交 `taynikstore` / `storeluma`（已入库） | **不重写** |
| emshop-d 已交并入库 `Substor` / `SubscriptionDotCheap` | **不重写** |
| EM-R / emshop-c 等已入库 ParsGPT / nevakeystore / aboutshop / Veriyfer / Cp669912 等 | **不重写** |
| `records/other/em-shop/` 全量已入库（含 taynikstore storeluma Substor 等） | **不重写** |

## 跳过

| 对象 | 原因 |
|------|------|
| RichAI / Canvora / crassus / AIVerseX / Pixora / geminiprosub / Shop_Ayham / ver_pixel / NovaStore / UPE / Veriyfer / Cp669912 / nevakeystore / aboutshop / Substor / SubscriptionDotCheap / taynikstore / storeluma / ParsGPT | 已入库或并行已交 |
| `@Gemini_shop_robot` / Warzone / AiSubShop / storeBatman / 既有 `records/other/bot-*.md` | 总目录已有 |
| `@Qamify_bot` `@ZinoShopbot` `@NyStoreOfficialBot` `@Paglu_*` `@AIXpress_Bot` `@gemini_subscribe_bot` | Gemini 同质单品闪购跳过 |
| `@Chatgpt_storebot`（Dazai） / `@SellzivoBot` / `@shopgojobot` | og 空壳或公开预览无价帖（与前批同判） |
| `@GemPeakBot` / gempeak.ir / `@GptPlusEshtrakiBot` | 价目多但下单主入口人工号 |
| `tuzifaka.net` / `@babywinwin` / `kikiai.store` / `@KiKi_love888` / `@vacklink` | 仅人工或无店铺 bot |
| `@shompol_bot` | 前批宁缺（bot 身份弱）；不重开 |
| `@ArianaProToolsBot` / arianaprotools.com | 首页有 AFN 多品，但 ChatGPT/CapCut 等 SKU 页 **404**、成交 CTA 偏 WhatsApp；本批已有 Zyko/Premium，**不凑第 3** |
| `@Mironovshop_bot` | 论坛主推 Gemini 账号档；评论质疑「Бот помер？」；偏单品垂直，宁缺 |
| CrashyShop / `@crashystxmm` | 论坛有价，**自动化 bot 用户名公开未检出**（仅「ТЫК」）；现联系为人工号 |
| `@spotifylobby` / `@SpotifyLobbyPremium` | 频道有价，入口**纯人工经理** |
| `@SubsMarketBot` / subs.market | 前批已判公开未核出稳定 ≥2 行标价 |
| `@gpt_eshop_bot` | og 仅 OpenAI 账号店摘要，**无公开多品价表可核链** |
| `goplus.pro` / `mfatools` | 同前批：无互证 bot 或仅人工 DM |
| Jero | 不编造 msgid；保留原草稿 |

## 排查范围（公开源）

- WebSearch：STOCK/PRICELIST；mipped ZykoLand / Premium Shop / CrashyShop / Shompol / Mironov；arianaprotools；spotifylobby
- 公开预览：`ZykoLand`/`Zykoland`（含 msgid 映射）、`arianaprotools`、`spotifylobby` 等
- 公开网页：mipped 上述帖；https://arianaprotools.com/ 及 `/product/*` 抽样（部分 404）
- curl 核 bot/客服/频道 og（ZykoLand_bot / ZykoLand / Premium_Shop_bot / MegaSEmka / ArianaProTools / Mironovshop / crashystxmm / gpt_eshop / SubsMarket 等）；**未**入群、**未**对 bot 下单

## 风险口径

观察 ≠ 推荐购买。价目远低于官方、成品号/NW 无 гарантии、代激活要密码、仿冒客服、论坛价与店内实时价漂移、跑路等已写入各稿。

## 文件清单

- 新建：`bot-zykoland-catalog.md`、`bot-premium-shop-rub.md`
- 本摘要：`_batch-2026-09-26-emshop-f-summary.md`
- 未改：`bot-jeroaccounts-support-menu.md`
