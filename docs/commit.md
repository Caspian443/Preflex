# Commit 规范

保持简单，优先写清楚这次改了什么。

推荐格式：

`type: summary`

常用 `type`：

- `feat`：新增功能
- `fix`：修复问题
- `docs`：文档变更
- `refactor`：重构但不改行为
- `test`：测试相关
- `chore`：杂项、脚本、配置

示例：

- `feat: add scheduler config loader`
- `fix: handle empty pipeline input`
- `docs: add project devlog and principles`

建议：

- `summary` 用英文，尽量控制在一行内
- 聚焦结果，不写执行过程
- 一次 commit 只表达一类改动
- 如果改动很多，先拆分再提交
