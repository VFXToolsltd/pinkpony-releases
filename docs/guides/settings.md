# Settings: how to

Settings opens from the gear button at the top right of the window (its title bar says Manage Projects). It holds each show's setup: the ShotGrid login, folders, budget figures and how reports look. It also moves a setup between machines and checks for updates.

Each job below lists what to press, in order, and what you'll see when it has worked.

**Jobs on this tab**

- [Set up a new show](#settings-new-project) — Once per show. The very first time the app starts, this opens on its own.
- [Switch to another show](#settings-switch) — When you work on more than one show.
- [Change the show's details](#settings-details) — When the show's folders, logo, colour or report title change.
- [Change the ShotGrid login](#settings-login) — When the ShotGrid administrator gives you a new key, or the show moves site.
- [Set the budget figures for reports](#settings-budget) — When the show's budget per episode, overheads or currency changes.
- [Change how reports look](#settings-reports) — When reports are for printing, projecting or a darkened review room, or need another paper size.
- [Send this setup to another machine](#settings-send-setup) — When another computer needs to work on the show, or after the budget, accounts or onset answers change on the main machine.
- [Receive a setup from the main machine](#settings-receive-setup) — On any computer other than the main machine, when a new setup file arrives.
- [Set up the shared sheet for outside parties](#settings-shared-sheet) — Once per show, and once on each computer that will publish to the sheet.
- [Add the fields ShotGrid needs](#settings-fields) — When setting up a show, or when a guide says ShotGrid needs a new field.
- [Bring in more ShotGrid fields](#settings-synced-fields) — When you want a shot or asset field in a report or spreadsheet that the app doesn't bring in yet.
- [Bring in a ShotGrid custom entity](#settings-custom-entities) — When the show keeps a new kind of record in ShotGrid that the app should read.
- [Group the statuses](#settings-statuses) — When ShotGrid gets a new shot status, or the charts show shots under Other.
- [Check for updates](#settings-updates) — When you hear a new version is out. The app never checks by itself.
- [Remove a show from this computer](#settings-delete) — When a show has finished and you no longer want it in the project list.

<a id="settings-new-project"></a>

## Set up a new show

*When: Once per show. The very first time the app starts, this opens on its own.*

Name the show, connect to ShotGrid, set its budget, then fill in its folders.

### 1. Start a new project

Open Settings with the gear button. On the Project tab, under Actions, press New Project.

1. At the very first start, closing this window without creating a project closes the app.

**Press:** `New Project`

### 2. Name the show and choose its type

Type the project's name exactly as ShotGrid spells it, then choose Episodic / TV Series (a budget per episode) or Feature Film (one total).

1. Already set up on the main machine? Press Open its setup file… instead (see Receive a setup from the main machine).

**Press:** `Next →`

### 3. Connect to ShotGrid

Enter the ShotGrid site address, the script name and its key, then test the connection. The app lists the site's projects so you can pick the exact one.

1. Ask the ShotGrid administrator for the site address, a script name and its key for this app.
2. Press Test Connection.
3. If it can't find the show by the name you typed, pick it from the ShotGrid Project list.
4. Press Next →. Skipping the test makes it warn you first: if the name is wrong, nothing will find the show.

**Press:** `Test Connection`

✓ When it has worked: A line says ✓ Connected and names the project.

### 4. Set the currency and budget

Enter the currency symbol and the budget: per episode plus an overheads budget for a series, or one total for a feature. A second currency and its rate are optional.

1. Overheads Keyword is part of an episode code: episodes whose code contains it are counted as Overheads.

**Press:** `Next →`

### 5. Check and create

Read the summary, then create the project.

1. When it asks Set up ShotGrid fields?, say Yes to add the extra fields the reports need. This needs a ShotGrid login with administrator rights, and can be done later (see Add the fields ShotGrid needs).

**Press:** `Create Project`

✓ When it has worked: The window closes and the new show is chosen in the project list.

### 6. Fill in the folders

Back in Settings, on the Project tab, choose this machine's folders (where reports go and the show's finance folder) and the logo, then save.

**Press:** `Save Changes`

✓ When it has worked: A message says your project settings are saved.


<a id="settings-switch"></a>

## Switch to another show

*When: When you work on more than one show.*

Change which show the whole app is working on.

### 1. Pick the show

Choose it from the PROJECT list at the top left of the window, and every tab then works on that show. Settings has the same list at its top, with a Switch button.

1. Save any changes in Settings first: switching drops anything unsaved.
2. The list can't be changed while a job is running. Wait for it to finish.

**Press:** `Switch`

✓ When it has worked: The window's title and colour change to that show's.


<a id="settings-details"></a>

## Change the show's details

*When: When the show's folders, logo, colour or report title change.*

Edit the Project tab and save.

### 1. Change the details

On the Project tab: the ShotGrid project name (exactly as ShotGrid spells it), the report title, the show's colour, the export and finance folders, the onset master spreadsheet's file name and the logo for PDF reports.

1. Browse… chooses a folder or the logo; Pick… chooses the colour.
2. Export Dir left blank means the Desktop.
3. The finance folder is where the budgets, cost tracker and studio reports go.

### 2. Save

Saves every tab at once, not just the one showing. If saving would empty a setting that holds something, it asks first; choose No to keep it.

**Press:** `Save Changes`

✓ When it has worked: A message says your project settings are saved, and the app takes on the show's colour.


<a id="settings-login"></a>

## Change the ShotGrid login

*When: When the ShotGrid administrator gives you a new key, or the show moves site.*

Enter the new login, save it, and check it works with a sync.

### 1. Enter the new login

On the ShotGrid tab, type the site address, the script name and its key. The key is hidden as you type.

1. Sequence Filter limits the app to some sequences, separated by commas. Leave it blank for all.
2. Tick the box for POs, invoices and bids only once ShotGrid is set up for them. The Finance tab's committed and spent figures need it.

### 2. Save

Saves the login with this show on this computer.

**Press:** `Save Changes`

✓ When it has worked: A message says your project settings are saved.

### 3. Check it works

Settings has no test button, so press Sync Now on the Home tab. If the login is wrong, the sync says so.

**Press:** `Sync Now`

✓ When it has worked: The Home tab says Last updated from ShotGrid with today's time.


<a id="settings-budget"></a>

## Set the budget figures for reports

*When: When the show's budget per episode, overheads or currency changes.*

The figures the Home tab and the reports measure spending against. The Finance tab's locked budget is separate and is loaded on that tab.

### 1. Check the show's type

The top of Settings shows Episodic / TV Series or Feature Film. Change… switches it and changes which budget fields show; values already typed are kept.

1. Do this before typing anything else: it reloads the form, and unsaved changes are lost.

**Press:** `Change…`

### 2. Enter the figures

On the Budget tab: the currency symbol, an optional second currency and its rate, and the budget. For a series that's per episode, the number of episodes and the overheads; for a feature, one total.

1. Overheads Keyword: episodes whose code contains it are counted as Overheads.
2. Excluded Episodes: episode codes, separated by commas, left out of every count and report.
3. Tick Show 2nd currency in reports to show both currencies.

### 3. Save

Saves every tab at once.

**Press:** `Save Changes`

✓ When it has worked: A message says your project settings are saved.


<a id="settings-reports"></a>

## Change how reports look

*When: When reports are for printing, projecting or a darkened review room, or need another paper size.*

Choose the show's report colours, PDF page size and picture quality.

### 1. Choose the look

On the Reports tab, choose Report Colours: Paper & Pen (the house style), Print Mono (black on white, for printing), Slate (dark, for a darkened room) or High Contrast (for projection and large screens).

1. PDF Page Size: A4, Letter or A3.
2. PDF Image Quality: Low makes the smallest files, High the sharpest pictures.

### 2. Save

Each show keeps its own choice. Reports and PDFs made from now on use it.

**Press:** `Save Changes`

✓ When it has worked: A message says your project settings are saved.


<a id="settings-send-setup"></a>

## Send this setup to another machine

*When: When another computer needs to work on the show, or after the budget, accounts or onset answers change on the main machine.*

Pack the show's whole setup into one file on the main machine, for the other computers to receive.

### 1. Make the setup file

On the main machine (the one that keeps the show's finances), go to the Project tab. Under Other machines, press Send this setup to another machine… and choose where to save the file.

1. It packs the settings, the ShotGrid login, the locked budget, the cost tracker, the accounts reports, the onset and script answers, the plans and crew list, and the weekly history.
2. Folder settings aren't packed: they stay each machine's own.

**Press:** `Send this setup to another machine…`

✓ When it has worked: A message says the setup file is ready and where it was saved.

### 2. Get it to the other machine

The file holds the ShotGrid login and the crew's email addresses, so handle it like a password. Copy it straight to the other computer, never into a shared chat or shared folder.


<a id="settings-receive-setup"></a>

## Receive a setup from the main machine

*When: On any computer other than the main machine, when a new setup file arrives.*

Make this computer match the main machine. Never do this on the computer that keeps the show's finances.

### 1. Make sure this isn't the finance machine

Receiving replaces this computer's budget, cost tracker, accounts reports, finance records and weekly history with the sender's. Never receive onto the computer that keeps the show's finances: setups only ever go out from it.

1. A safety copy is made first, but there's no button to put it back.

### 2. Open the setup file

On the Project tab, under Other machines, press Receive a setup from the main machine… and choose the file. It shows what the file holds and what taking it changes.

1. On a computer starting the app for the first time, Open its setup file… in the New Project Setup window does the same.

**Press:** `Receive a setup from the main machine…`

### 3. Take it

Read the list, then press Receive setup. If this computer has no finance folder for the show yet, it asks where it is.

1. If a cost tracker is open in Excel, close it first, or the receive stops.
2. If it says the setup came from a newer version, update this computer first (see Check for updates).

**Press:** `Receive setup`

✓ When it has worked: A message says this machine now matches the main one, and the Project tab says when it last took a setup.

### 4. Check the folders

Folder settings stay this computer's own. On the Project tab, fill in any that are blank, then save.

**Press:** `Save Changes`


<a id="settings-shared-sheet"></a>

## Set up the shared sheet for outside parties

*When: Once per show, and once on each computer that will publish to the sheet.*

Link the editors' read-only Google Sheet and give this computer the Google key it publishes with.

### 1. Paste the sheet's address

On the Project tab, under Shared sheet for outside parties, paste the Google Sheet's web address into Sheet.

### 2. Add the Google key

Choose the Google key file (.json) for the account the app publishes as. It is kept on this computer only and a setup file never carries it, so treat it like a password.

**Press:** `Choose the Google key…`

✓ When it has worked: A message names the Google account this computer now publishes as.

### 3. Save

Saves the sheet's address with the show.

**Press:** `Save Changes`

✓ When it has worked: A message says your project settings are saved.

### 4. Share the sheet

In Google Sheets, share the sheet with that Google account as an Editor and with the outside parties as Viewers. It is only updated when 'Also publish to the shared Google Sheet' is ticked on the Onset tab.

1. Anyone who needs the Search tab's box needs edit access. Every tab warns that changes are overwritten.


<a id="settings-fields"></a>

## Add the fields ShotGrid needs

*When: When setting up a show, or when a guide says ShotGrid needs a new field.*

Check the ShotGrid site for the extra fields a part of the app needs and add the missing ones. Fields already there are never changed.

### 1. Check the site

On the ShotGrid tab, press Provision ShotGrid Fields…. The app looks at the site straight away, and nothing changes yet.

**Press:** `Provision ShotGrid Fields…`

### 2. Choose what they're for

In Fields for, choose the part of the app: report fields, orders, the budget, shoot days, post days, or everything.

1. Will create: ticked, ready to add.
2. Missing, have a look first: unticked, because ShotGrid usually has these built in. Tick one only if your site really lacks it.
3. A different kind of field is already there: left alone. Mention it to the ShotGrid administrator.
4. Already present: nothing to do.

### 3. Add them

Press Create Selected and say Yes. This needs a ShotGrid login with administrator rights.

**Press:** `Create Selected`

✓ When it has worked: A message says how many fields were added, and the list checks the site again.


<a id="settings-synced-fields"></a>

## Bring in more ShotGrid fields

*When: When you want a shot or asset field in a report or spreadsheet that the app doesn't bring in yet.*

Tick the extra fields, save, then sync to fill them in.

### 1. Tick the fields

On the ShotGrid tab, press Synced ShotGrid Fields…, choose Shot or Asset, and tick the fields to bring in. The show's own fields are listed first.

1. Type in the search box to find a field.
2. If the list is empty, press Refresh from ShotGrid.
3. Fields marked always synced can't be unticked.
4. Reset to Defaults puts back the starting choice.

**Press:** `Synced ShotGrid Fields…`

### 2. Save

New fields stay empty until the next sync.

**Press:** `Save`

✓ When it has worked: A message lists the fields added.

### 3. Fill them in

Press Sync Now on the Home tab.

**Press:** `Sync Now`

✓ When it has worked: The Home tab says Last updated from ShotGrid with today's time.


<a id="settings-custom-entities"></a>

## Bring in a ShotGrid custom entity

*When: When the show keeps a new kind of record in ShotGrid that the app should read.*

Tick the custom entities to keep a copy of on this computer, save, then sync.

### 1. Open the list

On the ShotGrid tab, press Custom Entities…. It opens on the ones already kept, with how many records each has.

**Press:** `Custom Entities…`

### 2. List the site's custom entities

Lists every custom entity the site has. Tick the ones the app should keep a copy of.

1. 'Saved as' is the name the app keeps each one under. Leave it alone on one already ticked: other parts of the app look for it by that name.
2. Unticking stops one syncing but keeps what's already on this computer.

**Press:** `Load from ShotGrid`

### 3. Save

Their fields are picked up on each sync; you never list them.

**Press:** `Save`

✓ When it has worked: A message says how many will come across on the next sync.

### 4. Fill them in

Press Sync Now on the Home tab.

**Press:** `Sync Now`

✓ When it has worked: The Home tab says Last updated from ShotGrid with today's time.


<a id="settings-statuses"></a>

## Group the statuses

*When: When ShotGrid gets a new shot status, or the charts show shots under Other.*

Put each ShotGrid status in a group, so counts, costs and charts come out right.

### 1. List the statuses

On the ShotGrid tab, press Manage Statuses…. It opens on the statuses from the last sync; Refresh from ShotGrid lists every one the site has.

**Press:** `Manage Statuses…`

### 2. Put each status in a group

Choose a group for each: Final, Active (shown as In Progress), Waiting, Excluded or Other. You can also change the name shown in reports.

1. Excluded leaves those shots out of every count and cost. Use it for omitted shots.
2. Keep On Hold out of Excluded. Held money is still committed, and counts on purpose.
3. Anything left as Other shows as Other in the charts.

### 3. Save

Reports made from now on use the new groups.

**Press:** `Save`

✓ When it has worked: A message says your status groups are saved.


<a id="settings-updates"></a>

## Check for updates

*When: When you hear a new version is out. The app never checks by itself.*

See whether a newer version exists, and install it if you want to.

### 1. Choose which versions to see

On the Application tab, Update channel offers Match this build, Stable only or Include betas. It's kept as soon as you choose; usually leave it as it is.

### 2. Check

Press Check for Updates…. It only reads which version is newest, and nothing downloads yet.

**Press:** `Check for Updates…`

✓ When it has worked: A message says No update found, or which version is available.

### 3. Download it

If one is available, press Download & Install. It downloads the new version and checks it arrived intact.

1. If the message says this copy can't update itself, it says why. Press Open Release Page and download it from there instead.
2. Later closes the message without changing anything.

### 4. Install it

Save your work in other windows first. The app closes and opens again on the new version, and the old one is kept until the new one has started.

**Press:** `Close and Install`

✓ When it has worked: The app reopens, and the Application tab shows the new version next to Installed.


<a id="settings-delete"></a>

## Remove a show from this computer

*When: When a show has finished and you no longer want it in the project list.*

Remove the show's settings from this computer. Its data here is kept.

### 1. Delete the project

Pick the show in the Project list at the top of Settings, press Delete Project and confirm. Only its settings go; the show's data already on this computer is kept.

**Press:** `Delete Project`

✓ When it has worked: The show is gone from the project list.


## Words you'll see

- **Project** — One show's setup in the app. Pick the one you're working on from the list at the top of the window.
- **ShotGrid login** — The site address, a script name and its key, given by the ShotGrid administrator. They let the app read from ShotGrid and send to it.
- **Main machine** — The computer that keeps the show's finances. Setups are sent from it and received on the others, never the other way.
- **Setup file** — One file holding a show's whole setup, ShotGrid login included. Handle it like a password.
- **Field** — One piece of information ShotGrid keeps on a record, like a column in a spreadsheet.
- **Update channel** — Which new versions the update check offers: stable ones only, or test (beta) versions too.

[← All guides](README.md)

---

<sub>Generated 22 November 2026 for V4.35.0 from the app's own step lists, so the steps match the buttons in that version.</sub>
