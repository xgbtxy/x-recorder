# 批次 emshop-c 摘要 · EM 风格价目店铺（2026-09-26）

提案人：小弟·TG  
统一前缀：**`[低价·bot·价目]`**  
目录：`drafts/deals/bots/em-shop/`  
约束：未写 `records/`、未 git push、未发帖/试单/对 bot·客服发交易消息、未 VIP 转发；**未** SSH dig / Telethon / 碰 session / 2FA。

## 本批交审（2）

| # | 文件 | Bot | 价目可见性 | 主出处 |
|---|------|-----|------------|--------|
| 1 | `bot-veriyfer-store-pricelist.md` | `@Veriyferbot`（客服 `@VeirfyerSupportbot`） | 公开频道多帖美元表（Verify/Store） | `veriyfyer/93,98,137,144,117`（辅 169/89） |
| 2 | `bot-cp669912-ai369999-pricelist.md` | `@Cp669912_bot`（客服 `@cpai88_bot`） | 公开频道人民币多品代充价目表 | `ai369999/318`（辅 320） |

## 同目录并行（不叠交）

| 文件 / 状态 | 说明 |
|-------------|------|
| `bot-jeroaccounts-support-menu.md` | 仍在草稿；msgid 公开未检出；**本批不改不覆盖** |
| `records/other/em-shop/` 已入库 ver_pixel / NovaStore / UPE / geminiprosub / Shop_Ayham 等 | **不重写** |

## 跳过

| 对象 | 原因 |
|------|------|
| RichAI / Canvora / crassus / AIVerseX / Pixora / geminiprosub / Shop_Ayham / ver_pixel / NovaStore / UPE | 已入库 `records/other/em-shop/` |
| `@Gemini_shop_robot` / Warzone / AiSubShop / storeBatman / 既有 `records/other/bot-*.md` | 总目录已有 |
| `@Qamify_bot` `@ZinoShopbot` `@NyStoreOfficialBot` `@Paglu_*` `@AIXpress_Bot` 等 | Gemini 同质闪购跳过 |
| `@MMMARKETTBOT` | bot/评价频道 `@hqfback` 可开，但**公开 TG 窗无 $ 多品价目帖**（论坛价被 CF 挡，不硬凑 msgid） |
| `@YOLOGPT4bot` / `@aichatgpt4o` | 公开帖多品类但**仅见单档 150 元**；bot 偏双向客服非店菜单 |
| `@gpt6688` / acc199 | 自称价目表但近窗**无数字价**；入口为人客服+网站，非店铺 bot |
| `goplus.pro` | 站点有多品 ¥ 表，**未挂可核 @bot** |
| `geminipro_shop` + `@Gemini_Center` | 有 تومان价，入口为**人工号**非店铺 bot（与 EM-P 同判） |
| `substore_market` / Sellzivo / VaultXStore 公开窗 | 无新可用 $ 表 / 预览空 |
| Jero | 不编造 msgid；保留原草稿 |

## 排查范围（公开源）

- WebSearch：STOCK/PRICELIST/代充价目表；Veriyfer / Medellín / 中文代充频道
- 公开预览：`veriyfyer`（含 before= 翻页）、`ai369999`、`gemini12pro_channel`、`fork_bot_channel`、`geminipro18`、`hqfback`、`gpt6688`、`aichatgpt4o` 等
- curl 核 bot og（Veriyfer / Cp669912 / MMMARKETT / YOLOGPT4 等）；**未**入群、**未**对 bot 下单

## 风险口径

观察 ≠ 推荐购买。价目远低于官方、验机/Session、成品号、仿冒客服、跑路等已写入各稿。

## 文件清单

- 新建：`bot-veriyfer-store-pricelist.md`、`bot-cp669912-ai369999-pricelist.md`
- 本摘要：`_batch-2026-09-26-emshop-c-summary.md`
- 未改：`bot-jeroaccounts-support-menu.md`
