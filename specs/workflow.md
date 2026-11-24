# Spec-driven delivery

## Specification

A behavior change begins with a human-owned specification under `specs/`. Identify its owner or authorizing request, scope, observable behavior, invariants and acceptance criteria. Give criteria stable identifiers so a check or finding can refer to one requirement. Keep code, pseudocode and examples outside specifications.

Codex may draft revisions within the user's request. A draft that changes a product decision beyond that request needs the owner's decision before implementation. Record amendments and their affected criteria in the task record. A fix that restores specified behavior uses the existing criteria.

## Planning and execution

Before editing the implementation, record an ordered plan with stable stage IDs, dependencies, allowed paths, criteria and required checks for each stage. Use the smallest plan that covers the request. Select checks from the host project's tooling or define a reproducible inspection for a documentation-only criterion.

Choose the first unfinished stage in plan order whose dependencies have completion checkpoints. Implement, review the affected behavior, run the required tests and validate the final revision against each criterion. Include design review when the contract requires design evidence. If a fix or new test changes the reviewed revision, review the affected changes and refresh affected checks before completion.

## Model selection

The coordinator selects a model and reasoning effort before each activity. Honor explicit user selections and workspace restrictions first. Apply the first matching row below. Use the project's preferred available model for each row, or the listed default when supported.

| Activity | Default selection |
| --- | --- |
| Requirements analysis, planning, task assignment, research, or diagnosis with an unknown cause | Astra with high reasoning |
| Work in any role involving conflicting evidence, a consequential design decision, or unclear effects across component boundaries | Astra with high reasoning |
| Bounded implementation, known-cause fixes, routine logic review, test execution, evidence checks, or checkpoint summaries with explicit criteria | Sol with low reasoning |
| Work whose scope or verification method is still unclear | Astra with high reasoning to resolve the uncertainty |

Reclassify when evidence changes. A failed check with a known local fix can stay on Sol. An unexplained failure or a recurrence after repair calls for Astra to diagnose it. Once the cause, fix scope and verification method are clear, return bounded work to Sol. Model changes preserve the stage order, consumed cycles and required gates.

Apply the selection through an authorized model-selectable worker when available. Reuse a matching session for related work. If a preferred model is unavailable, use a supported equivalent for the activity. If switching is unavailable, record the active session as the fallback and proceed where its work can be verified. Use the recovery procedure when a required decision or check remains unresolved.

## Gates and recovery

For every required check, record the command or inspection method, revision or working diff, result and evidence location or concise observed output. A command gate requires its actual exit status. A manual gate requires an observation someone else can reproduce. A missing, skipped or unavailable required check leaves the stage incomplete.

Allow at most three cycles per stage, counting the initial implementation. Record each failed cycle, the cause and the assigned repair. Stop earlier for a missing prerequisite that another attempt cannot resolve. On exhaustion or a blocker, write a recovery checkpoint and halt the run.

Only a completion checkpoint satisfies a dependency. On resume, read the original plan and latest checkpoint, compare the recorded state with the working tree, and refresh evidence affected by drift. Preserve stage order, completed history and consumed cycles. An exhausted stage needs an explicit human decision on revised scope, prerequisites or a new repair budget before further repair. Record that decision before continuing.
