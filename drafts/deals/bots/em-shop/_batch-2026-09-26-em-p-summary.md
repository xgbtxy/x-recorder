# 批次 EM-P 摘要 · em-shop 价目店铺（2026-09-26）

提案人：小弟·低价资源  
统一前缀：**`[低价·bot·价目]`**  
目录：`drafts/deals/bots/em-shop/`  
约束：未写 `records/`、未 git push、未发帖/试单/对 bot 下单。

## 本批新交（3）

| # | 文件 | 店铺 bot | 客服（分开写） | 价目行数 | 关键出处 |
|---|------|----------|----------------|----------|----------|
| 1 | `bot-ver-pixel-fork-stock.md` | `@ver_pixel_bot` | `@leo_dfx`（批发/观察） | **5** | `fork_bot_channel/1158,1155,1148,1160`；辅 `gemini12pro_channel/152`（无 $） |
| 2 | `bot-upe-pebot-gptru.md` | `@u_pebot`（观察 `@upeesbot`） | `@upe4d`；Admin `@at_0m`；办理观察 `@creativerelab` | **7** | https://gptru.pro/tg-shop/（JSON-LD RUB）；辅 `u_pre/6868` |
| 3 | `bot-novastore-ai-pricelist.md` | `@novastore_ai_bot` | `@chat_admin90` | **5** | `novastore_ai/128,129`（辅 127） |

> **并行说明**：同窗 `emshop-b`（小弟·TG）摘要亦列入 `@ver_pixel_bot` 同路径文件；**不删不覆盖**，以目录现稿为准。EM-P 独有增量主要是 `#2 u_pebot`、`#3 novastore`。`emshop-b` 另交的 `@geminiprosub_bot` / `@Shop_Ayham_bot` **本批不重写**。

## 跳过

| 对象 | 原因 |
|------|------|
| `@crassus_market_bot` `@AIVerseXBot` `@Pixora_Tunisie_bot` | 已入库 `records/other/em-shop/` |
| `@RichAIStoreBot` `@canvora24bot` | 已入库；emshop-a 已交 |
| Jero / `@JeroAccountsBot` | 草稿保留；msgid 公开未检出；**不重复交** |
| `@geminiprosub_bot` `@Shop_Ayham_bot` | **并行 emshop-b 已交**（`geminipro18` / `ayhamdigital`）；不重写 |
| `@EliteMethodsStoreBot` / escrow / 举报 bot | 已入库；非价目店 |
| `@WarzoneShopBot` `@Gemini_shop_robot` `@AiSubShop_bot` `@AithSubscriptions_bot` `@VouchersShopBot` `@ExcaliburTechBot` `@TrustedShopingbot` `@Prime_Gadget_Store_bot` `@storeBatmanBot` `@toolswala_bot` 等 | `records/other/bot-*.md` 已有 |
| `@Qamify_bot` `@ZinoShopbot` `@NyStoreOfficialBot` `@Paglu_*` `@AIXpress_Bot` | 闪购控量 |
| `@nevakeystore_bot` | `gemini12pro_channel/163` 仅品类话术，无公开 $ 表 |
| `@Gemini_Center` + `geminipro_shop` | 公开有 تومان价，入口为**人工号**非店铺 bot |
| `@Sellzivo` / `@sellzivobot` | 频道公开预览 0 帖 |
| `substore_market` / `@Substor_bot` | INFO 频道公开窗无标价数字 |
| `elitemethodchat` / `chatgptplusbuysell` | join gate / 无帖体；不靠买卖群入门 |

## 排查范围（公开源）

- WebSearch：`t.me` Gemini/CapCut bot price channel；UPE4D / SubStore / Sellzivo / RichAI
- 公开预览：`gemini12pro_channel`、`fork_bot_channel`、`u_pre`、`novastore_ai`、`substore_market`、`geminipro_shop`、`richaistore`（已入库）
- 公开网页：https://gptru.pro/tg-shop/（schema.org Product/Offer）
- 扫描：`_scan-raw-2026-09-25.txt`（撞库+闪购过滤）
- curl 核 bot/客服 og；**未**入群、**未**对 bot 下单

## 风险口径

观察 ≠ 推荐购买。价目远低于官方、共享席位、凭证交付、仿冒客服、跑路等已写入各稿。

## 文件清单

- 新建：`bot-ver-pixel-fork-stock.md`、`bot-upe-pebot-gptru.md`、`bot-novastore-ai-pricelist.md`
- 本摘要：`_batch-2026-09-26-em-p-summary.md`
- 未改：`bot-jeroaccounts-support-menu.md`（保留）
