# LMDeploy v0.10.0：开源压缩+部署推理工具包发版

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/intern_lm/status/1965752368190070887
- 作者 / 频道：@intern_lm
- 发布时间：2025-09-10 12:21:01 UTC（约 2025-09-10 20:21 CST）

## 要点

- InternLM 官方账号发布 **LMDeploy v0.10.0**：开源 LLM 压缩 / 部署 / 服务工具包（TurboMind 引擎等，细节以文档为准）。
- 帖内强调对 **GPT-OSS MXFP4** 等路径的加速，并宣称在部分 GPU 场景相对 vLLM 更优（对比数字与场景待核实）。
- 可动手：`pip install lmdeploy`、GitHub 仓库与 ReadTheDocs；OpenAI 兼容 API 服务入口见文档。

## 落地链接（可选）

- 公告帖：https://x.com/intern_lm/status/1965752368190070887
- 仓库：https://github.com/InternLM/lmdeploy
- 文档：https://lmdeploy.readthedocs.io/en/latest/
- PyPI：https://pypi.org/project/lmdeploy/

## 价值判断

- 为什么值得记：补「压缩+服务一体」开源推理栈；与已入库 vLLM / 候选 SGLang 口味不同；官方账号可核。
- 风险 / 待核实：相对 vLLM 的吞吐对比与硬件前提待核实；InternLM/lmdeploy ★8098（2026-09-26 gh api）；Release v0.10.0 可开；同产品后续发版帖勿重复开条。

## 原文摘要（可选）

摘要：@intern_lm 称 LMDeploy v0.10.0 强化 GPT-OSS MXFP4 服务，并给出与 vLLM 的性能对比宣传。

## 与其他条目的关系（可选）

非 gpt-oss 模型权重条（已入库）；本条主体是 InternLM/lmdeploy 运行时。勿因帖内演示模型再开扩散条。
