# CSV: how to

The CSV tab turns any ShotGrid page saved as a CSV file into a tidy PDF report. You choose the columns, and each shot's picture can go in too.

Each job below lists what to press, in order, and what you'll see when it has worked.

**Jobs on this tab**

- [Make a PDF from a ShotGrid page](#csv-pdf) — Whenever someone wants a ShotGrid list as a printable PDF.

<a id="csv-pdf"></a>

## Make a PDF from a ShotGrid page

*When: Whenever someone wants a ShotGrid list as a printable PDF.*

Save the page from ShotGrid as a CSV, choose the columns, and make the PDF.

### 1. Export the page from ShotGrid

Any ShotGrid page can be saved as a CSV file: shots, versions, notes or anything else.

1. In ShotGrid, open the page and show the columns you want in the PDF.
2. Menu (☰) → Export → CSV. Save it somewhere you can find it.
3. For pictures, keep the shot's code column in it (for example Shot Code).

✓ When it has worked: A .csv file is saved on your computer.

### 2. Open the CSV

Choose the file you just saved. Every column in it is listed with a tick.

**Press:** `Open CSV…`

✓ When it has worked: The status line says how many rows are ready.

### 3. Choose what goes in

Name the report, choose the page shape and untick any column you don't want.

1. Type a Report Name. It heads the PDF and names the file.
2. Choose Portrait, or Landscape when there are many columns.
3. Under Columns to include, untick anything you don't need.
4. Include Thumbnails puts each shot's picture in the first column, using the pictures saved at your last sync. It only works if the file has a shot code column.
5. Tick Download Missing Thumbs to fetch any missing picture from the file's Thumbnail column, if it has one.

### 4. Make the PDF

Builds the report and opens it. A Status column's short codes are written out in words.

**Press:** `Generate PDF`

✓ When it has worked: The PDF opens. It is kept in the show's reports folder, under Custom\_CSV\_Reports and today's date.


## Words you'll see

- **CSV file** — A plain spreadsheet file. ShotGrid makes one when you export a page.
- **Export (ShotGrid)** — Downloading a ShotGrid page as a CSV file.
- **Thumbnail** — The small picture of each shot. The app saves them at every sync.
- **Orientation** — Which way up the page is: Portrait (tall) or Landscape (wide).

[← All guides](README.md)

---

<sub>Generated 22 November 2026 for V4.35.0 from the app's own step lists, so the steps match the buttons in that version.</sub>
