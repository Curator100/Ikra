# 🎯 HSC Hero — তোমার স্বপ্নের পথে

A vibrant, colorful HSC study companion PWA built for Bangladeshi students.

## 📁 Files (all flat — no subfolders needed)

```
index.html          ← Main app
manifest.json       ← PWA manifest
sw.js               ← Service worker (offline support)
netlify.toml        ← Netlify config
icon-192.png        ← App icon 192×192
icon-512.png        ← App icon 512×512
supabase-setup.sql  ← Run once in Supabase SQL editor
```

## 🚀 Deploy Steps

### 1. Supabase Setup
- Go to your Supabase project → SQL Editor → New Query
- Paste the contents of `supabase-setup.sql` and run it

### 2. GitHub
- Create a new repo
- Upload all files (drag & drop all into the repo root)
- No subfolders needed

### 3. Netlify
- Connect Netlify to your GitHub repo
- Publish directory: `.` (root)
- Deploy!

### 4. Install as PWA on Chrome Android
- Open the deployed URL in Chrome
- Tap the "Add to Home Screen" banner or ⋮ → Add to Home Screen
- Done! Works offline too.

## ✨ Features
- 📅 HSC countdown (days to 2 July 2026)
- ⏱️ Study time calculator (12-hour AM/PM, persists on refresh)
- 📊 Study stats: today / this week / this month
- 🔄 Smart revision schedule (Day 1, 3, 6, 10, 15)
- 📚 12 subjects × chapter bubbles (Red → Yellow → Green)
- 🌳 Duolingo-style chapter progress tree (14 steps)
- 🍅 Pomodoro timer (25 min, phone vibrates on finish)
- 🕌 5-waqt Namaz tracker
- 📱 Full PWA — installable, offline-capable
