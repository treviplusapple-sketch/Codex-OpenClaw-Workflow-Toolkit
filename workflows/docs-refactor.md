## `workflows/docs-refactor.md`

```md
# Documentation Refactor Workflow

A practical workflow for improving documentation with Codex.

## Goal

Help maintainers make documentation clearer, more consistent, and easier to navigate.

## When to Use

Use this workflow when:

- Documentation is outdated
- Setup steps are unclear
- README is too long
- Several docs repeat the same information
- Users ask the same questions repeatedly
- A feature changed and docs need updates

## Inputs

- Current README
- Existing docs
- User questions
- Issue links
- Changelog
- Project structure

## Workflow

### 1. Audit the Existing Docs

Ask Codex to identify:

- Missing setup steps
- Outdated commands
- Repeated content
- Broken structure
- Unclear terminology
- Missing examples

### 2. Propose a New Structure

Suggested structure:

```text
README.md
docs/
├─ getting-started.md
├─ concepts.md
├─ workflows.md
├─ examples.md
└─ troubleshooting.md
3. Rewrite Carefully

Rules:

Preserve accurate technical details
Do not invent unsupported features
Keep examples simple
Use consistent headings
Add checklists where useful
Separate beginner and advanced content
4. Review

Check:

Can a new user get started?
Are commands copy-paste friendly?
Are assumptions explained?
Are warnings visible?
Are examples realistic?
Prompt
Review and refactor this documentation.

Please provide:
1. Problems in the current structure
2. Suggested new structure
3. Sections that should be rewritten
4. Missing examples
5. A revised draft

Do not invent features that are not documented.
Mark uncertain areas clearly.
Output Template
## Documentation Audit

## Suggested Structure

## Rewrite Plan

## Revised Draft

## Open Questions
