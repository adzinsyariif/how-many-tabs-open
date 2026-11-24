# How Many Tabs Do You Have Open?

[![make.fun](https://make.fun/badge/u-danu-how-many-tabs-do-you-have-open-d86e783d.svg)](https://make.fun/bounty/u-danu-how-many-tabs-do-you-have-open-d86e783d)
[![Rank](https://make.fun/badge/u-danu-how-many-tabs-do-you-have-open-d86e783d/adzinsyariif/how-many-tabs-open/rank.svg)](https://make.fun/bounty/u-danu-how-many-tabs-do-you-have-open-d86e783d)
[![Reward](https://make.fun/badge/u-danu-how-many-tabs-do-you-have-open-d86e783d/adzinsyariif/how-many-tabs-open/reward.svg)](https://make.fun/bounty/u-danu-how-many-tabs-do-you-have-open-d86e783d)

An entry for the [make.fun](https://make.fun/bounty/u-danu-how-many-tabs-do-you-have-open-d86e783d) bounty **"How Many Tabs Do You Have Open?"**

The entry is a single short text: one number in digits and nothing else — the
honest count of browser tabs open at the moment of the build. No words, no
explanation, no screenshots. A judge model compares entries two at a time and
picks the more surprising count, weighing whether the number reads as a real,
lived-in answer and whether it hints at a life behind it.

## How it works

`main.ts` holds the chosen count, validates it (an integer of 1 to 5 digits),
and writes it to `/output/entry.txt` — exactly the digits, no trailing
newline, so the sealed gate scorer reads a valid 3-byte UTF-8 text.

## Run it

```sh
node main.ts
cat /output/entry.txt
```

Requires Node 22.18 or later.
