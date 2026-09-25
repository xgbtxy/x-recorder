# vLLM v0.28.0：高吞吐开源推理服务引擎发版

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/vllm_project/status/2092789782464315594
- 作者 / 频道：@vllm_project
- 发布时间：2026-08-27 01:42:20 UTC（约 2026-08-27 09:42 CST）

## 要点

- vLLM 官方发布 **v0.28.0**：高吞吐 LLM 推理/服务引擎，强调 speculative decoding、Model Runner V2、分层 KV offload 等（细节以 Release notes 为准）。
- 帖内提及对若干前沿开源模型服务路径的支持增强；跨厂商后端以文档/Release 为准。
- 可动手：`pip install` / Docker 镜像 / GitHub Releases；文档 https://docs.vllm.ai/

## 落地链接（可选）

- 公告帖：https://x.com/vllm_project/status/2092789782464315594
- Release：https://github.com/vllm-project/vllm/releases/tag/v0.28.0
- 仓库：https://github.com/vllm-project/vllm
- 文档：https://docs.vllm.ai/

## 价值判断

- 为什么值得记：生产向开源 serving 栈的可核发版帖；补本地/集群 inference 口味（records 尚无 vLLM）。
- 风险 / 待核实：吞吐/延迟宣传数字与默认行为变更待核实；升级有 breaking defaults；vllm-project/vllm ★92677（2026-09-26 gh api）；吞吐/延迟宣传与 breaking defaults 待核实。

## 原文摘要（可选）

摘要：vLLM 贴出 v0.28.0，列举 speculative decoding、Runner V2、KV offload 与新模型支持等亮点。

## 与其他条目的关系（可选）

互补 llama.cpp / Ollama（本机）与本条（GPU serving）。非模型权重条；勿对同版本扩散帖重复开条。
