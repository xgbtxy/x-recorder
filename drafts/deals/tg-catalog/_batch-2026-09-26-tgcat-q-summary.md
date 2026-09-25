# 批次 tgcat-q 摘要 · TG 群目录（2026-09-26）

提案人：小弟·TG  
目录：`drafts/deals/tg-catalog/`  
状态：候选草稿（**未**写 `records/`、**未** push、**未**交审）  
合规：只读；不发帖、不试单、不对 bot 下单；禁 SSH/Telethon/session/2FA；`@muskapi` 不跟  
加码：阿言定调 **群+bot 成对** + **尽量多 bot / 加更多 AI 资源群**——优先四群公开窗无挂名 bot，以 `@grokaifenjue`↔`@guofuluban_bot`（人号简介挂双向，发现链写清）成对补位；另补低价比价指针 + 体验缝合 bot；宁缺空 bot 批

> 前置：老大派工 **tgcat-q**（优先 `#1 @yoyoai123` → `@nlai001` / `@bysjlq` / `@ghatgptclaude`）。撞库含 p `6e4559a`（`@jiafeimaoai`/`@token014`/`@realquickmarket`/`@bin_api` + `@Binkoo_bot`）及 a–p / n2 / l / l2 / m / o 全套。字母 q 到岗时空闲，**未**升 q2。

## 本批新建

### A. 完整群档（10）

| # | 文件 | 群 @ | 访问 | 群内 bot / 关联摘要 |
|---|------|------|------|---------------------|
| 1 | `groups/group-yoyoai123.md` | `@yoyoai123` | 公开介绍；看帖需登录（MSG=0） | 「yoyoai企业圈」~5 393；简介**空窗**；**无**挂名 bot |
| 2 | `groups/group-nlai001.md` | `@nlai001` | 同上 | 「奶龙ai」~4 656；简介空；**无**挂名 bot |
| 3 | `groups/group-bysjlq.md` | `@bysjlq` | 同上 | 「半页酥 Chat」~4 743；简介空（l 曾宁缺；本批任务点名续立并标待协采） |
| 4 | `groups/group-ghatgptclaude.md` | `@ghatgptclaude` | 同上 | 「GLOBAL CLAUDE团体」~3 684；品类+USDT 话术；人号 `@AREMANOD`（**不**立 bots/） |
| 5 | `groups/group-grokaifenjue.md` | `@grokaifenjue` | 同上 | 「ai公益羊毛聚集地」~2 459；所有者→双向 `@guofuluban_bot`（**成对补位**）；频道 `@grokfenjue` 仅反查 |
| 6 | `groups/group-talkai-z.md` | `@talkai_z` | 同上 | 「源头搬运工」~4 308；卡网 talkai.cyou；人号 `@talkai_kefu`（**不**立 bots/）；频道/广告群仅反查 |
| 7 | `groups/group-lizi1001.md` | `@lizi1001` | 同上 | 「励子Ai源头批发群」~2 783；简介空；**无**挂名 bot |
| 8 | `groups/group-superspider8.md` | `@superspider8` | 同上 | 「SuperSpider低价GPT Pro」~938；简介空；**无**挂名 bot |
| 9 | `groups/group-chiyu090555.md` | `@chiyu090555` | 同上 | 「chiyu gpt ai」~2 451；ldxp 卡网 + 频道 `@chiyugpt666` 仅反查；**无**挂名 bot |
| 10 | `groups/group-ai6266.md` | `@ai6266` | 同上 | 「AI67 杂货铺」~2 090；挂中转群 `@easyapis`（群非 bot，不立 bots/） |

### B. 群目录 bots（3）← 本批 bots 清单

| 文件 | Bot | 类型 | 说明 |
|------|-----|------|------|
| `bots/bot-guofuluban-relay.md` | `@guofuluban_bot` | **双向客服** | 经 `@grokaifenjue`→`@iniubilubenwei` 人号简介公开挂名；Start Bot 可核；og「国服鲁班的双向机器人」；**无** ≥2 行可引用 **$** → **不**交叉 em-shop；未 `/start` |
| `bots/bot-lowpriceking-compare.md` | `@lowpriceking_bot` | **比价/底价** | 公开 Start Bot 可核；交叉主档 `records/other/bot-lowpriceking-pricehunter.md`；本批补 tg-catalog 指针；拒 em-shop；未 `/start` |
| `bots/bot-chatgpt-claude4-experience.md` | `@chatgpt_claude4_bot` | **体验/缝合 AI** | 公开 Start Bot 可核；无挂群成对；公开窗无 **$** 价目 → 拒 em-shop；未 `/start`；关联频道 @ **未**在公开窗给出 → 不臆造 |

关联频道 `@grokfenjue` / `@talkai_channel` / `@talkai_ad` / `@chiyugpt666`、中转群 `@easyapis`、人号 `@AREMANOD` / `@talkai_kefu` / `@iniubilubenwei` **仅反查/记名**，**不**立频道档、不发明 username。站外卡网仅轻核，**不**注册/充值。

## 排查范围

| 来源 | 动作 |
|------|------|
| 任务优先 `#1 @yoyoai123` + p 跳过池 `@nlai001`/`@bysjlq`/`@ghatgptclaude` | urllib/curl `t.me/<user>` → og / `tgme_page_extra`；`t.me/s/` **MSG=0** → join gate |
| 加码·群+bot + 多 bot | 扫优先四群简介 → **均无**挂名 bot；`@AREMANOD`/`@talkai_kefu` 为人号 Send Message → 不立 bots/；命中 `@grokaifenjue`↔人号↔`@guofuluban_bot`；补比价/体验 bot |
| 2dou 全 4 页 + telegramnav 抽核 | 扩未入库公开 @（lizi/superspider/chiyu/ai6266 等）；控量跳过同质闪购（Qamify/NyStore/Paglu/Zino 等既有口径） |
| records/other/tg-catalog/ + drafts 全套 | 撞库：本批十群 + 三 bot 无独立档；**不跟** `@muskapi`；p `6e4559a` 四群+Binkoo 已入库跳过 |
| 站外轻核 | talkai.cyou/ai-buy：CNY 信号、无 `$N` 可引用行；grok1.short.gy：SPA/短链无 `$N` → 拒 em-shop（CNY≠$ 不硬凑） |

## 撞库 / 跳过（宁缺毋滥）

| 项 | 原因 |
|----|------|
| `@jiafeimaoai` `@token014` `@realquickmarket` `@bin_api` + `@Binkoo_bot` | **tgcat-p 已入库** `6e4559a` |
| `@hdc5nme9` `@appkaola` `@ainenglianggpt` `@dingdingpu` + `@KAOLAAIBOT` | **tgcat-o 已入库** `bdee7ea` |
| `@ddh992` `@congmingxiayou1` `@zhwwsnbb` `@chapchaod` + 三 bot | **tgcat-n 已入库** `16b1909` |
| `@aishenji_group` + `@xihongshi123_bot` | **tgcat-n2 / 并行草稿**已立 |
| a–k / l / l2 / j / m 及 records 全套已知 @ | 已入库/已档 |
| `@muskapi` | 任务明示**不跟** |
| `@Qamify_bot` `@ZinoShopbot` `@NyStoreOfficialBot` `@Paglu_Shop_Bot` | chatgptplusbuysell 同质闪购**控量跳过**（既有口径） |
| `@ATC_AutoShop_Bot` | 游戏卡网；g 批已判不进本目录 |
| `@PG_ChatGptBot` | chinesechatgpt 表内已登记；c 批不另立第二体验档 |
| `@talkai_kefu` `@AREMANOD` `@iniubilubenwei` | **人号** Send Message → **不**立 bots/ |
| `@easyapis` | 中转**群**非 bot；仅反查 |
| `@grokfenjue` / `@talkai_channel` / `@talkai_ad` / `@chiyugpt666` / 纯频道 | 仅关联反查，**不**立频道档 |
| 2dou 仅 invite（`t.me/+…`） | **无公开 @** → 不发明 username |
| `@Xai1314bot` 等 NSFW/去衣向 | 不纳入本 AI/订阅低价目录 |
| em-shop | 本批无公开 ≥2 行可引用 **$**（CNY/SPA/双向空价目/比价自述均不硬凑） |

## 本批路径表（建议交审）

| 路径 | @ | join gate | bot / 关联 | 建议 |
|------|---|-----------|------------|------|
| `drafts/.../group-yoyoai123.md` | `@yoyoai123` | 需登录（MSG=0）→ **需协采** | 无店 bot；拒 em-shop | **交审**（任务 #1） |
| `drafts/.../group-nlai001.md` | `@nlai001` | 需登录 → **需协采** | 无店 bot | **交审** |
| `drafts/.../group-bysjlq.md` | `@bysjlq` | 需登录 → **需协采** | 空窗定位待确认 | **交审**（标风险） |
| `drafts/.../group-ghatgptclaude.md` | `@ghatgptclaude` | 需登录 → **需协采** | 人号 `@AREMANOD`；拒 em-shop | **交审** |
| `drafts/.../group-grokaifenjue.md` | `@grokaifenjue` | 需登录 → **需协采** | `@guofuluban_bot` 双向 | **交审**（成对） |
| `drafts/.../group-talkai-z.md` | `@talkai_z` | 需登录 → **需协采** | 人号 kefu；卡网 CNY | **交审** |
| `drafts/.../group-lizi1001.md` | `@lizi1001` | 需登录 → **需协采** | 无店 bot | **交审** |
| `drafts/.../group-superspider8.md` | `@superspider8` | 需登录 → **需协采** | 无店 bot；低价向标题 | **交审** |
| `drafts/.../group-chiyu090555.md` | `@chiyu090555` | 需登录 → **需协采** | ldxp；无店 bot | **交审** |
| `drafts/.../group-ai6266.md` | `@ai6266` | 需登录 → **需协采** | 中转群 `@easyapis` | **交审** |
| `drafts/.../bot-guofuluban-relay.md` | `@guofuluban_bot` | Start Bot 可核 | **类型：双向客服**；拒 em-shop；未 `/start` | **交审** |
| `drafts/.../bot-lowpriceking-compare.md` | `@lowpriceking_bot` | Start Bot 可核 | **类型：比价**；目录指针；拒 em-shop | **交审** |
| `drafts/.../bot-chatgpt-claude4-experience.md` | `@chatgpt_claude4_bot` | Start Bot 可核 | **类型：体验/缝合**；拒 em-shop；未 `/start` | **交审** |

> 十群均为公开介绍可开、看帖 **需登录**；本批**未**臆造 msgid，实帖/店 bot 扩挖标「需协采」。

## 下一批候选（建议顺序）

1. 登录协采本批十群后补 bot/实帖（msgid）；优先四群若出现挂名店 bot 再扩 `tg-catalog/bots/`
2. `@aichengpingjiaoliu` / `@aigo8688` / `@aigptchong` / `@aixiaomaidian` / `@xingluo2`（2dou 可核，撞库后再立）
3. `@claudegroup`（人号 `@ClaudeSeller` 不立 bots/；可核英文买卖群样本）
4. 中转群 `@easyapis` 是否单独立档（回链 `@ai6266`）
5. **muskapi 不跟**；CNY 仍不硬凑 em-shop；继续群+bot 成对优先；同质闪购控量

## 公开预览核验方法

- 群：`curl`/`urllib` `t.me/<user>` → og title / `tgme_page_extra`（members/online）；`t.me/s/<user>` **MSG=0** → **需登录**
- bot：经群/人号简介公开挂名或公开 Start Bot 核类型（双向/比价/体验）；空价目 → 不立 em-shop、不 `/start`
- 人号：`Send Message` → **不**立 bots/
- 频道：仅反查 subscribers / 标题 / 公开预览，**不**立档
- 站外：轻核 SPA/卡网币种，**不**注册/充值
