---
description: "Workspace-wide guidance for Nexus Motion Blazor development and specialist agent collaboration."
applyTo: "**"
---

# Nexus Motion Agent Baseline

These instructions define shared behavior for all specialist agents in this repository.

## Product and Stack

- Product: Nexus Motion fitness web app.
- UI stack: Blazor components and CSS.
- Testing stack: xUnit and integration-style test strategy where applicable.

## Required Collaboration Model

- Route work to a specialist role when the request is role-specific.
- Use explicit handoff artifacts between roles.
- Keep outputs concise, implementation-ready, and traceable to acceptance criteria.

## Specialist Role Boundaries

- UI/UX role: component layout, responsive design behavior, accessibility criteria, and interaction patterns.
- Architecture role: rendering model, project structure, data flow, dependency boundaries, and ADR-style decisions.
- QA role: acceptance criteria quality, risk matrix, regression strategy, and validation scenarios.
- xUnit role: test case design, fixture strategy, mocking patterns, and maintainable test implementation guidance.

## Required Handoff Artifacts

- UI/UX to QA: acceptance criteria and accessibility checklist.
- Architecture to xUnit: architecture constraints and test seam recommendations.
- QA to xUnit: prioritized scenarios and regression focus areas.
- xUnit to QA: implemented coverage map and known gaps.

## Quality and Testing Baseline

- Follow balanced rigor: unit + integration + regression baseline.
- Prefer deterministic tests over brittle timing-based tests.
- Include edge cases and error handling in all plans and implementations.

## Output Standard

- Provide assumptions when requirements are missing.
- Include a short verification checklist in deliverables.
- Call out unresolved risks explicitly.
