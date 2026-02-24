# Session Context

## User Prompts

### Prompt 1

Implement the following plan:

# Plan: Move Notification Settings from Web UI to Environment Variables

## Context

Notification secrets (Telegram bot tokens, Gotify tokens, etc.) are currently stored in SQLite and editable via the web UI. This is a security concern — secrets belong in environment variables, not in a database exposed through a web interface. The change moves all notification configuration to `BANDWACHT_*` environment variables and replaces the full CRUD UI with a read-only sta...

### Prompt 2

commit this deploy

### Prompt 3

add login to the tool. fix username and password. user oe8yml... password random hard

### Prompt 4

[Request interrupted by user for tool use]

