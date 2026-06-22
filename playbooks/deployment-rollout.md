# Deployment Rollout Playbook

Use this to move from demo to controlled pilot.

## Pilot Scope

- Users: who participates first?
- Workflow: what exact steps are in scope?
- Autonomy: what can the system do alone?
- Approval: where must humans approve?
- Data: what sources are allowed?
- Metrics: what proves value?

## Operational Readiness

- Prompt, model, retrieval, and tool versions are recorded.
- Logs and traces show user request, model call, tool call, output, validation, and errors.
- Rollback path is documented.
- Support owner is named.
- User feedback path exists.
- Security and privacy assumptions are written down.

## Handoff

The customer or internal owner should know:

- How to operate it.
- How to report failures.
- How to monitor quality.
- How to disable risky behavior.
- What should be improved next.
