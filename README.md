# MANIFEX Game Design Arsenal

**Status:** Early playable browser prototype. This is not yet a complete AI game engine.

## What currently works
- Single-page game studio interface.
- Prompt presets and local prompt-to-game configuration.
- Playable 2D canvas prototype with movement, collectibles, roaming enemies, health, score, and win conditions.
- Inspector controls for game name, genre, theme, difficulty, and objective.
- Local browser save/recovery using localStorage.
- Downloadable project configuration JSON.
- Basic runtime checks and an in-app console.
- No third-party dependencies or external credentials required.

## What does not exist yet
- No model/API integration; prompt processing uses local presets/configuration, not generative AI.
- No actual 3D engine adapter.
- Platformer selection is currently a genre label; the current gameplay loop is top-down movement.
- Assets are built-in placeholders; no external asset generation/import pipeline.
- Export currently downloads project JSON, not a standalone compiled game.
- No backend, user accounts, cloud project vault, collaboration, swarm execution, or deployment pipeline.
- Automated checks have not been run by the authoring environment. Treat build/qualification as NOT_MEASURED until run independently.

## Run
Open `index.html` in a modern browser. Use WASD or arrow keys to move. Collect crystals, avoid enemies, and try the selected win condition. Save persists settings in the current browser. Export downloads the project configuration JSON.

## Security and authority
This prototype runs locally in the browser and does not invoke external tools or systems. Connecting AI services, engine adapters, asset providers, or deployment capabilities must be a separate explicit integration with scoped authorization and auditable execution.
