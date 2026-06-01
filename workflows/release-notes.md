## `workflows/release-notes.md`

```md
# Release Notes Workflow

A practical workflow for drafting release notes from merged changes.

## Goal

Help maintainers turn commits, pull requests, and issue references into clear release notes.

## When to Use

Use this workflow before publishing a new version.

## Inputs

- Merged pull requests
- Commit messages
- Closed issues
- Breaking changes
- Migration notes
- Contributor names
- Version number

## Release Note Categories

Suggested sections:

- Highlights
- Added
- Changed
- Fixed
- Deprecated
- Removed
- Security
- Documentation
- Internal
- Migration Notes
- Contributors

## Workflow

### 1. Collect Changes

Gather:

- PR titles
- PR descriptions
- Commit summaries
- Related issue numbers
- Labels
- Test notes

### 2. Group Changes

Group changes by user impact:

- User-facing changes
- Developer-facing changes
- Documentation changes
- Internal maintenance
- Breaking changes

### 3. Draft Notes

Use clear language:

- Say what changed
- Explain why users should care
- Avoid internal-only jargon
- Mention migration steps when needed

### 4. Review Before Publishing

Check:

- Version number is correct
- Breaking changes are obvious
- Security fixes are handled carefully
- Contributors are credited
- Links are correct
- No private information is included

## Prompt

```text
Draft release notes from the following merged changes.

Please group the changes into:
- Highlights
- Added
- Changed
- Fixed
- Documentation
- Internal
- Migration Notes
- Contributors

Write for users and maintainers.
Do not exaggerate the impact.
Mark uncertain items clearly.
Output Template
# Release vX.Y.Z

## Highlights

## Added

## Changed

## Fixed

## Documentation

## Internal

## Migration Notes

## Contributors
