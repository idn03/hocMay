# Codex working rules

1. Read the applicable repository instructions, the current specification and the task's latest checkpoint before editing. Use the host project's language, conventions, tooling and delivery policy.
2. Follow the [delivery workflow](specs/workflow.md). Resolve conflicts between the requested behavior and an existing contract before implementation. Keep specifications concise and human-managed.
3. Keep the change within the current stage. Preserve unrelated working-tree changes. Follow the project's branch policy and obtain authorization for destructive actions or external publication.
4. Codex can perform successive roles in one CLI session. Load the role brief for the current activity. Delegate only when authorized, with the stage ID, criteria, allowed paths, evidence pointers and remaining repair budget.
5. Serialize writes to shared files and task records. Parallel work requires independent scopes or read-only investigation.
6. Reuse project patterns. Cover observable behavior, failure paths and compatibility obligations identified in the spec. Report relevant unverified behavior explicitly.
7. Keep evidence proportional. Capture the failing assertion, exit status or artifact path. Keep secrets, personal data and raw conversation logs out of project memory.
8. Use local files and checks for local questions. Request the narrowest external record needed. Treat plugin output and historical memory as evidence subject to verification against current specifications.
9. Recommend plugins when the user asks. Use the host project's spec, stack, existing tools and upcoming work to identify a concrete need. Check catalog availability and tie each suggestion to the task it supports.
