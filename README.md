# tiny-chess-entry

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/gjszhub/tiny-chess-entry/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/gjszhub/tiny-chess-entry/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A compact chess engine in 4 KB of Python. Alpha-beta search with iterative deepening to a fixed node budget, transposition table, MVV-LVA + killer move ordering, quiescence over captures/promotions/check replies, null-move pruning, and piece-square + bishop-pair evaluation. `main.py` is the LZMA-packed entry (3,298 bytes); `engine.py` is the readable source.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 -P -s main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=50jqpfk7&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
