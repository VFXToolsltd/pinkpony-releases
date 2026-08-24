<p align="center">
  <img src="docs/PPPS_Splash.png" alt="The Pink Pony Production Suite" width="100%">
</p>

<h1 align="center">The Pink Pony Production Suite</h1>

<p align="center">
  VFX production tracking, financial reporting and delivery tools for episodic and feature work.<br>
  By <a href="https://vfxtools.co.uk">VFX Tools Ltd</a>.
</p>

<p align="center">
  <a href="../../releases/latest"><img src="https://img.shields.io/github/v/release/VFXToolsltd/pinkpony-releases?label=latest&color=e6779f" alt="Latest release"></a>
  <img src="https://img.shields.io/badge/platform-macOS%20%7C%20Windows-lightgrey" alt="Platforms">
  <img src="https://img.shields.io/badge/licence-proprietary-black" alt="Licence">
</p>

---

This repository carries the **downloadable builds** and the **update feed** the app
reads. The source code is private; only the finished applications are published here.

- **[⬇ Download the latest release](../../releases/latest)**
- [How to install](#how-to-install) · [System requirements](#system-requirements) · [Updating](#updating) · [Troubleshooting](#troubleshooting) · [Uninstalling](#uninstalling)

---

## Download

Grab the build for your machine from the **[Releases](../../releases/latest)** page:

| File | For |
|------|-----|
| `PinkPony_<version>_mac_arm64.zip` | macOS on Apple silicon (M1 and later) |
| `PinkPony_<version>_win_x64.zip`   | Windows 10 / 11, 64-bit |

Each release also ships a **`SHA256SUMS`** file so you can confirm a download
arrived intact — see [Verifying your download](#verifying-your-download).

---

## How to install

The app is not code-signed, so on first launch both macOS and Windows will warn
that it comes from an unidentified developer. That is expected for an in-house
tool; the steps below clear the warning **once**, after which it opens normally.

### macOS

1. Download `PinkPony_<version>_mac_arm64.zip` and double-click to unzip.
2. Drag **The Pink Pony Project** into your **Applications** folder.
3. The first time you open it, macOS may say the app *"is damaged and can't be
   opened"*. This is the unsigned-app warning, not a real problem. Clear it once
   from Terminal:

   ```bash
   xattr -cr "/Applications/The Pink Pony Project.app"
   ```

4. Open the app normally from Applications. You won't need to do this again — not
   even after an in-app update.

> **Why the warning?** macOS flags anything downloaded from the internet that
> isn't signed with an Apple Developer certificate. The command above removes
> the download-quarantine flag from this one app.

### Windows

1. Download `PinkPony_<version>_win_x64.zip`.
2. **Right-click the zip → Properties → tick "Unblock" → OK.** Doing this before
   you extract clears the download warning from every file inside in one step.
3. Right-click the zip → **Extract All…** and choose a permanent home for it,
   such as `C:\Program Files\The Pink Pony Project` or a folder in your Documents.
   *(Don't run it from inside the zip — extract it first.)*
4. Open the folder and run **The Pink Pony Project.exe**.
5. If you skipped step 2, Windows SmartScreen may show a blue *"Windows protected
   your PC"* box. Click **More info → Run anyway**.

> **Tip:** right-click the `.exe` → **Send to → Desktop (create shortcut)** for
> easy launching. Keep the app in its extracted folder — it needs the files
> alongside it.

---

## First run

On first launch the app opens a short setup wizard. You will need your
**ShotGrid (Autodesk Flow) site URL and API credentials** for the show you're
tracking. These are stored only on your own machine, in
`~/.shotgrid_sync_tool/` (macOS) or `%USERPROFILE%\.shotgrid_sync_tool\`
(Windows), and are never sent anywhere except your own ShotGrid site.

---

## System requirements

|         | Minimum |
|---------|---------|
| macOS   | macOS 13 (Ventura) or later, Apple silicon |
| Windows | Windows 10 or 11, 64-bit |
| Disk    | ~400 MB |
| Network | Access to your ShotGrid site; internet only for the optional update check |

No Python or other runtime is required — everything is bundled.

---

## Updating

**The app never checks for updates on its own.** When you want to check, open
**Settings → Check for Updates…**. If a newer build exists it tells you the
version and offers to download and install it for you; you confirm before
anything is replaced, and your previous version is kept as a backup in case the
new one won't start.

You can also just download the newest release from this page and install it over
the top — same result.

---

## Verifying your download

Optional, but quick. Each release includes a `SHA256SUMS` file listing the
expected checksum of every download.

**macOS**

```bash
cd ~/Downloads
shasum -a 256 -c SHA256SUMS
```

**Windows (PowerShell)**

```powershell
Get-FileHash .\PinkPony_*_win_x64.zip -Algorithm SHA256
```

Compare the printed hash against the matching line in `SHA256SUMS`. If they
match, the file is intact.

---

## Troubleshooting

| Symptom | Fix |
|---------|-----|
| macOS: *"…is damaged and can't be opened"* | Run the `xattr -cr` command in [Install → macOS](#macos). It's the unsigned-app warning, not a corrupt file. |
| Windows: *"Windows protected your PC"* | Click **More info → Run anyway**, or Unblock the zip before extracting (step 2 above). |
| App won't start after an update | Your previous version is kept alongside the new one. The app restores it automatically if the new build fails to launch; if not, delete the new folder and unzip the previous release again. |
| "Check for Updates" says nothing found | You're on the latest build — or the machine is offline. The app never blocks on this; it just carries on. |
| Reports or sync fail | Confirm the ShotGrid URL and credentials in **Settings**, then run a sync. The log at `~/.shotgrid_sync_tool/logs/` records the reason. |

---

## Uninstalling

The app keeps everything in two places:

- **The application itself** — the `.app` (macOS) or the extracted folder
  (Windows). Delete it.
- **Your settings and cached data** — `~/.shotgrid_sync_tool/` (macOS) or
  `%USERPROFILE%\.shotgrid_sync_tool\` (Windows). Delete this too for a complete
  removal. It holds your ShotGrid credentials and the local data cache; nothing
  else on your system is touched.

---

## Privacy

Everything runs on your machine. The app talks to **your own ShotGrid site** and
nowhere else — except when you press **Check for Updates**, when it reads a small
version file from this repository. It does not use any AI service, and it sends
no telemetry or usage data anywhere.

## Security

Found a security issue? Please see [SECURITY.md](SECURITY.md) — don't open a
public issue for it.

## Support

Questions or problems: **[vfxtools.co.uk](https://vfxtools.co.uk)**.

---

<sub>© VFX Tools Ltd. All rights reserved. The application is provided **as is**,
without warranty of any kind, and is licensed for use on productions VFX Tools
Ltd is engaged on. See the **About** tab inside the app for the full notice.
This repository contains compiled builds only — no source code.</sub>
