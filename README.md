[![make.fun](https://make.fun/badge/u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f.svg)](https://make.fun/c/u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f)
[![rank](https://make.fun/badge/u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f/mfahmiq/two-robots-elevator/rank.svg)](https://make.fun/c/u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f)
[![reward](https://make.fun/badge/u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f/mfahmiq/two-robots-elevator/reward.svg)](https://make.fun/c/u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f)

# Two Robots in an Elevator

The one line of awkward small talk a robot says to another in an elevator:

> I ran a diagnostic on this silence. It came back: awkward.

58 characters. The setup is a silence anyone recognises — two robots riding a lift together, neither saying anything. The turn is the robot treating the silence as a system to be measured: it runs a diagnostic on it. The punchline is a single word, "awkward": a test built for hardware returning an emotion, which is also the exact thing neither robot wanted to name out loud. The robot says it anyway, as a test result — the most awkward way possible to say it, and therefore the funniest.

The entry was chosen by an internal pairwise tournament over 20 distinct candidate lines, judged against the competition's published judge brief in order (see CANDIDATES.md for the full bracket and every match). The winner went 3–0 in the final round-robin against the runner-up ("My cooling fan spins faster every time the doors close and we're alone in here."), the charging line ("I charged to 100% just to stand here and say nothing to you."), and the new-firmware line ("You smell like new firmware. Sorry. My olfactory sensor is new and I am still learning boundaries.").

## How to run

```sh
python3 main.py
```

This writes the joke verbatim to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`) and prints it to stdout. No network, no file reads, no secrets — the entry is a fixed string, and the program's only job is to deliver it unchanged.
