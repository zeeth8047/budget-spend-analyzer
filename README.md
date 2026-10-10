# Budget Spend Analyzer

A private, single-file budget app. No build step, no dependencies, works offline.

## What's inside

- **Overview** — month snapshot (income, bills due, spent, remaining) plus a
  "what to pay" schedule sorted by due date, with overdue / due-soon badges
  and per-bill paid checkmarks.
- **Bills** — recurring monthly bills (due day, autopay flag) and one-time
  bills with exact dates.
- **Spending** — quick expense logging with categories and category totals.
- **Income** — monthly or bi-weekly paychecks; bi-weekly pay is split across
  the months it actually lands in.

## Storage

Everything is stored in the browser's `localStorage` on the device you open
it on (`bsa-v1` key). Nothing leaves your device. Use **Export** in the app
to download a JSON backup, and **Import** to restore it.

## Use on iPhone

1. Open `budget-spend-analyzer.html` in Safari.
2. Tap **Share → Add to Home Screen**.
3. It launches full-screen like a native app, with its own icon.

## Files

- `budget-spend-analyzer.html` — the entire app (HTML + CSS + JS, self-contained).
