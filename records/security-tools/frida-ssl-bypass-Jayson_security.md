# frida-ssl-bypass：Android SSL/TLS pinning 相关 Frida 脚本入口

- 状态：已核（仅索引公开仓库；禁止当绕过教程）
- 分类：security-tools
- 记录日期：2026-09-25
- **来源 X（必填）**：https://x.com/Jayson_security/status/2101324384786845903
- 作者：@Jayson_security
- 推文时间：2026-09-19 14:55:48 UTC（约 2026-09-19 22:55 CST）

## 关键点

- 公开仓库 **frida-ssl-bypass**：面向 Android 应用的 Frida 脚本集合，帖内称覆盖 TrustManager / OkHttp / Conscrypt / OpenSSL 等常见证书校验路径。
- 用途定位为安全研究 / 流量分析辅助；本条**只记仓库入口与能力标签**，不写 hook 细节或绕过步骤。

## 落地链接（可选）

- 仓库：https://github.com/danieldev23/frida-ssl-bypass

## 价值判断

- 为什么值得记：直接对应关键词 Frida / Android；出处与仓库均可打开。
- 风险 / 待核实：典型双刃工具，易被滥用；星数/维护状态待核；入库仅作公开索引，禁止当教程转载。

## 原文摘要（可选）

作者转发 frida-ssl-bypass 仓库，称可用于 Android 上 SSL/TLS 证书 pinning 相关场景。
