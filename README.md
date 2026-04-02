# /// Applyd

**A data-driven job application tracker. One HTML file. No account, no server, no tracking.**

Built during dozens of real applications. Because spreadsheets don't tell you your interview rate.

→ **[Download applyd.html](https://github.com/KonradFrankDE/applyd/raw/main/applyd.html)** and open it in your browser. That's it.

---

## What it does

Applyd tracks your job applications and turns them into insight:

- **Dashboard** — 5 KPIs at a glance: response rate, interview rate, ghosting, frequency, total
- **Active Applications** — waiting time per application, next steps, due dates
- **Analytics** — funnel, stage breakdown, CV version performance, cover letter performance, role fit distribution, monthly activity, rejection patterns
- **Application log** — full table with quick-status, search, and filter
- **Interview history** — per-application timeline with stage, partner, rating, notes
- **Export** — CSV (Excel/Numbers) and JSON backup

---

## How to use

1. Download [`applyd.html`](https://github.com/KonradFrankDE/applyd/raw/main/applyd.html)
2. Open it in any modern browser (Chrome, Firefox, Safari, Edge)
3. Go to **Settings** → add your CV versions
4. Start tracking

All data is saved in your browser's `localStorage`. Nothing leaves your device.

---

## Features

| | |
|---|---|
| 🌐 DE / EN | Language toggle in Settings |
| 🌓 Dark / Light | Theme toggle in Settings |
| 📤 Export | CSV and JSON |
| 📥 Import | JSON re-import with duplicate detection |
| 📱 Responsive | Mobile, tablet, desktop |
| 🔒 Private | No server, no account, no analytics |
| ⚡ Zero dependencies | No frameworks, no CDN, no build step |

---

## Data model

Each application tracks:

`Position · Company · Date · Location · Status · First response · CV version · Cover letter (yes/no) · Role fit (1–3) · Channel · Contact · Next step · Due date · Salary expectation · Rejection reason · Link · Interview history`

**Status values:** Waiting → Interviewing → Closed / Self-cancelled

**Role fit:** 1 Stretch · 2 Match · 3 Strong Fit

---

## Privacy

- All data stored locally via `localStorage`
- No external requests (Google Fonts removed)
- No tracking, no analytics, no cookies
- Export your data anytime as JSON

---

## Background

I applied to dozens of positions over several months while tracking everything in a spreadsheet. At some point I wanted to know: what's my actual interview rate? Which CV version performs better? Where do I lose processes?

Applyd is the tool I built to answer those questions — in collaboration with [Claude](https://claude.ai) by Anthropic, without writing a single line of code manually. It's a single HTML file because that's the simplest thing that could possibly work — and simplicity is a feature.

---

## License

MIT © 2026 Konrad Frank

---

## Author

**Konrad Frank** — Engineering Leader, DACH

[LinkedIn](https://www.linkedin.com/in/konrad-frank) · [GitHub](https://github.com/KonradFrankDE)
