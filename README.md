# PrepDB

A feature-complete Progressive Web App for competitive exam preparation. Built solo in vanilla JavaScript. Originally developed for KIITEE (engineering entrance) prep.

Live: https://prepdb.netlify.app

## Features

**Dashboard**
- Exam countdown timer
- Overall progress percentage
- Task completion summary
- Study streak tracker
- Per-subject progress bars (Physics, Chemistry, Mathematics)

**Study Planning**
- AI Timetable Maker — describe your situation, set exam date, daily hours, weak subjects, and study style; generates a personalized weekly plan
- Schedule builder with custom study slots
- Task manager with priority levels (High / Medium / Low) and carry-over for incomplete tasks

**Focus & Productivity**
- Pomodoro timer (Work / Short Break / Long Break modes)
- Timer alerts
- Session stats — total sessions, today's sessions, total focus time

**Progress Tracking**
- Mock test logger — log scores by subject or full mock
- Score trend chart with subject filters
- Study session quick-log

**Notes**
- Note creation with date-based sorting

**Customization & Data**
- 6 themes: Dark, Deep Space, Light, Midnight, Neon, Amber
- Data export and import (JSON)
- PWA — installable, offline-capable

## Tech Stack
- HTML · CSS · Vanilla JavaScript
- GitHub Pages + Netlify (deployment)
- PWA (Web App Manifest + Service Worker)

## Setup
No build step required.

```bash
git clone https://github.com/adyaanurag-panigrahi/prepdb.git
cd prepdb
open index.html
