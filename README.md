# moon-tutorials

Downloadable tutorial resources for the moon-* apps (MoonLight, …). The apps don't ship them, so they stay small:
an app downloads a tutorial's files from this repository's releases the first time the tutorial starts, and checks
each file against the size and SHA-256 written in the app.

## Layout

- **One release per app and set**, tagged `<app>-<set>-<version>` — e.g. `moon-light-photos-1`. The files are the
  release's assets (not in the git tree), flat, named as the app asks for them.
- **A folder per app** in this repository (`moon-light/`, …) with the set's credits and notes.
- **Never replace an asset in a published release**: apps check every file by its digest. A changed set is a new
  release (`moon-light-photos-2`) and the app's manifest moves to it in the same app version.

Download URL: `https://github.com/moonbc-com/moon-tutorials/releases/download/<tag>/<file>`

## Sets

| App | Release | Contents | Size | Licence |
|---|---|---|---|---|
| MoonLight | `moon-light-photos-1` | 14 JPEGs (1800 px), 1 DNG, 1 CR3 for the four tutorials | 25 MB | CC0 (raw.pixls.us), see [moon-light/CREDITS.md](moon-light/CREDITS.md) |
