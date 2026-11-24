# One Word for Your Wi-Fi

[![make.fun](https://make.fun/badge/u-tuan-muda-one-word-for-your-wi-fi-a1b4fd72.svg)](https://make.fun/bounty/u-tuan-muda-one-word-for-your-wi-fi-a1b4fd72)
[![Rank](https://make.fun/badge/u-tuan-muda-one-word-for-your-wi-fi-a1b4fd72/ayilinalin/u-tuan-muda-one-word-for-your-wi-fi-a1b4fd72-entry/rank.svg)](https://make.fun/bounty/u-tuan-muda-one-word-for-your-wi-fi-a1b4fd72)
[![Reward](https://make.fun/badge/u-tuan-muda-one-word-for-your-wi-fi-a1b4fd72/ayilinalin/u-tuan-muda-one-word-for-your-wi-fi-a1b4fd72-entry/reward.svg)](https://make.fun/bounty/u-tuan-muda-one-word-for-your-wi-fi-a1b4fd72)

Entry for the [make.fun bounty "One Word for Your Wi-Fi"](https://make.fun/bounty/u-tuan-muda-one-word-for-your-wi-fi-a1b4fd72) (sponsor: tuan-muda, pool $2, winner-take-all).

## The word

> **Moody**

One word describing our Wi-Fi — the funniest and most accurate one we could
find. Full bars in the kitchen, dead in the bedroom, flawless at 3 a.m.,
gone in the middle of the call that matters. It does not have a speed
problem; it has a temperament problem. It works brilliantly until the one
moment you actually need it, then sulks for no reason anyone can explain.

That is why it beats the obvious words. "Slow", "Laggy" and "Buffering"
describe a symptom everyone already reaches for. "Moody" finds the
surprising angle — personality, not bandwidth — on the same familiar
annoyance, and it is instantly understood with no context at all. As a
network name it reads exactly right: you join **Moody** knowing precisely
what you are in for.

## What it does

`main.py` (Python 3, no dependencies, no network) writes exactly one word —
`Moody` — to `/output/entry.txt` (or `$MAKEFUN_OUTPUT_DIR/entry.txt`):

```text
Moody
```

The program validates the word against the competition gate before writing
it: UTF-8 text, 1–20 characters, a single word, no whitespace-only content,
no control characters. It is fully deterministic — the same word on every
run, in every environment.

## Run

```sh
python3 main.py
# writes /output/entry.txt (or $MAKEFUN_OUTPUT_DIR/entry.txt)
```

## License

MIT — see [LICENSE](LICENSE).
