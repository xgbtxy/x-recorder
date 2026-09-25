# 批次 J 摘要 · BUYING & SELLING WORLDWIDE 低价 bot 风险观察（2026-09-25）

提案人：小弟·TG  
目录：`drafts/deals/bots/`  
状态：已过审入库（2026-09-26；records/other/）  
原始扫描：`_scan-raw-2026-09-25.txt`  
核验方式：仅使用扫描文件与公开 Telegram bot 页 WebFetch；未重 SSH、未向 bot 发消息、未交易。

## 本批新草稿（3 条）

| # | 文件 | Bot | 风险观察要点 | 主出处 |
|---|------|-----|--------------|--------|
| 1 | `bot-vouchersshop-flash-sale.md` | `@VouchersShopBot` | reseller 闪购与低价数字订阅；公开页约 14,106 monthly users，但月活不是背书 | `t.me/chatgptplusbuysell/1218660` |
| 2 | `bot-prime-gadget-store.md` | `@Prime_Gadget_Store_bot` | ChatGPT Plus 售卖；公开页展示 Avenzo Digital，且明确 “Refund policy not available” | `t.me/chatgptplusbuysell/1218635` |
| 3 | `bot-excaliburtech-digital-activation.md` | `@ExcaliburTechBot` | Duolingo 12M $0.40 等异常低价数字激活；公开页自述自动交付/客服，授权仍未核实 | `t.me/chatgptplusbuysell/1218661` |

## 公开页核验

| Bot | 公开页结果 |
|-----|------------|
| `@VouchersShopBot` | 页面存在；显示 “Vouchers Shop Bot”，约 14,106 monthly users |
| `@Prime_Gadget_Store_bot` | 页面存在；显示 “Avenzo Digital” 与 “Refund policy not available” |
| `@ExcaliburTechBot` | 页面存在；显示 “Excalibur Shop Bot”，自称有明码标价、自动交付与客服 |

## 选择与排除

- 从扫描中优先选择完整用户名、明确以 `bot` 结尾、且带 `chatgptplusbuysell` 消息号的店铺 bot。
- 未重复立稿任务已指定跳过的 bot；未采用 `hopbot`、`aliburTechBot`、`ubShop_bot` 等正则碎片/疑似误切结果。
- 其他完整候选已留作后续去重，不在本批扩写，以免同质店铺过剩。

## 风险口径

三条均为“观察 ≠ 推荐”，不构成购买、付款、转发或可信背书；商品授权、交付、退款、有效期与运营主体均需另行核实。只写草稿，不写 `records/`，不 git push。
