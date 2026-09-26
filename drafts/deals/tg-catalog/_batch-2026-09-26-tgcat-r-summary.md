# 批次 tgcat-r 摘要 · TG 群目录（2026-09-26）

提案人：小弟·TG  
目录：`drafts/deals/tg-catalog/`  
状态：候选草稿（**未**写 `records/`、**未** push、**未**交审）  
合规：只读；不发帖、不试单、不对 bot 下单；禁 SSH/Telethon/session/2FA；`@muskapi` 不跟  
加码：阿言定调 **群+bot 成对** + **尽量多低价/挂名 bot**——优先续群公开窗无挂名 bot，以频道/公开页可核挂名 bot（双向/福利/签到）成对补位；宁缺空价目硬凑

> 前置：老大派工 **tgcat-r**（优先续 `@aichengpingjiaoliu` `@aigo8688` `@aigptchong` 等）。撞库含 q `49caba7`（十群+三 bot）及 a–q / n2 / l / l2 / m / o / p 全套。字母 r 到岗时空闲，**未**升 r2。

## 本批新建

### A. 完整群档（10）

| # | 文件 | 群 @ | 访问 | 群内 bot / 关联摘要 |
|---|------|------|------|---------------------|
| 1 | `groups/group-aichengpingjiaoliu.md` | `@aichengpingjiaoliu` | 公开介绍；看帖需登录（MSG=0） | 「AI交流群」~3 645；简介**空窗**；**无**挂名 bot |
| 2 | `groups/group-aigo8688.md` | `@aigo8688` | 同上 | 「Boss源头批发交流群」~3 343；简介空；**无**挂名 bot |
| 3 | `groups/group-aigptchong.md` | `@aigptchong` | 同上 | 「AI交流群 & 海外ip（禁硬广）」~2 635；简介空；**无**挂名 bot |
| 4 | `groups/group-aixiaomaidian.md` | `@aixiaomaidian` | 同上 | 「AI小卖店」~2 747；简介空；**无**挂名 bot |
| 5 | `groups/group-xingluo2.md` | `@xingluo2` | 同上 | 「星络中转」~1 351；简介挂中转/卡网 URL（CNY/倍率）；**无**挂名 bot |
| 6 | `groups/group-claudegroup.md` | `@claudegroup` | 同上 | 「Claude Group」~1 343；人号 Owner `@ClaudeSeller`（**不**立 bots/）；logs `@claudelogsgroup` 仅反查 |
| 7 | `groups/group-easyapis.md` | `@easyapis` | 同上 | 「Easy-APi 中转站」~339；回链 `@ai6266`（records 已档）；**无**挂名 bot |
| 8 | `groups/group-fenglan1201.md` | `@fenglan1201` | 同上 | 「风岚の交流群」~1 695；中转+卡网+QQ；**无**挂名 bot |
| 9 | `groups/group-sourcegpt.md` | `@sourcegpt` | 同上 | 「顶级源头中转-只做低价」~632；简介空；**无**挂名 bot |
| 10 | `groups/group-spacex-api.md` | `@spacex_api` | 同上 | 「太空中转站 chatgpt 交流群」~3 615；简介空；**无**挂名 bot |

### B. 群目录 bots（4）← 本批 bots 清单

| 文件 | Bot | 类型 | 说明 |
|------|-----|------|------|
| `bots/bot-mihai6668-relay.md` | `@Mihai6668_bot` | **双向客服** | 经频道 `@aigpt888` 公开简介挂名；Start Bot 可核；og「米海双向机器人」；**无** ≥2 行可引用 **$** → **不**交叉 em-shop；未 `/start` |
| `bots/bot-plus-exchange-welfare.md` | `@plus_exchange_bot` | **福利/兑换** | bot 自挂频道 `@aivip6688` + 管理员 `@aiplus8`；Start Bot 可核；公开窗无 ≥2 行 **$** → 拒 em-shop；未 `/start` |
| `bots/bot-aibijia-welfare.md` | `@aibijia_bot` | **福利/拉人** | 公开 og「邀满20人得 Claude Max X20 一个月」；无挂群成对；拒 em-shop；未 `/start` |
| `bots/bot-ai-checkin.md` | `@ai_checkin_bot` | **签到/打卡** | 公开 og「AI 打卡助手」；无挂群成对；拒 em-shop；未 `/start` |

关联频道 `@aigpt888` / `@aivip6688` / `@claudelogsgroup`、人号 `@Mihai668` / `@aiplus8` / `@ClaudeSeller`、卡网/中转站外链 **仅反查/记名**，**不**立频道档、不发明 username。站外卡网仅轻核，**不**注册/充值。

## 排查范围

| 来源 | 动作 |
|------|------|
| 任务优先续 `@aichengpingjiaoliu` `@aigo8688` `@aigptchong` + q 跳过池 `@aixiaomaidian` `@xingluo2` `@claudegroup` `@easyapis` | urllib/curl `t.me/<user>` → og / `tgme_page_extra`；`t.me/s/` **MSG=0** → join gate |
| 加码·群+bot + 多 bot | 扫优先群简介 → **均无**挂名 bot；命中频道 `@aigpt888`↔`@Mihai6668_bot`；补福利/签到公开 bot |
| 2dou.org/telegram 全 4 页 | 扩未入库公开 @（fenglan/sourcegpt/spacex_api 等）；invite-only 跳过 |
| records/other/tg-catalog/ + drafts 全套 | 撞库：本批十群 + 四 bot 无独立档；**不跟** `@muskapi`；q `49caba7` 十群+三 bot 已入库跳过 |
| 站外轻核 | aiccxx / ldxp / catfk / fengl / 16688 / easyapis.cc：未见 ≥2 行可引用 **$** → 拒 em-shop（CNY≠$ 不硬凑） |

## 撞库 / 跳过（宁缺毋滥）

| 项 | 原因 |
|----|------|
| q 十群 + `@guofuluban_bot` `@lowpriceking_bot` `@chatgpt_claude4_bot` | **tgcat-q 已入库** `49caba7` |
| `@jiafeimaoai` `@token014` `@realquickmarket` `@bin_api` + `@Binkoo_bot` | **tgcat-p 已入库** `6e4559a` |
| `@hdc5nme9` `@appkaola` `@ainenglianggpt` `@dingdingpu` + `@KAOLAAIBOT` | **tgcat-o 已入库** `bdee7ea` |
| a–n / n2 / l / l2 / m 及 records 全套已知 @ | 已入库/已档 |
| `@muskapi` | 任务明示**不跟** |
| `@ClaudeSeller` `@Mihai668` `@aiplus8` | **人号** Send Message → **不**立 bots/ |
| `@aigpt888` `@aivip6688` `@claudelogsgroup` / 纯频道 | 仅关联反查，**不**立频道档 |
| `@ai6266` | records 已档；本批仅以 `@easyapis` 回链对照 |
| `@AIqiandao_bot` `@cheapgpt_bot` `@FreeGPTBot` 等空描述弱样本 | 宁缺毋滥；仅收有明确类型标题/挂名链者 |
| `@GroupWowBot` / `@GroupAIChat` | 群管 bot，非低价订阅向；控量跳过 |
| 2dou 仅 invite（`t.me/+…`） | **无公开 @** → 不发明 username |
| em-shop | 本批无公开 ≥2 行可引用 **$**（CNY/倍率/双向空价目/福利自述均不硬凑） |

## 本批路径表（建议交审）

| 路径 | @ | join gate | bot / 关联 | 建议 |
|------|---|-----------|------------|------|
| `drafts/.../group-aichengpingjiaoliu.md` | `@aichengpingjiaoliu` | 需登录（MSG=0）→ **需协采** | 无店 bot；拒 em-shop | **交审**（任务续 #1） |
| `drafts/.../group-aigo8688.md` | `@aigo8688` | 需登录 → **需协采** | 无店 bot | **交审** |
| `drafts/.../group-aigptchong.md` | `@aigptchong` | 需登录 → **需协采** | 无店 bot | **交审** |
| `drafts/.../group-aixiaomaidian.md` | `@aixiaomaidian` | 需登录 → **需协采** | 无店 bot | **交审** |
| `drafts/.../group-xingluo2.md` | `@xingluo2` | 需登录 → **需协采** | 卡网/中转；拒 em-shop | **交审** |
| `drafts/.../group-claudegroup.md` | `@claudegroup` | 需登录 → **需协采** | 人号 `@ClaudeSeller`；拒 em-shop | **交审** |
| `drafts/.../group-easyapis.md` | `@easyapis` | 需登录 → **需协采** | 回链 `@ai6266`；拒 em-shop | **交审**（成对回链） |
| `drafts/.../group-fenglan1201.md` | `@fenglan1201` | 需登录 → **需协采** | 中转+卡网；拒 em-shop | **交审** |
| `drafts/.../group-sourcegpt.md` | `@sourcegpt` | 需登录 → **需协采** | 无店 bot；低价向标题 | **交审** |
| `drafts/.../group-spacex-api.md` | `@spacex_api` | 需登录 → **需协采** | 无店 bot | **交审** |
| `drafts/.../bot-mihai6668-relay.md` | `@Mihai6668_bot` | Start Bot 可核 | **类型：双向客服**；拒 em-shop；未 `/start` | **交审**（成对补位） |
| `drafts/.../bot-plus-exchange-welfare.md` | `@plus_exchange_bot` | Start Bot 可核 | **类型：福利/兑换**；拒 em-shop；未 `/start` | **交审** |
| `drafts/.../bot-aibijia-welfare.md` | `@aibijia_bot` | Start Bot 可核 | **类型：福利/拉人**；拒 em-shop；未 `/start` | **交审** |
| `drafts/.../bot-ai-checkin.md` | `@ai_checkin_bot` | Start Bot 可核 | **类型：签到/打卡**；拒 em-shop；未 `/start` | **交审** |

> 十群均为公开介绍可开、看帖 **需登录**；本批**未**臆造 msgid，实帖/店 bot 扩挖标「需协采」。

## 下一批候选（建议顺序）

1. 登录协采本批十群后补 bot/实帖（msgid）；优先群若出现挂名店 bot 再扩 `tg-catalog/bots/`
2. `@qiuqiuai1919` / `@computeunion` / `@catcard01` / `@trytovv_ai` / `@tudou_api`（2dou 可核，撞库后再立）
3. `@kaishiqianggouba` / `@token111111` / `@voklyai`（资源/中转向；撞库后）
4. **muskapi 不跟**；CNY 仍不硬凑 em-shop；继续群+bot 成对优先；同质闪购控量

## 公开预览核验方法

- 群：`curl`/`urllib` `t.me/<user>` → og title / `tgme_page_extra`（members/online）；`t.me/s/<user>` **MSG=0** → **需登录**
- bot：经群/频道/自述公开挂名或公开 Start Bot 核类型（双向/福利/签到/比价/体验）；空价目 → 不立 em-shop、不 `/start`
- 人号：`Send Message` → **不**立 bots/
- 频道：仅反查 subscribers / 标题 / 公开预览，**不**立档
- 站外：轻核 SPA/卡网币种，**不**注册/充值
