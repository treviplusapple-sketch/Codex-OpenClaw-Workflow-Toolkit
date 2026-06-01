## `workflows/pr-review.md`

```md
# Pull Request Review Workflow

A practical workflow for using Codex to assist with pull request review.

## Goal

Help maintainers review pull requests more consistently without replacing human judgment.

## When to Use

Use this workflow when:

- A pull request changes multiple files
- The purpose of a change is unclear
- Tests need review
- Documentation may need updates
- The maintainer wants a risk summary

## Inputs

- Pull request title
- Pull request description
- Changed files
- Diff
- Test results
- Related issues
- Project guidelines

## Workflow

### 1. Summarize the PR

Ask Codex to explain:

- What changed
- Why it changed
- Which files were affected
- Whether the change matches the PR description

### 2. Identify Risk Areas

Look for:

- Breaking changes
- Missing tests
- Unclear behavior changes
- Large unrelated edits
- Security-sensitive code
- Performance-sensitive code
- Documentation drift

### 3. Review Tests

Check:

- Are tests included?
- Do tests match the behavior change?
- Are edge cases covered?
- Are snapshots or fixtures updated intentionally?

### 4. Draft Review Comments

Comments should be:

- Specific
- Respectful
- Actionable
- Minimal
- Linked to the changed behavior

## Prompt

```text
Review this pull request as a maintainer assistant.

Please provide:
1. Summary of changes
2. Files with the highest review priority
3. Possible risks
4. Missing tests or documentation
5. Suggested review comments
6. Final recommendation: approve, request changes, or ask for clarification

Do not invent project rules.
If something is uncertain, mark it as uncertain.
Review Output Format
## PR Summary

## Main Files Changed

## Risk Assessment

## Test Coverage

## Documentation Impact

## Suggested Comments

## Recommendation
Human Review Reminder

Codex can assist review, but maintainers should make the final decision.
