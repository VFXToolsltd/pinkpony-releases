# Brief: how to

The Brief tab makes a work brief from a ShotGrid playlist or sequence: each shot's latest picture, brief, notes and drawings, as a spreadsheet and a PDF.

Each job below lists what to press, in order, and what you'll see when it has worked.

**Jobs on this tab**

- [Make a work brief](#brief-make) — When a vendor or supervisor needs the notes and pictures for a review playlist or whole sequences.
- [One step at a time](#brief-steps) — When you need only part of it (just the notes, or the PDF in the other layout), or a full run stopped partway.

<a id="brief-make"></a>

## Make a work brief

*When: When a vendor or supervisor needs the notes and pictures for a review playlist or whole sequences.*

Each shot's latest picture, brief, notes and drawings, as a spreadsheet and a PDF per sequence.

### 1. Choose what to fetch

Set Fetch By to Playlist for the latest version of each shot in a review playlist, or to Sequence for every shot in whole sequences.

1. Playlist: type the name exactly as ShotGrid has it under Playlist Name(s), separating several with commas.
2. Sequence: type the codes under Sequence Code(s), separated by commas.
3. Omitted shots are always left out.

### 2. Choose where it's saved

If you don't choose a folder, the brief goes in the Export Dir from Settings, or on your Desktop. Your choice lasts until the app is closed.

**Press:** `Select Folder…`

### 3. Choose the PDF layout

Under PDF Layout, Compact Grid puts each shot's picture above its notes and drawings. Supervisor Review puts a large picture beside the full notes.

### 4. Make it

Fetches the shots, their latest versions, notes and drawings from ShotGrid, saves the pictures, then makes the spreadsheet and the PDF. It reads ShotGrid directly, so no sync is needed first.

**Press:** `Run Full Pipeline`

✓ When it has worked: The status line says 'All done! Your work brief is saved in the export folder.'

### 5. Find the files

Inside is a folder named after the playlist or sequences, with a folder per sequence holding the pictures, the drawings, a notes file, the spreadsheet and the PDF.

**Press:** `Open Export Folder`


<a id="brief-steps"></a>

## One step at a time

*When: When you need only part of it (just the notes, or the PDF in the other layout), or a full run stopped partway.*

The same four steps as Make it, one button each.

### 1. Fetch from ShotGrid

Fetches the shots, latest versions, notes and drawings for the playlist or sequences typed above. Nothing is saved to the export folder yet.

**Press:** `1. Sync from ShotGrid`

✓ When it has worked: The status line says your work brief details are ready.

### 2. Save the pictures and notes

Saves each shot's picture and drawings into the export folder, with a notes file (CSV) per sequence.

**Press:** `2. Download & CSV`

✓ When it has worked: The status line says all the pictures are saved.

### 3. Make the spreadsheet

Makes the spreadsheet for each sequence from what was last fetched. Do steps 1 and 2 first.

**Press:** `3. Generate Excel`

✓ When it has worked: The status line says your work brief spreadsheet is saved.

### 4. Make the PDF

Makes the PDF in the layout chosen under PDF Layout, from what was last fetched. To change the layout, choose the other one and press this again; nothing is fetched.

**Press:** `4. Generate PDF Sheets`

✓ When it has worked: The status line says your contact sheet PDF is saved.


## Words you'll see

- **Work brief** — What a vendor or supervisor needs for each shot: its latest picture, the brief written for it, and every note and drawing.
- **Playlist** — A named list of versions in ShotGrid, usually made for a review.
- **Sequence** — A group of shots ShotGrid keeps together, known by its code.
- **Version** — One submitted piece of a shot's work, with its own notes.
- **Annotation** — A drawing made over a frame in ShotGrid when giving notes.
- **Contact sheet** — The PDF: a page per shot with its picture, brief, notes and drawings.

[← All guides](README.md)

---

<sub>Generated 22 November 2026 for V4.35.0 from the app's own step lists, so the steps match the buttons in that version.</sub>
