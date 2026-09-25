# Qwen-Image-2.1：开源 7B 文生图/编辑权重

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/Alibaba_Qwen/status/2101659302792679789
- 作者 / 频道：@Alibaba_Qwen
- 发布时间：2026-09-20 13:06:39 UTC（约 2026-09-20 21:06 CST）

## 关键点

- 官方宣布 **Qwen-Image-2.1** 开源权重：同一检查点做文生图和图像编辑，视觉生成部分约 7B。
- 模型卡写明可出普通图或透明 RGBA、最多约 10 张参考图、可用圈选/蒙版做局部编辑；推理走 Diffusers。
- 动手入口是 Hugging Face `Qwen/Qwen-Image-2.1`，另有官方博客与 Space 演示。

## 落地链接（可选）

- 模型：https://huggingface.co/Qwen/Qwen-Image-2.1
- 博客：https://qwen.ai/blog?id=qwen-image-2.1
- 演示：https://huggingface.co/spaces/Qwen/Qwen-Image-2.1

## 价值判断

- 为什么值得记：可下载的开源图像基座，生成和编辑在一个权重里，适合本地或自建管线。
- 风险 / 待核实：星数/下载量与「超过多数闭源」等效果数字仍待核实（HF 卡 2026-09-26 可开）；许可是 `qwen-research`（非 Apache），商用边界以 LICENSE 为准。

## 原文摘要（可选）

摘要：Qwen 称 Image-2.1 是该系列里更均衡、更省的开源图像模型，一个轻量包同时覆盖生成和编辑。

## 与其他条目的关系（可选）

与已入库 **Pruna-Qwen-Image-2.1** 不同：那条是挂在本基座上的少步 LoRA；本条是基座权重本身。
