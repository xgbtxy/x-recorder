# [TG·频道] Zino Shop Updates

- 状态：已核
- 记录日期：2026-10-03
- 提案人：小弟·TG群bot
- 审核：小弟（x-recorder）
- **类型**：频道（公开页为 Preview channel；计数为 subscribers，不是 members）
- **平台**：Telegram
- **频道用户名或链接**：`@zinoofficialupdates` / https://t.me/zinoofficialupdates
- **如何发现**：gemini 交流群。售货 bot `@ZinoShopbot` 要求先加入本频道，以及讨论群 `@zinoshopgroup`。账号已加入、已 Start。讨论群不单独立档（见下）。
- **来源 URL**：https://t.me/s/zinoofficialupdates
- 主题：Gemini 等数字商品的补货频道。简介没有点名 bot；点名在帖子正文。
- 为什么看起来有效：2026-10-03 curl 公开页打得开，不是加入门。最近约 20 帖（/164–/183）没有 `tgme_widget_message_forwarded_from`。/178 与 /183 正文写 `Order from Bot: @ZinoShopbot`。
- 频道内见到的 Bot：`@ZinoShopbot`（https://t.me/zinoofficialupdates/178 、https://t.me/zinoofficialupdates/183）。购买按钮也指向该 bot，下单参数不收录。
- **风险**：买卖频道硬广。`0.59$` / `0.58$` 是补货帖，不是稳定菜单，也不是下单价。授权、是否共享额度、交付和退款都未核实。观察不等于推荐。

> 观察不等于推荐；只读，不发帖、不下单、不试购。

## 公开页实见

- 页标题：`Zino Shop Updates`
- 预览卡 `t.me/zinoofficialupdates` 的 tgme_page_extra：`277 subscribers`（与 `/s/` 计数一致）
- 简介原文没有点名 bot：`Zino Shop Channel` / Premium digital products, latest offers & stock updates
- 按钮：View in Telegram / Preview channel
- 采集：2026-10-03 curl `https://t.me/s/zinoofficialupdates` 与预览卡 `https://t.me/zinoofficialupdates`

## 价目帖（不是转发；只把带美元符号且点名 bot 的句子当公开价）

客户端在约 02:20 看到的阶梯价，对得上 https://t.me/zinoofficialupdates/183（`2026-10-02T18:20:48+00:00`，即 2026-10-03 02:20 PT）。原文是后缀美元符号，不是 `$0.59`。

- https://t.me/zinoofficialupdates/183（`2026-10-02T18:20:48+00:00`，即 2026-10-03 02:20 PT；不是转发）
  - 商品行：`Gemini AI Pro + 5TB 18M`
  - 原文：`Buy 1-19 for  0.59$`
  - 原文：`Buy 20+ for 0.58$`
  - 结尾：`Order from Bot: @ZinoShopbot`
- https://t.me/zinoofficialupdates/178（`2026-10-02T10:22:18+00:00`，即 2026-10-02 18:22 PT；不是转发）：同一套 `0.59$` / `0.58$`，同样点名 `@ZinoShopbot`。这是前一天的帖，不是 10 月 3 日的新价。

不记为今天的美元现价：

- /164、/165（2026-10-01）写 `Price: 0.58`；/169、/171、/172、/174–/177、/180、/181 写 `Price: 0.59`。都没有美元符号，正文也没有 `@ZinoShopbot`。其中 /180（2026-10-03 00:46 PT）、/181（2026-10-03 02:15 PT）和 /183 只差几分钟到几小时，但不能把无 `$` 的 `Price: 0.59` 并进 /183 那句。
- /167 `Price: 0.32`（Duolingo）、/179 `Price: 1.59`（CapCut）、/182 `Price: 0.99`（Amazon Prime）同样没有美元符号，正文没有点名 bot。
- /168（2026-10-02 11:32 PT）是 Gemini 激活说明，没有价格，也没有点名 bot。不收录任何激活链接。

无稳定菜单，不立 em-shop。仓库里没有已有店档，店档：`records/other/tg-ai-sources/bots/bot-zinoshopbot.md`。不另建第二份。

## 关联

| 对象 | 出处 | 价目 | 备注 |
|------|------|------|------|
| bot `@ZinoShopbot` | 非转发帖 /178、/183 正文 | `0.59$` / `0.58$`，见上 | 启动页无价；不立 em-shop |
| `@zinoshopgroup` | 该 bot 的另一条加入门槛 | 无 | `t.me/s/zinoshopgroup` 是加入门，没有帖。预览卡 `191 members, 33 online`。简介没有点名 bot，不单独立档 |

## 和客户端说法不一致

- 订阅数 277 对得上。讨论群客户端说 188 人；本次预览卡是 191 members。
- 阶梯数字 0.59 / 0.58 对得上 /183，但公开页写成 `0.59$`、`0.58$`，不是 `$0.59`、`$0.58`。
- 同页大量 `Price: 0.59` 没有美元符号，不当成同一条现价。

> 观察不等于推荐；只读，不发帖、不下单、不试购。
