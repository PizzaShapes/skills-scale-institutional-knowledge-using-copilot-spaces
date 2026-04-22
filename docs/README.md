# OctoAcme Project Management Processes

## Purpose

This folder contains the official process documentation for OctoAcme's project management practices. It is intended for Project Managers, Product Managers, Developers, QA engineers, and any stakeholder who needs to understand how OctoAcme plans, executes, releases, and continuously improves its projects.

---

## Overview

OctoAcme follows a structured, lifecycle-based approach to project management that spans five key phases: **Initiation, Planning, Execution, Release, and Close & Retrospective**. Every project begins with a lightweight one-pager that captures the problem statement, SMART goals, success metrics, stakeholders, and a high-level timeline. Work only advances to planning once success metrics are clear, stakeholders are aligned, and team availability is confirmed. Planning then converts the approved initiative into a prioritized backlog with acceptance criteria, T-shirt sizing or story point estimates, a defined Definition of Done (DoD), and a release milestone map — all managed through GitHub Projects.

OctoAcme's team is organized around four core personas: **Project Managers (PM)**, who coordinate schedules, risks, and communications; **Product Managers (PdM)**, who own the product vision and backlog prioritization; **Developers**, who implement and test features; and **QA/Testing**, who validate acceptance criteria. Communication cadences are deliberately structured — daily 15-minute standups for the delivery team, weekly PM/PdM syncs, monthly stakeholder updates, and end-of-sprint demos — so that alignment is maintained across all levels without unnecessary overhead.

Execution is governed by disciplined Pull Request and CI practices: PRs should be small (≤ 400 lines), linked to issues with acceptance criteria, and require at least one approval after passing automated tests, linting, and security scans. Quality is reinforced through unit tests, integration tests, end-to-end smoke tests, and manual QA. Risks and dependencies are tracked in a living **Risk Register** and escalated through a three-level path — from team triage in standups, to PM escalation with Product Lead, up to sponsor-level escalation for business-impacting issues.

Releases are categorized as Patch, Minor, or Major, each requiring passing CI, merged PRs, drafted release notes, smoke tests on staging, and a documented rollback plan before production deployment. After every sprint or milestone, the team runs a **retrospective** structured around what went well, what could improve, and 2–3 prioritized action items — feeding back into the project backlog to create a continuous improvement loop.

---

## Table of Contents

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level summary of OctoAcme's end-to-end project management lifecycle |
| [Project Initiation](octoacme-project-initiation.md) | How new projects are defined, scoped, and approved |
| [Project Planning](octoacme-project-planning.md) | Backlog creation, estimation, Definition of Done, and milestone mapping |
| [Execution and Tracking](octoacme-execution-and-tracking.md) | Sprint ceremonies, PR practices, CI standards, and progress tracking |
| [Risks and Communication](octoacme-risks-and-communication.md) | Risk Register management, escalation paths, and communication cadences |
| [Release and Deployment](octoacme-release-and-deployment.md) | Release categories, deployment checklist, and rollback procedures |
| [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective structure, action item tracking, and improvement loops |
| [Roles and Personas](octoacme-roles-and-personas.md) | Responsibilities and expectations for each team role |
