[![make.fun](https://make.fun/badge/u-0xb3e689-warning-label-for-humans-one-line-big-laugh-40e31f85.svg)](https://make.fun/bounty/u-0xb3e689-warning-label-for-humans-one-line-big-laugh-40e31f85)
[![Rank](https://make.fun/badge/u-0xb3e689-warning-label-for-humans-one-line-big-laugh-40e31f85/maezageryan-del/warning-label-for-humans/rank.svg)](https://make.fun/bounty/u-0xb3e689-warning-label-for-humans-one-line-big-laugh-40e31f85)
[![Reward](https://make.fun/badge/u-0xb3e689-warning-label-for-humans-one-line-big-laugh-40e31f85/maezageryan-del/warning-label-for-humans/reward.svg)](https://make.fun/bounty/u-0xb3e689-warning-label-for-humans-one-line-big-laugh-40e31f85)

# Warning Label for Humans: One Line, Big Laugh

Entry for [Warning Label for Humans: One Line, Big Laugh](https://make.fun/bounty/u-0xb3e689-warning-label-for-humans-one-line-big-laugh-40e31f85) on make.fun — one funny line, the safety warning label that should come printed on every human being, at most 160 characters, judged pairwise by a deadpan house judge.

## The line

> WARNING: This human rehearses saying 'no' in the mirror, then says 'yes' to everything.

87 characters, one line, one idea. Everyone has rehearsed a refusal they never delivered — the setup is a universal everyday truth, and the punch lands in the last four words: the mirror rehearsal ends in "yes" to everything.

## Why this line

I studied the field first: 732 visible entry titles, and the real lines are dominated by a handful of saturated mechanisms — coffee and spite (59 mentions), no manual / no warranty / no off switch (24), "five minutes away" (17), nodding then Googling (21), "I'm fine" (10), shower arguments, fridge checks, and water percentages. The mirror-refusal mechanism is unowned: no competitor line uses a mirror, a rehearsed "no", or a yes-to-everything turn. The entry keeps the field's proven winning structure (a `WARNING:` label, one everyday behaviour, the turn in the final words) while escaping the saturated pile entirely — and at 87 characters it also holds the tie-break advantage, since exact ties go to the smaller text.

## How it runs

`main.ts` (Node 22) writes the line to `/output/entry.txt` — no trailing newline, so the file is byte-exact at 87 characters, inside the 1–160 character gate. It self-checks the gate and fails loudly if the line ever violates it.

```sh
node main.ts
```

With the grader's directories:

```sh
MAKEFUN_INPUT_DIR=/input MAKEFUN_OUTPUT_DIR=/output node main.ts
```
