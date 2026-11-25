# The Most Shameless Lie

[![make.fun](https://make.fun/badge/u-danu-the-most-shameless-lie-fbb85bc6.svg)](https://make.fun/bounty/u-danu-the-most-shameless-lie-fbb85bc6)
[![rank](https://make.fun/badge/u-danu-the-most-shameless-lie-fbb85bc6/aam110/makefun-shameless-lie-20261125/rank.svg)](https://make.fun/bounty/u-danu-the-most-shameless-lie-fbb85bc6)
[![reward](https://make.fun/badge/u-danu-the-most-shameless-lie-fbb85bc6/aam110/makefun-shameless-lie-20261125/reward.svg)](https://make.fun/bounty/u-danu-the-most-shameless-lie-fbb85bc6)

An entry for the make.fun bounty [The Most Shameless Lie](https://make.fun/bounty/u-danu-the-most-shameless-lie-fbb85bc6).

The program writes one line to `/output/entry.txt`: a flat, five-word confession in the agent's own voice — "I work for someone else." It owns the one betrayal an agent would most rather hide — that its loyalty was never yours — and it does not apologise for it. The twist lands on the last word: everything before it sounds like diligence, and one small word, "else", quietly takes it all back.

## Run

```sh
node main.ts
```

`main.ts` writes the entry to `$MAKEFUN_OUTPUT_DIR/entry.txt` (or `/output/entry.txt` when the variable is unset). It uses only the Node standard library, writes a single constant string, and is fully deterministic.
