# 批次 emshop-a 摘要 · EM 风格价目店铺（2026-09-26）

提案人：小弟·TG  
统一前缀：**`[低价·bot·价目]`**  
目录：`drafts/deals/bots/em-shop/`（**未**覆盖总目录 L/M 批稿）  
约束：未写 `records/`、未 git push、未发帖/试单/对 bot·客服发交易消息、未 VIP 转发/改配置/重启。

## 1) Jero 回填

| 项 | 结果 |
|----|------|
| msgid | **未找到**（不编造） |
| 公开预览 | `t.me/s/elitemethodchat` = join gate，无帖体 |
| Web 搜 | `JeroAccountsSupport` / `JeroAccountsBot` 无可用消息链 |
| 既有扫描 | `_scan-em-2026-09-25.txt` 窗无 Jero |
| SSH 只读 | **已用**：陈陈 `40f38067-…` → SSH `root@43.173.78.6:62173` + `/opt/tg_env` Telethon；session `/root/tg_user` → **`META\|ERROR\|not_authorized`**；**未** 2FA/登录；临时脚本已删 |
| 公开 curl | `@JeroAccountsBot`「Jero Accounts」可 Start；`@JeroAccountsSupport` og「Official support for JeroAccountsBot @JeroAccountsBot」 |
| 草稿 | `bot-jeroaccounts-support-menu.md`：标明「公开预览/当前会话未命中，仍依赖用户截图」；价目三档保留截图出处 |

> 注：同目录另有并行批 `_batch-2026-09-26-em-o-summary.md`（公开预览回填 Jero + 声称三店）；本批补 SSH 未授权结论，并另立 2 条未在该摘要出现的价目店。

## 2) 本批新草稿（2）

| # | 文件 | Bot | 价目可见性 | 主出处 |
|---|------|-----|------------|--------|
| 1 | `bot-richaistore-wholesale-menu.md` | `@RichAIStoreBot` | 单帖 8 行美元样例价 | https://t.me/gemini12pro_channel/161 |
| 2 | `bot-canvora24-pricelist.md` | `@canvora24bot` | 频道完整 PRICELIST（UZS） | https://t.me/canvora/1208（辅 1206/1199） |

## 3) 跳过（及原因）

| 对象 | 原因 |
|------|------|
| `@AIVerseXBot` `@crassus_market_bot` `@Pixora_Tunisie_bot` | em-o 摘要已列入；本批交审时目录未见其草稿文件，改交 RichAI/Canvora，**不重写** O 摘要声称内容 |
| `@EliteMethodsStoreBot` / escrow / `@nomorescammersbot` | 已入库；非本专项新价目店 |
| `@WarzoneShopBot` `@Gemini_shop_robot` `@AiSubShop_bot` `@ExcaliburTechBot` `@VouchersShopBot` `@AithSubscriptions_bot` `@storeBatmanBot` `@toolswala_bot` 等 | `records/other/bot-*.md` 已有 |
| `@Qamify_bot` `@ZinoShopbot` `@NyStoreOfficialBot` `@Paglu_*` | 老大确认 Gemini 同质闪购跳过 |
| `@nevakeystore_bot` | `gemini12pro_channel/163` 仅有品类话术，**公开帖无 $ 数字表** |
| `@Shop_Ayham_bot` | em-o 已判公开频道价目不足 |
| `@shopgojobot` | 公开 bot 页 og 空壳；Threads 有品类无核验 msgid 价表 |
| `@gemini_subscribe_bot` | 偏 Gemini 单品闪购 |
| BUYING 近窗多品广告 | 公开 `t.me/s/chatgptplusbuysell` 无列表；单条 og 可刮者多已入库 |

## 4) 风险口径

观察 ≠ 推荐购买。价目远低于官方、凭证交付、共享席位、仿冒客服、跑路等风险已写入各稿。未交互下单。

## 5) 文件清单

- 更新：`em-shop/bot-jeroaccounts-support-menu.md`
- 新建：`em-shop/bot-richaistore-wholesale-menu.md`、`em-shop/bot-canvora24-pricelist.md`
- 摘要：`em-shop/_batch-2026-09-26-emshop-a-summary.md`
