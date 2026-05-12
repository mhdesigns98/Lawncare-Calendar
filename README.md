# 🌿 Lawn & Yard Master Calendar

A clean, single-file seasonal maintenance calendar for **Zone 7b Tall Fescue** lawns — built to live on GitHub Pages and be easy to fork and adapt for your own zone, grass type, and plants.

**[→ View live demo](https://your-username.github.io/lawn-calendar)**

---

## What it does

- Month-by-month lawn and plant tasks with season-aware layout
- Time-sensitive alerts for windows that are easy to miss (pre-emergent, overseed, aeration, etc.)
- Quick reference table of all task windows at a glance
- Emergency symptom guide for both lawn and plants
- Auto-defaults to the current month on load
- Zero dependencies — one HTML file, no build step, no npm

---

## Fork & customize

Everything you need to edit lives in three clearly labeled blocks inside `index.html`:

| Block | What to change |
| :--- | :--- |
| `CONFIG` | Zone, grass type, location, last updated date |
| `CALENDAR_DATA` | Month-by-month tasks — 12 objects, one per month |
| `QUICK_REF` | The task window table on the Quick Reference tab |
| `EMERGENCY` | The symptom/fix rows on the Emergency Guide tab |

No framework knowledge required — it's plain JS objects. If you can edit a grocery list, you can customize this.

---

## Deploy to GitHub Pages

1. Fork this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Done — your calendar will be live at `https://your-username.github.io/lawn-calendar`

---

## Data sources (Zone 7b / Tall Fescue)

- [NC State Extension — Tall Fescue Lawn Maintenance Calendar](https://extension.ces.ncsu.edu/lawn-maintenance-calendars/tall-fescue/)
- [proylaw.com](https://proylaw.com) — ZIP-code level scheduling tool

Adjust all timing to your microclimate, soil test results, drainage, and shade conditions. This is a starting framework, not a substitute for a soil test.

---

## License

MIT — do whatever you want with it.
