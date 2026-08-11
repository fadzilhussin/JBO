# 🎨 The Workshop — Crew Creations

A little corner of the internet where the iO3 IT crew pins the things we build for fun —
trackers, tools, experiments, and whatever else we dream up.

**Live site:** https://YOUR-USERNAME.github.io/team-workshop/
_(replace with your real GitHub Pages URL once it's live)_

---

## What's in here

| File | What it is |
|------|------------|
| `index.html` | The Workshop wall — the landing page everyone sees first |
| `road-to-doomsday.html` | The Road to Doomsday Marvel watch-tracker (the first creation) |

Every creation is a plain, self-contained `.html` file. No build step, no dependencies —
open any of them in a browser and they just work.

---

## ➕ Add your creation

There are two ways in. Pick whichever you're comfortable with.

### Option A — No code (easiest)
1. Upload your `.html` file to this repo (**Add file → Upload files**, drop it in the root).
2. Open a new issue using the **"New creation"** form and fill in the fields.
3. A maintainer adds your card to the wall. Done.

### Option B — Do it yourself (a two-line change)
1. Upload your `.html` file to the repo root (same folder as `index.html`).
2. Open `index.html`, scroll to the `WORKS` list near the bottom, and add an entry:

```js
{
  title: "My Cool Thing",
  author: "Your Name",
  desc:  "One or two lines on what it is.",
  tag:   "Experiment",
  url:   "my-cool-thing.html",   // must sit in the same folder as index.html
  accent:"coral"                 // coral · amber · teal · blue · violet · pink
},
```

3. Commit (or open a pull request). GitHub Pages redeploys within about a minute.

> **Tip:** newest entries go at the **top** of the `WORKS` list.

---

## Run it locally

No server needed — just double-click `index.html` (or any page) to open it in your browser.

---

## House rules
- Keep it a single self-contained `.html` file where you can.
- This repo is public — never commit passwords, keys, or anything private.
- Have fun with it. That's the whole point. ◆
