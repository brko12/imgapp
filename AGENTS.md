# Agent Instructions

## Overview
Static HTML single-page app using Vite for build and environment variable management.

## Key Files
- `index.html` - App (HTML + CSS + JS)
- `.env` - Environment variables (webhook URL, Supabase URL and anon key)

## Running
```bash
npm install
npm run dev
```
Then open the URL shown (usually `http://localhost:5173`).

Requires n8n running on `http://localhost:5678` with webhook `e470ff5c-d737-49e2-bcc5-3299b9538029`.

## Environment Variables
- `VITE_WEBHOOK_URL` - n8n webhook URL for image generation
- `VITE_SUPABASE_URL` - Supabase project URL
- `VITE_SUPABASE_ANON_KEY` - Supabase anonymous key

## Supabase
- Project: https://vhyxskbdchtejpzhkoik.supabase.co
- Authentication enabled with email/password signup
- `public.profiles` table stores user name (linked to auth.users)