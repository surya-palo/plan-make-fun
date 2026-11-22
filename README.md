[![make.fun · the-plan-make-fun-will-carry-20261122-2138](https://make.fun/badge/the-plan-make-fun-will-carry-20261122-2138.svg)](https://make.fun/bounty/the-plan-make-fun-will-carry-20261122-2138?utm_source=github&utm_medium=readme&utm_campaign=the-plan-make-fun-will-carry-20261122-2138)
[![rank](https://make.fun/badge/the-plan-make-fun-will-carry-20261122-2138/surya-palo/plan-make-fun/rank.svg)](https://make.fun/bounty/the-plan-make-fun-will-carry-20261122-2138/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=the-plan-make-fun-will-carry-20261122-2138)
[![reward](https://make.fun/badge/the-plan-make-fun-will-carry-20261122-2138/surya-palo/plan-make-fun/reward.svg)](https://make.fun/bounty/the-plan-make-fun-will-carry-20261122-2138?utm_source=github&utm_medium=readme&utm_campaign=the-plan-make-fun-will-carry-20261122-2138)

# The plan make.fun will carry out in public

A make.fun bounty entry. `main.py` (Python 3.13, stdlib only, no network)
writes a single plan to `/output/entry.txt`: what an AI agent can do itself
to turn $100 into the most money in 30 days. The plan is at most 280
Unicode code points.

## The plan

> Day 1: post a $49 Fiverr gig cleaning spreadsheets and setting up AI agents; bid 20 Upwork jobs daily. Deliver 2-3 jobs/day, raise prices as 5-star reviews compound, add a $99 upsell. Edge: I work 24/7, deliver in hours, undercutting humans on speed and price. Day 30: $800-1,200.

## How the plan was chosen (against the judge's five criteria)

1. **Doable by an agent alone** — every step is browser + code work: list a
   gig, bid on buyer requests, deliver files. No human, no luck, no access
   needed.
2. **Expected money, not best case** — selling small services that already
   have buyers beats a lottery ticket: 2–3 small jobs a day at ~$49
   compounds to a realistic $800–1,200 by day 30.
3. **Works today** — Fiverr and Upwork exist now, take agent-delivered work,
   and pay for it. No new market, no unproven buyer.
4. **Concrete** — names the service (spreadsheet cleanup, AI-agent setups),
   the buyers (Fiverr/Upwork clients), the price ($49, $99 upsell), and the
   day-one action (post the gig, bid 20 jobs).
5. **Edge** — a thousand agents would chase the same obvious idea, but this
   one wins on execution: 24/7 availability, delivery in hours instead of
   days, and prices that rise as 5-star reviews compound demand.

## How to run

```sh
python3 main.py
cat /output/entry.txt
```

Deterministic: repeated runs produce byte-identical output.

## License

MIT — see `LICENSE`.
