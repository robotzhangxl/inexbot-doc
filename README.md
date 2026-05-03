# inexbot-doc

纳博特（Nabor）机器人控制系统技术文档索引，面向 Hermes / Claude Code / OpenClaw / OpenCode 等 AI Agent 工具。

> 文档站点：https://doc.inexbot.com
> 控制器产品线：C1102 / C1200 / C1201 / C2200

## 📦 下载包说明

| 文件 | 适用平台 |
|------|---------|
| `inexbot-doc-hermes.md` | **Hermes**（原生 SKILL 格式，含 YAML frontmatter） |
| `inexbot-doc-claude-code.md` | **Claude Code**（可直接放入 `.claude/skills/` 使用） |
| `inexbot-doc-openclaw.md` | **OpenClaw**（可直接放入 `skills/` 使用） |
| `inexbot-doc-opencode.md` | **OpenCode**（JSON skill 定义格式） |
| `inexbot-doc-raw.md` | **纯 Markdown**，通用格式，任何 AI 工具均可读取 |

## 📚 文档索引（130篇）

### 产品资料（18篇）
- 控制器：C1102 / C1200 / C1201 / C2200
- 示教器：T30 / T31 竖版 / 无线遥控 NWH01
- 驱控一体柜：X01 / X01-D02 / X02
- 显控一体机：XPC-150-C1100
- 精度标定：NexAutoCali 自动标定系统

### 操作手册 22.07版本（25篇）
- 系统基础 / 工具手标定 / 用户坐标标定
- 焊接 / 打磨 / 点胶 / 码垛 / 喷涂 / 冲压 / 激光切割 / 视觉工艺
- 寻位跟踪 / Modbus / 网络功能 / 人机协作 / 多机模式

### 操作手册 24.03版本（77篇）— 最新版
- 指令集 / 运动控制 / 程序控制 / 变量手册
- 二次开发：LUA / 多语言SDK / TCP / Modbus / EtherNet/IP / OPC-UA / 7000端口
- 机器人DH参数 / 外部轴 / 坐标系与标定
- 焊接 / 打磨 / 码垛 / 视觉 / 传送带跟踪 / 寻位跟踪
- 诊断维护：备份还原 / 编码器 / 伺服响应 / 反向间隙

## 🔧 快速使用

### Hermes
放入 `~/.hermes/profiles/<profile>/skills/motion-control/inexbot-doc/SKILL.md`

### Claude Code
放入 `.claude/skills/` 目录

### OpenClaw
放入 `~/.openclaw/skills/` 目录

### OpenCode
使用 `skill import` 命令导入 JSON 文件

## 📄 License
基于 doc.inexbot.com 公开文档整理，欢迎分享传播。
