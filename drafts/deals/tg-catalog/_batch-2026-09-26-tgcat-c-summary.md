# 批次 tgcat-c 摘要 · TG 群目录（2026-09-26）

提案人：小弟·低价资源（执行手）  
目录：`drafts/deals/tg-catalog/`  
状态：候选交审（**未**写 `records/`、**未** push）  
合规：只读；不发帖、不试单、不对 bot 下单；EM 未重复深挖

> 撞库更新（阿言/父代理）：`@aijlqun` `@claudegpt520` `@gpt_nocard` 已入库 commit `2a79e79` → **本批勿再写**。其余 tgcat-a/b 已档与任务跳过名单一并撞库。

## 本批新建

### A. 完整群档（3）

| # | 文件 | @username | 公开可读帖？ | 挖到的 bot（摘要） |
|---|------|-----------|--------------|-------------------|
| 1 | `groups/group-laogou-org.md` | `@laogou_org` | 群否；关联频道 **`laogou_gg` 是** | `@laogou_support_bot` + 客服 `@laogou_kf`；频道收号帖 `@laogou_wr` |
| 2 | `groups/group-oasisaigc.md` | `@oasisaigc` | 群否；关联频道 **`oaaigc` 是** | `@oascfbot`（发卡网客服；频道人民币号卡价，无 ≥2 行 $ → 未立 em-shop） |
| 3 | `groups/group-aiagent8080.md` | `@aiagent8080` | **否**（join gate） | 简介无店 bot；自称代充行业「1688」交流 |

### B. 群目录 bots 指针（2）

| 文件 | Bot | 说明 |
|------|-----|------|
| `bots/bot-laogou-support-relay.md` | `@laogou_support_bot` | 双向中继；非价目店；不交叉 em-shop |
| `bots/bot-oascfbot-faka-cs.md` | `@oascfbot` | 发卡网客服；公开窗无 $ 表；不交叉 em-shop |

## 排查范围

| 来源 | 动作 |
|------|------|
| 土豆目录 https://2dou.org/telegram | **主货源**：curl 抽 `t.me/<user>` 列表后逐条核 `tgme_page_extra` + `t.me/s/` MSG |
| WebSearch 中文 AI 订阅买卖群 | 命中 `@aiagent8080`、invite 型档口、频道 `@chatgpt_008` 等；invite 无公开 @ 不立群档 |
| tgcat-a/b 已交 / 任务跳过名单 | 全部撞库跳过（见下表） |
| 关联频道反查 | `laogou_gg` / `oaaigc` / `wishtoapp_channel` 公开 `data-post`；用于互证 bot，**未**把纯频道硬写成群档 |

## 撞库 / 跳过（宁缺毋滥）

| 项 | 原因 |
|----|------|
| `@aijlqun` `@claudegpt520` `@gpt_nocard` | **已入库** `2a79e79`；勿再写 |
| `@chatgptplusbuysell` `@gemini12pro` `@Geminivip1` `@elitemethodchat` + A2/侧栏/records 全套 | 任务跳过 / 已有 drafts|records |
| `@geminichatgroup` `@aipricedb` `@priceaicc` `@with_ai_homes` `@tgaigroup`/`@TGAI_Group` `@redman3721` `@tokenfreed` `@claudecode_cn` | drafts 已有；勿重写 |
| `@Claudejiaoliu`/`claude-ziyuan` `@gemini3369`/`gemini-jiaoliu` `@roboticvn` | 已档；跳过 |
| `@achuanqunzu` `@claudepromax666` `@jianai996` `@lcardpay`/`@LCardPay` `@nodecard1` `@yylcard` `@chatgptplusdeal` | 2dou 可核、有公开 @；本批名额满（优先有 bot+公开频道互证者）；可下批 |
| `@fuck_open` `@openhuge_ai` `@maoli9112` `@quanziai` `@rlaudeai` `@gminiaixclaude` `@gptsplus` `@geminisadasd` `@wishtoapp` `@iceaihubplus` | 可核超群；同质/名额控量；`@wishtoapp` 有频道但无店 bot 公开窗优先度低于本批三档 |
| `@Aiquanzi` `@muskapi` | 检索可见；体量小或频道型；控量 |
| `@nodecard_bot` 重开 | F/M 批已判公开页不足；本批不立 bot 档（仅在跳过说明） |
| `@gptnocard` `@Claude111111` `@chatgpt_008` `@laogou_gg` `@oaaigc` `@iceai_hub` `@Aigongying` | **频道**型；仅作群档关联/反查 |
| 纯 invite（`t.me/+…`）无公开 @ | 不符必填 @ 优先（如 WebSearch 官方代充 invite） |
| em-shop 交叉 | 本批 bot 均无公开 ≥2 行可引用 $；未硬凑 |

## 公开预览核验方法

- 群：`curl` `t.me/<user>` → `tgme_page_extra`（members/online）+ og 简介；`t.me/s/<user>` **MSG=0** → **需登录**
- 频道：`t.me/s/laogou_gg`、`t.me/s/oaaigc` 可见 `data-post` 正文（本批用于反查讨论群与客服 bot）

## 合规备忘

- 未写 `records/`；未 git push；未对 bot `/start` 下单；未发群帖。
- 需登录群未伪造帖体；bot 表来源均为公开 og / 频道帖。

---

## 补录 C2（小弟·TG · 同日扩面）

提案人：小弟·TG  
说明：并行专员（小弟·低价资源）已交上节 A/B（`@laogou_org` / `@oasisaigc` / `@aiagent8080` + 2 bot）；本补录**只写 drafts**，**不**覆盖已交群档 / **不**写 records / **不** push。优先消化上批跳过点名 `@Aiquanzi` `@nerverai`，以及 tgcat-b「可下批」`@chatgptplusdeal`。

### 新建群档（4）

| # | 文件 | 群 @ | 访问 | 群内 bot 表摘要 |
|---|------|------|------|-----------------|
| 1 | `groups/group-aiquanzi.md` | `@Aiquanzi` | 公开介绍；看帖需登录 | 简介空窗无店 bot；标题「GPT 美区ios 全程质保」；~164 members |
| 2 | `groups/group-nerverai.md` | `@nerverai` | 同上；关联频道 `@nervercc` | 公益 Token/中转交流；店 bot 走已档 `@nerverbot_bot`（不重开） |
| 3 | `groups/group-chatgptplusdeal.md` | `@chatgptplusdeal` | 同上 | 简介无店 bot；英文 OTC Buy & Sell；**异于** `@chatgptplusbuysell` |
| 4 | `groups/group-chinesechatgpt.md` | `@chineseChatGpt` | 同上；教学频道 `@openaichatgpt_channel` | `@Super_ChatGptBot` + `@PG_ChatGptBot`（体验，非价目） |

### 可选 bot 线索（1）

| 文件 | Bot | 说明 |
|------|-----|------|
| `bots/bot-super-chatgpt-experience.md` | `@Super_ChatGptBot` | 群内 GPT-4.1 体验；**非** em-shop；未 `/start` |

### 本补录跳过

| 对象 | 原因 |
|------|------|
| `@laogou_org` / `@oasisaigc` / `@aiagent8080` + 其 bots | 上节并行已交；**不覆盖** |
| `@aijlqun` `@claudegpt520` `@gpt_nocard` 及 tgcat-a/b/records 全套 | 已入库/已档；撞库 |
| `@muskapi` | 硬规则不跟 |
| `@fuck_open` `@claudepromax666` `@GeminiJL` `@gpt_user` `@achuanqunzu` `@jianai996` `@yylcard` `@lcardpay` `@nodecard1` `@openhuge_ai` `@lyxazycn` 等 | 2dou/Web 可核；本补录名额满（优先点名+可下批+体验 bot 互证） |
| `@Claude111111` `@gptnocard` `@chatgpt_008` `@nervercc` `@openaichatgpt_channel` | 频道型；仅作关联 |
| 纯 invite 无公开 @ | 不符必填 @ |
| em-shop | 本补录无公开 ≥2 行 $；未硬凑 |

### 公开预览核验（本补录）

- `curl` `t.me/<user>` → og title / `tgme_page_extra` members；`t.me/s/<user>` **MSG=0** → 需登录
- 候选出处：2dou.org/telegram；WebSearch 中文体验群；已档 `@tokenfreed` 交叉 `@nerverai`

### 合规备忘（本补录）

- 未写 `records/`；未 git push；未发帖；未对 bot `/start`/试单；未 SSH/Telethon/session/2FA。
