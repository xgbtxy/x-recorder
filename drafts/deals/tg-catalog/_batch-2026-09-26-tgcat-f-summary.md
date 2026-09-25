# 批次 tgcat-f 摘要 · TG 群目录（2026-09-26）

提案人：小弟·低价资源（执行手）  
目录：`drafts/deals/tg-catalog/`  
状态：候选交审（**未**写 `records/`、**未** push）  
合规：只读；不发帖、不试单、不对 bot 下单；EM 未重复深挖

> 前置：老大已批 tgcat-e 入库 `9a6422e`（`@achuanqunzu` `@lcardpay` `@nodecard1` `@fuck_open` + `@achuanshuangxiangbot`）。本批按 e 摘要「下一批」顺序立 **tgcat-f**。

## 本批新建

### A. 完整群档（4）

| # | 文件 | @username | 公开可读帖？ | 挖到的 bot / 客服（摘要） | 建议交审 |
|---|------|-----------|--------------|---------------------------|----------|
| 1 | `groups/group-lyxazycn.md` | `@lyxazycn` | **否**（join gate） | `@XiXiAiAutobot`（双向）+ `@PixelAuto_Xixi_Bot`（提交）；站外 lyxazy.cn；频道 `@lyxazytop` | **是** |
| 2 | `groups/group-openhuge-ai.md` | `@openhuge_ai` | **否**（join gate） | 公开窗无店 bot；运营号 `@openhuge` 回指；站外 biezou.com / ku0.com 等；简介口播折扣≠价目表 | **是** |
| 3 | `groups/group-wishtoapp.md` | `@wishtoapp` | **否**（join gate） | 无店 bot；充值 catfk.com + 官网 sub2api.wishtoapp.com；频道 `@wishtoapp_channel` 仅关联 | **是** |
| 4 | `groups/group-yylcard.md` | `@yylcard` | **否**（join gate） | 无店 bot；卡网 sd.ncet.top；与已入库 `@lcardpay`/`@nodecard1` 分线 | **是** |

### B. 群目录 bots 指针（2）

| 文件 | Bot | 说明 | 建议交审 |
|------|-----|------|----------|
| `bots/bot-xixiaiautobot-relay.md` | `@XiXiAiAutobot` | 双向客服；非价目店；不交叉 em-shop | **是** |
| `bots/bot-pixelauto-xixi-submit.md` | `@PixelAuto_Xixi_Bot` | 自助提交/订阅入口；公开窗无 ≥2 行 $；不交叉 em-shop | **是** |

## 排查范围

| 来源 | 动作 |
|------|------|
| tgcat-e 下一批优先表（lyxazycn → openhuge/wishtoapp → yylcard → 空窗 → 次优讨论） | 逐条 curl `t.me/<user>` → og / `tgme_page_extra`；`t.me/s/` **MSG=0** → join gate |
| records/other/tg-catalog/ + drafts/deals/tg-catalog/ + e/c/c2/a/b 全套 | 撞库：目标 @ 均无独立群/bot 档；摘要提及 ≠ 已立档 |
| 关联公开页反查 | `@lyxazytop` 频道回链双 bot；`@openhuge` → `@OpenHuge_ai`；`@wishtoapp_channel` subscribers 可预览；`@geminiKF` 为人号（非本批立档） |
| 空窗三项 / 次优讨论 | 可核但本批主表已满 4 档 → 下一批 |

## 撞库 / 跳过（宁缺毋滥）

| 项 | 原因 |
|----|------|
| `@achuanqunzu` `@lcardpay` `@nodecard1` `@fuck_open` + `@achuanshuangxiangbot` | **tgcat-e 已入库** `9a6422e`；勿再交 |
| `@Aiquanzi` `@nerverai` `@chatgptplusdeal` `@chineseChatGpt` + `@Super_ChatGptBot` | tgcat-c2 已入库 `39e52be` |
| `@laogou_org` `@oasisaigc` `@aiagent8080` + laogou/oascf bots | tgcat-c 已入库 |
| `@aijlqun` `@claudegpt520` `@gpt_nocard` + tgcat-a/b/records 全套（含 gemini*/tokenfreed/redman/EM/roboticvn 等） | 已入库/已档；撞库 |
| `@nerverbot_bot` | 已入库；勿立 |
| `@jianai996` `@claudepromax666` `@maoli9112` | 可核超群（members 齐全）但简介空窗（og 默认 join 句）、无店 bot；本批主表已满 4 → **下一批**（登录协采后再判） |
| `@gpt_user` `@GeminiJL` | 次优可核；chinesechatgpt/GROKZS 生态对照；名额满 → **下一批** |
| `@wishtoapp_channel` `@lyxazytop` `@GROKZS` 等纯频道 | 仅作关联/反查，**不**立频道档 |
| `@geminiKF` | `@GeminiJL` 挂名客服为人号（Send Message），非 bot；且本批未立 GeminiJL |
| em-shop | 本批无公开 ≥2 行可引用 $；`@openhuge_ai` 简介口播折扣与 `@PixelAuto_Xixi_Bot` og 品类句均不硬凑 |
| 纯 invite 无公开 @ | 不符必填 @ |

## 交审表（建议）

| 路径 | @ | join gate | bot / 关联 | 建议交审 |
|------|---|-----------|------------|----------|
| `groups/group-lyxazycn.md` | `@lyxazycn` | 需登录（MSG=0） | `@XiXiAiAutobot` + `@PixelAuto_Xixi_Bot`；频道 `@lyxazytop` | **是** |
| `groups/group-openhuge-ai.md` | `@openhuge_ai` | 需登录（MSG=0） | 无店 bot；`@openhuge` 回指 | **是** |
| `groups/group-wishtoapp.md` | `@wishtoapp` | 需登录（MSG=0） | 无店 bot；频道 `@wishtoapp_channel` | **是** |
| `groups/group-yylcard.md` | `@yylcard` | 需登录（MSG=0） | 无店 bot；卡网 sd.ncet.top | **是** |
| `bots/bot-xixiaiautobot-relay.md` | `@XiXiAiAutobot` | —（Start Bot） | 双向；挂于 lyxazycn | **是** |
| `bots/bot-pixelauto-xixi-submit.md` | `@PixelAuto_Xixi_Bot` | —（Start Bot） | 提交；挂于 lyxazycn / lyxazytop | **是** |

## 下一批候选（建议顺序）

1. `@jianai996` `@claudepromax666` `@maoli9112`（简介空窗，登录协采后再判）
2. `@gpt_user` `@GeminiJL`（次优讨论群；`@GeminiJL` 挂 `@geminiKF` 人号 + `@GROKZS` 频道）
3. 其他新公开 @（土豆/互推延伸；撞库后立）

## 公开预览核验方法

- 群：`curl`/`urllib` `t.me/<user>` → og title / `tgme_page_extra`（members/online）；`t.me/s/<user>` **MSG=0** → **需登录**
- 频道（仅关联）：`@lyxazytop` / `@wishtoapp_channel` → subscribers + `t.me/s/` 有 widget
- bot：经群/频道简介公开挂名核 og；空价目不立 em-shop、不 `/start`

## 合规备忘

- 未写 `records/`；未改 README 索引；未 git push；未发群帖；未对 bot `/start`/试单/购买；未接 VIP 转发。
- 需登录群未伪造帖体；观察 ≠ 推荐；状态均为「候选」。
