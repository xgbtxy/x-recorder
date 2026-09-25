# 现有条目审计清单（综合专员 · 首轮）

- 审计日期：2026-09-25
- 范围：`records/security-tools/` + `records/ai-resources/`（对照 `templates/record.md` 与 README 索引）
- 说明：本清单不直接改仓库文件；建议由对应专员补字段 / 老大审计后入库

## 一、条目一览

| 文件 | 目录分类 | 正文自称分类 | README 索引分类 | 来源 X | 落地仓库实测 |
|------|----------|--------------|-----------------|--------|--------------|
| `ASC-root-narrative-MGAldys4.md` | security-tools | security-tools | security-tools | 可打开 | `MG1937/ASC` 200，约 1953★ |
| `reverse-skill-bigaiguy.md` | security-tools | security-tools（兼 ai-resources） | security-tools / ai-resources | 可打开 | `zhaoxuya520/reverse-skill` 200，约 37466★ |
| `ToCo-buzz3r.md` | ai-resources | ai-resources（兼 security-tools） | security-tools / ai-resources | 可打开 | **正文写 `buzzer-re/ToCo` → 404；原帖实为 `buzzer-re/ToCode`（200，约 38★）** |

## 二、可能重复 / 主题重叠（非同 status 硬重复）

三条 **不是同一条 X 的重复入库**（status 互不相同），但同属「Agent × 逆向 / 移动安全」主题簇，交叉引用紧密：

1. **ASC ↔ ToCo**：ToCo 关键点写「常与 ASC / Agent 友好逆向一起出现」；ASC 帖本身也是 Agent + 移动安全叙事。
2. **ASC ↔ reverse-skill**：reverse-skill 关键点写「与 ASC『Agent 友好 CLI』互补」。
3. **分类双挂不一致**：`ToCo`、`reverse-skill` 正文/索引都写兼两类，但磁盘上各只放在一个目录；去重检索时容易漏一侧。

建议（供审计）：保留三条（来源不同），但在价值判断或关键点里互相加「参见」链接；双分类条目要么两边各放一份 stub，要么 README 索引加「主目录」列，避免只搜一个目录时漏记。

## 三、字段缺失 / 错误

### 1. `ToCo-buzz3r.md`（严重）

- **落地链接错误**：`https://github.com/buzzer-re/ToCo` 返回 404；原帖明文为 `https://github.com/buzzer-re/ToCode`。
- **推文时间占位**：写「（检索可见）」；可补为 `2026-06-07 05:03:05 UTC`（约 `2026-06-07 13:03 CST`）。
- **标题/文件名拼写**：标题与文件名用 ToCo，仓库实名 ToCode——建议标题或落地链接旁注明正确仓库名，避免继续传播错链。

### 2. `reverse-skill-bigaiguy.md`（中）

- **推文时间占位**：写「（检索日 2026-09-25 可见）」；可补为 `2026-09-22 09:29:35 UTC`（约 `2026-09-22 17:29 CST`）。
- **营销数字**：原帖称「刚过 36.4k stars」；2026-09-25 实测约 37466，量级一致，风险栏可改为「以仓库页为准（已抽查量级相符）」。
- **兼类未落盘**：仅在 `security-tools/`；若坚持兼 `ai-resources`，缺对称文件或索引说明。

### 3. `ASC-root-narrative-MGAldys4.md`（轻）

- 字段较完整；推文时间「约 2026-09-16」可精确到 `2026-09-16 08:46:34 UTC`。
- **关键点内嵌仓库 URL**，与「落地链接」节重复——可收束到落地链接节。
- **关联帖未单独立档**：同作者另有 ASC 介绍帖 `https://x.com/MGAldys4/status/2098541143474749913`（本条原文里已引用）。是否另建 security-tools 条目由网安专员决定；综合侧仅标注，不扩写 other。

### 4. README 索引（轻）

- 索引标题与文件标题不完全一致（缩写版），不影响链接核对，但检索时可能对不上文件名。
- `records/other/`、`records/vpn-proxy/` 目录在 README 已声明，仓库树中 other/vpn 尚无条目（本地空目录）。

## 四、本轮 other 草稿

- **0 条**。按老大指令已暂停无目标扫库；审计过程中未发现可核验、且不落在网安/AI/VPN 主责的新 X 线索。下轮仅在明确非重叠线索出现时最多交 2 条。

## 五、建议优先修补顺序

1. 修正 ToCo → ToCode 落地链接（及文件名/标题一致性）
2. 补三条「推文时间」精确值
3. 统一双分类条目的目录/索引策略
4. （可选）网安专员评估是否为 ASC 介绍帖单独建档
