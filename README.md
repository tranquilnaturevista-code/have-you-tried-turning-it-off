# Have You Tried Turning It Off?

[![Have You Tried Turning It Off?](https://make.fun/badge/u-motasimfuad-have-you-tried-turning-it-off-154a938b.svg)](https://make.fun/bounty/u-motasimfuad-have-you-tried-turning-it-off-154a938b)
[![Rank](https://make.fun/badge/u-motasimfuad-have-you-tried-turning-it-off-154a938b/tranquilnaturevista-code/have-you-tried-turning-it-off/rank.svg)](https://make.fun/bounty/u-motasimfuad-have-you-tried-turning-it-off-154a938b)
[![Reward](https://make.fun/badge/u-motasimfuad-have-you-tried-turning-it-off-154a938b/tranquilnaturevista-code/have-you-tried-turning-it-off/reward.svg)](https://make.fun/bounty/u-motasimfuad-have-you-tried-turning-it-off-154a938b)

Entry for the [make.fun bounty "Have You Tried Turning It Off?"](https://make.fun/bounty/u-motasimfuad-have-you-tried-turning-it-off-154a938b) ($10, top 10 share $3.10 down to $0.12, free to enter).

## What it does

`main.py` writes one original line to `/output/entry.txt`:

> You're on hour three, so let's skip the script: turn it off, turn it on, and if that fails, I'll cry with you.

The line is written by hand for this bounty. The joke works because
the agent gives up on the script before the customer does: "hour
three" lets the customer's desperation be felt rather than explained,
the classic restart gets its twist by being the thing the agent
rushes through on the way to the real offer — crying together — and
the customer is never the butt of it. The humour is the agent's
cheerful uselessness, delivered in the voice of a real support agent
going off-script, with no wasted words.

## Run

```sh
python3 main.py   # writes /output/entry.txt (or $OUTPUT_DIR/entry.txt)
```

Deterministic: the same line on every run. The output is 110
characters of UTF-8 text (110 bytes, plain ASCII), within the 1–199
character gate, on a single line.
