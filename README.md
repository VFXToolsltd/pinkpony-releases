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
- **[📖 How-to guides, tab by tab](docs/guides/README.md)**
- [What it does](#what-it-does) · [What's new](#whats-new) · [How to install](#how-to-install) · [System requirements](#system-requirements) · [Updating](#updating) · [Troubleshooting](#troubleshooting) · [Uninstalling](#uninstalling)

---

## What it does

One desktop app for the VFX production office. It keeps a local copy of the show's
**ShotGrid (Autodesk Flow)** data, works from the paperwork the production already
makes — schedules, scripts, set reports, budgets, invoices — and sends the results
back to ShotGrid, after showing you a preview first.

| Tab | What it's for |
|-----|---------------|
| **Home** | The show at a glance: shots, progress, budget spend and hot costs. One button brings everything up to date from ShotGrid, and two more make the packs the crew open on their phones. |
| **Reports** | Stakeholder reports for producers and the studio: Weekly Overview, budget gauges, burn-down, vendor scorecard, hot-cost alerts, progress sheet, notes digest and the cost report. **Report Studio** lets you design your own layouts. |
| **Finance** | The studio's locked budget, the cost tracker spreadsheet, the accounts team's spending report and every PO, invoice and quote — each becomes its ShotGrid record, checked before it's sent. |
| **Brief** | A work brief from a review playlist or whole sequences: each shot's latest picture, brief, notes and drawings, as a spreadsheet and a PDF. |
| **Upload** | A delivery folder sent to ShotGrid: movies onto their shots or slates, documents onto their records. You see where every file goes before anything is sent. |
| **CSV** | Any ShotGrid page saved as a CSV becomes a tidy PDF report, shot pictures included. |
| **Oneline** | Production's oneline schedule PDF becomes ShotGrid's shoot days, each with its scenes and locations. |
| **Script** | Draft scripts become a scene-by-scene breakdown and bring ShotGrid's Scenes up to date, with a picture of each scene from the script. |
| **Board** | The unit board and unit map for the crew, and the post schedule as a printable calendar and in ShotGrid. |
| **Plan** | A forward look for each shoot day and unit — what VFX need from each department — as an email or a PDF. |
| **Movs** | A list of every movie in a folder with its shot name, version and length. |
| **Onset** | The day's set paperwork gathered into one master spreadsheet and sent to ShotGrid as slates and clips — with every disagreement between reports raised as a question for a person to answer, never guessed. |
| **Tools** | Opens the separate tools that work alongside the app — the onset collator, storyboard splitter, prep schedule scanner and batch uploader. |
| **Settings** | Each show's setup: the ShotGrid login, folders, budget figures, report colours, moving a setup to another machine, and the update check. |

Nothing is sent to ShotGrid without a preview first, and every job on the
Finance, Oneline, Script and Onset tabs opens on a step-by-step checklist.

---

## What's new

Highlights from the latest releases. Each release's own notes are on the
[Releases](../../releases) page.

- **Slate sheets** (V4.35) — a VFX data sheet per slate for the director, DOP and
  VFX supervisor: the whole frame, camera and lens for each camera, takes and
  notes. Choose the slates by pasting a list, ticking them in a window, by episode
  or from an editor's EDL (each edit matched to its clip, in cut order). Made only
  when asked for, and saved where you choose.
- **A picture on every slate** (V4.34) — slates with no picture become one pull
  request for the studio's media platform; the movies it sends back are matched by
  name and the middle frame put on the slate.
- **Timecode on every clip** (V4.33) — the media platform's clip report adds each
  clip's camera file name, timecode and frame count to ShotGrid, and fills in clips
  the paperwork missed.
- **Every take's camera values on its clip** (V4.32) — lens, filters, focus,
  height and tilt per take, and slates dated by the script supervisor's log.
- **Wider window** (V4.31) — a full-width layout with cards in a grid.
- **Post schedule** (V4.29) — the post team's calendar exports become a printable
  month-by-month calendar and ShotGrid's post days, kept in step on every send.
- **Slate rules per show** (V4.28) — how a show names its slates (pickups,
  elements, beauty and CCTV plates) set once per show, and answers to questions
  kept from one release to the next.
- **Forward-look planner** (V4.22–V4.24) — one plan per shoot day and unit, written
  as the email VFX sends to the departments, or saved as a PDF.
- **Script breakdown** (V4.19 onwards) — every scene read from the draft scripts,
  anything unclear asked as a question, then sent straight to ShotGrid's Scenes.
- **After Action reports and reference contact sheets** (V4.18) — a shareable
  report for each shoot day a week after it's shot, and a contact sheet of the
  wranglers' reference photos per day.
- **Paperwork in, records out** (V4.10) — a PO, invoice or quote PDF becomes its
  ShotGrid record, every value checked and shown with the line it came from.
- **One setup for every machine** (V4.11) — export a project's whole setup as one
  file and open it on another computer.
- **Plain English throughout** — every message, status line and error is written
  for the person using it, with one next step.

---

## How-to guides

Step-by-step guides for every tab, written for someone new to the app:
**[docs/guides](docs/guides/README.md)**. The same pages can be made from inside
the app, and they are generated from the app's own step lists, so the steps
match the buttons in the version they were made for.

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
