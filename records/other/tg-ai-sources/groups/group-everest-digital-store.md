# [TG·频道] Everest Digital Store

- 状态：已核
- 记录日期：2026-10-03
- 提案人：小弟·TG群bot
- 审核：小弟（x-recorder）
- **类型**：频道（公开页为 Preview channel；计数为 subscribers，不是 members）
- **平台**：Telegram
- **频道用户名或链接**：`@everest_digital_store` / https://t.me/everest_digital_store
- **如何发现**：gemini 交流群。售货 bot `@everest_digital_store_bot` 要求先加入本频道，以及讨论群 `@googleaipro_gemini`。账号已加入、已 Start。讨论群不单独立档（见下）。
- **来源 URL**：https://t.me/s/everest_digital_store
- 主题：Gemini、ChatGPT 等数字商品补货频道。简介原文点名 bot。
- 为什么看起来有效：2026-10-03 curl 公开页打得开，不是加入门。最近约 20 帖（约 /1246–/1274，中间有缺号）没有 `tgme_widget_message_forwarded_from`。简介写 `Bot :- @Everest_Digital_store_bot`。多数补货帖的按钮指向同一个 bot，下单参数不收录。
- 频道内见到的 Bot：`@Everest_Digital_store_bot`（简介原文；与 https://t.me/everest_digital_store_bot 是同一个启动页）。另有客服 `@everest_digital_store_support`（/1269），不是售货 bot，不另建档。
- **风险**：买卖频道硬广。公开页上的 Gemini 数字在 `$0.65` 和 `0.70 USD` 之间来回出现，都不是客户端那句「新价 $0.70、旧价 $0.85」。授权、是否共享额度、交付和退款都未核实。观察不等于推荐。

> 观察不等于推荐；只读，不发帖、不下单、不试购。

## 公开页实见

- 页标题：`Everest Digital Store channel`
- 预览卡 `t.me/everest_digital_store` 的 tgme_page_extra：`2 849 subscribers`（`/s/` 计数为 `2.85K subscribers`）
- 简介原文点名 bot：`Get all digitals product at cheapest price` / `Bot :- @Everest_Digital_store_bot` / `Support:- @Everest_Digital_store_support` / `Channel :- https://t.me/everest_digital_store`
- 按钮：View in Telegram / Preview channel
- 采集：2026-10-03 curl `https://t.me/s/everest_digital_store` 与预览卡 `https://t.me/everest_digital_store`
- 这批评到的最新帖是 https://t.me/everest_digital_store/1274（`2026-10-02T15:38:44+00:00`，即 2026-10-02 23:38 PT）。公开预览里没有 2026-10-03 的帖。

## 价目帖（不是转发）

客户端说约 14:46 有一句点名 bot 的 `New Price: $0.70 USD`（旧价 `$0.85`）。这次抓到的 HTML 里 `0.85` 出现 0 次，也没有 `New Price: $0.70`。不记那句。

带 `$`、并且按钮指向该 bot 的句子（正文没有再写 `@`，挂名靠简介和按钮）：

- https://t.me/everest_digital_store/1265（`2026-10-02T07:35:54+00:00`，即 2026-10-02 15:35 PT；不是转发）
  - `Gemini 18 months link`
  - 原文：`New Price: $0.65 USD`
  - 原文：`Old Price: $0.70 USD`
- https://t.me/everest_digital_store/1246（`2026-09-30T23:35:53+00:00`，即 2026-10-01 07:35 PT；不是转发）
  - `CHATGPT PLUS K12 EDU — 2 YEARS`
  - 原文：`New Price: $5.90 USD`，`Old Price: $6.90 USD`
- https://t.me/everest_digital_store/1267（`2026-10-02T08:24:09+00:00`，即 2026-10-02 16:24 PT；不是转发）
  - `Quillbot 1 month code`（不是 AI 订阅菜单）
  - 原文：`Updated Price: $2.50 USD`，`Previous Price: $2.00 USD`

Gemini 后面又改口，而且没有美元符号，不能并成上面的 `$0.65` 现价，更不能写成今天的 `$0.70`：

- https://t.me/everest_digital_store/1271（`2026-10-02T13:53:44+00:00`，即 2026-10-02 21:53 PT）：`Unit Price: 0.65 USD`，库存 52。按钮指向该 bot。没有 `$`。
- https://t.me/everest_digital_store/1274（`2026-10-02T15:38:44+00:00`，即 2026-10-02 23:38 PT）：`Unit Price: 0.70 USD`，库存 93。这是本批最新的 Gemini 行。写法是 `0.70 USD`，不是 `New Price: $0.70 USD`，也没有旧价 `$0.85`。
- 更早的 `Unit Price: 0.70 USD` 还有 /1255（2026-10-01 18:27 PT）、/1260（2026-10-02 08:32 PT）。限时闪购 /1258 写 `Sale Price: 0.60 USD`（2026-10-01 22:52 PT），/1261 写 `Sale Price: 0.65 USD`（2026-10-02 10:02 PT）。都没有 `$`。

不记成该 bot 的价：https://t.me/everest_digital_store/1262（`2026-10-02T04:37:16+00:00`，即 2026-10-02 12:37 PT）正文有 `Price: $12.00`（Veo 3 Ultra），但这帖没有指向 bot 的按钮，也没有 `@` 该 bot。不收录帖里的网盘链接。

无稳定菜单，不立 em-shop。仓库里没有已有店档，店档：`records/other/tg-ai-sources/bots/bot-everest-digital-store-bot.md`。不另建第二份。

## 关联

| 对象 | 出处 | 价目 | 备注 |
|------|------|------|------|
| bot `@Everest_Digital_store_bot` | 简介原文；补货帖按钮 | 见上。没有「新价 $0.70 / 旧价 $0.85」 | 启动页无价；不另建第二份店档 |
| `@everest_digital_store_support` | 简介；帖 /1269 | 无 | 客服，不另建档 |
| `@googleaipro_gemini` | 该 bot 的另一条加入门槛；预览卡标题 Everest Digital Chat Group | 无 | `t.me/s/googleaipro_gemini` 是加入门，没有帖。预览卡 `2 776 members, 280 online`。简介没有点名 bot，不单独立档 |

## 和客户端说法不一致

- 订阅数：客户端 2,848；本次预览卡 `2 849 subscribers`。
- 讨论群：客户端 2,775；本次预览卡 `2 776 members`。
- 约 14:46 的 `New Price: $0.70 USD` / 旧价 `$0.85` 不在这次公开预览里。时间接近的 /1264 是 2026-10-02 14:42 PT，商品是 ChatGPT Plus K12，`Unit Price: 5.99 USD`，不是那句。
- 公开页里带 `$` 的 Gemini 新价是 /1265 的 `$0.65`（旧价 `$0.70`），时间是 2026-10-02 15:35 PT，而且随后又出现无 `$` 的 `0.65 USD` 和 `0.70 USD`。

> 观察不等于推荐；只读，不发帖、不下单、不试购。
