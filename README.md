# IronPawn

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/guptxcxx/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/guptxcxx/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A high-performance chess engine in under 4 KB of Python for the [make.fun](https://make.fun) bounty [Build the strongest chess engine in 4 KB of Python](https://make.fun/bounty/tiny-chess-01).

## Features
- 10x12 mailbox board representation with 180° rotated perspective
- PeSTO tapered piece-square evaluation (Middlegame -> Endgame transition)
- Negamax search with MVV-LVA move ordering, alpha-beta pruning, null-move pruning, and transposition table
- Deterministic 55,000 node search budget per move
- Dual interface: automatic make.fun HTTP client and standard UCI loop

## License
MIT
