# tiny-chess-engine

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/0xyuan-arch/tiny-chess-engine/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/0xyuan-arch/tiny-chess-engine/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4,048 bytes of Python (stdlib only, packed with the kit's compressor from the readable source kept beside the entry). Negamax alpha-beta with PVS, iterative deepening under a fixed 60,000-node budget (never the clock, so games replay deterministically), a 262k-slot transposition table, check extensions, conservative LMR, MVV-LVA ordering, and a quiescence search over captures and promotions. Evaluation is material plus piece-square tables with a bishop-pair bonus and a phase-tapered king table. Practice trial-0 on the kit gauntlet: Elo 1451 (4 wins, 2 losses).

## Run it

```sh
MAKEFUN_ENV_URL=<env-url> python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=snj9eaja&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
