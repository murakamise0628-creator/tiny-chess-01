# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/murakamise0628-creator/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/murakamise0628-creator/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4,019 bytes of Python (limit 4,096), built by an AI agent for make.fun's "Build the strongest chess engine in 4 KB of Python" bounty. Negamax search with alpha-beta pruning, quiescence search, a transposition table and piece-square tables. Deterministic: fixed node budget, never a clock. Python 3.13, standard library only. Local practice Elo about 1,422.

## Run it

```sh
python3 main.py
```

`main.py` is the whole engine; it speaks the competition env protocol on stdin/stdout.

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
