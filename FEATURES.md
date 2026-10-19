# Built-in features for pyra-os

Purpose: Python development

1. **organize project files** — run pyra-os-workspace. It creates ~/Documents/pyra-os-workspace/ with Inbox, Projects, Archive folders.
2. **draft a session plan** — run pyra-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/pyra-os-session-plans/.
3. **check task readiness** — run pyra-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/pyra-os-workspace features/pyra-os-plan features/pyra-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for Python development:

1. **Thonny** — org.thonny.Thonny
2. **DB Browser for SQLite** — org.sqlitebrowser.sqlitebrowser
3. **QGIS** — org.qgis.qgis

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.
