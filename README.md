# 纳博特（inexbot）机器人控制系统 文档索引

> ⚙️ **运动繁复，化简为境** — 纳博特科技官方知识库文档索引

本仓库自动同步自 [doc.inexbot.com](https://doc.inexbot.com)，每日检测更新并生成多种格式的文档索引。

## 仓库文件

| 文件 | 格式 | 用途 |
|------|------|------|
| `README.md` | Markdown | 本说明文件 |
| `inexbot-doc-hermes.md` | Hermes SKILL | Hermes AI Agent 技能格式（含 YAML frontmatter） |
| `inexbot-doc-claude-code.md` | Markdown | Claude Code 通用格式（纯 Markdown） |
| `inexbot-doc-openclaw.md` | Markdown | OpenClaw 格式（精简文档索引） |
| `inexbot-doc-opencode.json` | JSON | OpenCode 结构化格式 |
| `inexbot-doc-raw.md` | Markdown | 纯文档索引速查（无 QA/维护信息） |
| `hash-map-snapshot.json` | JSON | VitePress 内容哈希快照（用于变更检测） |

## 当前状态

- **文档总数**：154篇
- **更新日期**：2026-05-16

### 文档分布

| 类别 | 数量 | 说明 |
|------|------|------|
| 产品资料 | 18篇 | 控制系统7 + 显控一体机2 + 现场总线IO5 + 精度标定1 + 驱控一体柜3 |
| 技术资料 | 5篇 | 伺服报错代码 + 支持的伺服/外部轴/机器人/通讯协议 |
| 操作手册 22.07 | 25篇 | 系统基础5 + 标定3 + 工艺8 + 通讯3 + 高级功能5 + 其他1 |
| 操作手册 24.03 | 79篇 | 核心6 + 二次开发10 + 机器人9 + 外部轴5 + 坐标3 + 工艺12 + 位置5 + 通讯IO6 + 多机3 + 诊断维护6 + 示教器5 + 其他9 |
| 常见问题 FAQ | 23篇 | IO/伺服/焊接/激光/视觉/码垛/寻位等常见问题 |
| 行业方案 | 2篇 | 协作码垛 + 激光切割 |

## 格式说明

- **Hermes SKILL格式**：包含 YAML frontmatter 和完整的 Q&A 缓存区、维护指南，适合 Hermes Agent 加载使用
- **Claude Code格式**：纯 Markdown，移除 frontmatter，保留完整内容，适合 Claude Code 使用
- **OpenClaw格式**：精简版文档索引，仅保留核心目录结构
- **OpenCode格式**：结构化 JSON，包含分类统计和内容哈希映射
- **Raw格式**：纯文档索引速查，无 QA 和维护信息

## 变更检测

本仓库通过比较 VitePress 的 `/hashmap.json` 端点来检测文档变化。每次检测结果记录在 `hash-map-snapshot.json` 中。
