# 批次 tgcat-p 摘要 · TG 群目录（2026-09-26）

提案人：小弟·TG  
目录：`drafts/deals/tg-catalog/`  
状态：候选草稿（**未**写 `records/`、**未** push、**未**交审）  
合规：只读；不发帖、不试单、不对 bot 下单；禁 SSH/Telethon/session/2FA；`@muskapi` 不跟  
加码：阿言定调 **群+bot 成对**——优先四群公开窗无挂名 bot，故以 2dou 可核挂名双向 bot 的 `@bin_api` 补成对；宁缺空 bot 批

> 前置：老大派工 **tgcat-p**（优先 `#1 @jiafeimaoai` → `@token014` / `@realquickmarket` / `@yoyoai123`）。撞库含 o `bdee7ea`（`@hdc5nme9`/`@appkaola`/`@ainenglianggpt`/`@dingdingpu` + `@KAOLAAIBOT`）及 a–o / n2 / l / l2 / m 全套。字母 p 到岗时空闲，**未**升 p2。

## 本批新建

### A. 完整群档（4）

| # | 文件 | 群 @ | 访问 | 群内 bot / 关联摘要 |
|---|------|------|------|---------------------|
| 1 | `groups/group-jiafeimaoai.md` | `@jiafeimaoai` | 公开介绍；看帖需登录（MSG=0） | 「加菲猫的千层饼Ai资源」~2 998；频道 `@aijiafeimao`（~574；仅反查）+ 卡网 ldxp；**无**挂名 bot |
| 2 | `groups/group-token014.md` | `@token014` | 同上 | 「怪兽Ai\|Ai交流群（禁广）」~2 483；中转 yeclaw.cc + 卡网 wzyp（对接码 guai）；**无**挂名 bot |
| 3 | `groups/group-realquickmarket.md` | `@realquickmarket` | 同上 | 「AI技术交流群」~6 123；成品/外国卡网自动发货/国内私聊；**无**挂名 bot / 无卡网 URL |
| 4 | `groups/group-bin-api.md` | `@bin_api` | 同上 | 「BinAPI交流群」~81；挂名双向 `@Binkoo_bot` + 中转 api.binzzz.xyz（**成对补位**） |

### B. 群目录 bots 指针（1）← 本批 bots 清单

| 文件 | Bot | 类型 | 说明 |
|------|-----|------|------|
| `bots/bot-binkoo-relay.md` | `@Binkoo_bot` | **双向客服** | 群 `@bin_api` 简介公开挂名；Start Bot 可核；og「Binkoobot」；**无** ≥2 行可引用 **$** → **不**交叉 em-shop；未 `/start` |

关联频道 `@aijiafeimao`、invite-only `t.me/+ugo1kAHCQJBjOTVl`、售后数字群 1064032391 **仅反查/记名**，**不**立频道档、不发明 username。站外卡网/中转仅轻核，**不**注册/充值。

## 排查范围

| 来源 | 动作 |
|------|------|
| 任务优先 `#1 @jiafeimaoai` + o 跳过池 `@token014`/`@realquickmarket`/`@yoyoai123` | urllib/curl `t.me/<user>` → og / `tgme_page_extra`；`t.me/s/` **MSG=0** → join gate |
| 加码·群+bot | 扫优先四群简介 + 关联频道 `@aijiafeimao` 公开预览（20 帖）→ **均无**挂名 bot；2dou 全 4 页扩核 → 命中 `@bin_api`↔`@Binkoo_bot` |
| records/other/tg-catalog/ + drafts 全套 | 撞库：本批四 @ + `@Binkoo_bot` 无独立群/bot 档；**不跟** `@muskapi` |
| 站外轻核 | pay.ldxp.cn / wzyp.cn / yeclaw.cc / api.binzzz.xyz / talkai.cyou：频道侧可见 CNY/「r」价；中转见 USD/CNY/RMB 字样但**无** `$N` 可引用行 → 拒 em-shop（CNY≠$ 不硬凑） |

## 撞库 / 跳过（宁缺毋滥）

| 项 | 原因 |
|----|------|
| `@hdc5nme9` `@appkaola` `@ainenglianggpt` `@dingdingpu` + `@KAOLAAIBOT` | **tgcat-o 已入库** `bdee7ea` |
| `@ddh992` `@congmingxiayou1` `@zhwwsnbb` `@chapchaod` + 三 bot | **tgcat-n 已入库** `16b1909` |
| `@aishenji_group` + `@xihongshi123_bot` | **tgcat-n2 / 并行草稿**已立；勿复交、勿覆写 |
| `@receiptxin` `@claude1316` `@openai138` `@gptzg` | **tgcat-m 已入库** `f887ea3` |
| a–k / l / l2 / j 及 records 全套已知 @ | 已入库/已档 |
| `@muskapi` | 任务明示**不跟** |
| `@yoyoai123`（~5 393；简介空窗） | 可核公开群；本批主表已满 4（含必做 jiafeimaoai + 成对 bin_api）→ **下一批** |
| `@nlai001` `@bysjlq` `@ghatgptclaude` `@lizi1001` `@aichengpingjiaoliu` 等 | 可核超群；公开窗**无**挂名 bot → 让位成对补位 |
| `@talkai_z` / `@talkai_ad`（挂 `@talkai_kefu`） | `talkai_kefu` 公开页为**人号** Send Message → **不**立 bots/；群本身下一批可核 |
| `@grokaifenjue` 所有者人号挂 `@guofuluban_bot` | bot 在**人号**简介非群简介；本批不硬拉（已核 Start Bot，记入下一批可选） |
| `@aijiafeimao` / 纯频道 / invite-only `t.me/+…` | 仅关联/反查，**不**立频道档、不发明 username |
| 2dou 仅 invite（`t.me/+…`） | **无公开 @** → 不发明 username |
| em-shop | 本批无公开 ≥2 行可引用 **$**（CNY/「r」/ SPA / 双向空价目均不硬凑） |

## 本批路径表（建议交审）

| 路径 | @ | join gate | bot / 关联 | 建议 |
|------|---|-----------|------------|------|
| `drafts/.../group-jiafeimaoai.md` | `@jiafeimaoai` | 需登录（MSG=0）→ **需协采** | 频道 `@aijiafeimao` 仅反查；无店 bot；拒 em-shop | **交审**（任务 #1） |
| `drafts/.../group-token014.md` | `@token014` | 需登录（MSG=0）→ **需协采** | yeclaw + wzyp；无店 bot；拒 em-shop | **交审** |
| `drafts/.../group-realquickmarket.md` | `@realquickmarket` | 需登录（MSG=0）→ **需协采** | 无挂名 bot/卡网 URL；拒 em-shop | **交审** |
| `drafts/.../group-bin-api.md` | `@bin_api` | 需登录（MSG=0）→ **需协采** | `@Binkoo_bot` 双向；拒 em-shop | **交审**（成对） |
| `drafts/.../bot-binkoo-relay.md` | `@Binkoo_bot` | Start Bot 可核 | **类型：双向客服**；拒 em-shop；未 `/start` | **交审** |

> 四群均为公开介绍可开、看帖 **需登录**；本批**未**臆造 msgid，实帖/店 bot 扩挖标「需协采」。

## 下一批候选（建议顺序）

1. `@yoyoai123`（~5 393；简介空；需协采看是否群内挂 bot）
2. `@nlai001` / `@bysjlq` / `@ghatgptclaude` / `@lizi1001` / `@aichengpingjiaoliu`
3. `@talkai_z`（人号客服 `@talkai_kefu` 不立 bots/；可核卡网 talkai.cyou / ai-buy.vip）
4. `@grokaifenjue` + 可选 `@guofuluban_bot`（人号简介挂双向；若立须写清发现链）
5. 登录协采本批四群后补 bot/实帖（msgid）；优先四群若出现挂名店 bot 再扩 `tg-catalog/bots/`
6. **muskapi 不跟**；CNY 仍不硬凑 em-shop；继续群+bot 成对优先

## 公开预览核验方法

- 群：`curl`/`urllib` `t.me/<user>` → og title / `tgme_page_extra`（members/online）；`t.me/s/<user>` **MSG=0** → **需登录**
- bot：经群简介公开挂名核 Start Bot；标类型（双向/福利/价目）；空价目 → 不立 em-shop、不 `/start`
- 频道：仅反查 subscribers / 标题 / 公开预览币种信号，**不**立档
- 站外：轻核 SPA/卡网币种，**不**注册/充值
