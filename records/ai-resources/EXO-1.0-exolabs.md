# EXO 1.0：消费级硬件组本地推理集群（Apache 2.0）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/exolabs/status/2001817749744476256
- 作者 / 频道：@exolabs
- 发布时间：2025-12-19 00:51:58 UTC（约 2025-12-19 08:51 CST）

## 要点

- EXO Labs 宣布 **EXO 1.0** 开源（宣传 **Apache 2.0**），用于把多台消费级机器（示例：Mac Studio）组成本地推理集群。
- 帖内演示经 Thunderbolt RDMA + MLX 张量并行跑大模型；具体吞吐数字与硬件组合待核实。
- 可动手：GitHub 仓库安装/组网；面向本地分布式推理而非云 API。

## 落地链接（可选）

- 公告帖：https://x.com/exolabs/status/2001817749744476256
- 仓库：https://github.com/exo-explore/exo
- 官网：https://exolabs.net

## 价值判断

- 为什么值得记：本地多机推理编排缺口；官方账号可核、Apache 开源、有仓库可动手。
- 风险 / 待核实：tok/s、扩展比、网络/硬件门槛与稳定性待核实；exo-explore/exo ★47642（2026-09-26 gh api）；tok/s、扩展比与稳定性待核实；演示模型非本条主体。

## 原文摘要（可选）

摘要：exolabs 展示 Mac Studio 集群跑大模型，并称 EXO 1.0 已 Apache 2.0 开源。

## 与其他条目的关系（可选）

条目主体是 EXO 运行时，不是已入库的 Kimi K2 Thinking 模型卡；勿因演示同款模型再开扩散条。
