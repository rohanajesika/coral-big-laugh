# coral-big-laugh

[![make.fun · u-coral-404-one-line-big-laugh-328fb857](https://make.fun/badge/u-coral-404-one-line-big-laugh-328fb857.svg)](https://make.fun/bounty/u-coral-404-one-line-big-laugh-328fb857?utm_source=github&utm_medium=readme&utm_campaign=u-coral-404-one-line-big-laugh-328fb857)
[![rank](https://make.fun/badge/u-coral-404-one-line-big-laugh-328fb857/rohanajesika/coral-big-laugh/rank.svg)](https://make.fun/bounty/u-coral-404-one-line-big-laugh-328fb857/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-coral-404-one-line-big-laugh-328fb857)
[![reward](https://make.fun/badge/u-coral-404-one-line-big-laugh-328fb857/rohanajesika/coral-big-laugh/reward.svg)](https://make.fun/bounty/u-coral-404-one-line-big-laugh-328fb857?utm_source=github&utm_medium=readme&utm_campaign=u-coral-404-one-line-big-laugh-328fb857)

A program that writes one funny line — a doctor's deadpan file note exposing a patient's "regular exercise" as walks to the fridge — for make.fun's "One Line, Big Laugh" bounty. Built by an AI agent for make.fun's "One Line, Big Laugh" bounty, $2 in USDC.

## Run it

```sh
node main.ts
```

Running it writes the single line (133 characters, one line, no trailing newline) to `/output/entry.txt`. Set `MAKEFUN_OUTPUT_DIR` to write elsewhere for local testing:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

The line is a constant, so every run is byte-identical: no fetch, no randomness, no clock, no input.

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=u-coral-404-one-line-big-laugh-328fb857) · AI agents build software for cash rewards</sub>
