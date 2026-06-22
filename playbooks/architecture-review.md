# AI Architecture Review Playbook

Use this before building an AI workflow.

## Architecture Questions

- What is the user workflow?
- Which step needs AI, and which step should stay deterministic?
- What data is needed?
- Where are identity, permissions, and audit handled?
- Is the right pattern RAG, tools, workflow automation, agent loop, fine-tuning, or classic software?
- What is the human approval boundary?
- What gets logged and evaluated?
- What is the fallback when model, retrieval, or tools fail?

## Minimum Architecture Map

Include:

- User interface or entry point.
- API boundary.
- Data sources.
- Retrieval or tool layer.
- Model call and output schema.
- Validation and guardrails.
- Human review path.
- Logs, traces, metrics, and evals.
- Rollout and rollback path.

## Output

Create an architecture decision record using [`templates/architecture-decision-record.md`](../templates/architecture-decision-record.md).
