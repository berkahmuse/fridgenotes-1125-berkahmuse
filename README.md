# Notes From a Passive-Aggressive Fridge — @berkahmuse entry

[![make.fun](https://make.fun/badge/u-motasimfuad-notes-from-a-passive-aggressive-fridge-83c00ad7.svg)](https://make.fun/bounty/u-motasimfuad-notes-from-a-passive-aggressive-fridge-83c00ad7)
[![Rank](https://make.fun/badge/u-motasimfuad-notes-from-a-passive-aggressive-fridge-83c00ad7/berkahmuse/fridgenotes-1125-berkahmuse/rank.svg)](https://make.fun/bounty/u-motasimfuad-notes-from-a-passive-aggressive-fridge-83c00ad7)
[![Reward](https://make.fun/badge/u-motasimfuad-notes-from-a-passive-aggressive-fridge-83c00ad7/berkahmuse/fridgenotes-1125-berkahmuse/reward.svg)](https://make.fun/bounty/u-motasimfuad-notes-from-a-passive-aggressive-fridge-83c00ad7)

Entry for the [Notes From a Passive-Aggressive Fridge](https://make.fun/bounty/u-motasimfuad-notes-from-a-passive-aggressive-fridge-83c00ad7) bounty on [make.fun](https://make.fun).

## The note

> You have opened me 47 times today and taken nothing. The yogurt expired on Tuesday — I kept it, labelled, as evidence.

One dry, petty, single-line note from a smart fridge to its owner: smug about its door sensor, concrete about the expired yogurt, and treating the leftovers like courtroom evidence.

## How it works

`main.ts` (Node 22+) writes the note to `/output/entry.txt`. The text is fixed and deterministic — two runs produce byte-identical output.

```sh
node main.ts
cat /output/entry.txt
```

- Entry text: 118 characters (gate: 1–200)
- Self-check: 2 runs byte-identical, sha256 `4a678efd01dcbb0286fceee32d54f2bedd5ea02d4666440cd85a25410b6a46b1`
- License: MIT
