# Oneline: how to

The Oneline tab turns production's oneline schedule into ShotGrid's shoot days, so every day knows its scenes and locations.

Open the Oneline tab. At the top it asks What are you doing? — choose the job below and it walks you through the same steps, ticking each one off as it's done.

**Jobs on this tab**

- [New oneline issued](#oneline-new) — When production sends a new or revised oneline schedule PDF.

<a id="oneline-new"></a>

## New oneline issued

*When: When production sends a new or revised oneline schedule PDF.*

Turn the PDF into ShotGrid's shoot days, one file at a time.

### 1. Turn the PDF into a spreadsheet

Choose the oneline PDF. The app writes a spreadsheet next to it with one row per scene.

**Press:** `Choose the PDF and convert`

✓ When it has worked: A spreadsheet ending \_Breakout.xlsx appears next to the PDF.

### 2. Read what changed since the last oneline

The spreadsheet has a "Changes vs previous" tab: scenes that moved day, scenes added or dropped, days that changed date.

1. Open the \_Breakout.xlsx file and go to the "Changes vs previous" tab.
2. The Notes tab says which earlier spreadsheet it was compared with.
3. If that was the wrong one, pick the right one under All tools and convert again.

**Press:** `Open the spreadsheet`

*Done outside the app — then press “I've done this”.*

### 3. Tidy the spreadsheet

Open it in Excel and delete any stray rows that aren't scenes. Save and close.

1. Open the \_Breakout.xlsx file.
2. Delete rows that aren't real scenes (page headers, notes, blank rows).
3. Save, and close Excel — the app can't read a file Excel has open.

**Press:** `Open the spreadsheet`

*Done outside the app — then press “I've done this”.*

### 4. Download two pages from ShotGrid

The app needs ShotGrid's current Shoot Day and Scenes lists.

1. In ShotGrid, open the Shoot Day page for this project.
2. Menu (☰) → Export → CSV. Save it.
3. Do the same on the Scenes page.
4. Keep both files in the same folder as the spreadsheet.

*Done outside the app — then press “I've done this”.*

### 5. Make the new-scenes file

Lists any scene in the oneline that ShotGrid doesn't have yet.

**Press:** `Make the new-scenes file`

✓ When it has worked: A message says how many scenes need creating — often none.

### 6. Import the new scenes into ShotGrid

Only needed if the last step found new scenes.

1. In ShotGrid, open the Scenes page.
2. Menu (☰) → Import → choose the \_Scene\_Create.csv file.
3. Check the preview, then import.

*Done outside the app — then press “I've done this”.*

*The app skips this for you when there is nothing to do.*

### 7. Make the shoot-day file

Matches each shoot day in the oneline to ShotGrid and fills in its scenes and locations.

**Press:** `Make the shoot-day file`

✓ When it has worked: A message says how many days were matched.

### 8. Import the shoot days into ShotGrid

Updates the existing shoot days — nothing new is created.

1. In ShotGrid, open the Shoot Day page.
2. Menu (☰) → Import → choose the \_ShootDay\_Import.csv file.
3. Make sure it says it will UPDATE existing records, then import.

*Done outside the app — then press “I've done this”.*


## Words you'll see

- **Oneline** — Production's schedule PDF: every shoot day and the scenes shot on it.
- **Breakout spreadsheet** — The spreadsheet the app makes from the oneline, one row per scene.
- **Export (ShotGrid)** — Downloading a ShotGrid page as a CSV file.
- **Import (ShotGrid)** — Uploading a CSV file into a ShotGrid page to create or update records.

[← All guides](README.md)

---

<sub>Generated 22 November 2026 for V4.35.0 from the app's own step lists, so the steps match the buttons in that version.</sub>
