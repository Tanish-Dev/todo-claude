<div align="center">

# ✦ Things

### Tasks, beautifully done.

A gorgeous, glassmorphic todo app and matching landing page — built as a single, dependency‑free HTML file each. No build step, no framework, no backend. Just open and go.

<br/>

`Glassmorphism UI` · `Dark / Light` · `8 Accent Themes` · `Offline‑first` · `Zero dependencies`

`Tasks` · `Habits` · `Focus Timer` · `Notes` · `Spending` · `Countdowns` · `Quick Tools`

</div>

---

## ✨ Overview

**Things** is a fully‑featured personal productivity hub that runs entirely in the browser. It started as a task manager and now lives up to its name — a small suite of genuinely useful everyday **things**: tasks, habits, a focus timer, quick notes, spending, countdowns and a set of pocket utilities. Everything lives in `localStorage`, so it works offline and your data never leaves your device. The whole app is one self‑contained file: HTML, CSS, and vanilla JavaScript with no external requests.

It ships with four working sections — **Home**, **Tasks**, **Calendar**, and **Profile** — tied together by a frosted‑glass floating island navbar, and the **Home** screen doubles as a dashboard of live tool widgets.

---

## 📂 What's in this repo

| File | Description |
| --- | --- |
| **`index.html`** | The Things app — the full task manager described below. |
| **`landing.html`** | A polished marketing landing page for the app: pill navbar, two‑column hero with CSS app mockups, structural grid background, and a large footer wordmark. |
| **`README.md`** | You're reading it. |

---

## 🚀 Features

### 🏠 Home dashboard
- **Time‑aware greeting** (Good Morning / Afternoon / Evening) with your name
- **Live progress ring** showing today's completion percentage
- **Day‑streak counter** that rewards consecutive days of getting things done
- **In‑Progress carousel** — horizontally scrolling gradient cards for tasks already underway, sorted by progress
- **Today's Tasks** list with instant inline search

### ✅ Task management
- **Rich tasks** with title, notes, priority, category, due date & time, tags, and subtasks
- **Priority levels** — High / Medium / Low, each colour‑coded
- **Subtask checklists** that automatically drive the parent task's progress
- **Progress slider** — a beautiful bottom‑sheet slider with quick‑set chips (0 / 25 / 50 / 75 / Done) for tasks without subtasks
- **Pin to top**, **duplicate**, **edit**, and **delete** from a per‑task context menu
- **Recurring tasks** — daily, weekly, or monthly; completing one spawns the next occurrence automatically
- **Tags** with `#chip` rendering and search
- **Smart sorting** — Smart, Priority, Due date, Progress, Newest, or Name A–Z
- **Filtering** — All / Today / High / Medium / Low / Done, plus a dynamic chip per category
- **Undo** — deleting a task surfaces a toast with a 5‑second undo

### 📅 Calendar
- Full **month grid** with prev / next navigation and a jump‑to‑today button
- **Task dots** on every day, colour‑matched to each task's category
- Tap any date to see its scheduled tasks; the **+** button pre‑fills that day's date

### 👤 Profile & settings
- **Editable name** and auto‑generated avatar
- **Lifetime stats** — total tasks, completed, and completion rate
- **Dark / Light mode** (follows your system preference until you choose)
- **8 accent colours** — recolour the entire app instantly
- **Celebrate completions** toggle — confetti bursts when you finish a task
- **Category manager** — create and delete colour‑coded categories
- **Export / Import** your whole dataset as JSON for backup or transfer
- **Clear all data** with a confirmation guard

### 🧰 Everyday tools (Home dashboard widgets)
Beyond tasks, the Home screen is a command center of live widgets — each expanding into a full bottom‑sheet tool:

- **⏱️ Focus timer** — a Pomodoro timer with a live ring; configurable focus/break lengths (15–60m / 5–15m), auto‑switching between work and break, confetti on completion, and per‑day session + minute stats
- **✅ Habit tracker** — build daily routines with one‑tap completion, 🔥 streak counts, custom emoji icons and colours; reuses the app's streak/ring language
- **📝 Quick notes** — capture a thought instantly from Home, then manage everything (search, pin, edit, delete) in a full Notes sheet
- **💸 Spending tracker** — log expenses by category (Food, Transport, Bills…), with live **today** and **this‑month** totals and a recent‑expenses list
- **⏳ Countdowns** — "X days until…" for birthdays, trips and deadlines; the soonest event surfaces right on Home
- **🔧 Quick tools** — a pocket utility grid: **Tip splitter** (bill ÷ people with tip %), **Unit converter** (length / weight / volume / temperature), **Password generator** (length + character‑set toggles, crypto‑strong, one‑tap copy), and a **Calculator**

All tool data is included in **Export / Import** and **Clear all data**, so your whole life‑OS travels in one JSON file.

### 🎨 Design
- **Glassmorphism everywhere** — frosted blur, layered translucency, inner highlights, and soft shadows on every surface
- **Ambient gradient orbs** in the background that the glass blurs against
- **Floating island navbar** with a pill of circular tab buttons
- **Buttery micro‑interactions** — view transitions, card entrances, sheet slide‑ups, spring toggles, and a confetti celebration
- **Consistent typography** — system San‑Francisco font stack with a tight `-0.05em` letter‑spacing throughout
- **Fully responsive** and tuned for mobile: safe‑area insets, 16px inputs (no iOS zoom), `100dvh`, and touch‑friendly targets

---

## 🛠️ Tech

- **HTML + CSS + vanilla JavaScript** — no frameworks, no libraries, no build tools
- **CSS custom properties** for theming, accent colours, and glass tokens
- **`localStorage`** for persistence (key: `things_v4`)
- **`backdrop-filter`** for the glass effect
- **Web Animations API** for the confetti
- **`prefers-color-scheme`** for automatic dark/light detection

> Zero dependencies. The entire app is ~1,400 lines in a single file.

---

## ▶️ Getting started

No installation, no server required.

```bash
# clone
git clone https://github.com/Tanish-Dev/todo-claude.git
cd todo-claude

# open the app
open index.html        # macOS
# or just double‑click index.html in your file browser
```

Then optionally open `landing.html` to view the marketing page.

That's it — start adding tasks with the **+** button.

---

## ⌨️ Shortcuts

| Action | Shortcut |
| --- | --- |
| Save task (while the sheet is open) | `⌘ / Ctrl` + `Enter` |
| Close any sheet / menu | `Esc` |
| Add subtask (in the subtask field) | `Enter` |

---

## 💾 Data & privacy

Everything is stored locally in your browser via `localStorage`. Nothing is uploaded, tracked, or sent anywhere — there are no network requests at all. Use **Profile → Export data** to create a JSON backup, and **Import data** to restore it on another device or browser.

---

## 🗺️ Project structure

```
todo-claude/
├── index.html      # The Things app (task manager)
├── landing.html    # Marketing landing page
└── README.md
```

Both HTML files are completely self‑contained — styles and scripts are inlined.

---

<div align="center">

Made with care · `letter-spacing: -0.05em`

</div>
