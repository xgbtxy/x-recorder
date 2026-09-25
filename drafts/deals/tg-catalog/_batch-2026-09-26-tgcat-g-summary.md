# 批次 tgcat-g 摘要 · TG 群目录（2026-09-26）

提案人：小弟·TG  
目录：`drafts/deals/tg-catalog/`  
状态：候选交审（**未**写 `records/`、**未** push）  
合规：只读；不发帖、不试单、不对 bot 下单；禁 SSH/Telethon/session/2FA；`@muskapi` 不跟

> **批次号说明**：任务原指定 **tgcat-e**，但到岗时 e 已由并行专员（小弟·低价资源）交审并入库 `9a6422e`（`@achuanqunzu`/`@lcardpay`/`@nodecard1`/`@fuck_open`）；f 亦已占 drafts（`@lyxazycn`/`@openhuge_ai`/`@wishtoapp`/`@yylcard`）。**勿覆盖 e/f、勿复交同一批**。本批升号 **tgcat-g**，专吃 e/f 摘要「下一批」剩余优先池。

## 本批新建

### A. 完整群档（4）

| # | 文件 | 群 @ | 访问 | 群内 bot / 关联摘要 |
|---|------|------|------|---------------------|
| 1 | `groups/group-jianai996.md` | `@jianai996` | 公开介绍；看帖需登录（MSG=0） | 简介空窗；无店 bot |
| 2 | `groups/group-claudepromax666.md` | `@claudepromax666` | 同上 | 简介空窗；无店 bot；标题「claude Pro 源头交流」 |
| 3 | `groups/group-geminijl.md` | `@GeminiJL` | 同上；频道 `@GROKZS` 可读 | 客服人号 `@geminiKF`（非 bot）；频道抽样偏游戏外挂「Gemini」品牌 |
| 4 | `groups/group-gpt-user.md` | `@gpt_user` | 同上 | 简介无店 bot；ChatGPT AI 机器人讨论 |

### B. 群目录 bots（0）

本批无可立 bot：`@geminiKF` 为人号；`@GROKZS` 抽样店 `@ATC_AutoShop_Bot` 为游戏卡网旗舰，**不**纳入本 AI/订阅目录；空窗两群无公开 bot 挂名。

## 排查范围

| 来源 | 动作 |
|------|------|
| 任务优先候选 C2 跳过池 | 逐条 `curl` `t.me/<user>` → og / `tgme_page_extra`；`t.me/s/` **MSG=0** → 需登录；不可开则跳过（本批均可开） |
| records + drafts + e/f/c/c2/a/b | 全量撞库；已入库/已交 drafts **不覆盖** |
| 关联公开页 | `@GROKZS` widget 抽样；`@geminiKF` 人号核验 |

## 撞库 / 跳过（宁缺毋滥）

| 项 | 原因 |
|----|------|
| `@achuanqunzu` `@lcardpay` `@nodecard1` `@fuck_open` + `@achuanshuangxiangbot` | **tgcat-e 已入库** `9a6422e`；勿再交 |
| `@lyxazycn` `@openhuge_ai` `@wishtoapp` `@yylcard` + XiXi 双 bot | **tgcat-f** drafts 已占；勿覆盖 |
| `@Aiquanzi` `@nerverai` `@chatgptplusdeal` `@chineseChatGpt` 等 c2/c/a/b/records 全套 | 已入库/已档 |
| `@muskapi` | 硬规则不跟 |
| `@maoli9112` `@quanziai` `@rlaudeai` `@iceaihubplus` `@gptsplus` `@geminisadasd` `@gminiaixclaude` | 可核超群；本批名额满（优先消化任务点名剩余四 @）→ **下一批** |
| `@GROKZS` `@GeminiEJ` 等纯频道 | 仅关联/反查，不立频道档 |
| `@ATC_AutoShop_Bot` | 游戏卡网；不进本目录 bots/ |
| em-shop | 无公开 ≥2 行可引用 $；未硬凑 |
| 纯 invite 无公开 @ | 不符必填 @ |

## 公开预览核验方法

- 群：`curl` `t.me/<user>` → og title / `tgme_page_extra`（members/online）；`t.me/s/<user>` **MSG=0** → **需登录**
- 频道（仅关联）：`t.me/s/GROKZS` 有 `data-post`；用于消歧，不立档
- 客服：`@geminiKF` og 为人号（Send Message），非 Start Bot

## 合规备忘

- 未写 `records/`；未 git push；未发帖；未对 bot `/start`/试单/购买；未接 VIP；未 SSH/dig/Telethon/session/2FA。
- 需登录群未伪造帖体；观察 ≠ 推荐；不发明 username。
- **未**覆写 `_batch-2026-09-26-tgcat-e-summary.md`（已有并行稿 + 已入库）。

## 下一批候选（建议）

1. `@rlaudeai`（挂客服 `@ZuiLiu1` + 防失联频道 `@Rlaude91`）
2. `@geminisadasd`（卡网硬广；强制风险、不写购买步骤）
3. `@maoli9112` `@quanziai` `@iceaihubplus` `@gptsplus` `@gminiaixclaude`（简介空窗或同质控量）
