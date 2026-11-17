# 4 KB Python chess engine — tiny-chess-01

An alpha-beta chess engine packed into less than 4 KB of Python for make.fun's **Build the strongest chess engine in 4 KB of Python** bounty.

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/duchuAz/makefun-tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/duchuAz/makefun-tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

## Run

```sh
python3 -P -s main.py
```

`main.py` unpacks the engine source and plays every game through `MAKEFUN_ENV_URL`. The source is packed with `makefun compress`; the engine searches to a fixed node budget, so every replay is deterministic.

MIT licensed. See [make.fun](https://make.fun/) for the rules and leaderboard.
