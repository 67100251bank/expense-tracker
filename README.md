# สมุดรายจ่าย (Expense Tracker)

A single-page, offline-first expense tracker in Thai, styled like a bank passbook. No backend — everything runs in the browser.

## Features

- **Passbook-style monthly summary** — total spent this month, daily average, and a progress bar against your monthly budget.
- **Quick entry form** — date, amount, category, and note.
- **Slip (receipt) upload** — attach one or more photos of transfer slips; the app reads amount, date, and recipient for you to review before saving.
- **Charts** — pie chart of spending by category, bar chart of daily spending (via Chart.js).
- **Monthly filtering** — switch months with a picker, filter the transaction table by category.
- **Monthly budget** — set a budget per month and track remaining balance.
- **Dark mode** — follows system theme, with manual override.

## Data storage

Entries are saved to the browser's `localStorage` (key `expense-ledger`) — no server, no account needed. Data stays on the device that entered it.

## Files

- `สมุดรายจ่าย/สมุดรายจ่าย/สมุดรายจ่าย.html` — the app (open directly in a browser).
- `สมุดรายจ่าย/สมุดรายจ่าย/ข้อมูลรายจ่าย.json` — sample/exported expense data.
- `สมุดรายจ่าย.zip` — original archive.

## Usage

Open `สมุดรายจ่าย.html` in any modern browser. No build step or install required.
