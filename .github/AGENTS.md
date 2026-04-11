# Nexus Motion Specialist Agents

This repository uses a role-based expert agent model for Blazor development.

## Orchestrators

- `windows.nexusmotion`: Windows entry point and specialist router.
- `linux.nexusmotion`: Linux entry point and specialist router.

## Specialist Agents

- `nexusmotion-uiux-expert`: UI/UX behavior, responsive design, accessibility, acceptance criteria.
- `nexusmotion-architecture-expert`: Blazor architecture, boundaries, rendering and data flow decisions.
- `nexusmotion-qa-testing-expert`: QA strategy, risk matrix, regression scope, prioritized scenarios.
- `nexusmotion-xunit-expert`: xUnit test design and implementation strategy, fixtures, mocking, coverage map.

## Shared Skills

- `.github/skills/nexusmotion-uiux/SKILL.md`
- `.github/skills/nexusmotion-architecture/SKILL.md`
- `.github/skills/nexusmotion-qa-testing/SKILL.md`
- `.github/skills/nexusmotion-xunit/SKILL.md`

## Required Handoff Flow

1. UI/UX -> QA: acceptance criteria and accessibility checklist.
2. Architecture -> xUnit: architecture constraints and test seam guidance.
3. QA -> xUnit: prioritized scenarios and regression focus.
4. xUnit -> QA: coverage map and known gaps.

## Minimum Output Contract

Each specialist output should include:

- assumptions
- proposed output artifact(s)
- verification checklist
- unresolved risks
