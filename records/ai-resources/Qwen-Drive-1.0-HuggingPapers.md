# Qwen-Drive-1.0：自动驾驶向统一视觉-语言基础模型（开源权重）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/HuggingPapers/status/2095062917485887878
- 作者 / 频道：@HuggingPapers（社区转、非官宣）
- 发布时间：2026-09-02 08:14:58 UTC（约 2026-09-02 16:14 CST）

## 要点

- 社区日报转介：**Qwen-Drive-1.0** 在保持预训练 VLM 骨架（README 写基于 Qwen3.5-4B）前提下，统一接入 **3D 感知**、驾驶/通用 VQA 与 **运动规划**。
- 结构上挂 BEV Perception Head（检测/占用/地图分割等）与 Planning Expert，LLM Decoder 仍处理通用与驾驶 VQA；权重卡 `Qwen/Qwen-Drive-1.0-4B`。
- 可动手入口：Hugging Face 与 GitHub `QwenLM/Qwen-Drive-1.0`、ModelScope 镜像；技术报告 arXiv:2609.00111。星数/效果标 **待核实**。未见检索窗口内 @Alibaba_Qwen 同题官帖，标社区转。

## 落地链接（可选）

- 模型：https://huggingface.co/Qwen/Qwen-Drive-1.0-4B
- 仓库：https://github.com/QwenLM/Qwen-Drive-1.0
- 论文：https://arxiv.org/abs/2609.00111

## 价值判断

- 为什么值得记：官方组织 HF/GitHub 可下；产品轴是 **驾驶域统一 VLM**，不同于通用聊天或文生图发版。
- 风险 / 待核实：来源为社区转；实车/闭环评测数字与许可条款待核实；底座叙述含 Qwen3.5，勿与禁开的 Qwen3.8 旗舰线混为同一发版条。

## 原文摘要（可选）

摘要：@HuggingPapers 称阿里 Qwen-Drive-1.0 将 3D 感知、VQA 与运动规划纳入统一视觉-语言驾驶基础模型。

## 与其他条目的关系（可选）

相对已入库 Qwen Intelligence（手机 Agent）/ Qwen-Image / Qwen3-VL-Embedding：本条是 **自动驾驶感知+规划 VLM**。非 RoboDawn/PhysBrain 等具身操作条；非禁开 Qwen3.8 / Qwen-Audio-3.1 发版帖。
