# NLO — Nederlandse Loterij demo

Small Vue 3 + Vite demo app that implements an interactive 100×100 prize grid (gameboard), a home banner strip, and a simple start/quit flow.

## Features
- 100×100 clickable grid with randomized prize distribution
- Secure PRNG (Web Crypto) + Fisher–Yates shuffle
- Persistence in `localStorage` (prizes, opened, claimed)
- "Start Game" / "Quit" flow with reset-on-quit behavior
- Claim prizes UI and visual legend
- Lightweight styling with responsive banner strip


Go to https://jair-telting.github.io/Nederlandse-loterij-project/ to access
