# 批次 tgcat-o 摘要 · TG 群目录（2026-09-26）

提案人：小弟·TG  
目录：`drafts/deals/tg-catalog/`  
状态：候选草稿（**未**写 `records/`、**未** push、**未**交审）  
合规：只读；不发帖、不试单、不对 bot 下单；禁 SSH/Telethon/session/2FA；`@muskapi` 不跟

> 前置：老大派工 **tgcat-o**。撞库含 n `16b1909`（`@ddh992`/`@congmingxiayou1`/`@zhwwsnbb`/`@chapchaod` + 3 bots）及 a–n / n2 / l / l2 / m 全套。本批专吃任务优先 `#1 @hdc5nme9` + n/n2 跳过池可核新公开 @；与 n/n2 **无重叠**。字母 o 到岗时空闲，**未**升 o2。

## 本批新建

### A. 完整群档（4）

| # | 文件 | 群 @ | 访问 | 群内 bot / 关联摘要 |
|---|------|------|------|---------------------|
| 1 | `groups/group-hdc5nme9.md` | `@hdc5nme9` | 公开介绍；看帖需登录（MSG=0） | 「低价靠谱ai交流群」~8 358；简介空窗；无店 bot |
| 2 | `groups/group-appkaola.md` | `@appkaola` | 同上 | 「ChatGpt全网货源共享交流群」~1 403；挂名 `@KAOLAAIBOT`；中转 appkaola.com / 收录 ai.appkaola.com |
| 3 | `groups/group-ainenglianggpt.md` | `@ainenglianggpt` | 同上 | 「ai能量小店(刷屏直接t)」~3 752；频道 `@ainengliang911`（~686；仅反查）；无店 bot |
| 4 | `groups/group-dingdingpu.md` | `@dingdingpu` | 同上 | 「丁丁AI交流群（🈲广）」~3 631；卡网 ac-card.org（SPA 壳）；无店 bot |

### B. 群目录 bots 指针（1）

| 文件 | Bot | 说明 |
|------|-----|------|
| `bots/bot-kaolaaibot-welfare.md` | `@KAOLAAIBOT` | 群简介公开挂名「ChatGpt额度福利官」；Start Bot 可核；**无** ≥2 行可引用 **$** → **不**交叉 em-shop；未 `/start` |

关联频道 `@ainengliang911` 仅反查，**不**立频道档。站外中转/卡网/收录网仅轻核，**不**注册/充值。

## 排查范围

| 来源 | 动作 |
|------|------|
| 任务优先 `#1 @hdc5nme9` + n/n2 跳过池 | urllib/curl `t.me/<user>` → og / `tgme_page_extra`；`t.me/s/` **MSG=0** → join gate |
| 土豆 2dou.org/telegram 全 4 页（~142 公开 `t.me`） | 抽公开 @；对照 known（records 含 n `16b1909` + drafts a–n/n2）；invite-only 跳过 |
| records/other/tg-catalog/ + drafts 全套 | 撞库：本批四 @ + `@KAOLAAIBOT` 无独立群/bot 档；**不跟** `@muskapi` |
| 挂名 bot / 关联页反查 | `@KAOLAAIBOT`↔`@appkaola`；`@ainengliang911`↔`@ainenglianggpt`；ac-card.org←`@dingdingpu` |
| 站外轻核 | appkaola.com / ai.appkaola.com / ac-card.org：未见可靠 ≥2 行可引用 **$** → 拒 em-shop（CNY≠$ 不硬凑；收录网 `$1`/`$3` 疑似前端噪声） |

## 撞库 / 跳过（宁缺毋滥）

| 项 | 原因 |
|----|------|
| `@ddh992` `@congmingxiayou1` `@zhwwsnbb` `@chapchaod` + 三 bot | **tgcat-n 已入库** `16b1909` |
| `@aishenji_group` + `@xihongshi123_bot` | **tgcat-n2 / 并行草稿**已立；勿复交、勿覆写 |
| `@receiptxin` `@claude1316` `@openai138` `@gptzg` | **tgcat-m 已入库** `f887ea3` |
| `@xiaoxiaoipkyc` `@aiaoteman001` `@dhbdkk` `@kewang9898988` + `@Tsiaohu_Bot` | **tgcat-l2 已入库** `3f5a8fb` |
| `@AisouPro` `@Ai66888i` `@beibeishoo` `@aiappleid` | **tgcat-l 已入库** `18048ea` |
| a–k / j / j2 及 records 全套已知 @ | 已入库/已档 |
| `@muskapi` | 任务明示**不跟** |
| `@yoyoai123` `@realquickmarket` `@nlai001` `@bysjlq` `@ghatgptclaude` `@jiafeimaoai` `@token014` `@lizi1001` `@aichengpingjiaoliu` 等 | 可核超群；本批主表已满 4（含必做 hdc5nme9）→ **下一批** |
| `@ainengliang911` / 纯频道（`@group_res_share` `@kaishijuanba` `@tgxwzai` `@lingshuapi` 等） | 仅关联/反查，**不**立频道档 |
| `@gptclaude666778` / `@hanai8888` / `@mmbtaaa` / `@longtengchat` 等 | 公开页为人号 Send Message → 无合格公开群 @ |
| 2dou 仅 invite（`t.me/+…`） | **无公开 @** → 不发明 username |
| em-shop | 本批无公开 ≥2 行可引用 **$**（空窗 / SPA 壳 / 福利 bot / 卡网 CNY 均不硬凑） |

## 本批路径表（建议交审）

| 路径 | @ | join gate | bot / 关联 | 建议 |
|------|---|-----------|------------|------|
| `drafts/.../group-hdc5nme9.md` | `@hdc5nme9` | 需登录（MSG=0）→ **需协采** | 简介空；无店 bot | **交审**（任务 #1） |
| `drafts/.../group-appkaola.md` | `@appkaola` | 需登录（MSG=0）→ **需协采** | `@KAOLAAIBOT` + 双站；拒 em-shop | **交审** |
| `drafts/.../group-ainenglianggpt.md` | `@ainenglianggpt` | 需登录（MSG=0）→ **需协采** | 频道 `@ainengliang911` 仅反查；无店 bot | **交审** |
| `drafts/.../group-dingdingpu.md` | `@dingdingpu` | 需登录（MSG=0）→ **需协采** | ac-card.org SPA；拒 em-shop | **交审** |
| `drafts/.../bot-kaolaaibot-welfare.md` | `@KAOLAAIBOT` | Start Bot 可核 | 额度福利；拒 em-shop；未 `/start` | **交审** |

> 四群均为公开介绍可开、看帖 **需登录**；本批**未**臆造 msgid，实帖/店 bot 扩挖标「需协采」。

## 下一批候选（建议顺序）

1. `@jiafeimaoai`（~2 998；频道 `@aijiafeimao` + 卡网 ldxp；CNY 不硬凑 em-shop）
2. `@token014` / `@realquickmarket` / `@yoyoai123` / `@nlai001` / `@bysjlq` / `@ghatgptclaude` / `@lizi1001`
3. 登录协采本批四群后补 bot/实帖（msgid）；若出现挂名店 bot 再扩 `tg-catalog/bots/`
4. **muskapi 不跟**；CNY 仍不硬凑 em-shop

## 公开预览核验方法

- 群：`curl`/`urllib` `t.me/<user>` → og title / `tgme_page_extra`（members/online）；`t.me/s/<user>` **MSG=0** → **需登录**
- bot：经群简介公开挂名核 Start Bot；空价目 / 福利客服 → 不立 em-shop、不 `/start`
- 频道：仅反查 subscribers / 标题，**不**立档
- 站外：轻核 SPA/收录页币种信号，**不**注册/充值
- 不发明 username；不臆造 msgid

## 合规备忘

- 只写 `drafts/deals/tg-catalog/`；**未**直写 `records/`、**未** git push、未改 README、未发群帖、未对 bot `/start`/试单/购买、未接 VIP 转发。
- 需登录群未伪造帖体；观察 ≠ 推荐；个体档状态均为「候选」；本摘要**未**交审。
- a–n / n2 摘要与群档**未**覆写；本摘要文件名 `_batch-2026-09-26-tgcat-o-summary.md`。
