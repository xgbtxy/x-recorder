# OpenCodeReview：阿里开源混合架构 AI 代码审查 CLI（ocr）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/swarogan/status/2103614990590623929
- 作者 / 频道：@swarogan（社区转、非官宣）
- 发布时间：2026-09-25 22:37:51 UTC（约 2026-09-26 06:37 CST）

## 要点

- 社区试用帖指向阿里开源 **Open Code Review（OCR）**：确定性工程（选文件、打包、规则匹配、定位/反思）× LLM Agent 做深度 diff/全仓审查，强调行级评论与少误报。
- 可动手入口：`npm install -g @alibaba-group/open-code-review` 后 `ocr review` / `ocr scan` / `ocr delegate`；支持 Claude Code / Codex / Cursor 等插件与 Skill；官网含文档与 AACR-Bench。npm 版本抓取时约 1.12.x，**待核实**。
- GitHub `alibaba/open-code-review` 星数抓取时约 4.1 万（**待核实**）；自称内部两年、万级开发者验证（效果数字 **待核实**）。

## 落地链接（可选）

- 仓库：https://github.com/alibaba/open-code-review
- 官网/文档：https://open-codereview.ai
- npm：https://www.npmjs.com/package/@alibaba-group/open-code-review

## 价值判断

- 为什么值得记：可核 X 帖 + 超高星仓 + 可装 CLI；补「专用代码审查 harness」轴，而非通用 coding agent。
- 风险 / 待核实：来源为社区试用印象帖，非阿里官号；公开独立评测对召回/精度有争议，以官方基准与自测为准；需自备兼容 OpenAI/Anthropic 的模型端点（或用 Delegation Mode）。

## 原文摘要（可选）

摘要：@swarogan 称正在试用 Alibaba OpenCodeReview，关注大仓表现、真缺陷率、误报以及相对 Claude Code/Codex 的对比。

## 与其他条目的关系（可选）

社区转介；与 Claude Code / Codex 通用 Agent 不同：本条是 **审查专用确定性 harness + 可选委托宿主模型**。勿与已入库 ant apply / plugin-eval 等 Anthropic 编码插件混为同一项。
