# Korea 2026 — Live Itinerary Site

This folder is a ready-to-push GitHub Pages site. `index.html` is the shareable itinerary
(kept in sync with the planning files in `~/Projects/Korea`).

## One-time setup (~3 minutes)

1. Create an empty **public** repo on GitHub called `korea-2026` (no README, no .gitignore).
2. In Terminal:

   ```bash
   cd ~/Projects/Korea/korea-2026
   git remote add origin git@github.com:YOUR_USERNAME/korea-2026.git   # or the https URL
   git branch -M main
   git push -u origin main
   ```

3. On GitHub: repo → **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main` / `/ (root)` → Save.
4. Live URL (takes ~a minute to go live): `https://YOUR_USERNAME.github.io/korea-2026/`

## Update flow (every tweak after that)

Claude edits `index.html` and commits locally in this folder — you just run:

```bash
cd ~/Projects/Korea/korea-2026 && git push
```

(or press *Push* in GitHub Desktop). The live URL updates within a minute.
