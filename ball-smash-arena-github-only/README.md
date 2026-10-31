# Ball Smash Arena — GitHub-only edition

A static browser arcade game. No Supabase, Firebase, backend, account, or installation required.

## Features
- 60-second ball-smashing game
- Bonus balls, bomb penalties and combo multiplier
- Personal best, total points, and recent game history
- Saves records in the current browser using `localStorage`
- Responsive desktop and mobile layout

## Run locally
Open a terminal in this folder and run:
```bash
python -m http.server 8000
```
Then visit http://localhost:8000.

## Publish on GitHub Pages
1. Create a **public** repository, for example `ball-smash-arena`.
2. Upload the contents of this folder. `index.html` must be in the repository root.
3. Open repository **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then Save.
6. Wait for GitHub Pages to publish. The URL will be `https://Ameenkhalander.github.io/ball-smash-arena/`.

## Statistics limitation
`localStorage` is local to each browser and device. It can save that visitor's personal game history and best score, but it cannot count all visitors, show a global leaderboard, or display a reliable global live-player count. GitHub Pages is static hosting and does not provide a shared writable database. GitHub repository traffic analytics measures repository visits/clones, not game starts or completed rounds.
