# 批次 tgcat-h 摘要 · TG 群目录（2026-09-26）

提案人：小弟·TG（执行手）  
目录：`drafts/deals/tg-catalog/`  
状态：候选交审（**未**写 `records/`、**未** push）  
合规：只读；不发帖、不试单、不对 bot 下单；EM 未重复深挖

> 前置：TG 已以 **tgcat-g** 入库 `2e6a904`（`@jianai996` `@claudepromax666` `@GeminiJL` `@gpt_user`）。本批换池 **tgcat-h**，**勿**再交同套、**勿**写 g 摘要。

## 本批新建

### A. 完整群档（4）

| # | 文件 | @username | 公开可读帖？ | 挖到的 bot / 客服（摘要） | 建议交审 |
|---|------|-----------|--------------|---------------------------|----------|
| 1 | `groups/group-rlaudeai.md` | `@rlaudeai` | **否**（join gate） | 无店 bot；人号客服 `@ZuiLiu1`；防失联频道 `@Rlaude91`（仅关联） | **是** |
| 2 | `groups/group-geminisadasd.md` | `@geminisadasd` | **否**（join gate） | 无店 bot；简介卡网 https://ai66888.quanxianshe.top/ | **是** |
| 3 | `groups/group-maoli9112.md` | `@maoli9112` | **否**（join gate） | 简介空窗、无店 bot；**标登录协采** | **是** |
| 4 | `groups/group-quanziai.md` | `@quanziai` | **否**（join gate） | 无店 bot；简介自述交流/反诈；**≠** `@Aiquanzi` | **是** |

### B. 群目录 bots 指针（0）

| 说明 |
|------|
| 公开窗未见挂名店铺 bot；`@ZuiLiu1` 为个人号（Send Message），**不**立 bots/；无公开 ≥2 行 $ → **不**交叉 em-shop |

## 排查范围

| 来源 | 动作 |
|------|------|
| 本批优先核表（rlaudeai → geminisadasd → maoli9112 → quanziai → iceaihubplus） | 逐条 curl `t.me/<user>` → og / `tgme_page_extra`；`t.me/s/` **MSG=0** → join gate |
| records/other/tg-catalog/ + drafts/deals/tg-catalog/ + a/b/c/c2/e/f/g 全套 | 撞库：四目标 @ 均无独立群档；摘要提及 ≠ 已立档 |
| 关联公开页反查 | `@Rlaude91` 频道；`@ZuiLiu1` 人号回指；`@Aiquanzi`（已入库，消歧）；`@iceai_hub` 频道（对应下一批 `@iceaihubplus`） |
| 第 5 优先 `@iceaihubplus` | 可核超群（约 6 035 members；简介空窗；关联频道 `@iceai_hub`）→ 主表已满 4 → **下一批** |

## 撞库 / 跳过（宁缺毋滥）

| 项 | 原因 |
|----|------|
| `@jianai996` `@claudepromax666` `@GeminiJL` `@gpt_user` | **tgcat-g 已入库** `2e6a904`；勿再交；drafts 无残留同套群档 |
| `@Aiquanzi` `@nerverai` `@chatgptplusdeal` `@chineseChatGpt` | tgcat-c2 已入库；**注意** `@quanziai` ≠ `@Aiquanzi` |
| `@lyxazycn` `@openhuge_ai` `@wishtoapp` `@yylcard` | tgcat-f 已入库 |
| `@achuanqunzu` `@lcardpay` `@nodecard1` `@fuck_open` | tgcat-e 已入库 |
| `@laogou_org` `@oasisaigc` `@aiagent8080` + a/b/c/records 全套（gemini*/tokenfreed/redman/EM/roboticvn 等） | 已入库/已档；撞库 |
| `@iceaihubplus` | 可核但本批主表满 4；空窗+公益 PLUS 话术 → **下一批**（可登录协采；对照频道 `@iceai_hub`） |
| `@Rlaude91` `@iceai_hub` 等纯频道 | 仅作关联/反查，**不**立频道档 |
| `@ZuiLiu1` | 人号客服，非 bot；记入群档即可 |
| em-shop | 本批无公开 ≥2 行可引用 $ |
| 纯 invite 无公开 @ | 不符必填 @；本批未扩挖 |

## 交审表（建议）

| 路径 | @ | join gate | bot / 关联 | 建议交审 |
|------|---|-----------|------------|----------|
| `groups/group-rlaudeai.md` | `@rlaudeai` | 需登录（MSG=0） | `@ZuiLiu1` 人号；频道 `@Rlaude91` | **是** |
| `groups/group-geminisadasd.md` | `@geminisadasd` | 需登录（MSG=0） | 无店 bot；卡网 ai66888.quanxianshe.top | **是** |
| `groups/group-maoli9112.md` | `@maoli9112` | 需登录（MSG=0） | 简介空窗；登录协采 | **是** |
| `groups/group-quanziai.md` | `@quanziai` | 需登录（MSG=0） | 无店 bot；≠ `@Aiquanzi` | **是** |

## 下一批候选（建议顺序）

1. `@iceaihubplus`（简介空窗；关联 `@iceai_hub` 频道；登录协采后再判）
2. 其他新公开 @（土豆/互推延伸；撞库 a–h 后再立；宁缺毋滥）

## 公开预览核验方法

- 群：`curl`/`urllib` `t.me/<user>` → og title / `tgme_page_extra`（members/online）；`t.me/s/<user>` **MSG=0** → **需登录**
- 频道（仅关联）：`@Rlaude91` / `@iceai_hub` → subscribers
- 人号：`@ZuiLiu1` → Send Message（非 Start Bot）
- bot：经群简介公开挂名核；空价目不立 em-shop、不 `/start`

## 合规备忘

- 未写 `records/`；未改 README 索引；未 git push；未发群帖；未对 bot `/start`/试单/购买；未接 VIP 转发。
- 需登录群未伪造帖体；观察 ≠ 推荐；状态均为「候选」。
- 未交审（交审由父代理/老大处理）。
