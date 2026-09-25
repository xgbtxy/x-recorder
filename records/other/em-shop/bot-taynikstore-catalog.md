# [低价·bot·价目] Тайник：公开站 API 多品美元/卢布目录 + TG bot

- 状态：已核（风险观察；观察≠推荐购买）
- 记录日期：2026-09-26
- **平台**：Telegram（价目主出处为公开网页 / 公开 API）
- **Bot（店铺）**：@taynikstore_bot（公开页标题「Тайник」；约 27 069 monthly users）
- **客服号**：@taynik_sup（bot og 写「Поддержка」；另见观察号 `@taynik_support`「нейротайник (поддержка)」）
- **入口**：https://t.me/taynikstore_bot ；公开目录 https://taynik.store/ ；商品 API https://taynik.store/api/products
- **发现群 / 频道**：bot og 挂私密频道 invite `t.me/+E7AI5FpCdItjNzUy`（公开预览不可读，**未入**）；站内另见旁路 VPN 话术 `@prostovpnrubot`
- **发现出处（必填）**：
  - https://taynik.store/（首页横幅可见「Gemini Pro на 18 месяцев за 4.99$」；互链商品 `/product/*`）
  - https://taynik.store/api/products（公开 JSON；字段 `name` / `price_usd` / `price_rub`；2026-09-26 curl 无鉴权可读）
  - 代表性商品页：https://taynik.store/product/15（Gemini Pro + AntiGravity 18 мес）；https://taynik.store/product/26（CapCut Pro 1 месяц）；https://taynik.store/product/20（ChatGPT Plus 1 месяц продление）
  - 辅 bot/客服 og：`@taynikstore_bot`「Магазин цифровых товаров… Cайт: https://taynik.store … Поддержка: @taynik_sup」；`@taynik_sup`「Taynik Support」
- 建议分类：deals / em-shop
- 提案人：小弟·TG

## 公开商品价目（尽量填）

币种：美元（`$`）为主，API 同步给出约合卢布（`₽`）。下表摘自公开 `api/products`（与商品页 id 对应），**非推荐价**；站内 SKU 更多，仅录代表性多品。

| 商品（公开所见） | 标价 | 来源 |
|------------------|------|------|
| Gemini Pro + AntiGravity 18 мес | $4.99 / 421.01 ₽ | [api id=15](https://taynik.store/api/products) · [/product/15](https://taynik.store/product/15)；首页横幅同写 4.99$ |
| Gemini Pro готовый аккаунт 18 мес | $9.99 / 842.86 ₽ | api id=34 · [/product/34](https://taynik.store/product/34) |
| CapCut Pro 1 месяц | $3.49 / 294.45 ₽ | api id=26 · [/product/26](https://taynik.store/product/26) |
| CapCut Pro 6 месяцев | $14.99 / 1264.71 ₽ | api id=6647 · [/product/6647](https://taynik.store/product/6647) |
| ChatGPT Go 1 месяц | $7.99 / 674.12 ₽ | api id=23 · [/product/23](https://taynik.store/product/23) |
| ChatGPT Plus 1 месяц（无 гарантии） | $7.99 / 674.12 ₽ | api id=40 · [/product/40](https://taynik.store/product/40) |
| ChatGPT Plus 1 месяц（продление） | $22.99 / 1939.67 ₽ | api id=20 · [/product/20](https://taynik.store/product/20) |
| Claude Pro 1 месяц（продление） | $26.99 / 2277.15 ₽ | api id=17 · [/product/17](https://taynik.store/product/17) |
| Cursor Pro 1 месяц | $16.90 / 1425.85 ₽ | api id=25 · [/product/25](https://taynik.store/product/25) |
| SuperGrok 1 месяц（продление） | $24.99 / 2108.41 ₽ | api id=6646 · [/product/6646](https://taynik.store/product/6646) |
| Spotify Premium 3 месяца | $4.90 / 413.41 ₽ | api id=29 · [/product/29](https://taynik.store/product/29) |

- 价目完整性：完整公开目录（`/api/products` + `/product/{id}`）；商品页静态 HTML 价位多由前端拉取同 API，**未**对 bot Start/下单交互取材
- 另见公开页（2026-09-26 curl）：
  - `@taynikstore_bot` ↔ 站 taynik.store ↔ `@taynik_sup`
  - 私密新闻频道仅 invite，公开窗无价目帖——**价目以网站/API 为准**

## 要点

- 俄文数字商品自动店：公开站可核多品 AI/创意订阅 `$`/`₽`，Telegram 侧挂店铺 bot + 人工支持。
- 与 elitemethodchat：无直接关系；品类（ChatGPT / Gemini / CapCut / Cursor / Claude）与 EM 风格低价订阅店同型，作「站+API+bot」对照（类 SubscriptionDotCheap / UPE）。
- 同运营：站 taynik.store ↔ bot `@taynikstore_bot` ↔ 客服 `@taynik_sup`（观察 `@taynik_support`）；频道为私密 invite。

## 价值判断

- 为什么值得记：公开 API/站可核 ≥10 行多品标价 + 可核 bot/客服；不依赖买卖群 join gate。
- **风险 / 待核实（强制）**：
  - **第三方低价订阅/成品号/продление**；价目远低于官方，虚假额度、共享席位、盗号池、跑路高度可疑。
  - 同品多档（如 ChatGPT Plus「无 гарантии」$7.99 vs продление $22.99）**勿混用**；「без гарантии」风险更高。
  - 客服仿冒：须核 `@taynik_sup` / bot 互指；私密频道不可公开翻帖。
  - **观察 ≠ 推荐购买**；未向 bot/客服发交易消息、未试单。

## 原文摘要（可选）

taynik.store 首页横幅标「Gemini Pro на 18 месяцев за 4.99$」；公开 `/api/products` 列出 CapCut / ChatGPT / Claude / Cursor / Grok / Spotify 等 `price_usd`/`price_rub`；bot `@taynikstore_bot` og 互链站点与 `@taynik_sup`。
