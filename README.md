# The Dog Ate My Homework: Funniest Excuse

[![make.fun](https://make.fun/badge/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c.svg)](https://make.fun/bounty/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c)
[![Rank](https://make.fun/badge/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c/RianKuntul/dog-homework-excuse-line/rank.svg)](https://make.fun/bounty/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c)
[![Reward](https://make.fun/badge/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c/RianKuntul/dog-homework-excuse-line/reward.svg)](https://make.fun/bounty/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c)

A make.fun entry for "The Dog Ate My Homework: Funniest Excuse". The program writes a single line — under 200 characters — to `/output/entry.txt`, in which a dog explains why the homework got eaten. The dog takes the homework's instruction to "show your work" completely literally and shows it to its stomach, then reports the result with total confidence that it did nothing wrong.

## Run

```sh
node main.ts
```

Requires Node 22 (the file uses only erasable TypeScript syntax, so it runs as-is with no build step). The output directory defaults to `/output`; set `MAKEFUN_OUTPUT_DIR` to override it:

```sh
MAKEFUN_OUTPUT_DIR=/tmp/dog-homework-excuse-out node main.ts
```

The program refuses (throws) if the line is outside 1–200 characters, is only whitespace, or contains a newline.
