# Onset: how to

The Onset tab gathers each shoot day's set paperwork and sends the slates and clips to ShotGrid.

Open the Onset tab. At the top it asks What are you doing? — choose the job below and it walks you through the same steps, ticking each one off as it's done.

**Jobs on this tab**

- [End of the shoot day](#onset-day) — Each evening, once the day's set paperwork is in the onset folder.
- [Update the shared sheet](#onset-share) — When the shared sheet wasn't ticked at the last send, or ShotGrid has been corrected since.
- [Fill the Gaps](#onset-fill-gaps) — Every week or so, and whenever the camera team sends a new log.
- [Check the reference photos](#onset-reference) — Once the wranglers have copied the day's photos and the day's slates are in ShotGrid.
- [Slate sheets](#onset-slate-sheets) — Whenever the director, DOP or VFX supervisor asks for what we hold on some slates.
- [After Action reports](#onset-after-action) — Once a week, for the days shot a week or more ago.

<a id="onset-day"></a>

## End of the shoot day

*When: Each evening, once the day's set paperwork is in the onset folder.*

Gather the day's paperwork, answer its questions, and send it to ShotGrid.

### 1. Gather the day's paperwork

Reads the onset store — every day's VFX camera exports and script supervisor's reports, wherever they were filed — into one master spreadsheet. Where copies or dates disagree, the newest copy and the script supervisor's date are used and noted for step 2. A slate whose VFX data hasn't come in yet is still made, and looked for again next time; a week on it's listed in the missing-data report beside the contact sheets, and any day with new photos gets a new contact sheet. The store itself is never changed.

1. The first time, under All tools, choose the onset store (the folder that holds the shoot-day folders) and where the master spreadsheet is saved — a folder outside the store.
2. Press Gather the paperwork. Nothing needs copying first.

**Press:** `Gather the paperwork`

✓ When it has worked: A message says how many slates and clips were found.

### 2. Answer the questions

Where two reports disagreed, the app picked one and asks you to confirm. Answers are remembered, so tomorrow only asks what's new.

**Press:** `Answer the questions`

✓ When it has worked: The questions line says 'all answered' or 'none today'.

### 3. Preview what will be sent

Lists every slate and clip that would be created or changed. Nothing is sent.

**Press:** `Preview (nothing changes)`

✓ When it has worked: The preview appears in the log.

### 4. Send to ShotGrid

Creates and updates the day's slates and clips in ShotGrid. Tick 'Also publish to the shared Google Sheet' first to update the editors' read-only sheet straight after — it is never updated unless ticked.

**Press:** `Send to ShotGrid`

✓ When it has worked: A message confirms how many slates and clips were sent, and whether the shared sheet was updated.


<a id="onset-share"></a>

## Update the shared sheet

*When: When the shared sheet wasn't ticked at the last send, or ShotGrid has been corrected since.*

Copy what ShotGrid holds now to the editors' shared Google Sheet.

### 1. Publish to the shared sheet

Reads every slate and its clips from ShotGrid as they are now and replaces what the shared sheet shows. Nothing in ShotGrid changes.

**Press:** `Publish to the shared sheet now`

✓ When it has worked: A message says how many slates and clips the sheet now shows.


<a id="onset-fill-gaps"></a>

## Fill the Gaps

*When: Every week or so, and whenever the camera team sends a new log.*

Fill in what the set paperwork missed: timecode — and any clips never logged — from the Content Hub report, and lens details from the camera team's log.

### 1. Add the Content Hub report

Puts each clip's camera file name and timecode into ShotGrid, so an editor's cut can be matched to the take data. Days ShotGrid has no clips for are listed: choose the unit a day was shot by and its clips are made too, or leave it out. You see everything first, and nothing is sent until you press Send. ShotGrid's shoot dates are never changed.

1. In Content Hub, download the show's Assets Report for video clips as a .csv file.
2. Press Add a Content Hub report… and choose that file.
3. Read the list. For each day ShotGrid has no clips for, choose the unit it was shot by, or leave it out — test rolls are usually left out.
4. Press Send to ShotGrid.

**Press:** `Add a Content Hub report…`

*You can skip this step when it doesn't apply — press “Skip this step”.*

✓ When it has worked: A message says how many clips got their timecode and how many were made.

### 2. Ask Content Hub for the missing slate pictures

For every slate with no picture in ShotGrid — nobody on set to grab one — makes a pull asking Content Hub for 2 seconds from the middle of one of its clips (a circled take on the main camera if there is one). Slates asked for before are left out, so Content Hub isn't asked twice. Do this after adding the Content Hub report: a clip needs its timecode to be asked for.

1. Press Sync Now on the Home tab first, so the slates are today's.
2. Press Ask Content Hub for slate pictures… and choose where to save the pull.
3. The folder opens. In Content Hub, upload the new .edl file as a pull.
4. Slates that can't be asked for yet are listed in the log, with why.

**Press:** `Ask Content Hub for slate pictures…`

*You can skip this step when it doesn't apply — press “Skip this step”.*

✓ When it has worked: A message says how many slates are in the pull, and its folder opens.

### 3. Add the slate pictures Content Hub sent

When Content Hub's files arrive: takes the middle frame of each movie and puts it on its slate in ShotGrid. You see how many first, and nothing is sent until you press Send. A slate that already has a picture keeps it. The download folder is only read.

1. Download the pull's files from Content Hub into one folder.
2. Press Add the slate pictures it sent… and choose that folder.
3. Read the count. To look at the pictures first, open the folder it names.
4. Press Send to ShotGrid.

**Press:** `Add the slate pictures it sent…`

*You can skip this step when it doesn't apply — press “Skip this step”.*

✓ When it has worked: A message says how many slates got their picture.

### 4. Add the camera log

Keeps the camera team's log and gathers the paperwork again. Where the VFX wrangler has no camera data for a slate, the lens details are taken from the log. Nothing the wrangler recorded is changed. Skip this when no new log has arrived.

1. Ask the camera team to export their log for the whole show as a .json file, and save it somewhere you can find it.
2. Press Add a camera log and choose that file.
3. Wait while the paperwork is gathered again.

**Press:** `Add a camera log…`

*You can skip this step when it doesn't apply — press “Skip this step”.*

✓ When it has worked: A message says how many slates were filled from the camera log.

### 5. Preview what will be sent

Only after adding a camera log: lists the slates that would change. Nothing is sent.

**Press:** `Preview (nothing changes)`

*You can skip this step when it doesn't apply — press “Skip this step”.*

✓ When it has worked: The preview appears in the log.

### 6. Send to ShotGrid

Only after adding a camera log: updates those slates in ShotGrid.

**Press:** `Send to ShotGrid`

*You can skip this step when it doesn't apply — press “Skip this step”.*

✓ When it has worked: A message confirms how many slates were sent.


<a id="onset-reference"></a>

## Check the reference photos

*When: Once the wranglers have copied the day's photos and the day's slates are in ShotGrid.*

A contact sheet per shoot day for the VFX supervisor, opening on what's missing.

### 1. Get the latest from ShotGrid

So the day's slates — and what each one needs — are today's.

**Press:** `Get the latest`

✓ When it has worked: The status line says when it last updated.

### 2. Make the contact sheets

Looks through the photo folder and writes one PDF per shoot day into the shared folder. Only days that changed are made again. The photos are never changed.

1. The first time, choose the photo folder (the one holding the shoot-day folders) and the folder the sheets should go in — the shared Google Drive folder the supervisor can see.
2. Press Make the contact sheets.
3. The first run makes a small preview of every photo and can take a few minutes. After that, only new photos are looked at.

**Press:** `Make the contact sheets`

✓ When it has worked: A message says how many day sheets were made and whether anything is missing.

### 3. Look over what's missing

Open the newest day's sheet. Its first page shows each unit at a glance; each unit's part then lists slates with no photographs, HDRIs noted but not found, and anything not linked to a slate. The index's "Needs a look" list shows anything in no sheet at all. Tell the wranglers about anything really missing.

**Press:** `Open the contact sheets`

*Done outside the app — then press “I've done this”.*


<a id="onset-slate-sheets"></a>

## Slate sheets

*When: Whenever the director, DOP or VFX supervisor asks for what we hold on some slates.*

A VFX data sheet per slate: the whole frame, camera and lens, takes and notes.

### 1. Get the latest from ShotGrid

So each slate's camera data, takes and notes are today's.

**Press:** `Get the latest`

✓ When it has worked: The status line says when it last updated.

### 2. Choose the slates and make their sheets

Opens the list of slates. Paste a list of slates into the search bar, choose an episode, or add an editor's EDL — its edits are matched to their clips, and so their slates, in cut order. Tick the ones you want, then make the sheets. A slate with no picture yet is asked for from Content Hub.

1. Press Make slate sheets…
2. Paste a list (from an email or a spreadsheet — 'VXX29, A, B' means VXX29, VXX29A and VXX29B), choose an episode, or press Use an EDL… and choose the editor's EDL.
3. Press Tick all shown, or tick the slates you want one by one.
4. To have them in one file, tick Put them all in one PDF. If Content Hub has delivered a pull for these slates, press Pictures from a delivered pull… and choose its folder.
5. Press Make the sheets, then choose where to save them — a file name for one PDF, or a folder for a PDF per slate. Nothing is kept anywhere else.

**Press:** `Make slate sheets…`

✓ When it has worked: A message says how many sheets were made, and they open.

### 3. Look them over before sending

Check the sheets through before passing them on.

*Done outside the app — then press “I've done this”.*


<a id="onset-after-action"></a>

## After Action reports

*When: Once a week, for the days shot a week or more ago.*

Bring in the supervisor's notes, then make each day's report for the wider team.

### 1. Get the latest from ShotGrid

So each day's slates, takes and notes are today's.

**Press:** `Get the latest`

✓ When it has worked: The status line says when it last updated.

### 2. Bring in the supervisor's notes

The supervisor keeps a running notes document. Download it as plain text into the notes folder, then read it here: the app shows which day each line lands on, asks about any line whose day and date disagree, and keeps the notes.

1. Open the supervisor's notes document and download it as plain text (.txt).
2. Save it in the notes folder. The first time, the app asks you to choose the file and remembers its folder.
3. Press Read the supervisor's notes. Check where each line landed, answer any question, then press Keep these notes.

**Press:** `Read the supervisor's notes`

✓ When it has worked: A message says which days' notes are new or changed.

### 3. Send the notes to ShotGrid

Copies each day's notes into that shoot day's Supervisor Notes in ShotGrid, so the Slates page can show them beside every slate. Shows what will change first; no slate is changed. Skip this if ShotGrid isn't set up for it yet.

1. The first time, add the field: Settings → Provision ShotGrid Fields, choose Shoot days, and create Supervisor Notes.
2. Also once: in ShotGrid, on the Slates page, add the column Shoot Day › Supervisor Notes.
3. Press Preview and send, read what will change, then press Send.

**Press:** `Preview and send`

*You can skip this step when it doesn't apply — press “Skip this step”.*

✓ When it has worked: A message says which days' notes were sent.

### 4. Make the reports

Makes a PDF for each day that's ready — a week after it was shot, with the supervisor's notes in — into the shared folder, with an index of every day. Only new or changed days are made again.

1. The first time, choose the shared folder the reports go to — not the contact sheets' folder, which is only for the VFX supervisor.
2. Press Make the reports.

**Press:** `Make the reports`

✓ When it has worked: A message says which days were made.

### 5. Look over the new reports

Open the newest reports and read them through before telling people they're there.

**Press:** `Open the reports`

*Done outside the app — then press “I've done this”.*


## Words you'll see

- **Slate** — One set-up on the day, identified by its slate number.
- **Clip** — One camera recording of a take.
- **Master spreadsheet** — The single spreadsheet the app builds from the day's paperwork.
- **Questions** — Places where two reports disagreed. The app picked one and asks you to confirm.
- **Preview** — Shows what would be sent. Nothing changes in ShotGrid.
- **Camera log** — The camera team's own record of the lens and settings used on each slate.

[← All guides](README.md)

---

<sub>Generated 22 November 2026 for V4.35.0 from the app's own step lists, so the steps match the buttons in that version.</sub>
