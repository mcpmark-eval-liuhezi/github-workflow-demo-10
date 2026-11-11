# Workflow Audit

This page documents how the four pillars of a tidy end-to-end GitHub workflow — **branch**, **pull request**, **issue**, and **close-out** — fit together in a healthy repository.

## Branch

A branch is the unit of isolated work. Developers cut branches from a base (usually `main`) so features don't interleave with the stable line. Naming conventions (e.g., `feature/<name>`) keep intent visible at a glance.

## Pull Request

A pull request is the bridge between branch and main. The author opens it, describes the change, sets context on issues, and asks for review. A PR is where discussion, reviews, and CI checks converge before code lands in the default branch.

## Issue

An issue is the unit of tracked work: tickets, questions, follow-ups, and demos. Every meaningful PR gets a linked issue so the work, its owner, and its close-out are always visible in one place.

## Close-Out

Close-out happens in three steps:

1. **Targeted** — every sub-issue is resolved or re-scoped before a parent is closed.
2. **Linked** — the comment, linked issues, and merged PR are posted on the issue itself.
3. **Closed** — mark the issue as completed so the record is archived without losing lineage.
