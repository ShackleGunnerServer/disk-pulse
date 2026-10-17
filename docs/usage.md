# Usage Guide — disk-pulse

## Main Window

The dashboard shows live status and the primary action. *(Screenshot:
`assets/screenshots/main.png`)*

## Core Workflow

1. Launch disk-pulse
2. Configure options in the Settings tab
3. Use the main action (or global hotkey)
4. Status icon turns green when active

## Global Hotkeys (defaults, editable)

| Hotkey | Action |
|---|---|
| `Ctrl + Alt + X` | Toggle disk-pulse on/off |
| `Ctrl + Alt + S` | Open settings |
| `Shift + F9` | Panic key — restore defaults instantly |

## Profiles

Create per-scenario profiles in the Profiles tab, save to
`%APPDATA%\disk-pulse\profiles\`, share as files. Community presets live in
[`data/profiles/`](../data/profiles/).

## CLI Mode

```powershell
disk-pulse.exe --help        # all commands
disk-pulse.exe --version
```

All GUI actions are available as CLI flags for scripting and automation.
