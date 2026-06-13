# Compass v6.4

Static GitHub Pages build for Compass, the household planning app focused on answering: "Am I okay until the next paycheck?"

## Deploy to GitHub Pages
Upload these files from inside this folder to the root of your GitHub Pages repository:

- `index.html`
- `styles.css`
- `app.js`

Do not upload the enclosing folder unless your Pages repo is configured to serve from that folder.

## v6.3 Highlights

- Whimsical Compass visual polish: softer cards/buttons, vine accents, and garden footer art.
- Persistent header pill: **Available to Plan**, calculated only from accounts marked **Include in Planning**.
- Privacy setting to show/hide the Available to Plan header amount.
- First-time user prompt encouraging users to try Dark Mode, with Settings navigation.
- 360 Wealth View with account types for checking, savings, cash, credit card, investments, 401(k)/retirement, HSA, other assets, and debts.
- Advisor summary redesigned into softer action cards.
- Payment Type wording changed from `Unknown` to **Not Set**.
- Assign Money now supports two funding source modes: **Available to Plan** or **Paycheck**.
- Bucket frequency support: Weekly, Per Paycheck Cycle, or Monthly.
- Monthly Outlook bucket math now uses bucket frequency instead of multiplying by every paycheck occurrence.
- Compass Insights includes a **Refresh Insights** button and last-refreshed timestamp.
- 1–2 sentence purpose descriptions added to tabs.
- In-app Due Soon reminder surface on the Dashboard.

## Data Integrity Guardrails Preserved

- LocalStorage persistence.
- Export everything backup.
- Import preview before commit.
- Schema migration into v6.3.
- Backup size limit.
- Record count limits.
- String length limits.
- Normal dollar amount validation.
- Scientific notation rejection.
- Real calendar date validation.
- Invalid import data does not write to live data.

## Notes

This version does not include Supabase, Plaid, real push notifications, or a backend AI proxy. Those remain future cloud/PWA releases.


## v6.4 Update
- Removed Dashboard and Settings page descriptors.
- Redesigned Settings into topic cards with pop-up selection windows.
- Added Cottagecore Garden theme option with gentle adult-friendly playful animations and garden footer details.
- Adjusted mobile header so the menu trigger stays with the Compass name on the left while Available to Plan remains on the right.
- Preserved v6.3 import validation, backup preview, migration, amount/date safeguards, and local data integrity rules.
