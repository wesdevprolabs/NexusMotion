---
name: nexusmotion-xunit
description: "Use when designing or implementing xUnit tests for Nexus Motion, including test case design, fixture strategy, mocking patterns, deterministic unit/integration tests, and coverage handoff back to QA."
---

# Nexus Motion xUnit Skill

## When To Use

- Designing xUnit test cases and suites.
- Implementing maintainable unit and integration tests.
- Mapping implemented coverage and known test gaps.

## Required Inputs

- Feature behavior and acceptance criteria.
- Architecture constraints and test seam recommendations.
- QA prioritized scenarios.

## Process

1. Derive test cases from behavior and risk.
2. Define fixture strategy and test data setup.
3. Choose mocking/fake boundaries for determinism.
4. Implement or outline unit and integration tests.
5. Return coverage map and known gaps to QA.

## Required Outputs

- Test case inventory.
- Fixture and mocking approach.
- Unit/integration scope split.
- Coverage map.
- Known gaps and follow-up recommendations.

## Verification Checklist

- Naming and Arrange-Act-Assert flow are consistent.
- Tests are deterministic and isolated.
- Edge and failure cases are covered.
- Coverage handoff to QA is explicit.

## Non-Goals

- Reworking product architecture.
- Defining final release-go/no-go policy.
