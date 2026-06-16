# World Cup 2026 — Live Tracker

A live World Cup 2026 tracker built in Claude Cowork as a demo for Jera IT's
28-Day Cowork Challenge — to show how a working, self-updating dashboard can be
built in plain English, with no code.

**Live site:** https://jerait-dev.github.io/worldcup-tracker/

## What it does
- Group standings, with a chosen team's headline stats and gap to the leader
- Points-by-matchday trend vs the group leader
- Countdown to the next fixture and a last-results view, each with a short
  data-generated commentary line (build-up and reaction)
- **Scenarios** — a what-if on your team's next game: pick Win/Draw/Loss and see
  the provisional group table update
- **All fixtures** — every group's six games, scores or kickoff times
- **Top scorers** — tournament goal leaderboard, your team's players highlighted

## Data & sources
- Match data: openfootball (public domain)
- The page loads from a saved snapshot so it always renders; a best-effort
  "Refresh" tries the live source on demand.

## Updating
Edit `index.html`, commit the change, and GitHub Pages redeploys within a minute.

## Disclaimer
Unofficial fan project. No affiliation with, or endorsement by, FIFA or any
official body. Built for demonstration.
