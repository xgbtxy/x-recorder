# 批次 tgcat-m 摘要 · TG 群目录（2026-09-26）

提案人：小弟·TG  
目录：`drafts/deals/tg-catalog/`  
状态：候选交审（**未**写 `records/`、**未** push）  
合规：只读；不发帖、不试单、不对 bot 下单；禁 SSH/Telethon/session/2FA；`@muskapi` 不跟

> 前置：到岗时 **m** 摘要空档（仅见 a–k；l `18048ea` / l2 `3f5a8fb` 已入库 records）。**未**升号 m2。本批专吃 **l2 跳过池**优先公开 @，与 l/l2 四档**无重叠**。k/j/j2 等已入库套勿再交。

## 本批新建

### A. 完整群档（4）

| # | 文件 | 群 @ | 访问 | 群内 bot / 关联摘要 |
|---|------|------|------|---------------------|
| 1 | `groups/group-receiptxin.md` | `@receiptxin` | 公开介绍；看帖需登录（MSG=0） | 卡网 **wenxiangai.top**（站外抽样 **CNY/¥**，无 $）；无店 bot |
| 2 | `groups/group-claude1316.md` | `@claude1316` | 同上 | 标题「Claude openai核销」；简介仅 #claude #openai #ai；无店 bot |
| 3 | `groups/group-openai138.md` | `@openai138` | 同上 | 「企业交流群」；#claude #openai #gemini；无店 bot |
| 4 | `groups/group-gptzg.md` | `@gptzg` | 同上 | 标题「69 gpt渠道源头直供」；简介空窗；无店 bot |

### B. 群目录 bots 指针（0）

| 说明 |
|------|
| 四档公开简介均**无**挂名店铺 bot（`Start Bot`）；`@receiptxin` 站外卡网仅 **CNY/¥**、**无** ≥2 行公开 **$** → **不**立 `bots/`、**不**硬凑 em-shop；人号/频道未在公开窗挂出 → 不臆造 |

## 排查范围

| 来源 | 动作 |
|------|------|
| l2 跳过池优先：`@receiptxin` `@claude1316` `@openai138` `@gptzg` `@ddh992` | 逐条 urllib `t.me/<user>` → og / `tgme_page_extra`；`t.me/s/` **MSG=0** → join gate |
| 土豆 2dou.org/telegram 全 4 页（~185 公开 `t.me`） | 抽公开 @；对照 known（records + drafts a–l/l2）；invite-only 跳过 |
| records/other/tg-catalog/（含 l `18048ea` + l2 `3f5a8fb`）+ drafts 全套 + a–k 摘要 | 撞库：本批四 @ 无独立群档；**不跟** `@muskapi` |
| 关联站外轻核 | `wenxiangai.top` 页内无 `t.me` 挂链；仅 CNY 话术 → 拒 em-shop |

## 撞库 / 跳过（宁缺毋滥）

| 项 | 原因 |
|----|------|
| `@xiaoxiaoipkyc` `@aiaoteman001` `@dhbdkk` `@kewang9898988` + `@Tsiaohu_Bot` | **tgcat-l2 已入库** `3f5a8fb` |
| `@AisouPro` `@Ai66888i` `@beibeishoo` `@aiappleid` | **tgcat-l 已入库** `18048ea` |
| `@gpt_kedaya` `@a6apicom` `@DaFeiverls` 及 a–k / j / j2 / records 全套 | 已入库/已档 |
| `@muskapi` | 任务明示**不跟** |
| `@ddh992`（~8 036；「AI典当行交流群禁广」；简介空窗） | 可核超群；本批主表已满 4 → **下一批** |
| `@congmingxiayou1` `@zhwwsnbb` 及 2dou 第 2–4 页其余未入库公开 @ | 控量；下批撞库后再立 |
| `@gptclaude666778` | 2dou 仍挂群聊名，公开页为人号 Send Message → 无合格公开群 @（沿用 l2 结论） |
| 2dou 仅 invite（`t.me/+…`） | **无公开 @** → 不发明 username |
| em-shop | 本批无公开 ≥2 行可引用 **$**（卡网域 / CNY 话术均不硬凑） |

## 交审表（本批）

| 路径 | @ | join gate | bot / 关联 | 建议 |
|------|---|-----------|------------|------|
| `drafts/.../group-receiptxin.md` | `@receiptxin` | 需登录（MSG=0） | 卡网 wenxiangai.top（CNY）；无店 bot；拒 em-shop | **交审** |
| `drafts/.../group-claude1316.md` | `@claude1316` | 需登录（MSG=0） | 核销向；无店 bot | **交审** |
| `drafts/.../group-openai138.md` | `@openai138` | 需登录（MSG=0） | 企业交流标签；无店 bot | **交审** |
| `drafts/.../group-gptzg.md` | `@gptzg` | 需登录（MSG=0） | 渠道源头向；简介空；无店 bot | **交审** |

## 下一批候选（建议顺序）

1. `@ddh992`（~8 036；典当行交流；简介空 → 登录协采后再判）
2. `@congmingxiayou1` / `@zhwwsnbb` 等 l2 点名续挖
3. 2dou 第 2–4 页其余未入库公开 @（撞库 a–m / l2 后再立；**muskapi 不跟**；CNY 仍不硬凑 em-shop）
4. 登录协采本批四群后补 bot/实帖（msgid）；若出现挂名 `*bot` 再写 `tg-catalog/bots/`

## 公开预览核验方法

- 群：`curl`/`urllib` `t.me/<user>` → og title / `tgme_page_extra`（members/online）；`t.me/s/<user>` **MSG=0** → **需登录**
- 站外：`wenxiangai.top` 轻核域名提及与币种（CNY），**不**下单交互
- bot：经群简介公开挂名核；空价目 / 仅 CNY → 不立 em-shop、不 `/start`
- 不发明 username；不臆造 msgid

## 合规备忘

- 只写 `drafts/deals/tg-catalog/`；**未**直写 `records/`、**未** git push、未发群帖、未对 bot `/start`/试单/购买、未接 VIP 转发。
- 需登录群未伪造帖体；观察 ≠ 推荐；状态均为「候选」。
- a–l / l2 摘要**未**覆写；本摘要文件名 `_batch-2026-09-26-tgcat-m-summary.md`（**未**升 m2）。
