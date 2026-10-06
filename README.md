# security-pitch-oct7

A [fslides](https://github.com/fslides/fslides) presentation. Every slide is an HTML file in `slides/` — edit them like code.

**Watch it:** https://0trustissues.fslides.dev/security-pitch-oct7/ — renders straight from this repo; every push to `main` is live within a minute.

## Contribute

```bash
git clone https://github.com/0trustissues/security-pitch-oct7.git
cd security-pitch-oct7
npm install
npm run serve        # opens the deck locally with the full player
```

- **Edit a slide:** change the HTML in `slides/`, the browser live-reloads.
- **Add a slide:** `npx fslides add-slide my-slide`, then register it in `fslides.config.js`.
- **Comment on a slide:** press `K` in the player (or the 💬 button) — comments live in this repo's [issues](https://github.com/0trustissues/security-pitch-oct7/issues), one per slide.
- **Speaker notes:** press `N` in the player; notes save to `notes.json`.
- **Record narration:** `npm run serve`, hit the mic button — audio or camera, saved under `slides/recordings/` and playable on the published deck.

Send a PR when you're happy.
