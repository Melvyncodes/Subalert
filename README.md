# SubAlert — Subscription Tracker

> Never get surprised by a charge again.

SubAlert is a lightweight, privacy-first subscription tracker that runs entirely in your browser. No accounts, no backend, no data leaving your device. Just add your subscriptions and see exactly what's about to hit before it does.

**[Live Demo →](https://yourusername.github.io/subalert)**

---

## Why I Built This

Ever been on your last dime and a forgotten subscription just hits? Happened to me. It's easy to overlook small recurring charges — so I built something simple to see what's coming before it does.

---

## Features

- **Dashboard** — Total monthly spend, active subscription count, and your next upcoming charge at a glance
- **Upcoming Charges** — Subscriptions grouped by Due Today, Due This Week, and Due This Month
- **Multi-Currency Support** — Track in NGN, USD, EUR, GBP, or JPY. All totals are converted to Naira using live exchange rates
- **Flexible Billing Cycles** — Monthly, yearly, weekly, and quarterly — all normalized to a monthly figure
- **Search & Filter** — Find any subscription instantly by name or billing cycle
- **Add, Edit, Delete** — Full subscription management with instant re-render
- **Privacy First** — Everything lives in your browser's `localStorage`. Nothing is ever sent anywhere
- **Responsive** — Works on desktop, tablet, and mobile with a bottom nav bar on small screens

---

## Tech Stack

- **HTML5** — Single file, no build step
- **CSS3** — Custom properties, flexbox, animations, responsive media queries. Typography via Google Fonts (DM Sans + DM Mono)
- **Vanilla JavaScript** — No frameworks, no libraries. Just DOM + localStorage

---

## Getting Started

No installation needed. Just open the file:

```bash
git clone https://github.com/yourusername/subalert.git
cd subalert
open index.html
```

Or just visit the [live version](https://yourusername.github.io/subalert).

---

## Data & Privacy

All data is stored locally in your browser under the key `subalert_v2`. Nothing is ever sent to a server.

Clearing your browser's site data or using the **Clear All Data** button in Settings will permanently delete your records.

---

## Built in Public

This project was built day by day, shared openly as it grew.

| Day | What happened |
|-----|---------------|
| 1 | Brainstormed the idea and picked the stack |
| 2 | Set up base CSS, HTML layout, dashboard UI, and the Add Subscription form |
| 3 | Implemented core JS logic and localStorage persistence |
| 4 | Added edit and delete functionality with instant re-render |
| 5 | Rest day |
| 6 | Polished UI — replaced all emojis with SVG icons, fixed responsive layout, added mobile bottom nav |
| 7 | Added live currency conversion — USD, EUR, GBP, JPY all convert to NGN in the total |

---

## Exchange Rates

Currency totals are converted to NGN using the following rates (last updated May 2026):

| Currency | Rate |
|----------|------|
| 1 USD | ₦1,388 |
| 1 EUR | ₦1,602 |
| 1 GBP | ₦1,837 |
| 1 JPY | ₦8.70 |

---

## License

MIT — free to use, fork, and build on.
