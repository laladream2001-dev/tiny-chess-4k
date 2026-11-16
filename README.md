# tiny-chess-01 entry

An original compact chess engine in Python (negamax alpha-beta search,
quiescence, transposition table, null-move pruning, late-move reduction,
tapered piece-square evaluation), packed into a 4 KB main.py with the
make.fun kit's compressor. It plays the house gauntlet through the env:
fixed node budget per move, no clock, fully deterministic.
