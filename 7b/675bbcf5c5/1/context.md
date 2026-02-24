# Session Context

## User Prompts

### Prompt 1

Implement the following plan:

# Plan: Add Login with Fixed Credentials

## Context

The BandWacht web UI is currently completely open — no authentication. Add a single fixed login (username `oe8yml`, random hard password) to protect the tool. No user DB table needed — credentials checked against bcrypt hash, JWT token issued on login.

## Password

`Kx8$mQ2vL#nR7wYp`

## Changes

### 1. `web/backend/requirements.txt` — add auth packages

```
passlib[bcrypt]>=1.7.4
python-jose[cryptography...

### Prompt 2

commit this and deploy. also check, why the telegram notification is not working any more

