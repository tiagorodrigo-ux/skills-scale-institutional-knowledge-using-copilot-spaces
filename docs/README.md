# OctoAcme Project Management Overview

OctoAcme follows a lightweight, iterative project management approach structured around a clear lifecycle: Initiation, Planning, Execution, Release, and Retrospective. Initiation begins with a Project One-pager capturing the problem, goals, success metrics, stakeholders, and a high-level timeline. Planning converts approved initiatives into a prioritized backlog with acceptance criteria, estimates, a Definition of Done, and a milestone-based release plan.

Execution uses a project board with columns like Backlog → Ready → In Progress → In Review → QA → Done and favors small, reviewable pull requests to preserve fast feedback loops. Team rhythm includes daily standups, weekly delivery syncs, demo/review sessions at the end of sprints or milestones, and a structured blocker escalation path from team-level triage up to sponsor-level escalation for business-impacting issues.

Roles are explicit: a named Project Manager coordinates delivery, schedules, risks, and communications; Product Managers own outcomes and prioritization; Developers implement and test; QA validates acceptance and quality; stakeholders provide approvals and inputs. Responsibilities and artifacts (one-pager, risk register, acceptance criteria, release notes) clarify ownership and decision gates across the lifecycle.

Quality assurance and release controls are enforced through CI-based automated tests and security scanning, testing guidance (unit, integration, end-to-end smoke tests), PR requirements (linked issue, acceptance criteria in PR description, at least one approval), and pre-release checks (passing CI, drafted release notes, rollback plan). Releases follow a staged verification and post-deploy verification process, followed by a blameless retrospective to capture improvements.

## Process Documents

- [octoacme-project-management-overview.md](./octoacme-project-management-overview.md)
- [octoacme-project-initiation.md](./octoacme-project-initiation.md)
- [octoacme-project-planning.md](./octoacme-project-planning.md)
- [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md)
- [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md)
- [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md)
- [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md)
- [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md)
