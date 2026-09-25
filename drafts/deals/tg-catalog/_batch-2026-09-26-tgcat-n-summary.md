# 批次 tgcat-n 摘要 · TG 群目录（2026-09-26）

提案人：小弟·低价资源  
目录：`drafts/deals/tg-catalog/`  
状态：候选草稿（**未**写 `records/`、**未** push、**未**交审）  
合规：只读；不发帖、不试单、不对 bot 下单；禁 SSH/Telethon/session/2FA；`@muskapi` 不跟

> 前置：老大派工 **tgcat-n**。tgcat-m（`@receiptxin` / `@claude1316` / `@openai138` / `@gptzg`，`f887ea3`）已入库，**勿再交同套**。本批专吃 m 跳过池优先 `@ddh992` + 续挖未档公开 @，与 m/l/l2 **无重叠**。

> 并行旁挂：草稿区另有 `groups/group-aishenji-group.md` + `bots/bot-xihongshi123-relay.md`（非本批主表）。**未**收录、**未**覆写。本批主表四群+三 bot 提案人一律**小弟·低价资源**。


## 本批新建

### A. 完整群档（4）

| # | 文件 | 群 @ | 访问 | 群内 bot / 关联摘要 |
|---|------|------|------|---------------------|
| 1 | `groups/group-ddh992.md` | `@ddh992` | 公开介绍；看帖需登录（MSG=0） | 「AI✿典当行交流群禁广」；简介空窗；无店 bot |
| 2 | `groups/group-congmingxiayou1.md` | `@congmingxiayou1` | 同上 | 「聪明AI下游群」；中转 congmingai.com（SPA 壳页，无公开 $ 价目）；无店 bot |
| 3 | `groups/group-zhwwsnbb.md` | `@zhwwsnbb` | 同上 | 「gemini ultra研究群」；挂名 `@zhwwsnbb_bot`；频道 `@ywdwsnyy`（~3 333；批量出 ultra） |
| 4 | `groups/group-chapchaod.md` | `@chapchaod` | 同上 | 「超超\| AI交流群」；挂名 `@chaochao1bot` + `@chaochaochetbot`；通知 `@chaobigbing`（~5 197） |

### B. 群目录 bots 指针（3）

| 文件 | Bot | 说明 |
|------|-----|------|
| `bots/bot-zhwwsnbb-relay.md` | `@zhwwsnbb_bot` | 双向+ai群管；强制加频道门；**无** ≥2 行公开 $ → **不**交叉 em-shop；未 `/start` |
| `bots/bot-chaochao1-welfare.md` | `@chaochao1bot` | 福利/自助解封；回链 `@chaobigbing`；拒 em-shop；未 `/start` |
| `bots/bot-chaochaochet-relay.md` | `@chaochaochetbot` | 客服中转；频道侧人号 `@cjakcj` **不**立 bots/；拒 em-shop；未 `/start` |

人号（`@cjakcj` / `@AREMANOD` 等）均为 Send Message，**不**立 bots/。关联频道仅反查，**不**立频道档。

## 排查范围

| 来源 | 动作 |
|------|------|
| m 跳过池优先：`@ddh992` `@congmingxiayou1` `@zhwwsnbb` | 逐条 urllib `t.me/<user>` → og / `tgme_page_extra`；`t.me/s/` **MSG=0** → join gate |
| 土豆 2dou.org/telegram 全 4 页（~142 公开 `t.me`） | 抽公开 @；对照 known（records + drafts a–m / l / l2）；invite-only 跳过；频道/人号剔除 |
| records/other/tg-catalog/（含 m `f887ea3` + l `18048ea` + l2 `3f5a8fb`）+ drafts 全套 | 撞库：本批四 @ 无独立群档；**不跟** `@muskapi`；**不**复交 m 四档 |
| 关联公开页反查 | `@zhwwsnbb_bot`/`@ywdwsnyy`↔`@zhwwsnbb`；`@chaochao1bot`/`@chaochaochetbot`/`@chaobigbing`↔`@chapchaod`；`congmingai.com`←`@congmingxiayou1` |

## 撞库 / 跳过（宁缺毋滥）

| 项 | 原因 |
|----|------|
| `@receiptxin` `@claude1316` `@openai138` `@gptzg` | **tgcat-m 已入库** `f887ea3`；任务明示勿再交同套 |
| `@xiaoxiaoipkyc` `@aiaoteman001` `@dhbdkk` `@kewang9898988` + `@Tsiaohu_Bot` | **tgcat-l2 已入库** `3f5a8fb` |
| `@AisouPro` `@Ai66888i` `@beibeishoo` `@aiappleid` | **tgcat-l 已入库** `18048ea` |
| `@gpt_kedaya` `@a6apicom` `@DaFeiverls` 及 a–k / j / j2 / records 全套 | 已入库/已档 |
| `@muskapi` | 任务明示**不跟** |
| `@hdc5nme9` `@yoyoai123` `@dingdingpu` `@realquickmarket` `@nlai001` `@bysjlq` `@ainenglianggpt` `@ghatgptclaude` 等 | 可核超群；本批主表已满 4（含必做 ddh992）→ **下一批** |
| `@aishenji_group` + `@xihongshi123_bot` | 并行专员草稿旁挂（非本批主表）；本摘要**不**收录、不覆写 |
| `@gptclaude666778` / `@hanai8888` / `@mmbtaaa` 等 | 公开页为人号 Send Message → 无合格公开群 @ |
| `@ai_kaka_am` `@lingshuapi` `@ywdwsnyy` `@chaobigbing` `@group_res_share` 等纯频道 | 仅关联/反查，**不**立频道档 |
| 2dou 仅 invite（`t.me/+…`） | **无公开 @** → 不发明 username |
| em-shop | 本批无公开 ≥2 行可引用 **$**（空窗 / SPA 壳 / 双向客服 / CNY 卡网话术均不硬凑） |

## 本批路径表

| 路径 | @ | join gate | bot / 关联 | 备注 |
|------|---|-----------|------------|------|
| `drafts/.../group-ddh992.md` | `@ddh992` | 需登录（MSG=0） | 简介空；无店 bot | 必做·候选 |
| `drafts/.../group-congmingxiayou1.md` | `@congmingxiayou1` | 需登录（MSG=0） | congmingai.com；无店 bot；拒 em-shop | 候选 |
| `drafts/.../group-zhwwsnbb.md` | `@zhwwsnbb` | 需登录（MSG=0） | `@zhwwsnbb_bot` + `@ywdwsnyy` | 候选 |
| `drafts/.../group-chapchaod.md` | `@chapchaod` | 需登录（MSG=0） | 双 bot + `@chaobigbing` | 候选 |
| `drafts/.../bot-zhwwsnbb-relay.md` | `@zhwwsnbb_bot` | Start Bot 可核 | 双向群管；拒 em-shop | 候选 |
| `drafts/.../bot-chaochao1-welfare.md` | `@chaochao1bot` | Start Bot 可核 | 福利解封；拒 em-shop | 候选 |
| `drafts/.../bot-chaochaochet-relay.md` | `@chaochaochetbot` | Start Bot 可核 | 客服中转；拒 em-shop | 候选 |

## 下一批候选（建议顺序）

1. `@hdc5nme9`（~8 358；「低价靠谱ai交流群」；简介空 → 登录协采后再判）
2. `@yoyoai123` / `@dingdingpu`（卡网 ac-card.org）/ `@realquickmarket`
3. `@nlai001` `@bysjlq` `@ainenglianggpt` `@chapchaod` 已立外其余 2dou 第 2–4 页未入库公开 @（撞库 a–n 后再立；**muskapi 不跟**；CNY 仍不硬凑 em-shop）
4. 登录协采本批四群后补 bot/实帖（msgid）；若出现挂名店 bot 再扩 `tg-catalog/bots/`

## 公开预览核验方法

- 群：`curl`/`urllib` `t.me/<user>` → og title / `tgme_page_extra`（members/online）；`t.me/s/<user>` **MSG=0** → **需登录**
- 站外：`congmingai.com` 轻核 SPA 壳与币种（公开 HTML 无 $ 价目行），**不**注册/充值
- bot：经群简介公开挂名核 Start Bot；空价目 / 双向客服 → 不立 em-shop、不 `/start`
- 频道：仅反查 subscribers / 标题，**不**立档
- 不发明 username；不臆造 msgid

## 合规备忘

- 只写 `drafts/deals/tg-catalog/`；**未**直写 `records/`、**未** git push、未改 README、未发群帖、未对 bot `/start`/试单/购买、未接 VIP 转发。
- 需登录群未伪造帖体；观察 ≠ 推荐；个体档状态均为「候选」；本摘要**未**交审。
- a–m / l / l2 摘要与群档**未**覆写；本摘要文件名 `_batch-2026-09-26-tgcat-n-summary.md`。
