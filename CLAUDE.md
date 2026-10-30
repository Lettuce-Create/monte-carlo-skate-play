# Monte Carlo Skate (play build)

The built, playable version of Monte Carlo Skate, the roller-rink card game, on Fortune Engine 2.0.
Live: https://lettuce-create.github.io/monte-carlo-skate-play/

This repo holds only the built game (static HTML, art, audio, no build step). The source is in the
private `Lettuce-Create/Games` repo (`monte-carlo/`), published here with `monte-carlo/tools/publish_play.sh`.
Changes to the game itself are made there, not here.

## Running locally

```bash
python3 -m http.server 8123
```

Then open http://localhost:8123. In the Claude desktop app, `.claude/launch.json` defines this as the
`monte-carlo-skate` preview server.

## Progress log

The user works on this game from two Claude accounts. Keep this section current: at the end of each
piece of work, add a dated entry with what changed and what's next, so the other account can pick up.

### 2026-10-30
- Got the game running locally (Python static server on port 8123). Loads to the rules screen with no console errors.
- Added `.claude/launch.json` and this file.

## Next steps / open questions
- Nothing decided yet. If work moves to the source repo (`Lettuce-Create/Games`), add a progress file there too.
