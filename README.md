# inexbot-doc — 纳博特机器人技术顾问 Skill

纳博特（inexbot）机器人控制系统的技术顾问skill，涵盖产品选型、配置调试、二次开发、工艺应用全流程。文档索引基于 doc.inexbot.com（1104 篇：中文 557 + 英文 547，含 349 篇独立伺服报错页面，含 25.01 版本 37 篇新文档，含 14 篇行业方案）。2026-09-08 真实更新：双语镜像上线 + slug 重构 552→1096；2026-09-10 **真实内容更新 + 英文 slug 拼音化**：站点 hashmap 72395B→73197B（+802B，Last-Modified 2026-09-10，CHANGED hash=245 / NEW en=386 / REMOVED en=378 / CHANGED zh=144）；中文 144 篇内容实质更新、英文 slug 全面拼音化（禾川→hechuang、杰美康→jiemekang）、新增 8 篇英文文档（1096→1104）。每次回答问题后自动追加 Q&A 到下方缓存区。

## 📦 多格式分发

本仓库提供同一份内容的 5 种格式，便于不同 AI 工具使用：

| 文件 | 格式 | 适用工具 |
|------|------|---------|
| `inexbot-doc-hermes.md` | Hermes SKILL（含 YAML frontmatter） | Hermes Agent |
| `inexbot-doc-claude-code.md` | Claude Code 格式 | Claude Code CLI |
| `inexbot-doc-openclaw.md` | OpenClaw 格式 | OpenClaw |
| `inexbot-doc-opencode.json` | OpenCode JSON | OpenCode |
| `inexbot-doc-raw.md` | 纯 Markdown | 通用 |

## 📊 文档统计（截至 2026-09-10）

| 类别 | 数量 |
|------|------|
| 产品资料 | 21 篇 |
| 技术资料 | 4 篇 |
| 操作手册 22.07 版本 | 25 篇 |
| 操作手册 24.03 版本 | 78 篇 |
| **操作手册 25.01 版本** | **37 篇** |
| 常见问题分类 | 23 篇 |
| 伺服报错页面 | 349 篇 |
| **行业方案** | **14 篇** |
| **合计** | **1104 篇** |

## 🆕 2026-09-10 本次更新

- **类型**：自动同步（cron）
- **上传文件**：README + 5 格式（+ hash-map-snapshot.json 按需）

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
