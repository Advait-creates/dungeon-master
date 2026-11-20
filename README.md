# Dungeon Master — Gamified Study Platform

An RPG-style study platform that turns studying into a game: earn XP, level up, keep streaks alive, and unlock profile customizations while you learn.

Built July–October 2025. Grew to 400+ registered accounts.

## Features

- **Flashcards** — create your own decks and cards, with multiple study modes
- **Spaced repetition** — reviews scheduled around what you actually remember
- **Pomodoro timer** — focused study sessions that feed your progress
- **Brain blurts** — free-recall dumps to test what stuck
- **Study logging & analytics** — session history and charts of your activity
- **RPG progression** — XP for studying, levels, daily streaks, and rewards for perfect sessions
- **Profile customization** — unlockable avatars and themes as you level up
- **Accounts & cloud data** — Firebase Authentication and Firestore, so decks and progress follow you across devices

## Tech stack

- React 18 (Create React App) + React Router 7
- Firebase 12 — Auth + Firestore
- Tailwind CSS for the dungeon/retro themed UI
- Recharts, date-fns, lucide-react
- Deployed on Vercel, with Vercel Analytics and Speed Insights

## Run it locally

```bash
npm install
npm start        # development server
npm run build    # production build
```

Firebase configuration lives in `src/firebase.js` — point it at your own Firebase project to run your own instance.

## About this repo

Dungeon Master was originally developed in 2025 under my previous GitHub account (Pizzasamrad/study-app). In November 2026 I forked it to this account (Advait-creates) so all of my work lives in one place — the full original commit history (July–November 2025) is preserved here.
