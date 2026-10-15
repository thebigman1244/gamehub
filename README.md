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

## Notes

The destination URL is currently hard-coded, and the rotating path is cosmetic rather than an access-control mechanism. Make sure any linked or hosted games are distributed with permission and comply with their original licenses and terms.
