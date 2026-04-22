# GENERATOR: RIFT ASCENT

**Infinite Heat** — A canvas-based action game with prestige cycles, upgrades, co-op, and procedural audio.

> 🔐 **Built on [ARC-Core](https://github.com/GareBear99/ARC-Core)** — the authoritative event-and-receipt engine. Every player action, wave, prestige cycle, upgrade, and leaderboard submission is an ARC-Core-shaped event with a SHA-256 receipt. The receipt chain *is* the anti-cheat layer.

## 🎮 Play Now

**[https://garebear99.github.io/RiftAscent/](https://garebear99.github.io/RiftAscent/)**

## Features

- **Prestige Cycle** — 100-wave loop with meta progression
- **Infinite Heat** — Endless mode with scaling difficulty via wave composition and pressure
- **Upgrade Economy** — Enemies drop credits; spend at the shop to evolve builds
- **Geo Droids** — Cube, Prism, Arc, Mine companions with unique abilities
- **Procedural Audio** — Rift Synthwave engine that reacts to gameplay state
- **Co-op** — Local and online multiplayer
- **Daily Challenges** — Seeded runs with leaderboards
- **1000 Achievements** — Deep progression tracking

## Controls

| Key | Action |
|-----|--------|
| WASD | Move |
| LMB | Shoot |
| RMB | Fireball |
| E | Bomb |
| SHIFT | Dash (tap) |
| SPACE | Overdrive |
| B | Shop |
| ESC | Pause |
| H | Toggle HUD |

## Coming Soon

📱 iOS & Android

## 🏗️ Built on ARC-Core

Rift Ascent uses the [**ARC-Core**](https://github.com/GareBear99/ARC-Core) authority kernel as its backbone. Specifically:

| Gameplay layer | ARC-Core pattern |
|---|---|
| Player actions (move, shoot, dash, overdrive) | Event log with SHA-256 identity |
| Wave progression and prestige cycles | Replayable event chain |
| Co-op session sync | Shared receipt stream between clients |
| Leaderboard submissions | Signed receipts — tamper breaks the chain |
| Achievement unlocks (all 1000) | Receipt-verified events tied to player identity |
| Shop purchases and upgrades | Authority-gated mutations with audit trail |
| Daily challenges | Seeded event log reproducible across clients |

This means a full game run can be **replayed deterministically** from its event log, and any attempt to inject state client-side without producing a valid receipt is rejected at verification time.

**Related ARC repos**

- [ARC-Core](https://github.com/GareBear99/ARC-Core) — authority / event / receipt kernel
- [Arc-RAR](https://github.com/GareBear99/Arc-RAR) — future save-state archive bundles
- [ARC-Neuron-LLMBuilder](https://github.com/GareBear99/ARC-Neuron-LLMBuilder) — governed AI build loop (same author, same doctrine)

Support the whole ARC ecosystem: [💖 github.com/sponsors/GareBear99](https://github.com/sponsors/GareBear99)

## License

All rights reserved. © 2026
