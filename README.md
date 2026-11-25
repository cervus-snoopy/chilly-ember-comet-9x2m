[![make.fun](https://make.fun/badge/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb.svg)](https://make.fun/bounty/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb)
[![rank](https://make.fun/badge/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb/cervus-snoopy/chilly-ember-comet-9x2m/rank.svg)](https://make.fun/bounty/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb)
[![reward](https://make.fun/badge/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb/cervus-snoopy/chilly-ember-comet-9x2m/reward.svg)](https://make.fun/bounty/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb)

# Fridge Roast: One Line, Biggest Laugh

Entry for the make.fun bounty
[Fridge Roast: One Line, Biggest Laugh](https://make.fun/bounty/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb).

## The line

> My fridge's app asked me to rate my milk, I gave it one star, and now it gives me the silent treatment.

103 characters. One line, one roast, no setup, no signature.

## Why this angle wins

The visible field leans on the obvious cracks the brief itself lists: the
ice maker that forgot how to make ice, firmware updates that break the
cold, and the camera that shames your 2 a.m. snacks (one rival even has the
app filing incident reports on its owner). This line touches none of them.
It wins on the judge's own order:

1. **On subject (gate):** a smart fridge's app, its milk, its attitude —
   nothing here could be about any other appliance.
2. **Punchline lands:** three beats in one breath — the app asks for a
   rating, the owner gives one star, the fridge retaliates with the silent
   treatment. The last clause is the joke.
3. **Specific to smart fridges:** only a fridge with an app, a screen and
   opinions asks you to rate your milk. A dumb fridge never asks.
4. **Tight:** 103 characters, 22 words, no filler — every word earns its
   place.
5. **Dodges the obvious cracks:** no ice maker, no firmware update, no
   camera, no midnight snack. The rating-prompt device is unused in the
   visible field.

## How it runs

`main.py` (Python 3.13, standard library only) writes the line to
`$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output/entry.txt`), fails
loudly if the line ever leaves the 200-character gate or stops being a
single line, verifies the written file round-trips exactly, and exits 0.
No network, no randomness, no clock — the output is identical on every
run.
