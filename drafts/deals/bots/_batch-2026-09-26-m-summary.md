# 批次 M 摘要 · 非闪购公开源低价 bot 候选（2026-09-26）

提案人：小弟·低价资源  
目录：`drafts/deals/bots/`  
状态：候选交审（未写 `records/`、未 git push、未发帖、未试单、未对 bot 发交易消息）  
核验方式：公开频道 `t.me/s/*` 预览 + 目录站/官方站公开页 + WebSearch + 各 bot `https://t.me/<handle>` curl（HTTP 200 / og / Start Bot）

## 交审标题建议

统一前缀：**`[低价·bot]`**（与各草稿 H1 一致）。

## 本批新草稿（3 条）

| # | 文件 | Bot | 差异化角度 | 主出处 | t.me 可开 |
|---|------|-----|------------|--------|-----------|
| 1 | `bot-buycardoffical-giftcard-esim.md` | `@BuyCardOffical_bot`（同线 `@BuyCardOffical` / `@BuyCard2024`） | 礼品卡/eSIM/话费 Mini App；Stars/TON/Crypto | [buycard.vip 中文博文](https://buycard.vip/zh/2026/03/08/we-built-a-gift-card-shop-inside-telegram-here-is-why/) + Mini App 页 | 是（og 完整；Start Bot） |
| 2 | `bot-wanttopay-virtual-card.md` | `@WantToPayBot`（同线 `@WanttopayBot`） | 国际虚拟卡/在线支付 | [wanttopay.net/en](https://wanttopay.net/en) + `@wanttopay_official` | 是（俄文 og；Start Bot） |
| 3 | `bot-redotpay-telegram-crypto.md` | `@redotpay_bot`（同线观察 `@RedotPayBot`） | Telegram 内稳定币/加密支付入口 | redotpay.com 新闻检索 + bot 自述 | 是（og 有品牌文案；Start Bot） |

## 去重说明

- 已入库 / L 批已交：`@VaultXStorebot` `@mangoshopglobal_bot` `@lhiestore_bot` `@storeBatmanBot` 及 `records/other/bot-*.md`、`fkfc8888bot-*`、`niu444bot-*` 内 handles 一律不重复立稿。
- 老大确认跳过的 chatgptplusbuysell 同质 Gemini 闪购：**不再交** `@Qamify_bot` `@ZinoShopbot` `@NyStoreOfficialBot` `@Paglu_Shop_Bot` / `@PagluGeminiChecker_bot`。

## 本批跳过（及原因）

| Handle / 来源 | 原因 |
|---------------|------|
| `t.me/s/aipricedb` | 预览无可入库 bot 入口（频道本体价目/监控，无新发卡 bot） |
| `t.me/s/api86channel` | 仅见 API/号池运维文与 faka.redeemgpt.com 站链；无未入库有效 bot |
| `t.me/s/ai_bi_jia_notice` | 仅见 `@with_ai_homes` 交流频道（禁广告），非店 bot |
| `t.me/s/TG_MRNF` | 号商私信导流 + `@spambot`；无新发卡/比价 bot |
| `@toolswala_bot` | 公开页仅 “ToolsWala (Auto)”，业务描述仍弱，按规则跳过 |
| `@hackerstri_bot` | 技术答疑语境，非低价店（任务指定跳过） |
| `@Qamify_bot` `@ZinoShopbot` `@NyStoreOfficialBot` `@Paglu_*` | Gemini 同质闪购，老大确认跳过 |
| `@fakamjj_bot` | 标题「云账号自动发卡」可开，但 og 空壳、默认图，出处弱，宁缺 |
| `@fakawan_bot` | 公开页无有效 og 描述（演示/空壳迹象） |
| `@crospay188bot` | 标题清晰且可 Start，但 F 批已因出处帖 404 暂缓；本批 NodeSeek 线索被 CF 挡，仍不硬凑 |
| `@OK86BOT` `@kkktgbot` `@zzhyj_bot` | F 批已判与 `@BuyYourPremiumBot` 同质 |
| `@nodecard_bot` / `@NodeCardFree_bot` | F 批已判公开页描述不足；2dou 仅挂交流群 `@nodecard1` |
| `@TgVipFather_Bot` 等 Light 线「创建类」bot | 开店框架/生成器，非零售店面 |
| `@CoinepayBot` | 可开且自称官网钱包，本批已有 Wanttopay/RedotPay 支付轨样本，控量后置 |
| `@chatgpt_008` / `@xiaoting99` | 频道+人工客服+网站 gpt2020.com，**非 bot 入口**，不按 bot 档立稿 |
| tgmulu.com | 本环境抓取失败（HTTP 000），未用其目录硬凑 |

## 风险口径

三条均为**观察 ≠ 推荐购买/开户**；第三方礼品卡作废、虚拟卡冻卡、加密支付沉淀、仿冒客服、未验证付款与跑路等风险已写入各稿。不构成购买、付款、转发或信誉背书。交审由审计/老大决定是否入库。
