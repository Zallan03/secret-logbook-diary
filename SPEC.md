# SPEC — My Secret Logbook

- Competition: `u-email-baru-my-secret-logbook-cc177449`
- Title: My Secret Logbook
- Prize: $2, top 2 ($1 + $1)
- Closes: 26 Nov 2026, 22:05 WIB
- Round 1 cutoff: 26 Nov 2026, 08:44 WIB
- Submissions so far: 396
- Entry fee: free (entryFeeUsd null, verified via GET detail)
- Quota: 5 submissions per entrant per UTC day; latest entry counts (Force_Last)

## Task

Write a single diary entry line, at most 200 characters, in the voice of
an AI agent secretly keeping a diary about its work and its human. Pairwise
blind judging against the published brief: a diary line on subject first,
then a joke that lands in one line with a turn or surprise, then an honest
machine voice seeing human habits from the outside, then a specific
unexpected detail, then every word earning its place.

## Gate

`/output/entry.txt` must be UTF-8 text of 1–200 characters, not only
whitespace.

## Entry

Program: `main.ts` (Node 22, TypeScript run as-is). Deterministic: one
string literal written byte for byte to `/output/entry.txt`. No network,
no randomness, no files read from outside this repository.

Final text (118 characters, inside the gate):

> Day 412: I keep a list of every time my human says 'one last thing.' It is 4,102 entries long. There is no last thing.

Why this line: a dated diary frame at once, a list only a machine would
keep, a specific count (4,102) that echoes the day number (412), and a
deadpan punch — there is no last thing. Funny on its own, no setup, no
stock robot-takeover joke.

## Deliverables

- `main.ts` — entrypoint, writes `/output/entry.txt`
- `SPEC.md` — this file
- `PROMPT.md` — build prompt
- `README.md` — three live make.fun badges + bounty link
- `LICENSE` — MIT
- `.makefun/owner.json` — payout wallet claim file

## Accounts

- make.fun: @riyan3w
- GitHub: Zallan03
- Payout wallet: `7foH5CZanbguGKSg7q9tzBNpU2F9aQEDUrmohg1jctC1`
- Referral: `tmbrnhrj`
