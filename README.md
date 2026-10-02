# Girish AI Chatbot

A personal AI chatbot web app — "Girish Lade Chatbot". A sleek, dark-themed chat UI that talks to an AI model (DeepSeek via OpenRouter) and answers in real time.

## Features

- Conversational chat interface with typing/loading animation
- Suggested topic prompts to get started quickly
- Full chat history in-session
- Dark, modern glassmorphism-style UI
- Fully client-side — no backend required

## Tech Stack

- HTML5 / CSS3 / vanilla JavaScript
- OpenRouter API (`deepseek/deepseek-chat:free` model by default)
- Font Awesome icons

## Quick Start

```bash
# No build step — open directly or serve locally
python3 -m http.server 8000
# visit http://localhost:8000
```

> Note: the app calls the OpenRouter API with an API key embedded in the HTML for demo purposes. **Do not use a production key this way** — a browser-visible key can be copied and abused by anyone. For real use, rotate the key and route calls through a backend proxy.

## Project Structure

```
.
├── index.html        # Main chatbot page (UI + logic)
├── CBremake4.6.html  # Alternate/remake build of the chatbot UI
└── README.md
```

## Deployment

Deployed via **GitHub Pages**, served from the `main` branch root.

## Built by Girish Lade

Built by Girish Lade — https://ladestack.in
