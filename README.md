# robotzhangxl/inexbot-doc

Auto-synced inexbot robot technical documentation index, sourced daily from https://doc.inexbot.com

## Recent updates

- **2026-07-24 (drift-sync)**: SKILL.md 焊接 Q&A 缓存区追加 4 条问答 + 修复 frontmatter 块引用。doc.inexbot.com 站点零变化（552 docs hashmap 三方完全一致），仅本地 SKILL.md 相对 GitHub 产生 993 字节 drift，故只上传 5 格式文件 + README，不上传 hash-map-snapshot.json。
- 2026-07-23: 11 new docs in Industry Solutions (mobile humanoid robot, teaching-free spray, grinding, wafer, laser seek/track, laser welding, dispensing, logistics auto-bagging, palletizing, metal welding, medical robot). Total 541 -> 552.
- 2026-07-22: no-op (no changes).
- 2026-07-21: 6 new docs in v25.01 (IO functions, special processes, human-robot collaboration, multi-machine coordination, new dual-machine features, independent axis control).

## Files

| File | Purpose |
|------|---------|
| inexbot-doc-hermes.md | Hermes SKILL format (with YAML frontmatter) |
| inexbot-doc-claude-code.md | Claude Code format |
| inexbot-doc-openclaw.md | OpenClaw format |
| inexbot-doc-raw.md | Pure Markdown, no frontmatter |
| inexbot-doc-opencode.json | OpenCode JSON format |
| hash-map-snapshot.json | Current site hash map (552 docs, VitePress content hash) |
| README.md | This file |

## Document statistics (as of 2026-07-23)

| Category | Count |
|----------|-------|
| 产品资料 (Product) | 19 |
| 技术资料 (Tech resources) | 5 |
| 操作手册 22.07 版本 | 25 |
| 操作手册 24.03 版本 | 78 |
| **操作手册 25.01 版本** | **41** |
| 常见问题分类 (FAQ) | 23 |
| 伺服报错页面 (Servo error pages) | 349 |
| **行业方案 (Industry solutions)** | **13** (was 2 before 2026-07-23) |
| **Total** | **552** |

## Source

- Doc site: https://doc.inexbot.com
- Developer hub: https://ones.inexbot.com/wiki/external/org/8cdyvHV7
- Brand site: https://www.inexbot.com
- Synced daily by Hermes cron via `https://doc.inexbot.com/hashmap.json` with three-layer byte comparison (site / local baseline / GitHub snapshot) to skip redundant uploads.