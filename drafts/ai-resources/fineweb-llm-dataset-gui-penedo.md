# FineWeb：大规模高质量 Web 预训练数据集（可下载）

- 状态：候选
- 分类：ai-resources
- 记录日期：2026-09-25
- **来源 X（必填）**：https://x.com/gui_penedo/status/1781953413938557276
- 作者：@gui_penedo
- 推文时间：2024-04-21 07:49:35 UTC（约 2024-04-21 15:49 CST）

## 要点

- Hugging Face 预训练数据方向作者官宣 🍷 FineWeb：对 2013–2024 Common Crawl 过滤与去重后的高质量网页文本语料。
- 帖称约 15T tokens，并称在其上训练的模型优于 RefinedWeb、C4、Dolma、The Pile、SlimPajama 等（对比数字「待核实」）。
- 可动手：Hugging Face 数据集页直接 `load_dataset` / 下载；处理管线见 `huggingface/datatrove`。后续还有多语种 FineWeb2（另页，本条以本 status 为准）。

## 落地链接（可选）

- 数据集：https://huggingface.co/datasets/HuggingFaceFW/fineweb
- 处理库示例：https://github.com/huggingface/datatrove
- 多语种续作（可选参见）：https://huggingface.co/datasets/HuggingFaceFW/fineweb-2

## 价值判断

- 为什么值得记：对应「LLM dataset github」类需求——可下载、可复现过滤管线的主流开源预训练语料入口。
- 风险 / 待核实：原帖未直接贴 HF URL（落地链为同作者/同项目公开页）；token 量与 benchmark 以数据集卡与论文为准；网页语料仍可能含敏感/NSFW 残留。

## 原文摘要（可选）

摘要：发布 FineWeb，15T tokens 高质量网页数据，过滤去重 2013–2024 Common Crawl，并声称训练效果优于若干公开语料。
