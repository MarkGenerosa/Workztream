<p align="center">
  <img src="logo.png" alt="Workztream" width="120">
</p>

<h1 align="center">Workztream</h1>
<p align="center"><b>A technician-grade Windows maintenance toolkit — 17 tabs and counting.</b></p>

<p align="center">
  <a href="https://workztream.com">Website</a> ·
  <a href="https://github.com/YOUR-USERNAME/workztream/releases/latest">Download</a> ·
  <a href="https://github.com/YOUR-USERNAME/workztream/releases">Release Notes</a>
</p>

---

Workztream wraps SFC, DISM, Chkdsk, network resets, bloatware removal, and the rest of Windows' own repair and maintenance tools into one clean, admin-grade GUI — so you're not hunting through menus and Settings pages to do routine maintenance.

Free. No ads. No telemetry. No paid tier.

## What's in it

17 tabs today, and it keeps growing — every one exists because a real maintenance problem needed it, not a fixed list decided on day one.

- **Prep & Safety** — Restore Point, software inventory, a deterministic 0–100 Health Score, and one-click issue triage
- **Core Cleanup** — SFC, Temp cleanup (quarantined, not deleted outright), Disk Cleanup, Storage Sense, drive optimization
- **System Repair** — DISM RestoreHealth, component store trim, Group Policy refresh
- **Diagnostics & Health** — Battery report, Chkdsk, memory diagnostic, drive SMART status
- **Network** — DNS/IP/ARP refresh, Winsock/TCP-IP resets, saved Wi-Fi password recovery, speed test, connected-device scan
- **Updates & Apps** — Windows Update, service resets, winget, vendor download links
- **Browser & Startup** — Per-browser cache clearing, Startup Apps
- **Control Panel Applets** — One-click shortcuts to the classic admin consoles
- **RegEdit Processes** — USB storage toggle, NTFS long-path support
- **Laptop Drivers** — Vendor links plus a live scan of installed driver versions
- **Virus & Malware Scan** — Defender quick/full/offline scans
- **BitLocker Key** — Recovery password lookup
- **Software Manager** — Bulk uninstall straight from the registry, no more one-by-one
- **Startup Manager** — View and toggle what launches at sign-in
- **History** — Local trend log of disk/RAM/CPU, plus a shortcut into Event Viewer
- **Remote Machines** — Fleet health checks and quick fixes on other machines over PowerShell Remoting
- **Debloating** — Curated, risk-tagged bloatware removal and reversible privacy/telemetry toggles

Full descriptions and screenshots: [workztream.com](https://workztream.com)

## Download

Grab the latest installer from the [Releases page](https://github.com/YOUR-USERNAME/workztream/releases/latest). It's a standard Windows installer (built with Inno Setup) — no signup, no account required.

**Requirements:** Windows 10 or 11, PowerShell 5.1 or later (already installed on any supported Windows machine), Administrator rights (most tabs need elevation, and Workztream prompts for it automatically on launch).

**Windows SmartScreen note:** since this installer isn't yet code-signed, Windows will show "Windows protected your PC" the first time you run it. This is standard for any installer from a publisher SmartScreen doesn't yet recognize — click **More info → Run anyway** to proceed.

## What this repo contains

This repository hosts the [project website](https://workztream.com) and distributes compiled releases. The application source isn't published here at this time.

## Support the project

Workztream is free and stays that way — no paid tier, nothing locked. If it's saved you time, an optional donation is welcome via the [website](https://workztream.com#support).

## Feedback & issues

Found a bug or have a feature idea? Open an [issue](https://github.com/YOUR-USERNAME/workztream/issues) on this repo.

## License

Workztream is free to download and use. See [workztream.com](https://workztream.com) for full details.
