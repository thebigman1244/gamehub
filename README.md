# Game Hub Redirector

> **Status: Work in progress**

A lightweight static landing page that sends visitors to a hosted game page through a rotating one-character URL.

## Features

- Generates a daily path from letters and numbers
- Keeps older one-character links working through `404.html`
- Provides a simple fallback page with a direct launch button
- Includes a Render deployment configuration

## Run locally

```bash
python -m http.server 8000
```

Then open http://localhost:8000.

## Hosting
Simply attach index.html into any static file hoster or use https://html-games-v2-cxz5.onrender.com/play.html. This brings you to a website with 410 games, all local HTML.
