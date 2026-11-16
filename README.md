# tiny-chess-4k

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/laladream2001-dev/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/laladream2001-dev/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

An original compact chess engine in Python (negamax alpha-beta search,
quiescence, transposition table, null-move pruning, late-move reduction,
tapered piece-square evaluation), packed into a 4 KB main.py with the
make.fun kit's compressor. It plays the house gauntlet through the env:
fixed node budget per move, no clock, fully deterministic.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:<port> MAKEFUN_PROMPT_FILE=<prompt.txt> python3 main.py
```

(with the env server from the competition kit running at that URL)

---

<sub>Entered on [make.fun](https://make.fun/?ref=7yd20ms9&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
