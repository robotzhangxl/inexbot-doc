# inexbot-doc

> 纳博特（inexbot）科技知识库 — 130篇技术文档的机器可读索引

本仓库维护纳博特（inexbot）机器人控制系统的多格式文档索引，支持 AI Agent 系统（Hermes、Claude Code、OpenClaw、OpenCode）直接查询。

**文档站点**: https://doc.inexbot.com
**开发者中心**: https://ones.inexbot.com/wiki/external/org/8cdyvHV7

---

## 文档格式

| 文件 | 格式 | 用途 |
|------|------|------|
| `inexbot-doc-hermes.md` | Hermes SKILL (YAML frontmatter) | Hermes Agent 系统 |
| `inexbot-doc-claude-code.md` | 精简指令格式 | Claude Code 等 Agent |
| `inexbot-doc-openclaw.md` | OpenClaw 格式 | OpenClaw 系统 |
| `inexbot-doc-opencode.json` | JSON 格式 | OpenCode 等系统 |
| `inexbot-doc-raw.md` | 纯 Markdown | 通用 |

---

## 文档统计

- **总计**: 130 篇文档
- **产品资料**: 18 篇（控制器、驱控柜、现场总线IO、精度标定）
- **技术资料**: 5 篇（伺服报错代码、支持的型号、通讯协议）
- **操作手册 22.07版本**: 25 篇
- **操作手册 24.03版本**: 78 篇（最新）
- **行业方案**: 2 篇

---

## 核心文档速查

| 任务 | 文档 |
|------|------|
| 伺服报警排查 | `技术资料_常见问题与解决方案_伺服报错代码.md` |
| TCP 标定 | `操作手册_24.03版本_工具手标定手册.md` |
| 二次开发 SDK | `操作手册_24.03版本_dev多语言功能使用教程.md` |
| TCP 通讯 | `操作手册_24.03版本_tcp通讯功能手册.md` |
| 7000 端口协议 | `操作手册_24.03版本_7000端口.md` |
| 运动控制指令 | `操作手册_24.03版本_运动控制类指令.md` |
| 变量手册 | `操作手册_24.03版本_变量手册.md` |
| 焊接工艺 | `操作手册_24.03版本_焊接工艺.md` |
| LUA 编程 | `操作手册_24.03版本_lua教程.md` |

---

## 自动更新

本仓库由 Cron Job 自动同步 doc.inexbot.com，每日检测更新并推送至 GitHub。

---

*最后更新: 2026-05-06*
