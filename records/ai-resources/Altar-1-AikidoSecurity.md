# Altar-1：Aikido 开源权重安全模型（主权/本地化防御向）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/AikidoSecurity/status/2102035136678400056
- 作者 / 频道：@AikidoSecurity
- 发布时间：2026-09-21 14:00:05 UTC（约 2026-09-21 22:00 CST）

## 要点

- Aikido 官号发布 **Altar-1**：面向防御安全场景的开源权重模型，强调可在自有/气隙环境部署，避免把源码与未修复漏洞上下文送到第三方推理服务。
- 技术路径：基于 GLM-5.3，经量化 + 专家剪枝（REAP）压到约 **328 GB**（相对 BF16 约 1.51 TB，数字 **待核实**）；官博称在内部 CVE 再发现基准上接近量化父模型覆盖。
- 可动手入口：Hugging Face `AikidoSec/altar-1`；官博含 vLLM 服务与约 4×H200 节点部署说明。下载/点赞 **待核实**。

## 落地链接（可选）

- 官博：https://www.aikido.dev/blog/aikido-altar-open-weight-ai-sovereign-security
- 模型：https://huggingface.co/AikidoSec/altar-1

## 价值判断

- 为什么值得记：官帖 + HF 权重可下，轴是「主权/本地安全 Agent 模型」而非通用聊天模型。
- 风险 / 待核实：体量大、需多卡；大型企客户许可/审查条款以模型卡为准；安全效果数字 **待核实**；属安全厂商自研模型，非独立基准榜。

## 原文摘要（可选）

摘要：@AikidoSecurity 介绍 Altar-1，称其为可部署的开源权重防御级安全模型，强调「Own your own security」。

## 与其他条目的关系（可选）

与通用开源 LLM 发版不同：本条是 **安全/渗透测试工作负载向的开源权重模型**；勿与已入库各类 coding/多模态旗舰或 Shieldstral（内容安全分类小模型，若后续单列）混为同一项。
