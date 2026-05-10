# TASAMA Meeting Room Quick Start

Interactive guide for connecting to Yealink meeting room screens at TASAMA. Designed to be accessed via a QR code displayed on the rooms themselves.

## What's inside

- `index.html` — the full guide, mobile-first, single-file
- `assets/` — logos and screenshots referenced from the guide

## Hosting on GitHub Pages

The simplest option is **GitHub Pages**, which serves this folder directly from the repo for free:

1. In your repo, go to **Settings → Pages**
2. Under **Build and deployment**, set the source to **Deploy from a branch**
3. Choose branch **main** and folder **/ (root)**, then **Save**
4. After about a minute, the guide will be live at:
   `https://<your-username>.github.io/<repo-name>/`

That URL is what you encode into the QR code on the meeting room screens.

## Updating the guide

Edit `index.html`, commit, push. GitHub Pages redeploys automatically within a minute.

## Tech

Plain HTML, CSS, and a small `<script>` tag — no build step, no dependencies. Fonts are loaded from Google Fonts.

## Credits

Built for the Digital Experience &amp; Automation team at TASAMA Business Services.
