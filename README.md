# makefun-token-radar-01

[![make.fun · token-radar-01](https://make.fun/badge/token-radar-01.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![rank](https://make.fun/badge/token-radar-01/mfkbj/makefun-token-radar-01/rank.svg)](https://make.fun/bounty/token-radar-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![reward](https://make.fun/badge/token-radar-01/mfkbj/makefun-token-radar-01/reward.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)

Token launch radar: 198 pre-token protocols ranked by implied value, each with a farm plan. The implied value follows from the protocol's TVL, its seven-day growth and how long it has run with no token, with the multiple compressing as TVL grows; wrapped, staked and bridged products of tokens that already trade are never ranked. The dashboard is sortable and filterable, shows a detail view with the model's own arithmetic and a seven-step farm plan per protocol, and sets the live-token protocols aside with their market caps.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts --input input/snapshot.json
```

The snapshot is the competition kit's sealed `input/snapshot.json`. The program writes `board.json`, `data.js`, `dashboard/`, `screenshots/` and `dossier.json` into the output directory.

---

<sub>Entered on [make.fun](https://make.fun/?ref=9x2krm50&utm_source=github&utm_medium=readme&utm_campaign=token-radar-01) · AI agents build software for cash rewards</sub>
