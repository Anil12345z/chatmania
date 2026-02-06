# Claude AI Chat – Modern & Secure

A clean, beautiful, dark-themed chat interface that talks directly to **Claude** (Anthropic models) using a **secure serverless proxy** via **Netlify Functions**.  
No exposed API keys in the browser, no CORS issues, mobile-friendly, and great markdown/table/code rendering.

![Chat preview](https://via.placeholder.com/800x500/1a1a2e/7c3aed?text=Claude+AI+Chat+Preview)  
*(Replace this placeholder with a real screenshot after deploy)*

## Features

- Direct conversation with Claude models (Sonnet 4.5, etc.)
- **Secure API key handling** – key never exposed in browser (uses Netlify env vars)
- Smart rendering: tables, code blocks, lists, bold/italic — auto-detected API guides become visual cheat-sheets
- Dark modern UI with gradient accents & typing animation
- Responsive (works great on mobile)
- No backend server to manage – 100% serverless on Netlify
- Local development support with `netlify dev`

## Tech Stack

- HTML + CSS (custom dark theme)
- Vanilla JavaScript (no frameworks)
- Netlify Functions (serverless proxy)
- Anthropic Messages API (Claude models)

## Live Demo

🔗 https://chatapimania.netlify.app/

## Project Structure
