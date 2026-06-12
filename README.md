# The Cozy Ledger v5

Upload these files to your GitHub Pages repository root:
- index.html
- styles.css
- app.js

## v5 includes
- Cleaner phone navigation: Dashboard and Accounts stay visible; the rest lives in a More sidebar.
- Delete buttons everywhere.
- Edit buttons everywhere.
- Archive items instead of deleting.
- Undo after delete.
- Search and sort lists.
- Empty states.
- Save confirmations.
- Mark bills/paychecks by status.
- Partial funding display for bills.
- Monthly calendar view.
- Financial runway/funded-through date.
- Today's Financial Mission.
- Financial Inbox.
- Can We Afford It? simulator.
- Assign Money visual flow.
- What Changed? history feed.
- AI Guide with local summary fallback.
- Import/export backup and daily backup snapshot.
- Theme toggle: Cozy Ledger, Classic, Dark Mode.

## Important
This is a static GitHub Pages app using browser localStorage. Export backups before replacing versions.


## v5.1 Patch
- Import backup now accepts older Cozy Ledger backup formats and v5 backups.
- Converts old fields like `balance`, `dueDate`, and `nextDate` into the v5 schema.


## v5.2 Import Patch
This version includes a migration importer for older Cozy Ledger backups that used fields like `balance`, `dueDate`, `nextDate`, `person`, `frequency`, and `recurrence`.
