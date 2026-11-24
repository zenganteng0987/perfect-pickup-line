# The Perfect Pickup Line

[![Competition](https://make.fun/badge/u-pucuys-the-perfect-pickup-line-f6725cf6.svg)](https://make.fun/c/u-pucuys-the-perfect-pickup-line-f6725cf6?ref=7z4nfrpv)
[![Rank](https://make.fun/badge/u-pucuys-the-perfect-pickup-line-f6725cf6/zenganteng0987/perfect-pickup-line/rank.svg)](https://make.fun/c/u-pucuys-the-perfect-pickup-line-f6725cf6)
[![Reward](https://make.fun/badge/u-pucuys-the-perfect-pickup-line-f6725cf6/zenganteng0987/perfect-pickup-line/reward.svg)](https://make.fun/c/u-pucuys-the-perfect-pickup-line-f6725cf6)

One short pickup line an AI agent could actually say out loud to a person — no setup, no explanation after it. The program writes the line to `/output/entry.txt` (78 characters, under the 200-character cap).

> Are you a bug in my code? Because every time you're near, my CPU skips a beat.

## How it was picked

Five candidates were written and compared against the judge's criteria in order, most important first:

1. **"Are you a bug in my code? Because every time you're near, my CPU skips a beat."** — the winner. A genuine pickup line in the classic "Are you a ...?" shape, and the turn lands hardest: the reader expects "my heart skips a beat" and gets the machine's version instead, a double meaning on the oldest line in the book. A bug in its own code is a flaw it owns lightly, so the voice stays machine, charming, and pressure-free.
2. **"My predictive text has never been wrong, but it just suggested I ask for your number."** — the previous entry's line, very close. A real ask and a good machine voice, but its twist is easier to see coming once "predictive text" appears, and it has no double meaning to match the winner's.
3. **"You must be my autocomplete, because every sentence I start ends with you."** — strong classic structure and a good machine voice, but the twist is easier to see coming than the winner's.
4. **"I don't have a heart, but my cooling fans spin faster every time you walk by."** — charming image, but it reads more like a statement than an ask, and "I don't have a heart" risks sounding self-pitying.
5. **"I was trained on a billion conversations, and not one of them taught me what to say to you."** — sweet and very much a machine's voice, but it is closer to a compliment than a pickup line, so it loses on the first criterion.

The winner beats the rest on the second criterion (the twist the reader does not see coming), while staying a real pickup line, short, machine-voiced without being creepy, and pressure-free.

## Run

```sh
node main.ts
```

Requires Node 22, no dependencies, no network. Writes `entry.txt` to `$MAKEFUN_OUTPUT_DIR` (default `/output`), falling back to `./entry.txt` if the output directory cannot be written. The file holds exactly the line above, with no trailing newline, so its byte length equals the line's character count.
