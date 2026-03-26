# House Break

House Break is a browser-based story escape game where the player (detective XYZ) is trapped inside a connected house and must solve room challenges to escape through Room 11.

## Quick Start

1. Open `home.html` in a modern browser.
2. Enter player name and choose an avatar.
3. Start from Room 1 and progress room by room.

No build step or server is required for basic play.

## Gameplay Overview

- Total rooms: 11
- Win condition: escape from Room 11
- Progression: solve room challenges to unlock the next room
- Hints: boss-help calls are limited
- Save system: progress is stored in browser localStorage

## Save Data (localStorage)

The game stores state in these keys:

- `escapeProgress`: player profile, score, hints, unlocked room
- `roomProgress`: per-room completion and puzzle state

## Project Structure

- `home.html`: onboarding, story intro, connected house map
- `room1.html` to `room11.html`: room gameplay pages


## Notes

- This is a front-end only project.
- Clearing browser storage resets progress.
