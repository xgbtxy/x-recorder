# Context7 Search：面向 coding agent 的官方文档 grounding API

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-25
- **平台**：X
- **来源（必填）**：https://x.com/Context7AI/status/2102508908095123767
- 作者 / 频道：@Context7AI（Upstash）
- 发布时间：2026-09-22 21:22:41 UTC（约 2026-09-23 05:22 CST）

## 要点

- 官方介绍 **Context7 Search**：一次 GET 按问题检索「库作者维护的官方文档片段」，用于给 coding agent grounding（对比泛网页搜索）。
- 可动手试：`curl -G 'https://context7.com/api/v3/search' --data-urlencode 'query=…'`（无 key 有 IP 限流 demo）；正式用需 API key。亦有既有 MCP 包 `@upstash/context7-mcp`。
- 博客给出 Vercel AI SDK `tool` 示例：把 Search 挂成 agent 工具再写答案。

## 落地链接（可选）

- 发版博客：https://upstash.com/blog/context7-search
- 仓库：https://github.com/upstash/context7
- Search 试玩：https://context7.com/api/v3/search?query=what+is+nextjs

## 价值判断

- 为什么值得记：RAG/文档检索可动手入口，偏官方 docs 而非网页抓取；MCP+HTTP 双路径。
- 风险 / 待核实：星数/覆盖库数量待核实；免费额度与付费墙见官网；「扫描注入/恶意」为宣称，需本地验证。

## 原文摘要（可选）

摘要：Context7 宣布 Search API——一次请求拿官方文档 snippet，强调相对网页搜索更安全、省 token。
