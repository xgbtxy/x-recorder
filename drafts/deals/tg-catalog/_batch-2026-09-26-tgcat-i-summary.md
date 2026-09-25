# 批次 tgcat-i 摘要 · TG 群目录（2026-09-26）

提案人：小弟·TG  
目录：`drafts/deals/tg-catalog/`  
状态：候选交审（**未**写 `records/`、**未** push）  
合规：只读；不发帖、不试单、不对 bot 下单；禁 SSH/Telethon/session/2FA；`@muskapi` 不跟

> 前置：TG 已以 **tgcat-h** 入库 `5e89430`（`@rlaudeai` `@geminisadasd` `@maoli9112` `@quanziai`）。本批换池 **tgcat-i**，**勿**再交同套、**勿**覆写 e/f/g/h 摘要。

## 本批新建

### A. 完整群档（4）

| # | 文件 | 群 @ | 访问 | 群内 bot / 关联摘要 |
|---|------|------|------|---------------------|
| 1 | `groups/group-iceaihubplus.md` | `@iceaihubplus` | 公开介绍；看帖需登录（MSG=0） | 简介空窗；人号 `@ArcteryxSup` 回指 + 站外卡网；关联频道 `@iceai_hub` |
| 2 | `groups/group-gminiaixclaude.md` | `@gminiaixclaude` | 同上 | 挂所有者频道三枚；人号 `@Claudejinfu` 回指；无店 bot |
| 3 | `groups/group-gptsplus.md` | `@gptsplus` | 同上 | 简介空窗「源头渠道群」；无店 bot |
| 4 | `groups/group-chatgpt003.md` | `@chatgpt003` | 同上 | 简介自述 AI 星球多模型资源；无店 bot |

### B. 群目录 bots 指针（0）

| 说明 |
|------|
| `@ArcteryxSup` / `@Claudejinfu` 均为个人号（Send Message），**不**立 bots/；所有者/关联频道仅作反查，**不**立频道档；无公开 ≥2 行 $ → **不**交叉 em-shop |

## 排查范围

| 来源 | 动作 |
|------|------|
| 本批优先核表（`@iceaihubplus` → `@gminiaixclaude` → `@gptsplus` → 其他可核新公开 @） | 逐条 urllib `t.me/<user>` → og / `tgme_page_extra`；`t.me/s/` **MSG=0** → join gate |
| records/other/tg-catalog/groups/ + drafts/deals/tg-catalog/ + a/b/c/c2/e/f/g/h 全套 | 撞库：四目标 @ 无独立群档；摘要提及 ≠ 已立档 |
| 关联公开页反查 | `@iceai_hub` 频道；`@ArcteryxSup` 人号；`@gemini77claude` / `@Uultrageminicla7` / `@ClaudeGPTGeminipro`；`@Claudejinfu` |
| 第 4 档补位 | 公开目录站 tg.cool → `@chatgpt003`（可核超群 ~3 165 members；撞库无档） |

## 撞库 / 跳过（宁缺毋滥）

| 项 | 原因 |
|----|------|
| `@rlaudeai` `@geminisadasd` `@maoli9112` `@quanziai` | **tgcat-h 已入库** `5e89430`；任务明示禁止再立/再交 |
| `@jianai996` `@claudepromax666` `@GeminiJL` `@gpt_user` | tgcat-g 已入库 `2e6a904`；勿再交 |
| `@lyxazycn` `@openhuge_ai` `@wishtoapp` `@yylcard` | tgcat-f 已入库 |
| `@achuanqunzu` `@lcardpay` `@nodecard1` `@fuck_open` | tgcat-e 已入库 |
| `@Aiquanzi` `@nerverai` `@chatgptplusdeal` `@chineseChatGpt` + a/b/c/records 全套 | 已入库/已档 |
| `@muskapi` | 任务明示**不跟** |
| `@iceai_hub` `@gemini77claude` `@Uultrageminicla7` `@ClaudeGPTGeminipro` `/ @Aigongying` `@chatgpt_008` 等纯频道 | 仅关联/反查，**不**立频道档 |
| `@ArcteryxSup` `@Claudejinfu` | 人号客服/导流，非 bot；记入群档即可 |
| `@gptplusjiaoliu` | 可核但仅 ~74 members，体量过小 → **宁缺**不立 |
| em-shop | 本批无公开 ≥2 行可引用 $ |
| 纯 invite 无公开 @ | 不符必填 @；本批未扩挖 |

## 交审表（本批）

| 路径 | @ | join gate | bot / 关联 | 建议 |
|------|---|-----------|------------|------|
| `drafts/.../group-iceaihubplus.md` | `@iceaihubplus` | 需登录（MSG=0） | `@ArcteryxSup` 人号；频道 `@iceai_hub` | **交审** |
| `drafts/.../group-gminiaixclaude.md` | `@gminiaixclaude` | 需登录（MSG=0） | 所有者三频道；`@Claudejinfu` 人号 | **交审** |
| `drafts/.../group-gptsplus.md` | `@gptsplus` | 需登录（MSG=0） | 无店 bot；简介空窗 | **交审** |
| `drafts/.../group-chatgpt003.md` | `@chatgpt003` | 需登录（MSG=0） | 无店 bot；目录站入口 | **交审** |

## 下一批候选（建议顺序）

1. 登录协采本批四群后补 bot/实帖（msgid）
2. 其他新公开 @（土豆/互推/目录站延伸；撞库 a–i 后再立；**muskapi 不跟**；宁缺毋滥）
3. 关联频道抽样仅作消歧，勿立频道档

## 公开预览核验方法

- 群：`curl`/`urllib` `t.me/<user>` → og title / `tgme_page_extra`（members/online）；`t.me/s/<user>` **MSG=0** → **需登录**
- 频道（仅关联）：`@iceai_hub` / 所有者三频道 → subscribers
- 人号：`@ArcteryxSup` / `@Claudejinfu` → Send Message（非 Start Bot）
- bot：经群简介公开挂名核；空价目不立 em-shop、不 `/start`

## 合规备忘

- 只写 `drafts/deals/tg-catalog/`；**未**直写 `records/`、**未** git push、未发群帖、未对 bot `/start`/试单/购买、未接 VIP 转发。
- 需登录群未伪造帖体；观察 ≠ 推荐；状态均为「候选」。
- e/f/g/h 摘要**未**覆写；h 摘要保留。
