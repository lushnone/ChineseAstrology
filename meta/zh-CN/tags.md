# 标签与学科

Catalog 条目中的 **字段名与取值** 须与 [`catalog/schema/entry.schema.json`](../../catalog/schema/entry.schema.json) 一致。下文为中文说明。

## `disciplines`（数组，必填）

- `bazi` — 八字
- `ziwei` — 紫微斗数
- `qimen` — 奇门遁甲
- `liuyao` — 六爻
- `fengshui` — 风水（仅工具向）
- `calendar` — 万年历、节气、农历转换
- `general` — 多体系综合站、论坛、资讯

## `type`

- `website` | `webapp` | `ios` | `android` | `desktop` | `api` | `book` | `course` | `community`

## `pricing`

- `free` | `freemium` | `paid` | `subscription` | `unknown`

## 筛选（后续）

条目增多后，可由 YAML 生成索引页，例如：`disciplines: [bazi]` 且 `type: webapp`。
