# Awesome FDE Resources

A curated resource map for people learning Forward Deployed Engineering: customer discovery, AI use-case judgment, AI architecture, LLM application engineering, RAG, evals, security, production rollout, and executive communication.

## Why This Repo Exists

Forward Deployed Engineers sit in a difficult middle: they need enough engineering depth to build real systems, enough AI judgment to choose the right pattern, and enough customer sense to turn ambiguous business workflows into deployed products.

Most AI learning lists are too broad. Most system-design lists are not specific to AI deployment. Most interview prep does not teach customer-facing implementation judgment. This repo exists to answer a narrower question:

**What should someone study, build, and practice if they want to become useful as an FDE?**

The goal is resource sharing, not course completion. Every link should help a learner produce or explain an FDE artifact: a use-case score, a scope memo, an architecture decision, a thin prototype, an eval report, a security review, a rollout plan, or an interview answer.

## How To Use This

Start with the category that matches the FDE skill you want to improve.

- **Interview prep:** focus on customer discovery, architecture, evals, security, and rollout.
- **Portfolio building:** use the playbooks and templates to turn resources into artifacts.
- **Contribution:** add resources only when they clearly help an FDE task.

## Resource Categories

- [FDE Role, Use Cases, and Customer Discovery](resources/01-role-use-cases-customer-discovery.md)
- [Engineering Foundations and APIs](resources/02-engineering-foundations.md)
- [AI Architecture and Agents](resources/03-ai-architecture-agents.md)
- [LLM App Engineering and Tool Use](resources/04-llm-app-engineering.md)
- [RAG, Domain Knowledge, and GraphRAG](resources/05-rag-domain-knowledge.md)
- [Evaluation, Reliability, and Observability](resources/06-evaluation-reliability-observability.md)
- [Security, Privacy, and Governance](resources/07-security-governance.md)
- [Deployment, Rollout, and Maintainability](resources/08-deployment-rollout.md)
- [Demo, Communication, and Interview Practice](resources/09-demo-communication-interviews.md)

## Playbooks

These playbooks are original maintainer drafts for this repo. They are not copied from external sources. They translate the resource categories into practical FDE artifacts.

- [Use-Case Scoring Playbook](playbooks/use-case-scoring.md)
- [AI Architecture Review Playbook](playbooks/architecture-review.md)
- [Evaluation Report Playbook](playbooks/evaluation-report.md)
- [Deployment Rollout Playbook](playbooks/deployment-rollout.md)

## Templates

These templates are original maintainer drafts for this repo. They are meant as lightweight starting points, not canonical industry standards.

- [Use-Case Scoring Matrix](templates/use-case-scoring-matrix.md)
- [Architecture Decision Record](templates/architecture-decision-record.md)
- [Evaluation Report](templates/evaluation-report.md)
- [Demo Narrative](templates/demo-narrative.md)

## TODO

- Add a concrete learning path, possibly including a 20-hour starter path, once the recommended sequence and exercises are more fully specified.
- Add more examples of real FDE-style artifacts.
- Add more community-vetted resources beyond the initial FDE Coach source list.

## What Makes A Resource Worth Including?

A resource should pass at least one of these tests:

- It helps identify a valuable AI workflow.
- It helps reject a bad AI use case.
- It explains an architecture decision an FDE must defend.
- It helps build a deployed or deployment-ready AI workflow.
- It improves evals, observability, safety, or maintainability.
- It helps communicate tradeoffs to executives, security, engineering, or frontline users.

## What This Repo Is Not

- Not a generic AI reading list.
- Not a collection of every agent framework.
- Not a vendor catalog.
- Not a replacement for building projects.

## Contributing

Contributions are welcome. Please read [`CONTRIBUTING.md`](CONTRIBUTING.md) before opening a pull request.

## License

The original writing, playbooks, and templates in this repo are licensed under [CC BY 4.0](LICENSE). Linked resources keep their own licenses and terms. CC BY 4.0 was chosen because this is primarily educational writing and resource curation, not software code.
