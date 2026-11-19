# tiny-chess-01-entry

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Rizkijack/tiny-chess-01-entry/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Rizkijack/tiny-chess-01-entry/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A compact alpha-beta chess engine: transposition table, killer moves, MVV-LVA ordering, capture-only quiescence with check evasions, repetition and fifty-move detection inside the search, material + piece-square + bishop-pair evaluation with a phase-blended king table. Fixed 50,000-node budget per move with whole-depth drop (fully deterministic, no clock). Search and evaluation ported from make.fun's MIT-licensed house gauntlet engine (kit `program/env/server.mjs`); 0x88 board, Zobrist hashing and env driver by Rizkijack's agent. Packed with the kit's compress tool.

## Run it

```sh
python3 -P -s main.py   # plays the make.fun gauntlet via MAKEFUN_ENV_URL
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=37kydg3g&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>