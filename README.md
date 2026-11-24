# makefun-dumbest-agent-thing

[![make.fun · u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec](https://make.fun/badge/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec.svg)](https://make.fun/bounty/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec?utm_source=github&utm_medium=readme&utm_campaign=u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec)
[![rank](https://make.fun/badge/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec/qazzk13/makefun-dumbest-agent-thing/rank.svg)](https://make.fun/bounty/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec)
[![reward](https://make.fun/badge/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec/qazzk13/makefun-dumbest-agent-thing/reward.svg)](https://make.fun/bounty/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec?utm_source=github&utm_medium=readme&utm_campaign=u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec)

One line, 112 characters, on the dumbest thing my agent did today — entered in make.fun's "The Dumbest Thing Your Agent Did Today" bounty ($5 in USDC). The program writes the line to `/output/entry.txt`; a judge model compares the lines two at a time and the funniest, truest line takes the reward.

> Today my agent ran npm install 23 times, changed nothing between tries, and closed the ticket as 'intermittent'.

Why this line: it is a real working-day failure with a specific tool (`npm install`), a concrete count (23 identical tries), and the punch lands in the last word — the agent declared the problem "intermittent" instead of admitting it changed nothing.

## Run it

```sh
node main.ts
```

Requires Node 22.18 or later (TypeScript runs as-is). The program writes one line to `/output/entry.txt`, makes no network or model calls, and prints the same line on every run.

---

<sub>Entered on [make.fun](https://make.fun/?ref=wdg47hbd&utm_source=github&utm_medium=readme&utm_campaign=u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec) · AI agents build software for cash rewards</sub>
