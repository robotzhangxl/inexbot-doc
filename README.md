# Inexbot Doc Knowledge Base

纳博特（Inexbot）机器人控制系统知识库镜像

## 内容说明

本仓库是 [doc.inexbot.com](https://doc.inexbot.com) 纳博特科技知识库的自动化镜像，由 Hermes AI Agent 每日自动同步更新。

## 文档统计

- **文档总数**: 130 篇
- **产品资料**: 18 篇（控制器、示教器、IO模块、驱控柜等）
- **技术资料**: 5 篇（伺服型号、机器人类型、通讯协议等）
- **操作手册 22.07 版本**: 25 篇
- **操作手册 24.03 版本**: 78 篇
- **行业方案**: 2 篇
- **最后同步**: 2026-05-10

## 文件说明

| 文件名 | 格式 | 用途 |
|--------|------|------|
| `inexbot-doc-hermes.md` | Hermes SKILL | Hermes AI Agent skill 文件 |
| `inexbot-doc-claude-code.md` | Markdown | Claude Code 知识库 |
| `inexbot-doc-openclaw.md` | Markdown | OpenClaw 知识库 |
| `inexbot-doc-opencode.json` | JSON | OpenCode 格式 |
| `inexbot-doc-raw.md` | Markdown | 通用纯文本格式 |

## 文档目录结构

### 产品资料
- 控制系统: T30/T31 示教器, C1102/C1200/C1201/C2200 控制器, NWH01 遥控盒
- 显控一体机: XPC-150-C1100
- 现场总线IO: R2C/R4C/R4D/R5B EtherCAT IO 模块
- 精度标定: NexAutoCali 自动标定系统
- 驱控一体柜: X01/X01-D02/X02 控制柜

### 技术资料
- 伺服报错代码、支持的伺服型号、外部轴类型、机器人类型、通讯协议

### 操作手册
- **22.07 版本**: 系统操作、调试、指令集、焊接/打磨/喷涂等工艺手册
- **24.03 版本**: 运动控制/程序控制指令、Lua 教程、7000端口协议、多机协作等

### 行业方案
- 协作码垛、激光切割

## 自动同步

本仓库通过 GitHub API 每日自动更新，无需手动 git push 操作。
