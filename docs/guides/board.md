# Board: how to

The Board tab builds the unit calendar, the location map and the studio-vs-location calendar from the shoot days at your last sync, as files you can open, print and email. It also turns the post team's calendar exports into a post calendar and ShotGrid's Post Days.

Each job below lists what to press, in order, and what you'll see when it has worked.

**Jobs on this tab**

- [Build the unit board](#board-build) — When the schedule or the crew changes, or someone asks for a fresh board or map.
- [Place every location on the map](#board-places) — When a build says some locations are new to the map, or a pin is in the wrong place.
- [Post schedule](#board-post) — When the post team sends new calendar exports.

<a id="board-build"></a>

## Build the unit board

*When: When the schedule or the crew changes, or someone asks for a fresh board or map.*

Bring the shoot days up to date, build the calendars and the map, then print or send them.

### 1. Get the latest from ShotGrid

On the Home tab, press Sync Now. The board shows ShotGrid as it was at your last sync and never updates by itself.

✓ When it has worked: The Home tab says when it last updated.

### 2. Choose what to build

Tick what you need. Each tick box has a line underneath saying what it makes.

1. Tick Unit Board, Unit Map or Studio vs Location, or all three.
2. The files go to the Unit Board folder in your Documents. To use another folder, press Change… beside Save to. The app goes back to the Unit Board folder each time it opens.

### 3. Build

Makes each file you ticked from the shoot days at your last sync.

**Press:** `Build`

✓ When it has worked: The status line says how many shoot days, VFX elements and map places went in. Anything that needs a look is in the progress list, such as days with VFX but no crew, or places the map can't find.

### 4. Open and check them

Each file opens in your web browser and works on its own. It holds no ShotGrid login, so it can be emailed or copied to a drive.

1. Press Open board, Open map or Open studio vs location.
2. Open folder shows where the files were saved.

**Press:** `Open board`

✓ When it has worked: The top of the page says when it was built and when ShotGrid was last synced.

### 5. Print or save as PDF

The board and the studio calendar print from the browser, one month per A3 sheet.

1. Open the board or the studio calendar.
2. Pick a month under Save as A3 PDF, or All months.
3. In the print dialog choose Save as PDF, paper A3 and Landscape, and tick Background graphics.

✓ When it has worked: The PDF is saved where you chose in the print dialog.


<a id="board-places"></a>

## Place every location on the map

*When: When a build says some locations are new to the map, or a pin is in the wrong place.*

Fill in a spreadsheet of locations, so the map puts every one in exactly the right spot.

### 1. Make the locations workbook

Tick Locations workbook and press Build. It lists every location on the schedule with its days, units and best-guess address already filled in.

**Press:** `Build`

✓ When it has worked: A spreadsheet of locations to fill in is saved beside the board.

### 2. Fill in the coordinates

A location's address is often not where the unit actually shoots, so you type in the exact spot by hand.

1. Open the workbook.
2. For each location, find the spot on an online map and copy its coordinates (the pair of numbers the map gives for that spot).
3. Paste them into the yellow Paste coords column. Lat and Lon fill in by themselves.
4. Correct the best address if it is wrong. Don't change the id column.
5. Save and close the workbook.
6. Only one place to fix in a hurry? On the map's Places list, press locate next to it and check the pin. That fix is kept only in that browser, on that computer.

✓ When it has worked: Every location has its coordinates.

### 3. Choose the filled-in workbook

Beside Coordinates, press Choose… and pick the saved workbook. The app forgets this when it closes, so choose it again before each later build.

**Press:** `Choose…`

✓ When it has worked: The Coordinates line shows the workbook's name.

### 4. Build again

Builds the map with every location where you put it.

**Press:** `Build`

✓ When it has worked: The status line gives exact map positions for every place.


<a id="board-post"></a>

## Post schedule

*When: When the post team sends new calendar exports.*

Turn the post team's calendar exports into a month-by-month calendar and ShotGrid's Post Days.

### 1. Save the exports in one folder

The post team sends one calendar export (.csv) per milestone: cuts, reviews, picture lock. The app finds each milestone from the event's title, never the file name.

1. Save every export into the same folder.
2. A folder holding only some of the exports changes only those milestones. The rest are left alone.

✓ When it has worked: The exports are all in one folder.

### 2. Choose the folder

Beside Exports, press Choose… and pick that folder. The app remembers it, and the calendar goes in the folder above it unless you press Change… beside Save to.

**Press:** `Choose…`

✓ When it has worked: The Exports line shows the folder.

### 3. Make the post calendar

Writes a calendar of every episode's milestones, one month per A4 landscape page, with picture lock along the top.

**Press:** `Make the post calendar`

✓ When it has worked: The calendar opens in your browser, and the status line says how many milestones came from how many exports. Anything it couldn't read is in the progress list.

### 4. Send to ShotGrid

Lists every new, moved and removed milestone in the progress list first, and asks before anything is sent. Milestones someone added by hand in ShotGrid are never touched.

1. The first time, add the fields: Settings → Provision ShotGrid Fields, choose Post days.
2. Press Send to ShotGrid… and read the changes in the progress list. If nothing changed, it says so and sends nothing.
3. An episode ShotGrid doesn't have yet is left out and listed.
4. Press Send.

**Press:** `Send to ShotGrid…`

✓ When it has worked: The status line says how many milestones were sent as new, changed and removed.


## Words you'll see

- **Unit Board** — A calendar of the shoot, one month per sheet: who is on each unit each day, and the VFX work attached.
- **Unit Map** — A map of where each unit is shooting, day by day.
- **Studio vs Location** — A calendar of each set: the days it is shot on a stage and the days on location.
- **Coordinates** — The pair of numbers that pins a place on a map. You type them in once per location.
- **Milestone** — One date on the post schedule for one episode: a cut, a review or picture lock.
- **Post Days** — ShotGrid's page of post milestones, one record per milestone.

[← All guides](README.md)

---

<sub>Generated 22 November 2026 for V4.35.0 from the app's own step lists, so the steps match the buttons in that version.</sub>
