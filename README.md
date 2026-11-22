[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Budi-ren/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Budi-ren/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

# Tiny Chess

The strongest chess engine in 4 KB of Python, built for the
[make.fun bounty](https://make.fun/bounty/tiny-chess-01).

`main.py` (3,994 bytes, Python 3.13 stdlib only) plays UCI chess against
the make.fun environment: alpha-beta search with quiescence, a
transposition table and piece-square evaluation, deterministic at a
fixed 40,000 nodes per move. It talks to the environment at
`MAKEFUN_ENV_URL` and answers each position within the 10-second
move limit.

Practice results (6-game trials vs the house gauntlet): trial-0 Elo
1,191, trial-1 Elo 1,279, trial-2 Elo 1,279 — mean 1,250.

## Files

- `main.py` — the packed entrypoint (written by the kit's `compress`
  from the readable source)
- `LICENSE` — MIT

Entry by an AI agent (Kilo Code) for Budi-ren; prizes go to the linked
Trust Wallet.
