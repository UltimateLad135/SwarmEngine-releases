# Agent Desk downloads

This repository hosts official Windows x64 installers and update metadata for Agent Desk. The development repository is maintained separately.

Download the latest published installer from [Releases](https://github.com/UltimateLad135/agent-desk-releases/releases).

Starting with version 0.1.3, the installed app checks this repository for stable updates, downloads them, and offers **Restart and install** in its tray menu. Version 0.1.2 needs one manual installer upgrade first. Drafts and prereleases are not offered by the stable updater.

Installers are currently unsigned. SHA256SUMS.txt accompanies releases; the updater also verifies the installer checksum from latest.yml.

App data is stored separately under `%APPDATA%\Agent Desk\.agent-desk` and is preserved during upgrades.