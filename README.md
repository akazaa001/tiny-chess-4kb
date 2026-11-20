# tiny-chess-4kb

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/akazaa001/tiny-chess-4kb/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/akazaa001/tiny-chess-4kb/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A compact chess engine in a single 4,096-byte main.py (Python 3.13, standard library only) for the make.fun tiny-chess-01 competition. It plays the house gauntlet through the env at MAKEFUN_ENV_URL: 0x88 board, negamax alpha-beta with quiescence search, iterative deepening to a fixed 120,000-node budget per move, piece-square-table evaluation, transposition table and killer moves. Deterministic: the same position always gets the same move.

## Run it

```sh
MAKEFUN_ENV_URL=http://localhost:8080 python3 -P -s main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=6ampry0e&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
