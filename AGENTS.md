# Agent Instructions

## Overview
Static HTML single-page app using Vite for build and environment variable management.

## Key Files
- `index.html` - App (HTML + CSS + JS)
- `.env` - Environment variables (webhook URL)

## Running
```bash
npm install
npm run dev
```
Then open the URL shown (usually `http://localhost:5173`).

Requires n8n running on `http://localhost:5678` with webhook `e470ff5c-d737-49e2-bcc5-3299b9538029`.

## Webhook URL
Update `VITE_WEBHOOK_URL` in `.env` file when n8n webhook path changes.