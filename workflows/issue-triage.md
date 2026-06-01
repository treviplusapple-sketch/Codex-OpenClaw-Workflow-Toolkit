workflows/issue-triage.md
# Issue Triage Workflow

A practical workflow for using Codex to review, summarize, and classify GitHub issues.

## Goal

Help maintainers quickly understand new issues and decide what to do next.

## When to Use

Use this workflow when:

- A new issue is opened
- Several old issues need cleanup
- Bug reports are unclear
- Feature requests need prioritization
- Maintainers need a quick summary before responding

## Inputs

- Issue title
- Issue body
- Comments
- Related files or logs
- Project roadmap
- Known limitations

## Workflow

### 1. Read the Issue

Ask Codex to identify:

- What the user expected
- What actually happened
- Steps to reproduce
- Environment details
- Error messages
- Missing information

### 2. Classify the Issue

Suggested labels:

- `bug`
- `feature-request`
- `documentation`
- `question`
- `needs-reproduction`
- `needs-more-info`
- `good-first-issue`
- `wontfix`
- `duplicate`

### 3. Summarize the Issue

Use this format:

```md
## Summary

## Impact

## Reproduction Details

## Missing Information

## Suggested Label

## Suggested Response
4. Decide Next Action

Possible actions:

Ask for more information
Link to an existing issue
Create a reproduction task
Add to roadmap
Close as duplicate
Mark as good first issue
Escalate to maintainer review
Prompt
Review this GitHub issue and produce a maintainer-friendly triage summary.

Focus on:
- User intent
- Reproduction steps
- Missing details
- Suggested labels
- Suggested maintainer response

Do not assume information that is not present.
If important details are missing, list them clearly.
Maintainer Checklist

Is the issue understandable?

Can the problem be reproduced?

Is the scope small enough?

Are labels correct?

Is a maintainer response needed?

Should this become a roadmap item?
