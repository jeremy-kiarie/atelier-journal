# Atelier Journal

A premium, offline-first digital bullet journal for Windows and macOS. Calm, personal, and deeply customizable — built for people with zero technical experience.

## Features

- **Daily journal** — freeform writing, photos, quotes, checklists, stickers, and widgets with autosave
- **Mood garden** — multi-emotion logging, intensity, heatmaps, and gentle trend charts
- **Monthly log** — calendar, timeline, habits, goals, and reflection views
- **Month & year recaps** — Spotify Wrapped–style summaries with PDF export
- **Birthdays** — countdowns, gift ideas, and reminders
- **Life trackers** — habits plus custom trackers with weekly streaks
- **Themes** — cozy, minimal, dark, vintage, scrapbook, cyber, seasonal, and more
- **Backup** — export/import full journal as JSON (desktop file picker in Electron)
- **Gentle AI** — on-device reflection prompts (cloud AI optional later)

## Quick start

```bash
npm install
npm start
```

`npm start` launches the Vite dev server and Electron together.

### Web-only preview

```bash
npm run dev
```

Open http://localhost:5173 — works in the browser with IndexedDB storage (backup uses download instead of native dialogs).

## Build installers

```bash
npm run dist:win   # Windows NSIS installer → release/
npm run dist:mac   # macOS DMG (run on macOS)
```

## Privacy

All journal data stays in a local IndexedDB database on your device. No account required. Cloud sync can be added in a future release.

## Stack

- Electron + React + TypeScript + Vite
- Dexie (IndexedDB) for offline-first storage
- Framer Motion, Recharts, jsPDF

---

*Atelier* — your digital sanctuary for reflection, memory, and growth.
