# Lombitude · X Virality Board

Personal dashboard for [@Lombitude](https://x.com/Lombitude), tracking AI and tech announcement accounts on X. Read-only: nothing posts, likes, or replies.

Live: https://lalitsonawane.github.io/x-virality-board/

- `index.html` + `data.json` — the board (served by GitHub Pages from `main` / root)
- `config/watchlist.json` — timezone `Asia/Kolkata`, `min_views` 5000, `star_views` 10000, 15 watched accounts
- `board/` — starter reference files (SETUP.md, schema `data.example.json`, `enrich_leaderboards.py`, publish helper)
- `docs/` — first-run and daily-loop notes

`data.json` is intentionally empty until the first real digest. No example numbers are included.

Based on the starter at https://github.com/monkeyteamvip/x-virality-score (MIT). Not affiliated with X Corp.
