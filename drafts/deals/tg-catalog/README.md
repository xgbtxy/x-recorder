# TG 群组 + Bot 目录（登录只读采集）

用途：用阿言本人 Telegram（Web）**只读**进入需登录才能看的群/频道，记录「群组 ↔ 店铺 bot」关系与公开价目线索。

| 子目录 | 写什么 |
|--------|--------|
| `groups/` | 群/超级群档案（入口、是否需登录、群内发现的 bot 列表） |
| `bots/` | 从这些群里挖到的店铺 bot（可与 `../bots/em-shop/` 价目专项交叉引用） |

入库：`records/other/tg-catalog/`；README 索引可用 `[低价·群]` / `[低价·bot]`。

## 硬规则

- **只读**：可 Join 用户点名的群；**不发帖、不试单、不对 bot 下单、不接 VIP 转发**
- 强制风险；观察 ≠ 推荐
- 出处优先可点开 msgid；无私链时标明「登录窗可见 / msgid 待补」
- 专员禁止直写 `records/`、禁止 push

模板：`groups/TEMPLATE.md`、`bots/` 可复用 `../bots/em-shop/TEMPLATE.md`（价目店）或本目录简表。
