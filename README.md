# inexbot-doc — 纳博特机器人技术顾问 Skill

纳博特（inexbot）机器人控制系统的技术顾问skill，涵盖产品选型、配置调试、二次开发、工艺应用全流程。文档索引基于 doc.inexbot.com（552篇文档，含349篇独立伺服报错页面，含25.01版本41篇新文档，含13篇行业方案）。2026-07-23 站点行业方案新增 11 篇文档（轮式人形机器人运动控制系统、免编程示教系统喷涂、打磨、晶圆、激光寻位-跟踪、激光焊接、点胶、物流系统自动供包、码垛、金属焊接、医疗机器人）。每次回答问题后自动追加 Q&A 到下方缓存区。2026-07-27 cron：第 5 次捕获 SKILL.md-only drift (1224B)，三方 hashmap 仍全等 36858B，6 文件上传。

## 📦 多格式分发

本仓库提供同一份内容的 5 种格式，便于不同 AI 工具使用：

| 文件 | 格式 | 适用工具 |
|------|------|---------|
| `inexbot-doc-hermes.md` | Hermes SKILL（含 YAML frontmatter） | Hermes Agent |
| `inexbot-doc-claude-code.md` | Claude Code 格式 | Claude Code CLI |
| `inexbot-doc-openclaw.md` | OpenClaw 格式 | OpenClaw |
| `inexbot-doc-opencode.json` | OpenCode JSON | OpenCode |
| `inexbot-doc-raw.md` | 纯 Markdown | 通用 |

## 📊 文档统计（截至 2026-07-23）

| 类别 | 数量 |
|------|------|
| 产品资料 | 19 篇 |
| 技术资料 | 5 篇 |
| 操作手册 22.07 版本 | 25 篇 |
| 操作手册 24.03 版本 | 78 篇 |
| **操作手册 25.01 版本** | **41 篇** |
| 常见问题分类 | 23 篇 |
| 伺服报错页面 | 349 篇 |
| **行业方案** | **13 篇**（2026-07-23 +11） |
| **合计** | **552 篇** |

## 🆕 2026-08-06 本次更新

- **类型**：site rebuild + SKILL.md drift sync
- **站点变化**：hash map 内容变化但为**纯 VitePress rebuild**（md5 `b6cdef7f` → `fd5164f6`，552 篇全量 rehash，0 新增 / 0 移除 / 字节大小不变 = 无文档内容更新）→ 刷新 hash 基线（local baseline + `hash-map-snapshot.json`）
- **本地变更**：SKILL.md 在 2026-08-05 批次 B 上传后追加了「08-05 drift sync 实录」reference 条目 + 「每日脚本复用/两批同步模式」SOP 段（+1528B drift）
- **上传文件**：7 个（README + 5 格式 + `hash-map-snapshot.json`）
- **闭环验证**：回读 GitHub `inexbot-doc-hermes.md` md5 == 本地 SKILL.md md5

## 🔗 数据源

- 官方文档站：https://doc.inexbot.com
- 开发者中心：https://ones.inexbot.com/wiki/external/org/8cdyvHV7
- 品牌站：https://www.inexbot.com

## 🔄 自动同步

本仓库由每日 cron 任务自动同步至 doc.inexbot.com 站点更新。
同步策略：四方字节比对（site ↔ local baseline ↔ GitHub snapshot ↔ SKILL.md/hermes drift）。
仅在有实质更新时上传，无更新时静默跳过。

## 📜 许可

仅供内部技术参考使用，文档内容版权归纳博特科技所有。
