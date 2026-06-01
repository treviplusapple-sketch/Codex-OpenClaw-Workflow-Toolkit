## `prompts/automation-planning-template.md`

```md
# Automation Planning Template

A reusable prompt template for planning small automation workflows safely and clearly.

## Purpose

This template helps users turn repetitive tasks into structured automation plans.

It is designed for:

- Notification workflows
- Scheduled checks
- Document processing
- Local scripts
- Maintainer workflows
- Personal productivity systems

## Template

```text
I want to automate a recurring task.

Task description:
[Describe the task.]

Trigger:
[When should it run? Example: every day, when a file changes, when a new issue appears.]

Input:
[What data, file, page, message, or event does it read?]

Output:
[What should it produce? Example: alert, summary, file, issue comment.]

Environment:
[Local computer, server, GitHub Actions, OpenClaw, Codex, Obsidian, etc.]

Constraints:
[List privacy, security, permission, rate limits, or reliability constraints.]

Please produce:

1. Workflow overview
2. Required components
3. Data flow
4. Failure cases
5. Safe implementation plan
6. Logging strategy
7. Testing checklist
8. Future improvements
Safety Checklist

Before building an automation, confirm:

The user has permission to access the data.
The workflow does not bypass security controls.
Sensitive data is not logged unnecessarily.
The automation respects rate limits.
Alerts are useful and not spammy.
Failures are visible and recoverable.
Example Output Structure
# Automation Plan

## Goal

## Trigger

## Inputs

## Outputs

## Components

## Step-by-Step Flow

## Error Handling

## Logging

## Test Plan

## Future Improvements
