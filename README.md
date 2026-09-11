# Changeup

A simple metronome + chord-change trainer for guitar practice. Pick a tempo,
choose which chords you want in rotation (E, Em, D, Dm, A, Am, C, G), set how
many beats to hold each chord, and it'll click along and prompt you to switch
chords every N beats.

It's a single static `index.html` file — no build step, no dependencies.

## Run locally

Just open `index.html` in a browser, or serve the folder with any static
server, e.g.:

```
python3 -m http.server
```

## Deploy to GitHub Pages

1. Create a new GitHub repo and push this folder to it:
   ```
   git remote add origin <your-repo-url>
   git push -u origin main
   ```
2. On GitHub: **Settings → Pages → Source**, select the `main` branch and
   `/ (root)` folder, then save.
3. GitHub will publish it at `https://<your-username>.github.io/<repo-name>/`.
