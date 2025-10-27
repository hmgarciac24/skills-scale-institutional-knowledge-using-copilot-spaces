# OctoAcme Project Management Docs

This folder contains OctoAcme's project management process documentation. The goal is to centralize our processes, templates, and checklists so team members can quickly find guidance for initiating, planning, executing, releasing, and improving projects.

OctoAcme follows a lifecycle-based approach with clear phases: Initiation, Planning, Execution, Release, and Close & Retrospective. During Initiation we capture the problem statement, stakeholders, success metrics, and a one‑pager to frame work. Planning breaks work into shippable increments, identifies dependencies and risks, and produces a prioritized backlog with acceptance criteria and a Definition of Done. Execution focuses on small, testable increments, small PRs, CI checks, and regular demos to keep progress visible. Releases are checklist driven with pre-release verification, rollback plans, and post-deploy verification. Continuous improvement is driven through retrospectives and tracked action items.

Roles and responsibilities are explicit: Project Managers coordinate delivery and communications; Product Managers define outcomes and prioritize work; Developers implement, test, and document; QA validates acceptance criteria and quality gates; Stakeholders provide input and approvals. Communication is structured with daily standups, weekly delivery syncs, monthly stakeholder updates, and clear escalation paths for blockers and incidents. Risk management is maintained via a simple risk register that is reviewed at weekly syncs.

Quality is enforced via automated tests (unit, integration, smoke), CI-based security scans, PR review with acceptance criteria, and manual QA for critical flows. Retrospectives capture learnings and convert them into prioritized action items that feed back into the backlog and process docs.

Documentation index
- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)

How to use these docs
- Use this README as the single entry point for OctoAcme project management processes.
- Keep project-specific artifacts (one-pagers, release notes, risk registers) in the project repo under docs/ or .copilot/ for Spaces indexing.
- When proposing changes to process docs, open an issue using .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml and link the change to that issue.
- Keep the README updated when new process docs are added or renamed so links stay accurate.
