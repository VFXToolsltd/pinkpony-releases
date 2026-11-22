# Movs: how to

The Movs tab lists every movie (.mov) file in a folder with the shot each one belongs to, its version and its length, and saves the list as a CSV. The folder is only read.

Each job below lists what to press, in order, and what you'll see when it has worked.

**Jobs on this tab**

- [List a folder of movies](#movs-list) — When a delivery of movie files arrives and you need a list of what's in it.

<a id="movs-list"></a>

## List a folder of movies

*When: When a delivery of movie files arrives and you need a list of what's in it.*

List every .mov in a folder with its shot, check the names, and save the list as a CSV.

### 1. Get the latest from ShotGrid

On the Home tab, press Sync Now, so the list can say which shots ShotGrid has. Skip this if you only need the list.

✓ When it has worked: The Home tab says when it last updated.

### 2. Choose the folder

Choose the folder that holds the movies. Include subfolders is ticked to start with; untick it to list only the top folder.

**Press:** `Choose…`

✓ When it has worked: The Folder line shows the folder you chose.

### 3. List the movies

Reads each movie's shot and version from its file name, and its frames and frame rate from the file itself. On a big drive this can take a minute.

**Press:** `List Movs`

✓ When it has worked: The status line says how many movies were found, and the table lists them.

### 4. Check the shot names

The line under the table says how many shots there are, how many ShotGrid doesn't have, and anything that needs a look.

1. Double-click a shot name to correct it. The file itself isn't renamed.
2. In SG says whether ShotGrid had that shot at your last sync.
3. Hover over a row for its notes, such as two files with the same shot and version, or a length that couldn't be read.

### 5. Save the list

Saves the list as a CSV, adding each file's folder, duration, notes and full path. It goes in Mov Lists in your Documents folder unless you choose somewhere else.

**Press:** `Export CSV…`

✓ When it has worked: The CSV opens, and the status line says how many movies it lists.


## Words you'll see

- **Mov** — A movie file ending .mov, the usual form of a delivered shot.
- **Shot name** — Read from the file's name by the same rules the Upload tab uses. Correcting it here doesn't rename the file.
- **Version** — The file's version number, from its name (v003 is version 3).
- **In SG** — Whether ShotGrid had that shot at your last sync.
- **FPS** — Frames per second: the movie's frame rate.

[← All guides](README.md)

---

<sub>Generated 22 November 2026 for V4.35.0 from the app's own step lists, so the steps match the buttons in that version.</sub>
