# ZOLL-Scheduler

Drag-and-drop training schedule builder for ZOLL Clinical Education deployments. Builds multi-week schedules like the Geisinger Community template and exports them as Letter-portrait PDFs, one page per week.

## Run it

It is a single self-contained file. Open `index.html` in a browser, or serve the repo with GitHub Pages. jsPDF loads from cdnjs, so an internet connection is needed for PDF export.

## Features

- Drag blocks from the library onto the week grid; move, resize (time and days), duplicate and delete them
- Snap to 30 or 15 minutes, overlap warnings, undo and redo
- Day patterns: standard day, evening SuperUser, early Advanced start, Advanced only with 1 or 2 SuperUsers. Save your own from a day's menu
- Copy a day to other days, clear a day, add or duplicate weeks
- Project details: hospital, contacts, training and go-live dates, footer stamp
- Vector PDF export that mirrors the Geisinger layout, with the ZOLL Clinical Education logo
- Autosaves in the browser; File > Save project file / Open project file for `.json` backups

## Keyboard

Double-click renames a block. Arrow keys nudge, Shift+Up/Down resizes, Delete removes, Ctrl+D duplicates, Ctrl+Z / Ctrl+Shift+Z undo and redo.
