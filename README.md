# Sthapana

**Sthapana** is an offline Windows desktop application for civil-works cost estimation. It reproduces a master costing workbook with full calculation parity, so you can build and price civil construction estimates with spreadsheet-grade accuracy — without the spreadsheet, and without an internet connection.

This repository is the official **distribution channel** for Sthapana. It hosts the signed Windows installer and the update manifest the application uses to keep itself current. It does not contain application source code.

---

## Download & Install

1. Open the [**latest release**](https://github.com/Mukund2910/Sthapana-releases/releases/latest).
2. Download **`Sthapana_<version>_x64-setup.exe`**.
3. Run the installer. Sthapana installs for the current user — **no administrator rights required**.
4. Launch **Sthapana** from the Start menu.

That's the only manual download you'll ever need. After this, the app updates itself (see below).

---

## System Requirements

- **OS:** Windows 10 or Windows 11 (64-bit)
- **Internet:** Not required to use the app — only used to check for and download updates
- **Disk:** A few hundred MB free

---

## Automatic Updates

Sthapana checks for a new version **every time it starts**. When one is available, it prompts you to update; accepting downloads the new version, installs it, and relaunches the app.

Every update is **cryptographically signed and verified** before it's installed, so the app will only update from genuine, untampered releases.

You don't need to revisit this page for updates — only for a first-time install or a reinstall.

---

## What's in a release

Each release published here contains:

| File | Purpose |
|------|---------|
| `Sthapana_<version>_x64-setup.exe` | The Windows installer |
| `Sthapana_<version>_x64-setup.exe.sig` | Signature used to verify the update |
| `latest.json` | Update manifest read by the in-app updater |

Browse the full [version history](https://github.com/Mukund2910/Sthapana-releases/releases) to see what changed in each release.

---

## Support

For access requests, questions, or to report a problem, contact **<your-email@example.com>**.

> When reporting an issue, please include your Sthapana version (shown in the app) and a short description of what you were doing.

---

## License

Sthapana is proprietary software. © 2026 <Your Name / Organization>. All rights reserved.
Unauthorized copying, distribution, or modification is not permitted.
