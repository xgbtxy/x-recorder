# [TG·频道] MashaGPT

- 状态：驳回
- 记录日期：2026-10-03
- **类型**：频道（公开页计数为 subscribers）
- **平台**：Telegram
- **显示名**：MashaGPT
- **用户名**：`@mashagpt`
- **入口 URL**：https://t.me/mashagpt
- **来源 URL**：https://t.me/s/mashagpt
- **发现方式**：公开检索「mashagpt telegram 990」后，2026-10-03 curl 公开预览核对（未登录、未加入、未发帖、未下单）
- **售卖内容（该页自称）**：俄语聚合器，卖自家对 ChatGPT、Claude、Gemini、Grok 的访问。简介写站点 mashagpt.ru，并点名 bot `@mashaofficial_bot`
- **公开价格（原文，卖方自己的帖，不是转发）**：
  - https://t.me/mashagpt/1191（2026-02-27 14:26 上海）：`купили подписку за 990₽`
  - https://t.me/mashagpt/1193（2026-03-16 16:40 上海）：`Снизили цену на пакет 100 млн токенов` / `Теперь 3 960 ₽ вместо 4 990 ₽`。同帖还有 `Новая линейка тарифов` `Base / Ultra / Pro`，以及 `Тариф Ultra` `50 млн токенов в рамках подписки вместо 40 млн`。帖里没有把 990₽ 再写成新菜单
  - https://t.me/mashagpt/1205（2026-05-18 17:38 上海）没有新的卢布数字：`ChatGPT 5.5, Claude Sonnet 4.6, Claude Opus 4.7 и Gemini 3.1 Pro — в 2 раза дешевле для всех тарифов и без изменения лимитов. Платите столько же — получаете в 2 раза больше сообщений.` 这句是「同样的钱、两倍消息」，不能改写成新的卢布现价
- **来源消息链接**：https://t.me/mashagpt/1193 ；交叉 https://t.me/mashagpt/1191 、https://t.me/mashagpt/1205
- **为什么算俄区**：简介和帖子是俄语；价用 ₽；简介自称在俄罗斯提供这些模型（`№1 в России` 是该页说法）
- **为什么算卢布价 / 低于官方**：价就是卢布，不是美元。990₽ 是卖方在帖里说出的订阅价；3 960 ₽ 是卖方自己的 1 亿 token 包。官方 ChatGPT Plus 是美元月费，这里是卢布计价的聚合器额度，不是官方收银台
- 建议分类：other/tg-ai-sources（类型：俄罗斯卖家自己的多模型聚合频道）
- 提案人：小弟·俄区店

> 驳回：价目停在 2–3 月，5 月帖没有新的卢布数字，不能当 10 月现价。不建 bot 档。

## 群内见到的 Bot

- `@mashaofficial_bot`：写在频道简介（`t.me/mashagpt` 的 og:description：`Бот - @mashaofficial_bot`）。启动页 https://t.me/mashaofficial_bot 本次 curl 为 200，og:title `Masha AI`，og:description 有 `8 топовых нейросетей в одном чате`，**启动页没有价目**。价只在频道帖。未点 Start

## 公开页实见（2026-10-03 curl）

- https://t.me/s/mashagpt 与 https://t.me/mashagpt 均为 HTTP 200
- og:title：`MashaGPT`
- og:description（view 页原文，制表符为空格转写）：`✨ Нейросеть - mashagpt.ru` / `Сервис для работы с нейросетями ChatGPT, Claude, Gemini, Grok - №1 в России.` / `Бот - @mashaofficial_bot` / `По вопросам сотрудничества - @lolux` / `Регистрация канала - 4778340851`
- tgme_page_extra：`144 889 subscribers`（2026-10-03 复核 view 页；稿里曾写 144 908，人数会变）
- 帖流有 `tgme_widget_message`。上列价目帖正文没有 `message_forwarded`，记为卖方自己的帖
- 未加入、未发帖、未下单、未 /start

## 风险 / 待核实（强制）

- 非官方聚合。可能是额度转售、共享或事后改价。990₽ 是 2026-02-27 帖里的说法，3 960 ₽ 是 2026-03-16 的 token 包，都不是 2026-10-03 的完整菜单
- 2026-04-17 帖 https://t.me/mashagpt/1199 把 Claude 写成与官方 API 同价（`$3` / `$15`、`$5` / `$25` 每百万 token）。那是美元 API 口径，不是低于官方，本条不把它当低价
- 观察 ≠ 推荐。未发消息、未下单、未试购
