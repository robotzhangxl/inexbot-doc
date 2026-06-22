# 纳博特机器人控制系统文档索引

纳博特（inexbot）机器人控制系统，控制器产品线 C1102/C1103/C1201/C2200 系列。
文档站点: https://doc.inexbot.com
开发者中心: https://ones.inexbot.com/wiki/external/org/8cdyvHV7

## 文档总数：507篇（含349篇独立伺服报错页面，25.01版本4篇新文档）

### 产品资料（19篇）
- 控制器（8）：C1102, C1103 (NEW), C1201, C2200, T30, T31, T40 (NEW), NWH01
- 驱控一体柜/显控一体机（4）：X01, X01-D02, X02, XPC-150-NC (NEW)
- 现场总线IO/精度标定（5）：R2C, R4C, R4D, R5B, NexAutoCali

### 技术资料（5篇）
伺服报错代码、支持的伺服型号、外部轴类型、机器人类型、通讯协议地址码

### 22.07版本操作手册（25篇）
系统操作、调试、指令集、标定、焊接、打磨、喷涂、冲压、激光切割、视觉、寻位跟踪、通讯等

### 24.03版本操作手册（78篇）— 当前稳定版
运动控制/程序控制指令、变量手册、Lua教程、7000端口协议、Modbus/EIP/OPC-UA、TCP通讯、多机协作、工艺手册、示教器等

### 25.01版本操作手册（4篇）— 最新版
外部轴使用手册、工具手标定、用户坐标标定、输入输出类/定时器类/运算类手册

### 常见问题FAQ（23篇分类 + 349篇伺服报错）
分类：IO与安全、焊接、视觉、码垛、系统配置、运动控制、通讯等

### 行业方案（2篇）
协作码垛、激光切割

## 快速问答

Q: 焊接指令有哪些？
A: ARCON, ARCOFF, ARCSET, WVON, WVOFF, FSWELDON/OFF, CIL, SPOTWELD, REFP, FEEDWIRE

Q: C1201 接口？
A: 1×EtherCAT + 3×Ethernet, 2×CAN, 1×RS485, 1×RS232, 16DI/16DO, 编码器, PWM

Q: Python 连接方式？
A: 7000端口(JSON over TCP) 或 TCP Server/Client

Q: T40 示教器？
A: 新品，文档已上线 doc.inexbot.com

## 在线访问
正确格式: https://doc.inexbot.com/操作手册/24.03版本/运动控制类指令
