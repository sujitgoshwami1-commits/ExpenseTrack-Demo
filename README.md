# ExpenseTrack — Business Expense & Reimbursement Manager

A single-file, offline-friendly expense management system for tracking business spending and employee reimbursements — with receipt image attachments and monthly budget tracking per category.

**[View Live Demo →](#)** *(replace with your GitHub Pages demo link)*

---

## Features

- **Expense Logging** — date, employee, category, amount, description, and receipt image, all in one entry
- **Receipt Attachments** — attach a photo of any receipt or bill; images are automatically compressed so they stay lightweight
- **Reimbursement Workflow** — track each expense through Pending → Approved / Rejected → Reimbursed
- **Employee Tracking** — see who submitted what, and how much each person has spent this month
- **Category Budgets** — set a monthly budget per category and see spend vs. budget at a glance, with an over-budget warning
- **Reports Dashboard** — budget vs actual, spend by category, spend by employee, status breakdown
- **Day / Night theme** — toggle between light and dark mode
- **No backend required** — runs entirely in the browser using LocalStorage; no server, database, or account needed
- **Responsive** — works on desktop, tablet, and mobile

## Getting Started

1. Download or clone this repository
2. Open `index.html` in any modern browser
3. That's it — demo data loads automatically on first run

No build step, no dependencies, no installation.

## Tech Stack

- HTML5, CSS3 (custom properties for theming), vanilla JavaScript
- Browser LocalStorage for data persistence, with client-side image compression (Canvas API) for receipts
- Google Fonts (Space Grotesk, Inter, JetBrains Mono)

## Data & Privacy

All data — including receipt images — is stored locally in your browser's LocalStorage. Nothing is sent to any server. Clearing your browser data will reset the app; use the **Reset Demo Data** button in the sidebar to restore the sample dataset at any time.

## Important

This is a front-end, browser-based application. It does not include a hosted backend, cloud database, user authentication, or server-side sync across devices.

Your data persists in the browser until you clear site data or use the Reset Demo Data button — it does **not** auto-reset on its own, so it's safe for real day-to-day use. (The separately hosted live demo does reset nightly, so visitors always see a clean sample dataset — that behavior is not present in this package.)

Because receipt images are stored as part of the browser's LocalStorage, very large numbers of high-resolution receipts may approach the browser's storage limit (typically 5–10MB per site). Images are compressed automatically to reduce this risk.

## License

See `LICENSE` file.

## Support

Built and maintained by UpComing Solution. For customization, bulk licensing, or a hosted/multi-user version with a real backend, get in touch.
