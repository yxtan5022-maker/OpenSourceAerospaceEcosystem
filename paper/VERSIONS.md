# 版本清单（VERSIONS）

每次迭代都会把上一版（tex + pdf）归档到 `versions/vN_名称/`，当前最新版始终为 `paper/` 下的
`main_zh.tex/.pdf` 与 `main_en.tex/.pdf`（不含版本后缀）。

| 版本 | 日期 | 位置 | 说明 |
|------|------|------|------|
| v1 | 2026-08 | `versions/v1_sidewaystable/` | sidewaystable 旋转表格版；中 18 页 / 英 21 页；标题随表格旋转 90°，标题文字倒向 |
| v2 | 2026-08 | `versions/v2_pdflscape_blank/` | 改用 pdflscape 真横版页；标题正常，但表 2 整箱超高被推到下一页，产生异常空白横版页（中 20 / 英 23 页） |
| v3（当前） | 2026-08 | `paper/` | 修复空白页：表格缩为 `\small`、列间距收窄、精简单元格文字，表格一页放下；中 19 页 / 英 22 页 |

## 历史变更摘要

- v1 → v2：表格由 `rotating` 的 `sidewaystable` 改为 `pdflscape` 的 `landscape` 页，标题文字恢复正读。
- v2 → v3：修复空白横版页。根因是概念映射表（8 行）在横版页可用高度（约 15.4cm）内放不下，
  整箱不可断被推到下一页。修复 = 表格字体 `\small` + `\tabcolsep` 4pt + 精简单元格文字。
