# PayPal Remote MCP：Agent 可调的官方商务/支付 MCP

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/paypaldev/status/1925212212618252419
- 作者 / 频道：@paypaldev
- 发布时间：2025-05-21 15:28:54 UTC（约 2025-05-21 23:28 CST）

## 要点

- PayPal Developer 宣布远程 **MCP server** 支持 OpenAI LLM，方便用自然语言做 agentic commerce（发票、交易查询等能力以文档工具列表为准）。
- 可动手入口：文档 `developer.paypal.com/ai-tools/mcp-server`；托管端点如 `https://mcp.paypal.com/sse` / HTTP 变体（需 PayPal 凭证；匿名探测常 401）。
- 属未入库的垂直支付/商务 MCP；帖为 OpenAI 接入更新，产品主体是已公开的 Remote MCP（可与后续 Anthropic 支持帖交叉，不另拆除非能力面明显分叉）。

## 落地链接（可选）

- 文档：https://developer.paypal.com/ai-tools/mcp-server
- 相关博文（帖内）：https://developer.paypal.com/community/blog/openai-paypal-mcp/
- 开源/工具包线索：https://github.com/paypal/paypal-mcp-server （paypal/paypal-mcp-server ★12（2026-09-26 gh api））

## 价值判断

- 为什么值得记：官方远程支付 MCP，文档可开，适合 Agent 接结账/发票等商务动作。
- 风险 / 待核实：涉及真实资金与商户数据，务必沙箱先行；效果与工具覆盖面待核实；paypal/paypal-mcp-server ★12（2026-09-26 gh api）。

## 原文摘要（可选）

摘要：官方称 PayPal remote MCP 现已支持 OpenAI LLM，并链到开发者博客说明。

## 与其他条目的关系（可选）

非 Stripe MCP 重复（竞品支付面，可并列）；非 Cloudflare API MCP（本条是 PayPal 产品 MCP，即便早期 Demo Day 曾跑在 Cloudflare 上也不并入 Cloudflare 条）。同账号后续 Anthropic 支持帖（如 status/1925593315719962889）视为同产品增量，不必再开草稿。
