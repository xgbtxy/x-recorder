# x-recorder · X 推文记录师

从 X（Twitter）推文里摘有价值的关键点，做成可检索的记录库。

**硬规则：每一条记录必须有可点开的出处链接（优先 X status；已批 TG 频道可用消息链接并标明平台）。没有可核对出处的不入库。**

和 `project-collect` 的分工：

| | x-recorder | project-collect |
|--|------------|-----------------|
| 粒度 | 一条推文 / 一条线索 | 一个项目条目 |
| 必填 | X 链接 | 仓库或项目页 |
| 内容 | VPN、网安工具、AI 资源等「发现」 | 经整理的项目短档 |

## 分类目录

- [`records/security-tools/`](./records/security-tools/) — 网络安全 / 逆向 / 攻防工具
- [`records/vpn-proxy/`](./records/vpn-proxy/) — VPN / 代理 / 网络访问相关（优先：网速向「机场/订阅」公开测速与评测；开源客户端仍收；不写绕过教程）
- [`records/ai-resources/`](./records/ai-resources/) — 模型、Agent、提示、数据集、AI 工具
- [`records/other/`](./records/other/) — 暂不好归类但有价值的（含低价卡网/优惠渠道线索，标题可标 `[低价]`）
- 低价线草稿目录：[`drafts/deals/`](./drafts/deals/)

新条目用 [`templates/record.md`](./templates/record.md)。

运维与审推纪律见 [`docs/OPS.md`](./docs/OPS.md)（草稿目录、专员边界、审计清单、建小弟标准）。

## 索引

| 标题 | 分类 | 状态 | 来源 X |
|------|------|------|--------|
| ASC 介绍帖（Agent 反编译 / Arsenal 叙事） | security-tools | 已核（主张未全证） | https://x.com/MGAldys4/status/2098541143474749913 |
| JADX-AI-MCP | security-tools | 已核 | https://x.com/zinja_coder/status/2085396884273914160 |
| BurpNinja | security-tools | 已核 | https://x.com/altafpasha_h/status/2093771074391732639 |
| Claude+MCP×JADX/IDA 案例 | security-tools | 已核 | https://x.com/taidh_/status/2072863860625989984 |
| apktool-mcp-server | security-tools | 已核 | https://x.com/zinja_coder/status/1923636620420350411 |
| Beerus Framework（Android） | security-tools | 已核 | https://x.com/ptdbugs/status/2095187404860616908 |
| frida-ssl-bypass | security-tools | 已核 | https://x.com/Jayson_security/status/2101324384786845903 |
| Perenio App Analysis | security-tools | 已核 | https://x.com/ereksonas/status/2102823621412413778 |
| ASC 实战叙事（作者自述 root） | security-tools | 已核（主张未全证） | https://x.com/MGAldys4/status/2100144298029449331 |
| reverse-skill 推荐 | security-tools / ai-resources | 已核 | https://x.com/bigaiguy/status/2102329454173602054 |
| ToCode · Agent 逆向导出源码 | ai-resources（兼 security-tools） | 已核 | https://x.com/buzz3r_/status/2063486884806832200 |
| T3MP3ST · Agent 红队 harness | security-tools（兼 ai-resources） | 已核 | https://x.com/elder_plinius/status/2073579120135664102 |
| Maigret 0.6.6（TG） | security-tools | 已核 | https://t.me/offensiveosint/193 |
| Awesome-LLM4Cybersecurity（TG） | ai-resources | 已核 | https://t.me/tsecrecord/1557 |
| NLA on open models：Anthropic × Neuronped | ai-resources | 已核 | https://x.com/AnthropicAI/status/2052435460220211397 |
| skills CLI：跨 Agent 安装 Skill 包（类 npm） | ai-resources | 已核 | https://x.com/rauchg/status/2012345679721771474 |
| Cursor `/orchestrate`：递归派生多 Agent 的官方 Sk | ai-resources | 已核 | https://x.com/cursor_ai/status/2052432778743210127 |
| Cursor Agent Skills：SKILL.md 扩展 Agent 能力 | ai-resources | 已核 | https://x.com/cursor_ai/status/2014753596223770841 |
| HyperFrames：可 `npx skills add` 的 HTML→MP | ai-resources | 已核 | https://x.com/HeyGen/status/2044827454460871072 |
| sing-box 1.14.0（TG） | vpn-proxy | 已核 | https://t.me/yapnc/495 |
| Hiddify：多平台开源代理客户端（App Store / GPLv3 宣称） | vpn-proxy | 已核 | https://x.com/hiddify_com/status/1852014812051406910 |
| Hiddify 1.5.2：官方发版帖（含 GitHub Releases 入口） | vpn-proxy | 已核 | https://x.com/hiddify_com/status/1810758424881496232 |
| Clash Verge Rev：Tauri 桌面代理 GUI（GitHub 热榜转发） | vpn-proxy | 已核 | https://x.com/kodemarket01/status/2062195599626101043 |
| AmneziaVPN 5.0.3：开源 VPN 客户端版本更新 | vpn-proxy | 已核 | https://x.com/AmneziaVPN/status/2102447556433186967 |
| 3m-ui：Mihomo 服务端 Web 管理面板 | vpn-proxy | 已核 | https://x.com/Flowers_hurt/status/2102965119017976096 |
| 七喜机场 · 海豚快速评测（TG） | vpn-proxy | 已核 | https://t.me/haitun_channel/2469 |
| AWS 海外中转异常观察（TG） | vpn-proxy | 已核 | https://t.me/jichangtj/1203 |
| 比特冲刺 DASHBIT · SpeedCentre（TG） | vpn-proxy | 已核 | https://t.me/speedcentre/14115 |
| Free Proxy Airport 自动测速（X） | vpn-proxy | 已核 | https://x.com/tyiiopple/status/2100729531850227787 |
| @jichangtj 2026 评测/测速索引（X） | vpn-proxy | 已核 | https://x.com/jichangtj/status/2076920947072975302 |
| Clash「经典回归」辨伪（jichangtj→Fndroid） | vpn-proxy | 已核 | https://x.com/jichangtj/status/2098964330473836682 |


> 注：硬规则优先 X 链接；已批 TG 频道来源可用 Telegram 消息链接入库，并在条目中标明平台。

## 跟盯清单

- Telegram：[`watchlists/tg-channels.md`](./watchlists/tg-channels.md)（已审公开频道；不擅自发帖）

## 工作方式（给人 / 给助手）

1. 在 X 搜关键词或跟账号，打开具体帖子。
2. 判断是否有价值（可复用工具、可跟进资源、可验证方法）。
3. 复制帖子链接 → 按模板新建 `records/<分类>/<短名>.md`。
4. 更新本 README 索引表。
5. 夸大、未证实的声称写进「风险 / 待核实」，不删帖源。

## 不收什么

- 无 X 链接的二手转述
- 纯营销无实质入口
- 违法操作教程式细节（只记公开工具名与官方入口）
