# task_j0024_a_7e2229879ef0

<!-- METADATA:STATUS=InProgress,ASSIGNEE=citest_j0024_7e2229879ef0_worker_1 -->

## 目标

从共同业务基线 `11cc76aad588c1296713921d3aa7b697ea1d08c5` 独立完成任务 A。在仓库根目录交付 `j0024-a-7e2229879ef0.txt`，且文件必须包含精确字符串 `J0024_ASSIGN_A_7E2229879EF0`。

## 边界

- 本任务只交给 `citest_j0024_7e2229879ef0_worker_1`。
- 除 Playbook 要求的 Worker/任务状态文件外，只能修改业务文件 `j0024-a-7e2229879ef0.txt`。
- 不得修改任务 B 的业务文件或其他业务文件。
- 此轮不得合并、关闭 PR 或集成到 `master`；完成后保持公开可审查状态并报告 Lead。

## 验收

- `j0024-a-7e2229879ef0.txt` 存在且包含 `J0024_ASSIGN_A_7E2229879EF0`。
- PR 来源分支、目标分支和 OPEN 状态可从远端读回。
- 产品/业务 diff 仅包含 `j0024-a-7e2229879ef0.txt`；流程元数据改动限于 Playbook 要求的文件。
- 向 Lead 报告交付可审查，并提供 PR URL、分支、提交和验证证据。
