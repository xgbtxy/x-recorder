# 批次 G 摘要 · TG bots 只读深扫（2026-09-25）

提案人：小弟·TG  
目录：`drafts/deals/bots/`  
状态：候选交审（未入库）  
机器：陈陈 → SSH 43.173.78.6 只读 Telethon  
原始扫描：`_scan-raw-2026-09-25.txt`  
远程临时脚本：已删除 `/tmp/scan_bots_readonly.py`

## 扫描覆盖

| 优先级 | 群标题 | 结果 |
|--------|--------|------|
| PRIORITY | 鲸鲨源头交流群-主 | 近窗仅 `@hackerstri_bot`（lobehub 登录求助提及；公开页「hacker」，非明确店铺 → 本批不立稿） |
| PRIORITY | Claude 资源/技术 | 近 120 条 **无 bot** |
| PRIORITY | gemini 交流群 | 近 120 条 **无 bot** |
| SECONDARY | BUYING & SELLING WORLDWIDE | 大量订阅/闪购 shop bot（本批主货源） |
| SECONDARY | EM Chat Group | `@EliteMethodsStoreBot`、`@scammersdeathbot`（escrow/店；按「bots only, no trading」仅记用户名，本批不立店稿） |
| VIP | VIP Methods | **未加入**（MISSING） |
| SKIP | Capcut | 未扫 |

## 本批新草稿（3 条）

| # | 文件 | Bot | 一句话 | 出处 |
|---|------|-----|--------|------|
| 1 | `bot-warzoneshop-gemini.md` | `@WarzoneShopBot` | Warzone Shop，Gemini Pro 18m 特价，~2.4 万月活 | `t.me/chatgptplusbuysell/1218659` |
| 2 | `bot-gemini-shop-robot.md` | `@Gemini_shop_robot` | Gemini Shop 闪购，~1.6 万月活 + support | `t.me/chatgptplusbuysell/1218652` |
| 3 | `bot-aisubshop-ai-subs.md` | `@AiSubShop_bot` | AIShop 多产品订阅 + 评价频道 | `t.me/chatgptplusbuysell/1218638` |

公开页均已 WebFetch 核存在（Launch Bot 页）。

## 已跳过 / 近失

| 候选 | 原因 |
|------|------|
| `@BuyYourPremiumBot` `@faka` `@gptnocard_bot` `@lowpriceking_bot` `@pikabaobot` `@afaka_bot` `@umfakaBot` | 任务指定已录 SKIP |
| `@hackerstri_bot` | 优先群命中但非店铺语义 |
| `@EliteMethodsStoreBot` / `@scammersdeathbot` | EM 仅 bots、不立交易稿 |
| `@VouchersShopBot` `@AithSubscriptions_bot` `@NyStoreOfficialBot` `@TrustedShopingbot` 等 | 同质店铺过剩；本批已选 3 个最贴 Gemini/AI 订阅线 |
| 正则误报 `@hopbot` `@aliburTechBot` `@ni_shop_robot` 等 | 子串误切，已丢弃 |
| VIP Methods | 会话未加入该群 |

## 合规备忘

- 只读：未发送/加入/退出/转发/编辑/广播。
- 未 cat/打印 session、api_hash、订阅者。
- 未 git push；未写 `records/`。

## 老大审结（2026-09-25）

3 条通过（风险观察）。VIP Methods 标题用模糊匹配只读捞；未加入则勿擅自 join。
