# Meal Plan App

A personal meal planning app for Chris & wife. Built as a single HTML file — no dependencies, no build step.

## Features
- 📅 Weekly plan with day-by-day view (auto-opens today)
- 🥩 Full dinner menu with filters (beef / chicken / no starch / rice nights / batch cook)
- 🥗 Midday options menu with traffic-light ratings
- 🛒 Shopping list with tap-to-check and copy-to-clipboard
- 📉 Weight progress tracker toward 165 lb goal

## Deploy to Vercel

1. Push this repo to GitHub
2. Go to vercel.com → New Project → Import this repo
3. Vercel auto-detects the static file — hit Deploy
4. Done. Share the URL with your wife.

## Update the plan

Come back to Claude with changes (new meals, ratings, adjustments) and Claude will update `index.html` directly. Push to GitHub and Vercel auto-deploys the update.

## Data

- Shopping list checkmarks and weight log are saved locally in the browser (localStorage)
- To reset the shopping list, tap "Reset list" in the app
