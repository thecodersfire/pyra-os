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

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for Python development:

1. **Godot Engine** — build and test 2D and 3D games (org.godotengine.Godot)
2. **Wireshark** — inspect network traffic (org.wireshark.Wireshark)
3. **OpenSCAD** — model parametric 3D parts in code (org.openscad.OpenSCAD)
4. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
5. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
6. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
7. **GNOME Logs** — inspect logs during troubleshooting (org.gnome.Logs)
8. **Disk Usage Analyzer** — find large files and manage storage (org.gnome.baobab)
9. **Flatseal** — review Flatpak app permissions (com.github.tchx84.Flatseal)
10. **GNOME Extensions** — manage GNOME desktop extensions (org.gnome.Extensions)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
