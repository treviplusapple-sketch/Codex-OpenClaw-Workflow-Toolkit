prompts/codex-task-template.md
# Codex Task Template

A reusable template for turning maintenance tasks into clear Codex instructions.

## Purpose

This template helps maintainers describe a task in a structured way so Codex can work with less ambiguity.

It is designed for:

- Small bug fixes
- Documentation edits
- Refactoring tasks
- Test updates
- Repository cleanup
- Release preparation

## Template

```text
# Task

Describe the exact task Codex should complete.

# Context

Explain the repository, related files, current behavior, and any important constraints.

# Files to Inspect

List files, directories, or patterns Codex should review first.

# Instructions

1. Read the relevant files.
2. Identify the minimum safe change.
3. Make the change.
4. Update or add tests if needed.
5. Summarize the change clearly.

# Constraints

- Do not rewrite unrelated code.
- Preserve the existing style.
- Avoid large architectural changes unless requested.
- Explain any uncertainty before making assumptions.

# Expected Output

Provide:
- A short summary of changes
- Files modified
- Tests added or updated
- Any follow-up work
Example
# Task

Update the release notes workflow documentation to include a checklist for maintainers.

# Context

This repository provides Codex/OpenClaw workflow templates for maintainers. The release notes guide currently explains the purpose but does not include a concrete checklist.

# Files to Inspect

- workflows/release-notes.md
- docs/roadmap.md

# Instructions

Add a practical checklist that maintainers can follow before publishing a release.

# Constraints

Keep the document concise and beginner-friendly.

# Expected Output

Summarize the documentation changes and mention any sections added.
