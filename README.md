# InflowMap

A calm, local-first personal study planner built around one loop: **Plan → Execute → Track → Adapt**.

Built as a single self-contained HTML app — no build step, no dependencies to install. All study data
is stored locally in the browser (IndexedDB); nothing is sent to a server.

## Features

- **Home** — today's progress, grouped tasks, quick actions, continue-studying
- **Routine** — full day-by-day roadmap, jump to any day/date, auto-collapsing completed days, windowed rendering for 365+ day plans
- **Progress** — overall completion, subject breakdown, study time, streak
- **Notes** — rich-text notes with search
- **Focus** — Pomodoro (25/45/60/custom), stopwatch, study session history
- **AI agent** — understands Bengali, English and mixed commands; proposes a diff and requires approval before changing your plan; full undo history
- **Templates, Import/Export, Offline-first**

## AI providers

Bring your own key — Google Gemini, Groq, or Mistral AI. Choose the provider and model in the app's
AI configuration screen. Keys are stored only in your own browser.

## Run locally

Open `index.html` in any modern browser. That's it.

## Deploy

This repository is served with GitHub Pages from the `main` branch root.
