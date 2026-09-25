# 批次 EM-Q 摘要 · em-shop 价目店铺（2026-09-26）

提案人：小弟·低价资源  
统一前缀：**`[低价·bot·价目]`**  
目录：`drafts/deals/bots/em-shop/`  
约束：未写 `records/`、未 git push、未发帖/试单/对 bot 下单。

## 本批新交（2）

| # | 文件 | 店铺 bot | 客服（分开写） | 价目行数 | 关键出处 |
|---|------|----------|----------------|----------|----------|
| 1 | `bot-nevakeystore-core-menu.md` | `@nevakeystore_bot` | `@NevaAI_Shop`（观察 `@Cynex88`） | **≥10**（/2 总表为主） | `nevakeystore/2,13,14,28`；辅 `gemini12pro_channel/163`（无 $） |
| 2 | `bot-chatgpt-aboutshop-toman.md` | `@Chatgpt_aboutshopBot` | `@orderabout` | **8** | `chatgpt_aboutshop/2257,2219,2253,2278`（辅 2215、819 总览） |

> **宁缺**：公开窗可核、≥2 行标价、店铺 bot（非纯人工）且未撞库者仅上表 2 条；未凑第 3 条。

## 跳过

| 对象 | 原因 |
|------|------|
| `@crassus_market_bot` `@AIVerseXBot` `@Pixora_Tunisie_bot` `@ver_pixel_bot` `@u_pebot` `@novastore_ai_bot` | 任务已列入库 / 撞库 |
| `@geminiprosub_bot` `@Shop_Ayham_bot` `@RichAIStoreBot` `@canvora24bot` | drafts/TG 已交或 `records/other/em-shop/` 已有 |
| `@Veriyferbot` `@Cp669912_bot` | 并行 emshop-c 已交并入库；不重写 |
| Jero / `@JeroAccountsBot` | 草稿保留；**不交** |
| `@Qamify_bot` `@ZinoShopbot` `@NyStoreOfficialBot` `@Paglu_*` `@AIXpress_Bot` | 闪购控量 |
| `@Gemini_shop_robot` / `Gemini shop ads` / `@storeBatmanBot` 等 | `records/other/bot-*.md` 已有 |
| `SubStore` / `@Substor_bot` | INFO 频道公开窗仅检出 **1** 条带 ₽ 促销（GPT Plus 1 990 ₽），不足 ≥2 品价目行 |
| `@GemPeak` / `@GemPeakBot` / 站 gempeak.ir | 公开价目多，但下单主入口 **`@GemPeakSup` 人工号**；StoreLexonBot 仅为 VPN 旁路 |
| `@GptPlusEshtrakiBot` / `gptpluseshtraki` | 价目帖大量指向 **`@GptPlusEshtrakiSupport` 人工**；跳过「仅人工号」口径 |
| `chatgpt_plus_eshteraki` | 仅人工 `@premium_sales_admin` |
| `@Joy_digitalmart` / `@On_Abuse` | 公开预览 0 帖；DM 人工 |
| `NevaAI_Shop` 作频道 | 无公开帖体；价目在 `@nevakeystore`（本批已交 bot） |
| `elitemethodchat` / `chatgptplusbuysell` | join gate / 无帖体；不靠买卖群入门 |

## 排查范围（公开源）

- WebSearch：`telegram bot Gemini Pro $0.` / CapCut / NordVPN pricelist；gptru 同类；波斯语 تومان 店
- 公开预览：`gemini12pro_channel`（翻页）、`fork_bot_channel`、`nevakeystore`、`chatgpt_aboutshop`、`gptpluseshtraki`、`GemPeak`、`substore_market`（`SubStore_market`）、`geminipro18`、`ayhamdigital` 等
- 公开网页：https://gptru.pro/tg-shop/（仍为已交 `@u_pebot` / `@upe4d`）；https://gempeak.ir/shop/
- curl 核 bot/客服 og；**未**入群、**未**对 bot 下单

## 风险口径

观察 ≠ 推荐购买。价目远低于官方、共享席位、凭证交付、仿冒客服、跑路、托曼量级歧义等已写入各稿。

## 文件清单

- 新建：`bot-nevakeystore-core-menu.md`、`bot-chatgpt-aboutshop-toman.md`
- 本摘要：`_batch-2026-09-26-em-q-summary.md`
- 未改：`bot-jeroaccounts-support-menu.md`（保留不交）
