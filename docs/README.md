# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management documentation. This README is the entry point to the process docs in this folder and is designed to help teams quickly understand how work moves from idea to delivery. It summarizes our operating model and points to the detailed guidance for each phase, role, and ceremony.

OctoAcme uses a structured, iterative lifecycle that starts with initiation and planning, continues through execution and risk-managed delivery, and ends with release and retrospective follow-through. Teams begin with a one-pager and success metrics, then build prioritized backlog items with acceptance criteria and a clear Definition of Done. During execution, work is tracked in visible workflows and validated through code review, CI checks, and testing before release.

Roles are intentionally clear: Project Managers coordinate planning, dependencies, risk tracking, and stakeholder alignment; Product Managers define outcomes and prioritize value; Developers design, build, and test features; and QA/Testing validates acceptance criteria and release readiness. This role clarity supports faster decisions and shared accountability across cross-functional work.

Communication is continuous and layered through standups, weekly delivery/PM-PdM syncs, demos, milestone or weekly stakeholder updates, and explicit escalation paths. Quality assurance is built into every phase using acceptance criteria, unit/integration/smoke testing, CI/security scanning, deployment checklists, and blameless retrospectives with tracked action items. These docs reflect OctoAcme's core principles—customer-first delivery, iterative progress, data-informed decisions, and continuous improvement.

## Project Lifecycle

1. **Initiation**: define problem statement, stakeholders, outcomes, and a go/no-go path
2. **Planning**: create backlog, acceptance criteria, estimates, dependencies, and release milestones
3. **Execution & Tracking**: deliver in small increments with reviews, CI checks, demos, and ongoing risk updates
4. **Risk & Communication Management**: maintain risk register, status updates, and escalation paths
5. **Release & Deployment**: verify readiness, deploy safely, communicate release status, and prepare rollback
6. **Retrospective & Continuous Improvement**: capture learnings and track process improvements to completion

## Documentation Index

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

## Roles and Responsibilities (Quick View)

- **Project Manager**: plans delivery, manages timelines/risks, and coordinates communication
- **Product Manager**: defines product outcomes, prioritizes backlog, and validates impact
- **Developer**: implements and tests features, contributes to reviews, and flags technical risks
- **QA/Testing**: verifies acceptance criteria, test coverage, and release quality

## Communication and Cadence

- Daily standups for blockers, progress, and dependencies
- Weekly PM/PdM and delivery syncs for status, decisions, and risk review
- Sprint or milestone demos/reviews for stakeholder visibility
- Weekly or milestone-based updates using a shared source of truth
- Escalation path from team triage to PM/Product Lead to sponsor when required

## Quality Assurance Practices

- Acceptance criteria defined during planning and reflected in backlog items/PRs
- Unit, integration, and end-to-end smoke tests based on risk and criticality
- CI validation (tests/lint/security checks) before merge and release
- Release readiness checklist, post-deploy verification, and rollback preparedness
- Blameless retrospectives with owned action items tracked in backlog/issues

## Using These Docs with Copilot Spaces

To help Copilot Spaces provide context-aware project guidance:

1. Start with [Project Management Overview](./octoacme-project-management-overview.md) and this README.
2. Keep your project one-pager/charter, risk register, and release notes updated in your repository.
3. Add these process docs (or relevant excerpts) to your repository’s `.copilot/` context so Copilot can reference them.
4. Reference specific process docs in prompts (for example planning, risk, or release docs) to get role-aware and phase-aware responses.

---

For process updates, propose a docs PR and align changes with OctoAcme principles and retrospective learnings.
