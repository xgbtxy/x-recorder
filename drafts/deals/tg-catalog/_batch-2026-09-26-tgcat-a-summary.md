# 批次 tgcat-a 摘要 · TG 群目录（2026-09-26）

提案人：小弟·低价资源  
目录：`drafts/deals/tg-catalog/`  
状态：候选交审（**未**写 `records/`、**未** push）  
合规：只读；不发帖、不试单、不对 bot 下单；EM 未重复深挖

## 本批新建

### A. 完整群档（3）

| # | 文件 | @username | 公开可读帖？ | 挖到的 bot（摘要） |
|---|------|-----------|--------------|-------------------|
| 1 | `groups/group-chatgptplusbuysell.md` | `@chatgptplusbuysell` | **否**（join gate） | 登录窗扫描已入库店一批：Warzone / Gemini_shop_robot / AiSubShop / Aith / Vouchers / Excalibur / TrustedShoping / Prime_Gadget / storeBatman / lhiestore / MangoShop / ToolsWala / VaultX 等；Gemini 闪购同质跳过 |
| 2 | `groups/group-gemini12pro.md` | `@gemini12pro` | 群否；关联频道 **`gemini12pro_channel` 是** | `@gemini12pro_bot`（公益 Helper）；频道公开推广 `@AiVerseXBot`（$0.45）、`@Gemini_shop_robot`、`@ver_pixel_bot`/`fork_bot_channel` 等 |
| 3 | `groups/group-geminivip1.md` | `@Geminivip1` | **否**（join gate）；简介+卡网公开 | `@SSkyGPTbot` + 客服 `@lengmeng28` / store.dimosky.com（无 ≥2 行公开 $ → 未立 em-shop） |

### B. 侧栏提案协采短条（3）

| 文件 | 显示名 | 公开 username | 跳过/待办 |
|------|--------|---------------|-----------|
| `groups/group-claude-ziyuan-jishu.md` | Claude 资源/技术 | **无**（id `-1003830420390`） | 扫描 NO_BOTS；待老大补 @/invite/msgid |
| `groups/group-gemini-jiaoliu.md` | gemini 交流群 | **无**（id `-1003728745211`） | 扫描 NO_BOTS；勿与 `@gemini12pro`/`@geminichatgroup` 混同 |
| `groups/group-roboticvn-shop.md` | ROBOTICVN SHOP | **无** | 扫描未 FOUND；`@roboticshop`/`@roboticvn` 仅为个人号；维修 invite 未互证 |

### C. 群目录 bots 简档（1）

| 文件 | Bot | 说明 |
|------|-----|------|
| `bots/bot-sskygpt-free-upgrade.md` | `@SSkyGPTbot` | 公益升级；非价目店；不交叉 em-shop |

## 公开预览核验方法

- 群：`curl`/`WebFetch` `t.me/<user>` 取 og（members / 简介）；`t.me/s/<user>` **MSG=0** → 记 **需登录**
- 频道：`t.me/s/gemini12pro_channel`、`t.me/s/fork_bot_channel` 可见 `data-post` 正文（本批用于反查讨论群与推广 bot，**未**把纯频道硬写成群档）

## 撞库 / 跳过

| 项 | 原因 |
|----|------|
| `@elitemethodchat` / EM 深挖 | 已有 `group-elitemethodchat.md`；老大在采；本批跳过 |
| `records/other/em-shop` 与既有 `bot-*.md` handles | 买卖群扫描店已入库者只交叉引用，不重开 em-shop |
| `@Qamify_bot` `@ZinoShopbot` `@NyStoreOfficialBot` `@Paglu_*` | Gemini 同质闪购控量 |
| `@geminichatgroup` `@redman3721` `@tokenfreed` `@claudecode_cn` | 有公开 @ 但 join gate；本批名额优先侧栏+买卖主货源+频道反查讨论群；可下批立档 |
| `store.dimosky.com` → em-shop | 静态首页无 ≥2 行可引用公开 $；未交互 API 硬凑 |
| 纯频道当群 | 未立；仅在 `group-gemini12pro` 内标明关联频道公开可读 |

## 合规备忘

- 未写 `records/`；未 git push；未对 bot 发 `/start` 下单；未发群帖。
- 需登录群未伪造帖体；bot 表来源均为公开 og/频道帖或既有 Telethon LINKHINT。

## 补录 A2（小弟·TG · 同日扩面）

提案人：小弟·TG  
说明：并行专员已交 A 节 3 群并入库 `records/other/tg-catalog/`；本补录**只写 drafts**，**不**覆盖已交群档 / **不**写 records / **不** push。

### 新建群档（4）

| # | 文件 | 群 @ | 访问 | 群内 bot 表摘要 |
|---|------|------|------|-----------------|
| 1 | `groups/group-aipricedb.md` | `@aipricedb` | 公开介绍；看帖需登录 | 简介无店 bot；比价站 www.aipricedb.com |
| 2 | `groups/group-with-ai-homes.md` | `@with_ai_homes` | 同上 | 简介无店 bot；出处 `ai_bi_jia_notice/15` |
| 3 | `groups/group-geminichatgroup.md` | `@geminichatgroup` | 同上 | 人工 `@AWS_Namei02` + API 联盟链；无店铺 bot 公开窗 |
| 4 | `groups/group-priceaicc.md` | `@priceaicc` | 同上 | 简介无店 bot；公告频道 `@priceaicc2`（不立频道档） |

### 可选 bot 线索（1）

| 文件 | Bot | 说明 |
|------|-----|------|
| `bots/bot-gemini12pro-pixel-helper.md` | `@gemini12pro_bot` | 公益升级 Helper；与已交 `group-gemini12pro` 互证；**非** em-shop |

### 本补录跳过

| 对象 | 原因 |
|------|------|
| `@chatgptplusbuysell` / `@gemini12pro` / `@Geminivip1` | A 节已交（部分已 records）；**不覆盖** |
| `@elitemethodchat` | 种子 + EM 回填；不覆盖 |
| 侧栏三提案（无公开 @） | 留协采；不动 |
| `@fork_bot_channel` / `@api86channel` / `@gamestore86channel` / `@ai_bi_jia_notice` / `@chatgpt_008` | 频道型；优先 Group |
| `@Aiquanzi` / `@TGAI_Group` / `@muskapi` | t.me 可开，名额满；可下批 |

合规：公开预览优先；未发明 username；观察 ≠ 推荐；未发帖/试单/对 bot 交易；未 Telethon/SSH dig/session。
