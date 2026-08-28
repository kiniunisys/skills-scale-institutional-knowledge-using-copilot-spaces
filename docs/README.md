# OctoAcme Project Management Documentation

## Overview
OctoAcme follows a structured, customer‑first project management approach that emphasizes iterative delivery, clear ownership, and data‑informed decisions. Projects move through Initiation, Planning, Execution, Release, and Retrospective stages, and the team uses lightweight artifacts (Project One‑pagers, backlogs, acceptance criteria, and a Risk Register) to keep work measurable and traceable.

OctoAcme stages work to reduce risk and increase feedback frequency. Initiation validates the business need and success metrics; Planning breaks approved initiatives into shippable increments with estimates and a Definition of Done; Execution uses sprint backlogs, small PRs, CI checks, and QA to maintain quality; Release follows a pre‑release checklist (staging smoke tests, rollback plan, release notes); Retrospectives capture action items and drive continuous improvement.

Roles and ownership are explicit: Product Managers define outcomes and success metrics, Project Managers coordinate delivery and communication, Developers implement and test features, and QA validates acceptance criteria. Communication is rhythmic (daily standups, weekly delivery syncs, sprint demos, and monthly stakeholder updates) with a tiered blocker escalation path that scales from team triage to sponsor‑level intervention for business‑impacting issues.

Quality assurance combines automated and manual practices: unit and integration tests, end‑to‑end smoke tests for critical flows, security scanning in CI, and a PR workflow that requires small, documented changes with acceptance criteria and at least one approval before merging. Dashboards (velocity, burndown, errors, latency, usage) and the Risk Register make project health and trade‑offs visible.

## Documentation Index
- [Project Management Overview](./octoacme-project-management-overview.md) - High‑level framework, principles, and lifecycle
- [Project Initiation](./octoacme-project-initiation.md) - How to validate ideas and create a project one‑pager
- [Project Planning](./octoacme-project-planning.md) - Backlog formation, estimation, release planning, and DoD
- [Execution & Tracking](./octoacme-execution-and-tracking.md) - Day‑to‑day workflows, PR conventions, CI expectations, and metrics
- [Risks & Communication](./octoacme-risks-and-communication.md) - Risk register, escalation paths, and stakeholder comms
- [Release & Deployment](./octoacme-release-and-deployment.md) - Release types, pre‑release checks, deployment checklist, and rollback playbook
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) - Post‑release reviews and action items
- [Roles & Personas](./octoacme-roles-and-personas.md) - Role definitions and typical responsibilities

## Quick Reference — which doc to use
- Starting a new idea or validating business need: Project Initiation
- Turning an approved initiative into a backlog and timeline: Project Planning
- Day‑to‑day delivery, PRs, and QA: Execution & Tracking
- Managing cross‑team risks and stakeholder updates: Risks & Communication
- Preparing for and executing a release: Release & Deployment
- Running retrospectives and tracking improvements: Retrospective & Continuous Improvement
- Role expectations and persona prompts for exercises: Roles & Personas
- High‑level principles and lifecycle summary: Project Management Overview

## Getting started
1. Create or update the Project One‑pager for your initiative (see Project Initiation).
2. Add initial artifacts into the project repository under docs/ or .copilot/ so Copilot Spaces can use them as context.
3. Use the Backlog template and Definition of Done from Project Planning before pulling work into a sprint.

## Contribution & Maintenance
- Keep links and filenames up to date when adding new process docs.
- Small edits that improve clarity can be made via PR; substantial process changes should be reviewed with PM and Product Lead.

## Acceptance Checklist
- [x] Content aligns with existing process docs
- [x] Improves discoverability and provides a clear entry point
- [ ] Proposed content reviewed with stakeholders (optional — proceed if you'd like a review step)

---

If you'd like, I can open a PR for this README now, or I can update it based on stakeholder feedback first.