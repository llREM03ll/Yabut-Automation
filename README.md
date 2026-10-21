# Yabut Group Ledger

Single-file web app for encoding materials, creating a Bill of Materials and statements, and tracking progress.

## Use
Open `index.html` in a browser, or turn on GitHub Pages (Settings > Pages > Deploy from branch > main > root).

## Notes
- Data is saved in the browser (localStorage). Use Project > Backup to copy a backup.
- Import accepts Excel ledgers with columns like ITEM NO, DESCRIPTION, QTY, UNIT, HARDWARE, UNIT COST, DELIVERY DATE.
- Uses SheetJS 0.18.5 from cdnjs for reading Excel files.
