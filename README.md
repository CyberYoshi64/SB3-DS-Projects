# SB3-DS-Projects

This repository contains SmileBASIC 3 projects that can be sent over to your 3DS into SmileBASIC's extData.

This repository should be used for demos or massive games (20+ MB projects)

---

## Repository updates

CyberYoshi64 will update this repository every week in order for the in-app downloader to work properly.

Only meta data will be refreshed.

---

## Add, Patch or Delete projects

### Requirements for adding projects

- Project files are contained in the project folder (keep folder and file names)
- Project files are copied straight from SmileBASIC's extData (raw format)
- `<project>/TMETA_NAME.TXT` - Name, creator and description of the project (have tag "Name:" etc. before the name and avoid using " ::")
- `<project>/meta_image.png` - 48x48¹ project icon as PNG.²

¹ If the icon is not 48x48 in size, it will be corrected to be 48x48 in `prjic.t3x`.

² A GRP located as `<project>/BMETA_IMAGE.GRP` can be used as a replacement and CyberYoshi64 will replace it with a png equivalent.

#### When requirements are met for your project…

Simply file a pull request to this repository by pasting the folder into the repository.

When wanting a deletion for a project, simply add a dummy `delete_it` file into the project folder.

Please don't abuse this to delete or corrupt projects that you haven't created yourself, unless there's a reason (takedown notice, etc.).

---

## Download projects to SmileBASIC

These steps cannot be followed since the app doesn't allow it yet.
Wait for the implementation by watching out for it [here](https://github.com/CyberYoshi64/SB-Download-Station/releases).

1. Open the **SmileBASIC Download Station** (3DSX/CIA).
2. Select ***Download menu***.
3. Choose a project you'd like to download, and select "**Download project**"
