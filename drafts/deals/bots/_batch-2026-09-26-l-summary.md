# 批次 L 摘要 · BUYING & SELLING WORLDWIDE 低价 bot 候选（2026-09-26）

提案人：小弟·低价资源  
目录：`drafts/deals/bots/`  
状态：候选交审（未写 `records/`、未 git push、未对 bot 发交易消息）  
原始扫描：`_scan-raw-2026-09-25.txt`  
核验方式：扫描 msgid + 各 bot 公开 `https://t.me/<handle>` 页（curl HTTP 200 / og:title）；出处群消息页无公开 widget（需登录），以扫描 LINKHINT 为准。

## 交审标题建议

统一前缀：**`[低价·bot]`**（与各草稿 H1 一致）。

## 本批新草稿（4 条）

| # | 文件 | Bot | 差异化角度 | 主出处 | t.me 可开 |
|---|------|-----|------------|--------|-----------|
| 1 | `bot-vaultxstore-digital-goods.md` | `@VaultXStorebot`（同线观察 `@VaultXNetBot`） | 俄文自动数字商品/订阅店 + 频道/客服挂点 | [1218549](https://t.me/chatgptplusbuysell/1218549) | 是（VaultXStore；NetBot 亦 200） |
| 2 | `bot-mangoshopglobal-api-codex.md` | `@mangoshopglobal_bot` | API CODEX Token 标价；Mango Digital Store | [1218566](https://t.me/chatgptplusbuysell/1218566) | 是（Mango Digital Store 🥭） |
| 3 | `bot-lhiestore-chatgpt-plus.md` | `@lhiestore_bot` | ChatGPT Plus PRIVATE / READY STOCK | [1218605](https://t.me/chatgptplusbuysell/1218605) | 是（Lhie Store） |
| 4 | `bot-storebatman-applepay-subs.md` | `@storeBatmanBot` | ChatGPT Plus(Apple Pay) $4.5 话术 | [1218639](https://t.me/chatgptplusbuysell/1218639) | 是（storebat） |

## 去重说明

- 已入库 handles（`records/other/bot-*.md` 等）一律不重复立稿：含 `@ExcaliburTechBot` `@VouchersShopBot` `@WarzoneShopBot` `@Gemini_shop_robot` `@AiSubShop_bot` `@AithSubscriptions_bot` `@TrustedShopingbot` `@Prime_Gadget_Store_bot` 及 EM 线等。
- 忽略扫描正则截断假命中：`@amify_bot` `@hopbot` `@manBot` `@niChecker_bot` `@oshopglobal_bot` 等。

## 本批跳过（及原因）

| Handle | 原因 |
|--------|------|
| `@Qamify_bot` | t.me 可开，但广告为 Gemini 询价应答，同质度高，控量后置 |
| `@ZinoShopbot` | Gemini 18M 同质硬广（亦见 1218591），批次 K/本批刻意控 Gemini 闪购 |
| `@NyStoreOfficialBot` | Gemini + 5TB 同质；虽有 users 数字，仍控量 |
| `@Paglu_Shop_Bot` / `@PagluGeminiChecker_bot` | 同帖双 bot（店+checker）结构有趣，但内容仍是 Gemini 硬广，留后续 |
| `@toolswala_bot` | 公开页仅 “ToolsWala (Auto)”，业务描述弱于本批四条 |
| 可选频道 `t.me/s/aipricedb` `api86channel` `ai_bi_jia_notice` `TG_MRNF` | 抽查未捞到未入库有效新 bot（仅见无关 spambot） |

## 风险口径

四条均为**观察 ≠ 推荐购买**；买卖群硬广、虚假额度、盗号/session、未验证付款、跑路、钓鱼客服等风险已写入各稿。不构成购买、付款、转发或信誉背书。交审由审计/老大决定是否入库。
