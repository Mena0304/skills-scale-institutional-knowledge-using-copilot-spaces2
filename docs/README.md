# OctoAcme Project Management Docs

This README consolidates links to OctoAcme's process documentation and provides a brief summary of the project management processes used across projects.

Overview

OctoAcme runs projects with a customer-first, iterative approach documented in docs/. Work starts with a lightweight initiation step (a Project One-pager that clarifies the problem, SMART goals, success metrics, stakeholders, and a high-level timeline) and progresses through planning, execution, release, and retrospective stages. Core artifacts—project one-pagers, a prioritized backlog, Definition of Done, release plans, and a risk register—act as the single source of truth for decisions and status.

Planning and execution emphasize small, shippable increments. Planning breaks approved initiatives into backlog items with acceptance criteria, estimates, and owners; sprint planning pulls items that meet the Definition of Done. Execution uses a project board with clear columns (Backlog → Ready → In Progress → In Review → QA → Done). Pull requests should be small and reviewable, include the linked issue and acceptance criteria, and pass automated CI checks (tests, linting, security scans) before review.

Roles & communication

Roles and responsibilities are explicit: Product Managers define outcomes and prioritize the backlog; Project Managers coordinate delivery, timelines, risks, and stakeholder communications; Developers build and test features; QA validates acceptance criteria and test plans. Communication is structured to maintain alignment: daily standups for short-cycle coordination, weekly PM–PdM syncs, regular demos/reviews, and monthly stakeholder updates. Risks are tracked in a Risk Register with clear escalation paths (team → PM → Product Lead → Sponsor).

Quality Assurance & continuous improvement

Quality is enforced through automated and manual testing: unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, and CI security scanning. Manual QA is used for feature acceptance when required. After milestones and releases, timeboxed retrospectives capture learnings and convert them into prioritized action items that feed back into the backlog for continuous improvement.

Process documents

- docs/octoacme-project-management-overview.md — Overview, principles, roles, artifacts, and lifecycle
- docs/octoacme-project-initiation.md — Project initiation guide and one-pager template
- docs/octoacme-project-planning.md — Planning activities, backlog template, and checklists
- docs/octoacme-execution-and-tracking.md — Team rhythm, workflows, QA, and escalation
- docs/octoacme-release-and-deployment.md — Release types, deployment checklist, and playbook
- docs/octoacme-risks-and-communication.md — Risk register guidance and communication templates
- docs/octoacme-retrospective-and-continuous-improvement.md — Retrospective structure and action tracking
- docs/octoacme-roles-and-personas.md — Role definitions and responsibilities

How to use

- Keep this README in docs/ as the single entrypoint for OctoAcme process documentation.
- Link to this README from the repo root or project READMEs to improve discoverability.
- When proposing updates, use the Add Content to Project Management Process Docs issue template in .github/ISSUE_TEMPLATE/.

