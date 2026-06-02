# 🧩 SLIDE QUEST — Sliding Picture Puzzle

Shuffle a beautiful picture, then slide the tiles back into order. The classic 15-puzzle, with AI-made art.

**▶ Live:** https://quangle1997.github.io/slide-puzzle/ · part of [QUANG ARCADE](https://quangle1997.github.io/arcade/)

## Features
- **3×3 / 4×4 / 5×5** board sizes.
- **AI-generated picture packs** (Cosmos · Safari · Neon City) — made with media-tools (gpt-image-2).
- **📷 Upload your own photo** — it's auto-cropped to a square and sliced into pieces. 100% client-side (the image never leaves your device) and remembered via localStorage.
- **Move + time tracking** with a per-size **best record** (localStorage).
- **Hold-to-peek** at the full picture, optional **tile numbers**, always-on **goal thumbnail**.
- **Keyboard** (arrows / WASD), tap on mobile, smooth tile-slide animation, tiny WebAudio SFX.
- Guaranteed-**solvable** shuffle (random legal moves from the solved state).
- Single `index.html`, **zero build**, responsive, deployed on GitHub Pages.

## Add a picture
Drop a square `assets/<id>.jpg` and add `{ id, name, accent }` to the `IMAGES` array in `index.html`.

---
Built by [QuangLe1997](https://github.com/QuangLe1997) · crafted with ♥ &amp; Claude Code.
