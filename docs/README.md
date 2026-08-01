# OctoAcme Project Management Docs

This folder contains OctoAcme's program and project management process documents. Use these docs as the single source of truth for how our teams initiate, plan, execute, and improve projects.

## Documents
- octoacme-project-management-overview.md
- octoacme-project-initiation.md
- octoacme-project-planning.md
- octoacme-execution-and-tracking.md
- octoacme-risks-and-communication.md
- octoacme-release-and-deployment.md
- octoacme-retrospective-and-continuous-improvement.md
- octoacme-roles-and-personas.md

## Summary
OctoAcme follows an iterative, outcome-focused lifecycle: Initiation → Planning → Execution → Release → Close. New initiatives begin with a lightweight Project One‑pager that clarifies the problem, objective, success metrics, stakeholders, and a high‑level timeline. Planning breaks approved work into shippable increments, captures acceptance criteria and Definition of Done, and records dependencies and risks to guide execution.

Work is tracked on a project board (Backlog → Ready → In Progress → In Review → QA → Done) and delivered via small, reviewable pull requests. Backlog items include clear acceptance criteria, owner, estimate, and priority. The pull request workflow expects automated checks (unit/integration tests, linting, security scans) and at least one approval before merge; releases require pre‑release checks, release notes, staging smoke tests, and rollback plans.

Roles and responsibilities are explicit: Product Managers define outcomes and prioritize the backlog; Project Managers coordinate delivery, schedules, and stakeholder communications; Developers implement features and own tests and docs; QA validates acceptance criteria and runs integration/E2E checks. Communication cadence includes daily standups for blockers, weekly delivery syncs for progress and risks, and demos at the end of each sprint or milestone. Risk management and a simple register ensure issues are assessed, mitigated, and escalated when necessary.

## How to use
- Read the Project Management Overview to understand principles and key artifacts.
- For new projects, start with the Project Initiation guide and the Project One‑pager template.
- Follow the Planning and Execution guides for backlog, PR, and release practices.
- Use the Roles & Personas doc to clarify handoffs and responsibilities.
