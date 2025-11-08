# Sno-King 12U A2 — GitHub Pages Website

This repository is a clean, mobile-first site (Jekyll on GitHub Pages) to publish tournaments, team events, and travel info.

## 1) Create the Repository on GitHub
1. Go to GitHub → **New repository**.
2. Name it something like `sno-king-tournaments` (Public).
3. Click **Create repository**.

## 2) Upload Files
1. Click **Add file → Upload files**.
2. Drag **all files and folders** from this zip into the upload box.
3. Click **Commit changes**.

## 3) Enable GitHub Pages
1. Go to **Settings → Pages**.
2. Under **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: `main`
   - Folder: `/ (root)`
3. Save. Your site URL will appear (e.g. `https://YOURNAME.github.io/sno-king-tournaments/`).

## 4) Add / Edit Content
- Tournaments live in `_tournaments/` (one Markdown file per tourney).
- Team events live in `_events/`.
- Customize look & feel in `assets/css/site.css`.

## 5) Where to Put PDFs
Place rules/schedule PDFs in `docs/` and link to them from a tournament page's `docs:` section.