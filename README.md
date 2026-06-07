# SunForge Cordoba PO System

This repository currently hosts the Netlify doorway for the Cordoba PO system.

## Current production approach

- Netlify = doorway / launch page
- Google Apps Script = working PO app and backend
- Google Sheet = PO data storage
- Google Drive = PDF archive
- SunForge HQ = later link only

## Current version

Cordoba PO Google-only R30 Drive Save.

## Important

Do not merge the full Cordoba PO logic into SunForge HQ yet.
Do not overwrite the Golden R30 recovery folder.
Do not use old R29 files as production.

## Setup

Edit `index.html` and replace:

- `PASTE_CORDOBA_PO_WEB_APP_URL_HERE`
- `PASTE_CORDOBA_PO_PDF_ARCHIVE_URL_HERE`

Then commit and push to GitHub. Netlify will deploy the doorway.


## R30 Production URL Status

The Netlify doorway index.html has been updated with the current Google Apps Script Web App URL. The PDF archive URL is intentionally not published in this public repository.
