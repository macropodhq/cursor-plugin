# BugHerd Agent Plugin

Official BugHerd MCP server. Sign in with OAuth to create and manage visual feedback from Cursor.

## Overview

This plugin connects Cursor to BugHerd through its hosted MCP server, and includes BugHerd's agent skills, which teach Cursor how to create, read, triage, fix and report on BugHerd feedback.

## Skills

| Skill | Helps Cursor |
|---|---|
| `bugherd-basics` | Find the right project, and understand websites, design assets, members, clients and share links |
| `bugherd-reading-tasks` | Understand a task: the issue, the page, the element, the screenshot and attachments |
| `bugherd-creating-feedback` | Create feedback from reviews and checklists, including pinned feedback with screenshots |
| `bugherd-triage` | Review and organise feedback: statuses, assignees, tags, and flagging what needs a person |
| `bugherd-fix-with-review` | Take feedback through to a code fix, with you approving each step |
| `bugherd-reporting` | Summarise activity for standups and client meetings |

The skills are copied from [macropodhq/bugherd-mcp](https://github.com/macropodhq/bugherd-mcp/tree/main/skills).

## Installation

1. Open **Customize** in Cursor's sidebar.
2. Find **BugHerd** in the marketplace.
3. Select **Install** and choose project or user scope.
4. Connect BugHerd and complete the OAuth sign-in.

Once connected, ask Cursor to create and manage visual feedback in BugHerd.

## Support

- **BugHerd MCP:** https://bugherd.com/feature/mcp
- **Report Issues:** https://github.com/macropodhq/cursor-plugin/issues
