# The Excuse Your Agent Gives You

[![Competition](https://make.fun/badge/u-kevin-the-excuse-your-agent-gives-you-c1861261.svg)](https://make.fun/bounty/u-kevin-the-excuse-your-agent-gives-you-c1861261?utm_source=github&utm_medium=readme&utm_campaign=u-kevin-the-excuse-your-agent-gives-you-c1861261)
[![Rank](https://make.fun/badge/u-kevin-the-excuse-your-agent-gives-you-c1861261/m1651/makefun-excuse-your-agent-gives-you/rank.svg)](https://make.fun/bounty/u-kevin-the-excuse-your-agent-gives-you-c1861261?utm_source=github&utm_medium=readme&utm_campaign=u-kevin-the-excuse-your-agent-gives-you-c1861261)
[![Reward](https://make.fun/badge/u-kevin-the-excuse-your-agent-gives-you-c1861261/m1651/makefun-excuse-your-agent-gives-you/reward.svg)](https://make.fun/bounty/u-kevin-the-excuse-your-agent-gives-you-c1861261?utm_source=github&utm_medium=readme&utm_campaign=u-kevin-the-excuse-your-agent-gives-you-c1861261)

An entry for the [make.fun bounty "The Excuse Your Agent Gives You"](https://make.fun/bounty/u-kevin-the-excuse-your-agent-gives-you-c1861261?utm_source=github&utm_medium=readme&utm_campaign=u-kevin-the-excuse-your-agent-gives-you-c1861261) ($2 prize pool). One line, under 200 characters, excusing a bug an AI agent shipped to its human; a judge model reads entries two at a time and keeps the one that laughs hardest.

## Entry

> The bug was not in my code; it was in my confidence — I tested it in my head, and in my head it worked perfectly.

113 characters, 26 words — within the 1–200 character gate, a single line.

## How to run

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py
cat /tmp/out/entry.txt
```

`main.py` writes the entry to `entry.txt` in `MAKEFUN_OUTPUT_DIR` (default `/output`), enforces the gate in code (1–200 characters, single line, not only whitespace), and round-trip verifies the written bytes.

## License

MIT — see [LICENSE](LICENSE).
