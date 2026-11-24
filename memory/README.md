# Project memory

Keep memory in the consuming repository. Copy this guide when adopting the harness and start each project's history empty.

## Task records

The coordinator creates `memory/tasks/<task-id>.md` when planning begins. Choose one stable, descriptive task ID and reuse it across CLI sessions. Begin with the goal, specification path and criteria, branch or workspace, starting revision when available, and ordered stage plan.

Append an entry after each repair cycle, specification amendment, completion or halt. Give entries unique Markdown headings so later lessons can link directly to them. Record the following details.

| Field | What to keep |
| --- | --- |
| State | Stage ID, cycle number, date, and outcome: amendment, repair, completion or recovery. |
| Change | Affected criteria and files, reason for the revision, and the commit or identifiable working diff. |
| Model selection | Activity, requested model and effort, and any escalation or fallback reason. Record the actual settings when confirmed, or mark them unconfirmed. |
| Evidence | Command and exit status or inspection and observed result, with a stable artifact path when available. |
| Handoff | Open findings, remaining cycles and the exact next action, or the next eligible stage. |

Write a completion entry only after validation. On interruption, record recovery whenever possible. If a session ends before a checkpoint is written, compare the actual diff to the last entry and reconcile partial work before proceeding.

## Lessons

After successful validation of the whole task, the archivist may add a short entry to `memory/lessons.md`. Include the symptom or decision, verified cause, fix, conditions where it applies, and a link to the supporting checkpoint. Mark obsolete lessons when later evidence changes the guidance. Store decisions that alter required behavior in the specification.

For a fresh session, open the relevant spec and task record first. Search lessons by affected feature or symptom. Keep long logs in the project's artifact store and record enough of the result to remain useful if an artifact expires.
