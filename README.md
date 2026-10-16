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
Use website such as cloudflare, or any static html hoster and it will give instant access to 410 games.
