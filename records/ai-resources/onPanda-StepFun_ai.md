# onPanda：阶跃开源的 Token 级对齐标注与模型检视工具

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/StepFun_ai/status/2102454115473510643
- 作者 / 频道：@StepFun_ai
- 发布时间：2026-09-22 17:44:57 UTC（约 2026-09-23 01:44 CST）

## 要点

- StepFun 开源内部工具 **onPanda**：以「定位首个不当 token → 选候选/手改 → 让模型续写」做 on-policy 对齐数据标注，并支持 Agent 轨迹（图/音/视频）标注。
- 同工具可做模型检视：看 token 概率与 top-k、逐步干预解码，浏览器内探索 SVG / Web / Agent 任务。
- 官帖给出 Web 试用与论文；代码仓 `on-panda/on-panda`（星数 **待核实**）。宣称标注耗时中位数降约 52% 等效果数字 **待核实**。

## 落地链接（可选）

- 试用：https://onpanda.diyer22.com
- 仓库：https://github.com/on-panda/on-panda
- 论文：https://huggingface.co/papers/2609.24983

## 价值判断

- 为什么值得记：可核官帖 + GitHub/Web 可动手，补齐「数据标注 / 检视」工具轴，非纯模型营销。
- 风险 / 待核实：试用域名挂在个人/项目站（diyer22），生产可用性与持续维护待观察；效果百分比待复现。

## 原文摘要（可选）

摘要：@StepFun_ai 宣布开源 onPanda，强调 token 级纠错标注与浏览器内模型检视，并给出试用与论文链接。

## 与其他条目的关系（可选）

同厂商 **Step 5**（模型）与 **Step Code**（Coding Agent）产品轴不同；本条是 **对齐数据标注 + 检视工具**。勿与泛 MCP/Skill 安装包混淆。
