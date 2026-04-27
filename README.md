# DailyQuest

DailyQuest is a static, single-page challenge website where players can solve daily coding prompts, answer trivia questions, complete logic puzzles, earn points, and climb a simulated live leaderboard.

## Features

- **Code Sprint:** JavaScript coding challenges with an in-browser editor, runnable tests, hints, reset, submit, timer, and point scoring.
- **Daily challenge rotation:** Seeded by date so the featured coding challenge changes automatically.
- **Math, science, and coding subjects:** Includes 12 coding challenges across Coding, Math, and Science.
- **Trivia Rush:** Timed 10-question trivia rounds with category selection.
- **Logic Lock:** Daily seeded logic puzzles covering deduction, sequences, ciphers, patterns, and ordering.
- **Leaderboard:** Simulated live leaderboard with animated point updates.
- **Account UI:** Login and account creation form mockup for a future user system.
- **Animated experience:** Responsive hero, particle effects, cursor trail, reveal animations, countdown, and confetti.

## Coding Challenge Subjects

### Coding

- Two Sum
- Contains Duplicate
- Reverse Words
- FizzBuzz
- Chunk Array
- Balanced Brackets
- Binary Search

### Math

- Prime Factors
- Triangle Number

### Science

- Gravity Drop
- Classify pH
- DNA Complement

## Tech Stack

- HTML
- CSS
- Vanilla JavaScript
- Tailwind CSS CDN
- Google Fonts
- Material Symbols

No backend, bundler, or package install is required.

## Project Structure

```text
dailyquest/
├── index.html
├── brief.txt
└── build-report.json
```

## Run Locally

Open `dailyquest/index.html` directly in a browser.

You can also serve the folder with any static server, for example:

```bash
cd dailyquest
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Deployment

DailyQuest can be deployed to any static host, including GitHub Pages, Netlify, Vercel, or Cloudflare Pages. The entry file is:

```text
dailyquest/index.html
```

## Notes

This project is currently fully client-side. The leaderboard and account form are simulated UI features, so they do not persist real user accounts or server-side scores yet.
