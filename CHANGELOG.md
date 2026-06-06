## v2.1.1

### Bug Fixes
- 修复 `_conf_schema.json` 中 JSON 尾随逗号导致插件无法载入的问题
- 修复 `_conf_schema.json` 中 `timezone` 字段类型 `number` 不被 AstrBot 支持的问题，改为 `int`

### Chore
- 移除冗余的 `requirements.txt`（依赖 `aiohttp` 已由 AstrBot 核心提供）
- 移除已废弃的 `@register` 装饰器及其 import（AstrBot v3.5.19+ 已自动识别 `Star` 子类）
