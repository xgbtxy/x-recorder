# 批次 tgcat-k 摘要 · TG 群目录（2026-09-26）

提案人：小弟·TG  
目录：`drafts/deals/tg-catalog/`  
状态：候选交审（**未**写 `records/`、**未** push）  
合规：只读；不发帖、不试单、不对 bot 下单；禁 SSH/Telethon/session/2FA；`@muskapi` 不跟

> 前置：TG 已以 **tgcat-j** `db407db`（`@awscdn888` `@apidiyidazhan` `@poqunai` `@xenterai` + bots）+ **tgcat-j2** `293f50f`（`@ainh666` `@mguishu` `@CHATGPTaigongshi` `@duoqudaochengpin`）入库。本批换池 **tgcat-k**，**勿**再交 j/j2 同套；**勿**覆写 a–j 摘要。

## 本批新建

### A. 完整群档（3）

| # | 文件 | 群 @ | 访问 | 群内 bot / 关联摘要 |
|---|------|------|------|---------------------|
| 1 | `groups/group-gpt-kedaya.md` | `@gpt_kedaya` | 公开介绍；看帖需登录（MSG=0） | 标题「小菲猪后援会 🈲广」；简介空窗；与 `@mguishu` 菲区消歧 |
| 2 | `groups/group-a6apicom.md` | `@a6apicom` | 同上 | Token 交易所超群；挂频道 `@a6apiai` + a6api.com；无店 bot |
| 3 | `groups/group-dafeiverls.md` | `@DaFeiverls` | 同上 | 简介 **CNY** 价目行（105/300/580/998…）；~334 members；**无** $ → 不硬凑 em-shop |

### B. 群目录 bots 指针（0）

| 说明 |
|------|
| 三档公开简介均**无**挂名店铺 bot；`@a6apiai` 为纯频道仅关联反查，**不**立频道档；`@DaFeiverls` 仅 CNY 话术、无人号/bot @ → **不**立 bots/、**不**交叉 em-shop |

## 排查范围

| 来源 | 动作 |
|------|------|
| 本批优先核表（`@gpt_kedaya` → `@a6apicom` → `@DaFeiverls` → 不够再补） | 逐条 urllib `t.me/<user>` → og / `tgme_page_extra`；`t.me/s/` **MSG=0** → join gate |
| records/other/tg-catalog/（含 j + j2）+ drafts/deals/tg-catalog/ + a–j 全套摘要 | 撞库：三目标 @ 无独立群档；摘要提及 ≠ 已立档；**不跟** `@muskapi` |
| 关联公开页反查 | `@a6apiai` 频道 ↔ `@a6apicom`；`@mguishu` 已入菲区线作消歧对照 |
| 第 4 档补位 | 候选 `@apidiyidazhan` **已入库** j → 跳过；其余主题不符/体量过小 → 宁缺不立第 4 |

## 撞库 / 跳过（宁缺毋滥）

| 项 | 原因 |
|----|------|
| `@ainh666` `@mguishu` `@CHATGPTaigongshi` `@duoqudaochengpin` | **tgcat-j2 已入库** `293f50f`；任务明示撞库含此套 |
| `@awscdn888` `@apidiyidazhan` `@poqunai` `@xenterai` + `@apizhushou_bot` 等 | **tgcat-j 已入库** `db407db`；有挂名 bot 已在 `bots/` |
| `@iceaihubplus` `@gminiaixclaude` `@gptsplus` `@chatgpt003` | tgcat-i 已入库 `5b52f45` |
| `@rlaudeai` `@geminisadasd` `@maoli9112` `@quanziai` | tgcat-h 已入库 |
| `@jianai996` `@claudepromax666` `@GeminiJL` `@gpt_user` 及 e/f/g/c2/a/b/c/records 全套 | 已入库/已档 |
| `@muskapi` | 任务明示**不跟**（curl 可核 ~918 members，仍跳过） |
| `@a6apiai` `@apizongzhuan` `@AWS158` 等纯频道 | 仅关联/反查，**不**立频道档 |
| `@waigpt` `@buy_sell_gmail` `@nghienvoc` `@lpolarischat` | 体验机器人群 / Gmail 买卖 / VN SheerID / 羊毛流媒体 → 主题不符 |
| `@gptplusjiaoliu` 等 <100 members | 体量过小 → 宁缺 |
| em-shop | `@DaFeiverls` 仅 **CNY** 价目行，**无**公开 ≥2 行 $ → **不**硬凑 |

## 交审表（本批）

| 路径 | @ | join gate | bot / 关联 | 建议 |
|------|---|-----------|------------|------|
| `drafts/.../group-gpt-kedaya.md` | `@gpt_kedaya` | 需登录（MSG=0） | 无店 bot；与 `@mguishu` 消歧 | **交审** |
| `drafts/.../group-a6apicom.md` | `@a6apicom` | 需登录（MSG=0） | 频道 `@a6apiai`；站外 a6api.com | **交审** |
| `drafts/.../group-dafeiverls.md` | `@DaFeiverls` | 需登录（MSG=0） | CNY 价目话术；无店 bot；拒 em-shop | **交审** |

## 下一批候选（建议顺序）

1. 登录协采本批三群后补 bot/实帖（msgid）
2. 其他新公开 @（土豆/互推/目录站延伸；撞库 a–k 后再立；**muskapi 不跟**；宁缺毋滥）
3. 关联频道抽样仅作消歧，勿立频道档；CNY 价目仍不硬凑 em-shop

## 公开预览核验方法

- 群：`curl`/`urllib` `t.me/<user>` → og title / `tgme_page_extra`（members/online）；`t.me/s/<user>` **MSG=0** → **需登录**
- 频道（仅关联）：`@a6apiai` → subscribers
- bot：经群简介公开挂名核；空价目 / 仅 CNY → 不立 em-shop、不 `/start`
- 不发明 username；不臆造 msgid

## 合规备忘

- 只写 `drafts/deals/tg-catalog/`；**未**直写 `records/`、**未** git push、未发群帖、未对 bot `/start`/试单/购买、未接 VIP 转发。
- 需登录群未伪造帖体；观察 ≠ 推荐；状态均为「候选」。
- a–j 摘要**未**覆写；本摘要文件名 `_batch-2026-09-26-tgcat-k-summary.md`。
