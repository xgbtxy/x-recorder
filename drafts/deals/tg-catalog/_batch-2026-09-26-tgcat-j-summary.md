# 批次 tgcat-j 摘要 · TG 群目录（2026-09-26）

提案人：小弟·低价资源  
目录：`drafts/deals/tg-catalog/`  
状态：候选交审（**未**写 `records/`、**未** push）  
合规：只读；不发帖、不试单、不对 bot 下单；禁 SSH/Telethon/session/2FA；`@muskapi` 不跟

> 前置：TG 已以 **tgcat-i** 入库 `5b52f45`（`@iceaihubplus` `@gminiaixclaude` `@gptsplus` `@chatgpt003`）。本批换池 **tgcat-j**，**勿**再交 i 同套；drafts 无 i 群档/摘要残留（已清）。

## 本批新建

### A. 完整群档（5）

| # | 文件 | 群 @ | 访问 | 群内 bot / 关联摘要 |
|---|------|------|------|---------------------|
| 1 | `groups/group-ainh666.md` | `@ainh666` | 公开介绍；看帖需登录（MSG=0） | 简介「低价GPT/Gemini 交流群」；无店 bot |
| 2 | `groups/group-awscdn888.md` | `@awscdn888` | 同上 | 挂群主人号 `@AwsLuffy`；关联频道 `@AWS158`；标签 Claude/Gemini |
| 3 | `groups/group-mguishu.md` | `@mguishu` | 同上 | 简介卡网 feiai.plus；人号线索 `@feiaiplus`（非简介直挂） |
| 4 | `groups/group-chatgptaigongshi.md` | `@CHATGPTaigongshi` | 同上 | 简介空窗；超群 ~11 703 members |
| 5 | `groups/group-duoqudaochengpin.md` | `@duoqudaochengpin` | 同上 | 简介「稳定，靠谱」；username 偏多渠道成品话术；无店 bot |

### B. 群目录 bots 指针（0）

| 说明 |
|------|
| `@AwsLuffy` / `@feiaiplus` 等均为个人号（Send Message），**不**立 bots/；`@AWS158` 等纯频道仅关联反查，**不**立频道档；无公开 ≥2 行 $ → **不**交叉 em-shop |

## 排查范围

| 来源 | 动作 |
|------|------|
| 土豆 2dou.org/telegram 全页 `t.me/` 抽链 | 对未入库 username 逐条 urllib `t.me/<user>` → og / `tgme_page_extra`；`t.me/s/` **MSG=0** → join gate |
| 公开 Web 检索（ChatGPT/Claude/Gemini 交流群、发卡交流群） | 命中 `@CHATGPTaigongshi` 等；tg.cool 辅证 `@DaFeiverls`（体量偏小 → 下一批） |
| records/other/tg-catalog/ + drafts/deals/tg-catalog/ + a–i 全套 | 撞库：五目标 @ 无独立群档；摘要提及 ≠ 已立档；**不跟** `@muskapi` |
| 关联公开页反查 | `@AwsLuffy` ↔ `@awscdn888` / `@AWS158`；feiai.plus / `@feiaiplus` 卡网生态 |

## 撞库 / 跳过（宁缺毋滥）

| 项 | 原因 |
|----|------|
| `@iceaihubplus` `@gminiaixclaude` `@gptsplus` `@chatgpt003` | **tgcat-i 已入库** `5b52f45`；任务明示禁止再立/再交 |
| `@rlaudeai` `@geminisadasd` `@maoli9112` `@quanziai` | tgcat-h 已入库 `5e89430` |
| `@jianai996` `@claudepromax666` `@GeminiJL` `@gpt_user` | tgcat-g 已入库 |
| `@lyxazycn` `@openhuge_ai` `@wishtoapp` `@yylcard` | tgcat-f 已入库 |
| `@achuanqunzu` `@lcardpay` `@nodecard1` `@fuck_open` | tgcat-e 已入库 |
| `@Aiquanzi` `@nerverai` `@chatgptplusdeal` `@chineseChatGpt` + a/b/c/records 全套（gemini*/tokenfreed/redman/EM/laogou/oasisaigc/aiagent8080/aijlqun 等） | 已入库/已档 |
| `@Claudejiaoliu` | 已档 `group-claude-ziyuan-jishu`（records+drafts） |
| `@muskapi` | 任务明示**不跟** |
| `@gpt_kedaya` | 可核超群（~5 810；「小菲猪后援会」空窗）→ 名额满 5 → **下一批** |
| `@apidiyidazhan` + `@apizhushou_bot` | 可核（章鱼哥 API 联盟；有挂名 bot）→ 偏中转联盟 → **下一批**（优先 bots/） |
| `@a6apicom` | Token 交易所超群；非本批主池 → **下一批** |
| `@DaFeiverls` | 有 CNY 价目行但仅 ~334 members；无 $ 价目 → 宁缺控量 → **下一批** |
| `@waigpt` `@buy_sell_gmail` `@nghienvoc` `@lpolarischat` | 体验机器人群 / Gmail 买卖 / VN SheerID / 羊毛流媒体 → 主题不符本批 |
| `@gptplusjiaoliu` 等 <100 members | 体量过小 → 宁缺 |
| `@AWS158` `@apizongzhuan` `@a6apiai` `@ploarispublic` 等纯频道 | 仅关联/反查，**不**立频道档 |
| em-shop | 本批无公开 ≥2 行可引用 $ |

## 交审表（本批）

| 路径 | @ | join gate | bot / 关联 | 建议 |
|------|---|-----------|------------|------|
| `drafts/.../group-ainh666.md` | `@ainh666` | 需登录（MSG=0） | 无店 bot；低价 GPT/Gemini | **交审** |
| `drafts/.../group-awscdn888.md` | `@awscdn888` | 需登录（MSG=0） | `@AwsLuffy` 人号；频道 `@AWS158` | **交审** |
| `drafts/.../group-mguishu.md` | `@mguishu` | 需登录（MSG=0） | 卡网 feiai.plus；无店 bot | **交审** |
| `drafts/.../group-chatgptaigongshi.md` | `@CHATGPTaigongshi` | 需登录（MSG=0） | 简介空窗；大型中文社区 | **交审** |
| `drafts/.../group-duoqudaochengpin.md` | `@duoqudaochengpin` | 需登录（MSG=0） | 无店 bot；成品话术 username | **交审** |

## 下一批候选（建议顺序）

1. `@gpt_kedaya`（小菲猪后援会；空窗；与 mguishu 菲区线消歧后立）
2. `@apidiyidazhan` + 挂名 bot `@apizhushou_bot`（优先写 `tg-catalog/bots/`；关联频道 `@apizongzhuan`）
3. `@a6apicom`（Token 交易所；关联 `@a6apiai`）
4. `@DaFeiverls`（有 CNY 价目；体量小；**无** $ → 仍不硬凑 em-shop）
5. 其他新公开 @（土豆/互推/目录站延伸；撞库 a–j 后再立；**muskapi 不跟**；宁缺毋滥）

## 公开预览核验方法

- 群：`curl`/`urllib` `t.me/<user>` → og title / `tgme_page_extra`（members/online）；`t.me/s/<user>` **MSG=0** → **需登录**
- 频道（仅关联）：`@AWS158` 等 → subscribers
- 人号：`@AwsLuffy` / `@feiaiplus` → Send Message（非 Start Bot）
- bot：经群简介公开挂名核；空价目不立 em-shop、不 `/start`

## 合规备忘

- 只写 `drafts/deals/tg-catalog/`；**未**直写 `records/`、**未** git push、未发群帖、未对 bot `/start`/试单/购买、未接 VIP 转发。
- 需登录群未伪造帖体；观察 ≠ 推荐；状态均为「候选」。
- e/f/g/h/i 摘要**未**覆写；i 残留已删勿交。
