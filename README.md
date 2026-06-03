# inexbot-doc

纳博特科技知识库 — 多轴运动控制系统技术文档自动同步。

> **来源**: https://doc.inexbot.com  
> **最后同步**: 2026-06-03 12:00 UTC  
> **总文档数**: 502篇

## 文件说明

| 文件 | 格式 | 用途 |
|------|------|------|
| `inexbot-doc-hermes.md` | YAML frontmatter + Markdown | Hermes AI Agent SKILL 格式 |
| `inexbot-doc-claude-code.md` | Markdown | Claude Code 知识库格式 |
| `inexbot-doc-openclaw.md` | Markdown | OpenClaw 格式 |
| `inexbot-doc-opencode.json` | JSON | OpenCode 知识库格式 |
| `inexbot-doc-raw.md` | Markdown | 纯文本通用格式 |
| `hash-map-snapshot.json` | JSON | VitePress hashmap 快照 |

## 同步机制

每日自动运行 cron 任务：
1. 抓取 doc.inexbot.com/hashmap.json
2. 对比本地哈希基线检测变化
3. 更新 SKILL.md 和参考文件
4. 生成 5 种格式的文档文件
5. 通过 GitHub API 上传

## 文档分类

- 产品资料: 18篇
- 技术资料: 5篇
- 操作手册 22.07: 25篇
- 操作手册 24.03: 78篇
- 常见问题 FAQ: 372篇（含349篇独立伺服报错页面）
- 行业方案: 2篇
