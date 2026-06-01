## `examples/openclaw-config-notes.md`

```md
# OpenClaw Configuration Notes

This file collects notes for organizing OpenClaw-related workflows.

## Purpose

The goal is to document practical setup patterns for using OpenClaw with Codex-based maintainer workflows.

## Example Use Cases

- Running a documentation cleanup task
- Summarizing repository changes
- Preparing issue triage notes
- Drafting release notes
- Organizing local automation tasks

## Suggested Workspace Structure

```text
workspace/
├─ tasks/
├─ notes/
├─ outputs/
└─ logs/
Configuration Principles
Keep task instructions explicit.
Keep outputs reviewable.
Avoid storing secrets in plain text.
Separate local notes from public repository files.
Log important decisions.
Prefer small tasks over large vague tasks.
Example Task Format
Task:
Review workflows/pr-review.md and suggest improvements.

Context:
This repository provides maintainer workflow templates.

Output:
Return a concise list of suggested edits and a revised section if needed.
Future Work
Add real OpenClaw configuration examples
Add sample task files
Add troubleshooting notes
Add security and privacy guidance
