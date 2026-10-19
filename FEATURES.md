# Built-in features for curious-cubs-os

Purpose: kids creative learning

1. **prepare study and research files** — run curious-cubs-os-workspace. It creates ~/Documents/curious-cubs-os-workspace/ with Notes, Sources, Assignments folders.
2. **plan a learning session** — run curious-cubs-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/curious-cubs-os-session-plans/.
3. **check study and source readiness** — run curious-cubs-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/curious-cubs-os-workspace features/curious-cubs-os-plan features/curious-cubs-os-check "$HOME/.local/bin/"
