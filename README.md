# Vesper Desk — public releases

**This repository is releases and download binaries only.** It does **not** contain the Vesper Desk application source code.

Use it to:

- Download the Windows installer and portable builds
- Let the in-app updater read GitHub Releases (`latest.yml`, Setup `.exe`, `.blockmap`)

## Download

**Latest release:** [github.com/Justin-Developer01/vesper-desk-public/releases/latest](https://github.com/Justin-Developer01/vesper-desk-public/releases/latest)

| Asset | What it is |
| --- | --- |
| `Vesper-Desk-Setup-*.exe` | NSIS installer (recommended) |
| `Vesper-Desk-Portable-*.exe` | Portable EXE (no install) |
| `latest.yml` | electron-updater metadata |
| `*.exe.blockmap` | Delta / integrity helper for the updater |

Ignore GitHub’s automatic **Source code** zip/tarball on each release. That archive is only this stub repo (this README), **not** the private Electron app source.

Product site: [www.vesperdesk.app](https://www.vesperdesk.app) · Download page: [www.vesperdesk.app/download](https://www.vesperdesk.app/download)

## Source code

The Windows app lives in a **private** repository. Making *this* repo public does **not** publish that source. Contributors and CI publish installer assets here from the private build; they do not push the desk tree into this repo.

You do **not** need to clone this repository to install or update Vesper Desk. Open [Releases](https://github.com/Justin-Developer01/vesper-desk-public/releases) and download the Setup EXE.

## Licence

Installer and portable builds are proprietary (“All rights reserved”). Third-party notices ship inside the app (Settings → Support → About & legal).
