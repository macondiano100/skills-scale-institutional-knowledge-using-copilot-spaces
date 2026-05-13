---
name: "Create README for OctoAcme Project Management Docs"
about: "Create a README that provides an overview of OctoAcme project management processes with links to all documentation"
title: "[Process Doc Update]: Create README for OctoAcme Project Management Docs with Process Summary and Links"
labels: ["documentation", "process improvement"]
---

## Which process document do you want to update?
**`<new document>` – README.md (new)**

## Summary of New Content
Create a new `README.md` file in the `docs/` directory that serves as a central hub and entry point for all OctoAcme project management documentation. The README should:

- Provide a clear overview of OctoAcme's project management approach and core principles
- Include a summary of the OctoAcme project lifecycle (Initiation → Planning → Execution → Release → Close & Retrospective)
- List key roles and responsibilities
- Provide organized links to all existing process documents in the `docs/` folder
- Include navigation guidance for different user personas (new team members, project leads, etc.)
- Explain how to use the process documents and where to find specific guidance

## Why is this update needed?

The project management process documents are currently scattered across the `docs/` folder without a centralized entry point. This creates several challenges:

- **Discoverability**: New team members must search through individual files to understand OctoAcme's approach
- **Onboarding friction**: Lack of a unified index increases time to productivity for new teammates
- **Navigation gaps**: No clear guidance on which document to consult for a specific phase or question
- **Knowledge accessibility**: Team members may not know all available processes or best practices
- **Alignment with Copilot Spaces purpose**: A README directly supports the goal of scaling institutional knowledge by creating a searchable, structured knowledge hub

A well-structured README will:
- Serve as the single source of truth for OctoAcme project management
- Accelerate onboarding and reduce single-person dependency risk
- Enable consistent, repeatable project execution
- Improve discoverability and help users quickly find relevant guidance

## Suggested Content

````markdown
# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management Process Library! This directory contains comprehensive guidance for running projects at OctoAcme.

## Quick Start

OctoAcme follows a structured, customer-first approach to project delivery with clear roles, iterative delivery, and data-informed decisions. Whether you're initiating a new project, planning work, executing delivery, managing risks, or capturing learnings—you'll find actionable guidance here.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named leads and clear responsibilities
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## OctoAcme Project Lifecycle

Our projects follow five core phases:

1. **[Initiation](./octoacme-project-initiation.md)** – Validate business need, align stakeholders, decide go/no-go
2. **[Planning](./octoacme-project-planning.md)** – Break work into shippable increments, identify risks and dependencies
3. **[Execution](./octoacme-execution-and-tracking.md)** – Build, test, review, and iterate with daily standups and progress tracking
4. **[Release](./octoacme-release-and-deployment.md)** – Deploy to production with pre-release checks and rollback planning
5. **[Close & Retrospective](./octoacme-retrospective-and-continuous-improvement.md)** – Capture learnings and drive continuous improvement

## Core Roles

- **Project Manager (PM)** – Coordinates delivery, schedules, risks, communications
- **Product Manager (PdM)** – Defines outcomes, prioritizes backlog, measures success
- **Developers** – Implement features, collaborate on design and testability
- **QA/Testing** – Validate quality and acceptance criteria
- **Stakeholders** – Provide inputs, approvals, and guidance

See [OctoAcme Personas](./octoacme-roles-and-personas.md) for detailed role descriptions.

## Process Documentation

### Overview & Reference
- **[Project Management Overview](./octoacme-project-management-overview.md)** – High-level introduction to OctoAcme's approach, key roles, and lifecycle

### By Project Phase

#### Initiation
- **[Project Initiation Guide](./octoacme-project-initiation.md)** – Validate business need, align stakeholders, create lightweight plan

#### Planning
- **[Project Planning](./octoacme-project-planning.md)** – Break work into backlog, estimate scope, identify dependencies, create release plan

#### Execution
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** – Manage day-to-day delivery, run standups, track progress toward milestones

#### Risk & Communication
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** – Identify and manage risks, escalate blockers, communicate status

#### Release
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** – Standardize releases, deployment checklists, rollback procedures

#### Retrospective & Continuous Improvement
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** – Capture learnings, drive improvements, track action items

### Reference
- **[Roles & Personas](./octoacme-roles-and-personas.md)** – Detailed descriptions of typical team roles and responsibilities

## How to Use These Docs

- **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md)
- **Kicking off a project?** Follow the [Initiation Guide](./octoacme-project-initiation.md)
- **In execution phase?** Reference [Execution & Tracking](./octoacme-execution-and-tracking.md)
- **Managing risks?** Check [Risk Management & Communication](./octoacme-risks-and-communication.md)
- **Preparing for release?** See [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- **Ready to retrospect?** Review [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- **Curious about roles?** Explore [Roles & Personas](./octoacme-roles-and-personas.md)

## Key Artifacts

Every OctoAcme project maintains:
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Communication Cadence

- **Weekly sync** between PM + PdM
- **Twice-weekly standups** for delivery team (or as agreed)
- **Monthly stakeholder updates**
- **Ad-hoc escalations** as needed

## Contributing & Feedback

Have suggestions to improve these processes? Use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template to propose updates or new content.

---

*Last updated: 2026-05-13*
````

## Acceptance Criteria
- ✅ Content aligns with existing process docs
- ✅ Update improves clarity or closes a documented gap
- ✅ Proposed content has been reviewed with stakeholders (if needed)
