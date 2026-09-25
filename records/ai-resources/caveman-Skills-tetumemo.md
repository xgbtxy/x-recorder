# Caveman（JuliusBrussee/caveman）：少废话省输出 Token 的 Agent Skill

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/tetumemo/status/2045102005908332881
- 作者 / 频道：@tetumemo（介绍/测评帖；仓库作者 JuliusBrussee）
- 发布时间：2026-04-17 11:28:09 UTC（约 2026-04-17 19:28 CST）

## 要点

- **JuliusBrussee/caveman**：开源 Agent Skill（及配套站点/代理层），逼编码 Agent 用极简「原始人」口吻回复，宣称显著削减可见输出 token，代码/命令仍要求准确。
- 安装：`npx skills add JuliusBrussee/caveman -g`（README / skills.sh 一致）；可用 `/caveman` 开关。
- 介绍帖对比普通回复与 caveman / 日文 genshijin 变体的 token 差，并链到 GitHub Skills 获取方式。

## 落地链接（可选）

- 仓库：https://github.com/JuliusBrussee/caveman
- 目录：https://www.skills.sh/juliusbrussee/caveman
- 站点：https://caveman.so/

## 价值判断

- 为什么值得记：一行 `npx skills add` 可装的第三方内容包，场景明确（压输出冗词），仓库与 skills.sh 可开。
- 风险 / 待核实：
  - 「65%/80% 省 token」等效果数字标「待核实」（多来自作者初测/转述，HN 亦有争议）。
  - 主要压**可见输出**，不保证思维链/总费用下降；过简风格可能伤可读性或个别任务质量。
  - 站点另推 proxy/平台层，权限与外连面大于「纯 SKILL.md」——安装前分清只要 skill 还是整栈。
  - 星数约 107834（JuliusBrussee/caveman，2026-09-26 核）。

## 原文摘要（可选）

摘要：日文帖演示「像原始人说话」系统提示对 Claude 输出 token 的削减，并说明可从 GitHub 以 Skills 方式安装 caveman。

## 与其他条目的关系（可选）

**非** skills-cli 本体；也非 ECC/obra 类大方法论合集。本条为可装的**单一风格/省词内容包**；日文优化分支 genshijin 为衍生，不在本条展开。
