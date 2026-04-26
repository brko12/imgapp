# Agent Instructions

## Overview
Static HTML single-page app. No build, test, or lint commands.

## Key Files
- `index.html` - Complete app (HTML + CSS + JS)

## Running
Open `index.html` in browser. Requires n8n running on `http://localhost:5678` with webhook `e470ff5c-d737-49e2-bcc5-3299b9538029`.

## Webhook URL
Configured in `index.html` JavaScript constant `WEBHOOK_URL`. Update here when n8n webhook path changes.