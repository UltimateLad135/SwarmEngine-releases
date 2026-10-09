# Swarm Engine downloads

**Build your team. Start the swarm.**

This repository hosts official Windows x64 installers and update metadata for Swarm Engine, formerly Agent Desk. The development repository is maintained separately.

Download the latest published installer from [Releases](https://github.com/UltimateLad135/agent-desk-releases/releases).

Starting with version 0.1.3, the installed app checks this repository for stable updates, downloads them, and offers **Restart and install** in its tray menu. Version 0.1.2 needs one manual installer upgrade first. Drafts and prereleases are not offered by the stable updater.

Version 0.1.5 introduces the Swarm Engine name. Existing Agent Desk installations use this same update feed. The repository address stays unchanged for compatibility; older releases retain their original names.

Installers are currently unsigned. SHA256SUMS.txt accompanies releases; the updater also verifies the installer checksum from latest.yml.

App data remains separate under `%APPDATA%\Agent Desk\.agent-desk`, preserving existing teams, connections, watches and preferences through the rename. Do not rename that data directory by hand.
