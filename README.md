# PBS Backup Manager — Releases

This repository hosts official releases of **PBS Backup Manager**, a Windows backup client for [Proxmox Backup Server](https://www.proxmox.com/en/proxmox-backup-server).

## Download

Download the latest version from the [Releases](../../releases/latest) page.

| File | Description |
|------|-------------|
| `PBSBackupManager.exe` | Main application |
| `checksums.txt` | SHA-256 checksum for verification |

## Features

- Full PC backup (raw partitions + NTFS file tree)
- Incremental backups with deduplication
- File restore with NTFS browser
- Scheduled backups with cron expressions
- Built-in auto-updater
- Pause / Resume backup
- Proxmox Backup Server compatible (FIDX/PXAR format)

## Installation

1. Download `PBSBackupManager.exe`
2. Run it — no installer required
3. Configure your PBS server under **Settings → Servers**

## Updates

The app checks for updates automatically on startup and can self-update via **Settings → Updates**.
