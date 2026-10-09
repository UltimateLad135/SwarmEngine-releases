# Swarm Engine downloads

**Build your team. Start the swarm.**

This repository hosts official Windows x64 installers and update metadata for Swarm Engine, formerly Agent Desk. The development repository is maintained separately.

Download the latest published installer from [Releases](https://github.com/UltimateLad135/SwarmEngine-releases/releases).

Starting with version 0.1.3, the installed app checks for stable updates, downloads them, and offers **Restart and install** in its tray menu. Version 0.1.2 needs one manual installer upgrade first. Drafts and prereleases are not offered by the stable updater.

Version 0.1.5 introduced the Swarm Engine name. Version 0.1.6 completes repository references and project-name recognition, corrects the tray version label, and supports the Swarm Engine data-folder location. New packages use this repository's canonical SwarmEngine-releases address; older installed update feeds continue working through the former agent-desk-releases redirect. Older releases retain their original names.

Installers are currently unsigned. SHA256SUMS.txt accompanies releases; the updater also verifies the installer checksum from latest.yml.

App data stays outside the installed program. New or explicitly migrated installations use `%APPDATA%\Swarm Engine\.agent-desk`. Existing legacy-only `%APPDATA%\Agent Desk\.agent-desk` stores are preserved until an explicit offline migration; the app does not move or merge them automatically. If both stores exist, select the intended one with `AGENT_DESK_DATA_DIR`. Back up the entire private store and stop the app before any folder migration. Saved teams, connections, watches, preferences and Chromium state must remain together.
