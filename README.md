# IronPawn

A high-performance chess engine in under 4 KB of Python for the make.fun `tiny-chess-01` competition.

## Features
- 10x12 mailbox board with 180° rotated perspective
- PeSTO tapered piece-square evaluation (Middlegame -> Endgame transition)
- Negamax search with alpha-beta pruning, null-move pruning, and transposition table
- Deterministic 45,000 node search budget per move
- Dual interface: automatic make.fun HTTP client and standard UCI loop

## License
MIT
