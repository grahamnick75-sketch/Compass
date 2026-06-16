# Compass v6.5.2.3

Assign Money + Paid Bills Hotfix.

## What changed
- Assign Money now reserves dollars as active assigned money.
- Still Unassigned = included planning balances minus active assigned money.
- Assign Money has a sticky Available to Assign summary that updates live.
- Bills can be marked paid with payment date, paid amount, and optional account-balance update.
- Paid bill records can be undone.
- Active funding sessions can be reversed from Funding History.
- Old backups still import safely; older funding history is imported as history only, not active reserved money.

## Deploy
Upload `index.html`, `app.js`, `styles.css`, and `README.md` to the repo root. No asset folder is required for this hotfix.
