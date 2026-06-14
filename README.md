# Bewafa — Discord Server Website

A single-file, pure HTML/CSS/JS landing page for the **Bewafa** Discord server (`discord.gg/bewafa`).

## Files
- `index.html` — the entire website (HTML + CSS + JS, no build step).
- `assets/icon.gif` — the animated server icon.
- `assets/music.mp3` — **add your own track here** to enable background music.

## Background music
The top-left toggle controls background music. Drop an MP3 at `assets/music.mp3`
(the toggle starts **Off**; browsers require a user click before audio can play).

## Editing content
Everything is plain HTML in `index.html`:
- **Staff of the Week** and **Owners** — update the names/roles in those sections each week.
- **Features**, **About**, **FAQ** — edit the text directly.

## Run locally
Just open `index.html` in a browser, or serve it:
```
python3 -m http.server 8000
```
Then visit http://localhost:8000

## Deploy (GitHub Pages)
Settings → Pages → Deploy from branch → `main` / root.
