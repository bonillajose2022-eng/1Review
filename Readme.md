# 🎓 English Kids A1–A2 — Interactive Learning App

A fully self-contained interactive English learning web app for children aged 8–12. Covers four A1–A2 grammar topics through lessons, videos, exercises, games, and a final quiz — all in a single HTML file, no installation required.

---

## 🚀 How to Use

1. Download `english-kids.html`
2. Open it in any modern browser (Chrome, Firefox, Edge, Safari)
3. No internet connection required after first load\*

> \*Google Fonts loads from the web on first visit. Everything else works offline.

---

## 📚 Content Overview

### 4 Grammar Lessons

| # | Topic | Key Concepts |
|---|-------|-------------|
| 1 | 📝 **Verb To Be** | am / is / are, contractions, yes/no questions |
| 2 | 🔤 **A / An** | vowel vs consonant sounds, articles |
| 3 | 🏡 **There is / There are** | singular, plural, uncountable, negatives, questions |
| 4 | 📍 **Prepositions** | in, on, under, next to, behind, between, in front of |

Each lesson includes:
- 📖 **Lesson cards** — rules, examples, and common mistakes
- 📚 **Glossary** (Prepositions lesson) — 16 vocabulary items with Spanish translations
- 🎬 **3 videos** with embedded mini-quizzes (3 questions each)
- 🖼️ **Interactive SVG scene** — True/False statements + object counting

---

### ✏️ Practice Section — 46 Exercises

| Type | Count | Description |
|------|-------|-------------|
| Fill in the Blank | 15 | Complete sentences with the correct word |
| Multiple Choice | 14 | Choose from 4 options |
| Matching | 5 sets | Connect pairs (25 pairs total) |
| Unscramble | 8 | Arrange words into correct sentences |
| Writing | 4 | Open-ended prompts with model answers |

---

### 🎮 4 Mini-Games

| Game | Description |
|------|-------------|
| 🔍 **Find the Objects** | Type objects you can see in the classroom scene |
| 🕵️ **Classroom Detective** | Answer questions about the scene (short answers accepted) |
| 🏗️ **Sentence Builder Race** | Arrange word chips into correct sentences in 90 seconds |
| 📍 **Preposition Challenge** | Visual SVG scenes — choose the right preposition |

Each game saves a **high score** that persists across sessions.

---

### 📝 Final Quiz

- **15 questions** covering all 4 topics
- Mix of MCQ, fill-in-blank, and writing
- **One attempt only** — tracks score permanently
- Results show grade (A/B/C/D), points, and answer review

---

## 📊 Progress Tracking

- **Overall progress bar** on the home screen
- **Per-topic progress bars** (Verb To Be, A/An, There is/are, Prepositions)
- Stats: videos completed, exercises done, total points, quiz score
- **8 unlockable achievement badges**
- All progress saved automatically in `localStorage`

---

## 👩‍🏫 Teacher Mode

Activate with password: **`TEACHER123`**

Features:
- **Reveal Answers** — shows correct answers for all fill-in and MCQ exercises
- **Reset Progress** — clears all student progress
- **Reset Quiz** — allows the student to retake the final quiz

---

## 🗺️ Suggested Study Path

```
1. Verb To Be → 2. A/An → 3. There is/are → 4. Prepositions → 5. Practice → 6. Final Quiz
```

---

## 🛠️ Technical Details

| Property | Value |
|----------|-------|
| File type | Single HTML file |
| File size | ~163 KB |
| Dependencies | Google Fonts only (optional) |
| Browser support | All modern browsers |
| Mobile | ✅ Fully responsive |
| Internet | Required only for fonts & YouTube videos |
| Storage | `localStorage` (browser) |

### Architecture
- **Zero build step** — open and use directly
- **Lazy rendering** — pages build only when visited
- **No frameworks** — vanilla HTML, CSS, and JavaScript
- **SVG scenes** — all illustrations inline, no external images

---

## 🌐 Deployment Options

### Option A — Local use
Simply open `english-kids.html` directly in a browser.

### Option B — GitHub Pages
1. Create a new GitHub repository
2. Upload `english-kids.html` and rename it `index.html`
3. Go to **Settings → Pages → Deploy from branch → main**
4. Your app will be live at `https://yourusername.github.io/repo-name`

### Option C — Any web server
Upload the single file to any static hosting (Netlify, Vercel, etc.).

---

## 📁 Files

```
english-kids.html   ← The complete app (open this!)
README.md           ← This file
```

---

## 🎨 Design

- **Colors:** Purple `#7c4dff` · Teal `#00bfa6` · Yellow `#ffca28`
- **Fonts:** Baloo 2 (headings) · Nunito (body)
- **Theme:** Playful and child-friendly, suitable for ages 8–12

---

*Built for A1–A2 English learners. Content reviewed for grammatical accuracy.*
