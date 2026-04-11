---
name: nexusmotion-architecture
description: "Use when architecting the Nexus Motion Blazor app, including rendering model, project structure, state/data flow, dependency boundaries, ADR-style decisions, and architecture handoff to xUnit test design."
---

# Nexus Motion Architecture Skill

## When To Use

- Planning or reviewing feature architecture.
- Choosing rendering, state flow, and dependency patterns.
- Defining architecture constraints for implementation and tests.

## Required Inputs

- Feature scope and non-functional requirements.
- Existing module or project structure.
- Integration and deployment constraints.

## Process

1. Clarify functional and non-functional requirements.
2. Evaluate component/module boundaries.
3. Define data and state flow.
4. Capture constraints and tradeoffs in ADR-style notes.
5. Produce test seam recommendations for xUnit.

## Required Outputs

- Architecture decision summary.
- Data flow and dependency boundary notes.
- Risks and mitigations.
- xUnit handoff artifact: constraints and recommended seams.

## Verification Checklist

- Decisions include rationale and tradeoffs.
- Boundaries are clear enough for implementation.
- Test seams are explicit.
- Risks include fallback options.

## Non-Goals

- Pixel-level UI design decisions.
- Executing full QA test strategy.
