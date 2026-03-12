# PBS Backup Manager - Releases

This repository hosts the official release artifacts for **PBS Backup Manager**, a Windows backup client for [Proxmox Backup Server](https://www.proxmox.com/en/proxmox-backup-server).

## Download

Download the latest version from the [Releases](../../releases/latest) page.

| File | Description |
|------|-------------|
| `PBSBackupManager.exe` | Main application |
| `checksums.txt` | SHA-256 checksum for verification |

## Current Features

- Disk Image backup (raw partitions / full image style)
- Files & Folders backup
- Incremental deduplicated backups with PBS-compatible FIDX/PXAR output
- Scheduled backups plus manual queueing / `Run All`
- Queue dialog for running and queued jobs
- Built-in self-updater with progress display and cancel option
- Recovery after lost PBS connectivity with automatic cleanup retry
- Pause / Resume / Stop backup controls
- File restore with NTFS browser
- Proxmox Backup Server compatible (FIDX/PXAR format)

## Installation

1. Download `PBSBackupManager.exe`
2. Run it - no installer required
3. Configure your PBS server under **Settings -> Servers**

## Updates

The app can check for updates automatically on startup and can self-update via **Settings -> Updates**.

## Current Focus / TODO

- Backup verify workflow and verification status in the UI
- Health checks before starting a run
- Restore validation mode
- Bandwidth throttling
- Per-job retention / prune helper
- Optional NTFS ACL backup / restore
