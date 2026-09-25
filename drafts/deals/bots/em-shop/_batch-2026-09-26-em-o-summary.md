# 批次 EM-O 摘要 · em-shop 价目店铺（2026-09-26）

提案人：小弟·低价资源  
统一前缀：**`[低价·bot·价目]`**  
目录：`drafts/deals/bots/em-shop/`  
约束：未写 `records/`、未 git push、未发帖/试单/对 bot 下单。

## 任务 A · Jero 回填

| 项 | 结果 |
|----|------|
| msgid | **未找到** |
| 公开预览 | `t.me/s/elitemethodchat` = join gate，无帖体（与 `_scan-em-2026-09-25.txt` META 一致） |
| 网页搜 | `JeroAccountsSupport` / `JeroAccountsBot` / `elitemethodchat` 无可用消息链 |
| EM 扫描 | 窗内无 Jero；仅有 `@EliteMethodsStoreBot` / escrow（已入库，跳过） |
| curl 核 | `@JeroAccountsBot` 标题「Jero Accounts」可 Start；`@JeroAccountsSupport` og「Official support for JeroAccountsBot @JeroAccountsBot」 |
| 草稿更新 | `bot-jeroaccounts-support-menu.md`：发现群写 elitemethodchat（注明 join gate）；**发现出处**改为「公开预览未检出；仍待补」；价目保持截图三档、**未编造 msgid、未臆造增补商品** |

## 任务 B · 新交（3）

| # | 文件 | 店铺 bot | 客服（分开写） | 价目行数 | 关键出处 |
|---|------|----------|----------------|----------|----------|
| 1 | `bot-crassus-market-subs.md` | `@crassus_market_bot` | `@crassus_support`（观察 `@markus_crassus`） | **5** | `crassus_market/43,59,60,74` |
| 2 | `bot-aiversex-hub-menu.md` | `@AIVerseXBot` | `@GT_VERIFIED` / `@AIVerseXSupport` | **7** | `gemini12pro_channel/162` + `AIVerseXHub/337,344,349` |
| 3 | `bot-pixora-tunisie-menu.md` | `@Pixora_Tunisie_bot`（同品牌观察 `@pixora_digital_bot`） | `@PixoraCS` | **3**（成交单价 2 + From 摘要 1） | `PixoraDigital/2725,2729` + `gemini12pro_channel/166` |

## 跳过

| 对象 | 原因 |
|------|------|
| `@EliteMethodsStoreBot` / `@scammersdeathbot` / `@nomorescammersbot` | 已入库；escrow/举报非价目店 |
| `@WarzoneShopBot` `@Gemini_shop_robot` `@AiSubShop_bot` `@AithSubscriptions_bot` `@VouchersShopBot` `@ExcaliburTechBot` `@TrustedShopingbot` `@Prime_Gadget_Store_bot` 等 | `records/other/bot-*.md` 已有 |
| M/N 批未入库稿 | BuyCard / WantToPay / RedotPay / kise / toolswala — 撞库跳过 |
| `@Qamify_bot` `@ZinoShopbot` `@NyStoreOfficialBot` `@Paglu_*` | 老大确认 Gemini 同质闪购跳过 |
| `@geminiprosub_bot` | og 有品类名，**无公开 $ 数字** |
| `@AIXpress_Bot` | 仅 Gemini 批量闪购，控量 |
| `@Shop_Ayham_bot` | 公开频道价目未在本批检出足够数字 |
| `elitemethodchat` 公开预览深挖 | **卡点**：join gate / 无 JS 可渲染帖体；curl 无 `data-post` |

## 卡点说明

- `t.me/s/elitemethodchat` 与 `t.me/s/chatgptplusbuysell`：公开预览无消息列表（群 join gate）。单条 `t.me/chatgptplusbuysell/<msgid>` 亦无 widget 正文可刮（与既有 Telethon 扫描窗互补，本批未再交互入群）。
- Jero msgid 需后续有登录只读窗或用户补链；**禁止编造**。

## 文件清单

- 更新：`em-shop/bot-jeroaccounts-support-menu.md`
- 新建：`em-shop/bot-crassus-market-subs.md`、`em-shop/bot-aiversex-hub-menu.md`、`em-shop/bot-pixora-tunisie-menu.md`
- 本摘要：`em-shop/_batch-2026-09-26-em-o-summary.md`
