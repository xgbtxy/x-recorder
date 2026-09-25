# Mercury 2.5：Inception 扩散 LLM（高吞吐 + 可调推理）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/_inception_ai/status/2097365772289151417
- 作者 / 频道：@_inception_ai
- 发布时间：2026-09-08 16:45:41 UTC（约 2026-09-09 00:45 CST）

## 要点

- Inception Labs 发布 **Mercury 2.5**：官称当前最强量产扩散语言模型（dLLM），相对 Mercury 2 智力约升 40%，在常见 NVIDIA GPU 上可达约 1,100+ tok/s（吞吐数字 **待核实**）。
- 面向低延迟场景：搜索/RAG 多跳调用、语音 Agent、编码子 Agent 的 compaction / 路由 / 工具检索等。
- 同期预告 **Mercury Voice**、**Mercury Router**（预览）；对外入口为 Inception API、OpenRouter、Baseten。
- 官博还写 260K 上下文、可调推理、并行工具调用与 schema-aligned JSON；价格与折扣以官网为准（**待核实**）。

## 落地链接（可选）

- 模型页：https://inceptionlabs.ai/models
- 官博：https://www.inceptionlabs.ai/blog/introducing-mercury-2-5
- 文档：https://docs.inceptionlabs.ai

## 价值判断

- 为什么值得记：可核官帖 + 可动手 API/托管入口，产品轴是「扩散架构 × 低延迟量产」，非纯榜单营销。
- 风险 / 待核实：开源权重未在本帖承诺；基准对比与 tok/s、价格以实测/账单为准；与传统自回归 frontier 能力边界需实测。

## 原文摘要（可选）

摘要：@_inception_ai 宣布 Mercury 2.5 上线，强调相对 Mercury 2 的智力提升与高吞吐，并给出 API / OpenRouter / Baseten 入口。

## 与其他条目的关系（可选）

勿与已入库自回归大模型发版帖混为同一产品；本条是 **扩散 LLM 服务**。同批若收 Step 5 等 MoE 旗舰，轴心分别是「扩散低延迟」vs「Agentic MoE 旗舰」。
