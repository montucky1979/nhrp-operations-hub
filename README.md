# NHRP Operations Hub — Copy Buttons Update

This build is based on the latest Filters/Categories version.

## Added
- A **Copy** button beside every **Spawn Code** shown in a table.
- A **Copy** button beside every **Discord ID** shown in a table.
- Clicking it copies the exact value and shows the existing **Copied** toast.

This is applied automatically by the shared table renderer, so it covers current and future tables whose column header is exactly `Spawn Code` or `Discord ID`.

## Install
Replace these files in the current Operations Hub:
- `app.js`
- `styles.css`
- `index.html` (safe to replace with this matching build)
- `assets/` and `templates/` if you are replacing the whole package

Keep your current working `config.js`.

No Supabase SQL update is required for this change.
