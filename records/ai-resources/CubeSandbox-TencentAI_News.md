# CubeSandbox：腾讯云开源 AI Agent 沙箱（毫秒级启动 / 快照回滚 / E2B 兼容 API）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/TencentAI_News/status/2099445261185765528
- 作者 / 频道：@TencentAI_News
- 发布时间：2026-09-14 10:28:50 UTC（约 2026-09-14 18:28 CST）

## 要点

- 腾讯云开源 **CubeSandbox**：面向 AI Agent 的即时、可并发、硬件级隔离轻量沙箱服务；文档称 E2B 兼容 API、高密度部署。
- 开源后社区反馈驱动的更新（同帖）：跨节点 pause/resume、CubeMaster 多副本去单点、LLM 代理超时从 60s 提到 2h 等。
- 可动手：GitHub 仓 + PyPI `cubesandbox`；Apache-2.0。星数约 12.7k（2026-09-26 抽查，**待核实**）。
- 同账号另有产品说明帖（如回滚/隔离叙事），本条以开源跟进帖为出处。

## 落地链接（可选）

- 仓库：https://github.com/TencentCloud/CubeSandbox

## 价值判断

- 为什么值得记：可核官帖 + 开源仓/PyPI，补「Agent 执行隔离与快照回滚」基础设施入口，非纯云营销页。
- 风险 / 待核实：自建集群运维成本；pause/resume 内存占用官帖亦承认待优化；与商业 E2B / 厂商沙箱的 API 兼容面待实测。

## 原文摘要（可选）

摘要：@TencentAI_News 汇报 CubeSandbox 开源后按社区反馈改进跨节点暂停恢复与高可用，并链到 GitHub。

## 与其他条目的关系（可选）

相对已入库 **Azure Container Apps Sandboxes** 等：本条是 **可自建开源沙箱运行时**。与同批 **BrowserSkill** 同属腾讯 AI 工具线但产品轴不同（沙箱隔离 vs 本机浏览器桥）。
