# 批次 tgcat-e 摘要 · TG 群目录（2026-09-26）

提案人：小弟·低价资源（执行手）  
目录：`drafts/deals/tg-catalog/`  
状态：候选交审（**未**写 `records/`、**未** push）  
合规：只读；不发帖、不试单、不对 bot 下单；EM 未重复深挖

> 换池说明：老大提醒 aiquanzi / chatgptplusdeal / chinesechatgpt / nerverai / Super_ChatGptBot 已由 TG 以 **tgcat-c2** 入 `39e52be`；**勿再交同套**。tgcat-d 已正式驳回。`@nerverbot_bot` 已在 `2a79e79`，勿立。本批只挖跳过池**新** `@`。

## 本批新建

### A. 完整群档（4）

| # | 文件 | @username | 公开可读帖？ | 挖到的 bot / 客服（摘要） | 建议交审 |
|---|------|-----------|--------------|---------------------------|----------|
| 1 | `groups/group-achuanqunzu.md` | `@achuanqunzu` | **否**（join gate） | 客服 `@achuankf` → 双向 `@achuanshuangxiangbot`；站外 achuan.pro | **是** |
| 2 | `groups/group-lcardpay.md` | `@lcardpay`（=`@LCardPay`） | **否**（join gate） | 人工客服 `@LCardpay8` / `@bepyp`；卡网 card4399.com；**非 bot** | **是** |
| 3 | `groups/group-nodecard1.md` | `@nodecard1` | **否**（join gate） | 售后 `@nodecard_bot`（og 空；仅表内，不另立 bot 档） | **是** |
| 4 | `groups/group-fuck-open.md` | `@fuck_open` | **否**（join gate） | 简介无店 bot；挂站外 oai9.com 货源搜索 | **是** |

### B. 群目录 bots 指针（1）

| 文件 | Bot | 说明 | 建议交审 |
|------|-----|------|----------|
| `bots/bot-achuanshuangxiang-relay.md` | `@achuanshuangxiangbot` | 双向中继；非价目店；不交叉 em-shop | **是** |

## 排查范围

| 来源 | 动作 |
|------|------|
| 跳过池优先表（任务点名 1–11） | 逐条 `curl` `t.me/<user>` → og / `tgme_page_extra`；`t.me/s/` **MSG=0** → join gate |
| records/other/tg-catalog/ + drafts/deals/tg-catalog/ | 撞库：已有群档 `@` 与 tgcat-a/b/c/c2 全套跳过；摘要跳过表提及 ≠ 已立档 |
| 关联公开页反查 | `@achuankf` → `@achuanshuangxiangbot`；`@LCardpay8`/`@bepyp` 回链本群；`@nodecard_bot` og 空 |
| tgcat-d | **已驳回**；本批不写 d 摘要、不复用其交审内容 |

## 撞库 / 跳过（宁缺毋滥）

| 项 | 原因 |
|----|------|
| `@Aiquanzi` `@nerverai` `@chatgptplusdeal` `@chineseChatGpt` + `@Super_ChatGptBot` | **tgcat-c2 已入库**（提醒 commit `39e52be`）；勿再交 |
| `@laogou_org` `@oasisaigc` `@aiagent8080` + laogou/oascf bots | tgcat-c 已档/已入 records |
| `@aijlqun` `@claudegpt520` `@gpt_nocard` + tgcat-a/b/records 全套（含 gemini*/tokenfreed/redman/EM/roboticvn 等） | 已入库/已档；撞库 |
| `@nerverbot_bot` | **已入库** `2a79e79`；勿立 |
| `@jianai996` `@claudepromax666` `@maoli9112` | 可核超群（members 齐全）但简介空窗、无店 bot；本批名额满 → **下一批** |
| `@yylcard` | 可核；卡网 sd.ncet.top；与本批 `@lcardpay`/`@nodecard1` 同质控量 → **下一批** |
| `@openhuge_ai` | 可核；biezou 中转话术+站外链；`@laogou_org` 档曾作对照提及但**无**独立群档；本批控量 → **下一批** |
| `@wishtoapp` | 可核；充值站+官网+频道 `@wishtoapp_channel`；无店 bot 公开窗 → **下一批** |
| `@lyxazycn` | 次优可核；挂 `@XiXiAiAutobot` + `@PixelAuto_Xixi_Bot` + 商城；本批优先完成主表 1–7 有简介者 → **下一批优先** |
| `@gpt_user` `@GeminiJL` | 次优可核；chinesechatgpt/GROKZS 生态对照；控量 → **下一批** |
| `@nodecard_bot` 另立 bot 档 | 公开 og 空描述；F/M 已判不足；仅群表登记 |
| `@LCardPay` 重复档 | 与 `@lcardpay` **同实体**；只立一档 |
| 纯频道（`@wishtoapp_channel` `@GROKZS` 等） | 仅作关联/反查，不立频道档 |
| em-shop | 本批无公开 ≥2 行可引用 $；未硬凑 |
| 纯 invite 无公开 @ | 不符必填 @ |

## 下一批候选（建议顺序）

1. `@lyxazycn`（双向客服 + 提交 bot，信息密度高）
2. `@openhuge_ai` / `@wishtoapp`（中转/Sub2API 向，需与 laogou/nerver 线对照）
3. `@yylcard`（卡网第三条线）
4. `@jianai996` `@claudepromax666` `@maoli9112`（简介空窗，登录协采后再判）
5. `@gpt_user` `@GeminiJL`（次优讨论群）

## 公开预览核验方法

- 群：`curl` `t.me/<user>` → og title / `tgme_page_extra`（members/online）；`t.me/s/<user>` **MSG=0** → **需登录**
- 类型确认：`@lcardpay`/`@LCardPay` 均为 **members** 超群，非 bot
- bot：经客服/群简介公开挂名核 og；空描述不立档、不 `/start`

## 合规备忘

- 未写 `records/`；未改 README 索引；未 git push；未发群帖；未对 bot `/start`/试单/购买；未接 VIP 转发。
- 需登录群未伪造帖体；观察 ≠ 推荐；状态均为「候选」。
