# Mushroom Batch Logging System

This web interface is used to log mushroom batch actions (stage changes, harvest, notes, weights) into Google Sheets using QR codes.

## Pages
- `form.html` - Logging form (auto-filled via QR codes)
- `qr.html` - Generates QR codes for each Batch × Species
- `scanner.html` - Camera-based QR scanner
- `species_batches.json` - List of batch/species pairs generated from spreadsheet

## Deployment
Hosted via GitHub Pages.

Backend is a Google Apps Script Web App that writes logs to the Sheet6 tab of the Google Sheet.
