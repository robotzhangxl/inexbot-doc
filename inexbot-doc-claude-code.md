# Nabor Robot Control System - Technical Consultant

## System Overview
Nabor (纳博特) robot controllers: C1102/C1200/C1201/C2200 series.
Documentation: https://doc.inexbot.com
Developer Center: https://ones.inexbot.com/wiki/external/org/8cdyvHV7

## Document Index (130 docs)

### Product Documentation (18)
Controllers: C1102, C1200, C1201, C2200, T30/T31 teaching pendants, NWH01 wireless remote
Drive-control cabinets: X01, X01-D02, X02
Display-control一体机: XPC-150-C1100
Fieldbus IO: R2C/R4C/R4D/R5B EtherCAT IO modules
Calibration: NexAutoCali auto calibration system

### Technical Documentation (5)
- Servo error codes (troubleshooting)
- Supported servo models, external axis types, robot types
- Communication protocols & address codes

### Operation Manuals 22.07 (25)
System, calibration, processes (welding/cutting/grinding/painting/palletizing/laser/visual), networking (FinTCP/Modbus/Ethernet), collaboration/multi-machine/adaptive accel

### Operation Manuals 24.03 (78) - Latest
Core: Motion control, program control, variables, conditions, debugging
Development: Lua, multi-language SDK, TCP, Modbus, EIP, OPC-UA, port 7000, FinTCP, PC simulation
Robot config: DH parameters, structure, 6-axis collaboration, 3rd-party adapters (Luosen/FAW/CR20/SR5/CR10V/Tianji 7-axis)
External axes, coordinates, processes (welding/laser/grinding/palletizing/visual/conveyor/interference), diagnostics, teaching pendant

### Industry Solutions (2)
Collaborative palletizing, laser cutting

## Quick Q&A
Q: C1201 interfaces? A: EtherCAT, digital I/O, RS485/232 COM, CAN
Q: TCP calibration? A: 4-point or 6-point method on pendant
Q: Python connection? A: TCP protocol, see 7000 port docs or SDK
Q: Servo E001? A: Check servo error code doc

## Full Index
Access: https://doc.inexbot.com/{document_name}.md
See main SKILL.md for complete listing.
