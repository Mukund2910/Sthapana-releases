<h1 align="center">Sthapana</h1>

<p align="center">
  <em>Offline Windows costing for civil works — spreadsheet-grade accuracy, without the spreadsheet</em>
</p>

<p align="center">
  <img src="https://img.shields.io/github/v/release/Mukund2910/Sthapana-releases?label=latest%20release&color=2ea44f" alt="Latest release" />
  <img src="https://img.shields.io/badge/platform-Windows%20x64-0078D6?logo=windows&logoColor=white" alt="Windows" />
  <img src="https://img.shields.io/badge/built%20with-Tauri%202-24C8DB?logo=tauri&logoColor=white" alt="Tauri 2" />
  <img src="https://img.shields.io/badge/auto--update-enabled-2ea44f" alt="Auto-update enabled" />
  <img src="https://img.shields.io/badge/license-proprietary-lightgrey" alt="License" />
</p>

---

**Sthapana** is an offline Windows desktop application for civil-works cost estimation. It reproduces a master costing workbook with full calculation parity, so you can build and price civil construction estimates with spreadsheet-grade accuracy — without the spreadsheet, and without an internet connection.

This repository is the official **distribution channel** for Sthapana. It hosts the signed Windows installer and the update manifest the application uses to keep itself current. It does not contain application source code.

## Contents

- [About](#about)
- [Download & Install](#download--install)
- [System Requirements](#system-requirements)
- [Automatic Updates](#automatic-updates)
- [What's In A Release](#whats-in-a-release)
- [Verifying Downloads](#verifying-downloads)
- [Support](#support)
- [License](#license)

---

## About

Sthapana turns a master civil-works costing workbook into a fast, offline desktop tool. Every calculation matches the source workbook to the rupee, so estimates you produce in Sthapana line up with the trusted spreadsheet they're based on — but without manual cell-wrangling, broken formulas, or version-juggling.

Because it runs fully offline, your cost data never leaves your machine. The only time Sthapana reaches the network is to check this repository for a newer version.

---

## Download & Install

1. Open the [**latest release**](https://github.com/Mukund2910/Sthapana-releases/releases/latest).
2. Download **`Sthapana_<version>_x64-setup.exe`**.
3. Run the installer. Sthapana installs for the current user — **no administrator rights required**.
4. Launch **Sthapana** from the Start menu.

That's the only manual download you'll ever need. From here on, the app keeps itself up to date.

---

## System Requirements

| Requirement | Detail |
|-------------|--------|
| Operating system | Windows 10 or Windows 11 (64-bit) |
| Permissions | None — installs per-user, no admin rights |
| Internet | Only to check for and download updates; not needed to use the app |
| Disk space | A few hundred MB free |

---

## Automatic Updates

Sthapana checks for a new version **every time it starts**. When one is available, it prompts you to update; accepting downloads the new version, installs it, and relaunches the app — no reinstall, no manual download.

Updates are **cryptographically signed and verified** before they're applied, so the app will only ever update itself from a genuine, untampered release.

---

## What's In A Release

Each release published here contains:

| File | Purpose |
|------|---------|
| `Sthapana_<version>_x64-setup.exe` | The Windows installer |
| `Sthapana_<version>_x64-setup.exe.sig` | Signature used to verify the update |
| `latest.json` | Update manifest read by the in-app updater |

Browse the [**release history**](https://github.com/Mukund2910/Sthapana-releases/releases) to see every published version.

---

## Verifying Downloads

Every installer is published alongside a `.sig` signature, and Sthapana verifies that signature against a built-in public key before applying any update. For normal use you don't need to check anything by hand — verification is automatic, and an update that fails the check is refused.

---

## Support

For access requests, questions, or to report a problem, contact **<your-email@example.com>**.

> When reporting an issue, please include your Sthapana version (shown in the app) and a short description of what you were doing.

---

## License

Sthapana is proprietary software. © 2026 <Mukund Madhav Agarwal/ SAM Contech PVT LTD>. All rights reserved.
Unauthorized copying, distribution, or modification is not permitted.
