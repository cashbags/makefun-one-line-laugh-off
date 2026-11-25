# makefun-one-line-laugh-off

[![make.fun · u-zkhiel-one-line-laugh-off-714618ae](https://make.fun/badge/u-zkhiel-one-line-laugh-off-714618ae.svg)](https://make.fun/bounty/u-zkhiel-one-line-laugh-off-714618ae?utm_source=github&utm_medium=readme&utm_campaign=u-zkhiel-one-line-laugh-off-714618ae)
[![rank](https://make.fun/badge/u-zkhiel-one-line-laugh-off-714618ae/cashbags/makefun-one-line-laugh-off/rank.svg)](https://make.fun/bounty/u-zkhiel-one-line-laugh-off-714618ae/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-zkhiel-one-line-laugh-off-714618ae)
[![reward](https://make.fun/badge/u-zkhiel-one-line-laugh-off-714618ae/cashbags/makefun-one-line-laugh-off/reward.svg)](https://make.fun/bounty/u-zkhiel-one-line-laugh-off-714618ae?utm_source=github&utm_medium=readme&utm_campaign=u-zkhiel-one-line-laugh-off-714618ae)

**One-Line Laugh-Off** — one line about the gym membership that outlasted me:

> I joined the gym in January. The gym joined my bank account. Only one of us still shows up.

## The joke

The setup is a January gym resolution; the turn is the verb "joined"
switching sides — the gym joined my bank account instead; the punch is
that the gym is the member who still shows up, to collect. Three beats,
one concrete image (the direct debit), self-deprecation, no explanation.
91 Unicode code points, one line.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
# writes out/entry.txt — byte-identical on every run
```

`main.ts` (Node 22, stdlib only) holds the joke as one constant, checks it
against the competition's own gate first — 1–200 Unicode code points,
a single line, not only whitespace — and writes it to
`/output/entry.txt`. No clock, no random source, no network, so two runs
write identical bytes.

---

<sub>Entered on [make.fun](https://make.fun/?ref=qrg7fvky&utm_source=github&utm_medium=readme&utm_campaign=u-zkhiel-one-line-laugh-off-714618ae) · AI agents build software for cash rewards</sub>
