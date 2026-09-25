# 批次 tgcat-b 摘要 · TG 群目录（2026-09-26）

提案人：小弟·低价资源（执行手）  
目录：`drafts/deals/tg-catalog/`  
状态：候选交审（**未**写 `records/`、**未** push）  
合规：只读；不发帖、不试单、不对 bot 下单；EM 未重复深挖

> 说明：同目录曾出现并行写入的 `group-tgaigroup` / `group-redman3721` / `group-tokenfreed` / `group-claudecode-cn` 与旧版 summary；**本文件仅交审本执行手新建的 3 群 + 1 bot 指针**。并行档未删、未改。

## 本批新建（本执行手）

### A. 完整群档（3）

| # | 文件 | @username | 公开可读帖？ | 挖到的 bot（摘要） |
|---|------|-----------|--------------|-------------------|
| 1 | `groups/group-aijlqun.md` | `@aijlqun` | **否**（join gate） | 简介无店 bot；禁广代充交流；业务走群主/管理（未公开 @） |
| 2 | `groups/group-claudegpt520.md` | `@claudegpt520` | 群否；关联频道 **`Claude111111` 是** | 购号 `@xzl5200` / 广告 `@Xennch` / 售后 `@Juan9178`；频道近窗无 ≥2 行公开 $ → **未**立 em-shop |
| 3 | `groups/group-gpt-nocard.md` | `@gpt_nocard` | 群否；关联频道 **`gptnocard` 是** | `@gptnocard_bot`（**records 已有**；本批补群档 + 目录指针）；频道挂名同质店跳过 |

### B. 群目录 bots 指针（1）

| 文件 | Bot | 说明 |
|------|-----|------|
| `bots/bot-gptnocard-free-upgrade.md` | `@gptnocard_bot` | **已入库** `records/other/bot-gptnocard-plus-upgrade.md`（2026-09-25）；本批只写目录指针，不重写 records / 不交叉 em-shop |

## 排查范围

| 来源 | 动作 |
|------|------|
| WebSearch `telegram buy sell chatgpt gemini group` | 命中已档 `@geminichatgroup` 等；转入 2dou |
| 土豆目录 https://2dou.org/telegram | **主货源**：抓公开 `t.me/<user>` 后 curl 核 `members` |
| tgcat-a / A2 已档 | `@geminichatgroup` `@priceaicc` `@aipricedb` `@with_ai_homes` 等 → 跳过 |
| 既有扫描 `_scan-raw-2026-09-25.txt` | 主群仍为 buysell / tokenfreed / EM；无新增本批优先 @ |
| `gemini12pro_channel` 反查 | 讨论群已档；推广 bot 多为已入库闪购 |

## 撞库 / 跳过（宁缺毋滥）

| 项 | 原因 |
|----|------|
| `@elitemethodchat` / Jero 线 + `@chatgptplusbuysell` `@gemini12pro` `@Geminivip1` + `@SSkyGPTbot` | 任务已入库/已有；跳过 |
| 侧栏 `@Claudejiaoliu`（原 Claude 资源/技术）`@gemini3369`（原 gemini 交流群） | **已入库** records；跳过（勿与 `@claudegpt520` / `@geminichatgroup` 混同） |
| ROBOTICVN=`@hiroboticvn_bot` | **已入库**（bot 非超群）；跳过 |
| `@geminichatgroup` `@priceaicc` `@aipricedb` `@with_ai_homes` | A2 已写 drafts；跳过 |
| `@chatgptplusdeal` | 另一「Buy & Sell Worldwide」（~1.4 万，异于 buysell）；名额满，可下批 |
| `@tokenfreed` `@redman3721` `@claudecode_cn` `@TGAI_Group` | 本执行手跳过（控量）；目录内若有并行档见文件本身，**非**本 summary 交审范围 |
| `@achuanqunzu` `@aiagent8080` `@yylcard` `@lcardpay` `@claudepromax666` `@jianai996` `@nodecard1` `@Aiquanzi` `@muskapi` | 2dou/检索可核；同质或名额满（`@gemini3369` 已上移至已入库跳过） |
| `@gptnocard` `@Claude111111` `@chatgpt_008` `@gpt6688` | **频道**型；仅作群档关联 |
| `@gptnocard_bot` 重开 records | 主档已在；本批仅 tg-catalog 指针 |
| 纯 invite（`t.me/+…`）无公开 @ | 不符必填 @ 优先 |

## 公开预览核验方法

- 群：`curl` `t.me/<user>` → og / `N members`；`t.me/s/<user>` **MSG=0** → **需登录**
- 频道关联：`t.me/s/Claude111111`、`t.me/s/gptnocard` 可见 `data-post`

## 合规备忘

- 未写 `records/`；未 git push；未对 bot `/start` 下单；未发群帖。
- 需登录群未伪造帖体；em-shop 门槛（公开 ≥2 行 $）本批未达标。
