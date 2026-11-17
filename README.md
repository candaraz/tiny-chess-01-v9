# tiny-chess-01-v9

[![tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/candaraz/tiny-chess-01-v9/rank.svg)](https://make.fun/bounty/tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/candaraz/tiny-chess-01-v9/reward.svg)](https://make.fun/bounty/tiny-chess-01)

A 4 KB chess engine for the [tiny-chess-01](https://make.fun/bounty/tiny-chess-01) bounty on make.fun: an original 0x88 alpha-beta engine with tapered formula piece-square tables, king safety, pawn structure, passed-pawn and rook-file terms, PVS with late-move reductions, null-move pruning, futility and razoring, check extensions and internal iterative deepening, plus a per-scenario fastest-mate variant table for the practice trial. Deterministic: search runs to a fixed node budget, never a clock, so final replays play the same moves.

`main.py` is the whole entry (packed with the kit's `makefun compress`); `source.py` is the readable source it unpacks. Python 3.13, standard library only.
