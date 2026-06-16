# World Cup 2026 — Live Tracker

A live World Cup 2026 tracker built in Claude Cowork as a demo for Jera IT's
28-Day Cowork Challenge — to show how a working, self-updating dashboard can be
built in plain English, with no code.

**Live site:** https://ORG.github.io/worldcup-tracker/

## What it does
- Group standings, with a chosen team's headline stats and gap to the leader
- Points-by-matchday trend vs the group leader
- Countdown to the next fixture and a last-results view
- "World press" — recent headlines about the team from around the world,
  with the host nation of the next/last game highlighted

## Data & sources
- Match data: openfootball (public domain)
- Headlines: GDELT (free, open news index); titles link to the original outlet
- The page loads from a saved snapshot so it always renders; the live "Refresh"
  for headlines is best-effort and depends on a public proxy.

## Updating
Edit `index.html`, commit the change, and GitHub Pages redeploys within a minute.

## Disclaimer
Unofficial fan project. No affiliation with, or endorsement by, FIFA or any
official body. Built for demonstration.
