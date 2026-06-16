# Compass v6.5.2.4

Starter household + bucket/savings goal logic patch.

## What changed
- New starter households no longer show Nick/Danielle; household members start empty until the user adds people.
- Existing helpful example Accounts/Buckets/Savings Goals remain generic.
- Available to Plan language replaces Still Unassigned anywhere it refers to free planning dollars.
- Account and 360 Wealth View cards now handle larger dollar amounts without overflowing.
- Bucket frequency labels explain their reset behavior.
- Monthly buckets reset on the 1st of each month; weekly buckets reset weekly; per-paycheck buckets reset by paycheck period; one-time buckets stop recommending after funded.
- Savings Goals now have contribution frequency: Monthly, Per Paycheck, or One-Time.
- Assign Money recommends the planned savings contribution amount, not the full remaining goal balance.
- Savings Goals now support Move to Saved / Undo Saved, mirroring Mark Paid / Undo Paid for bills.
- Import/export migration keeps older backups viable and preserves v6.5.2.3 active funding reservations.

## Deploy
Upload `index.html`, `app.js`, `styles.css`, and `README.md` to the repo root. No asset folder is required for this patch.
