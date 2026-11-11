# Claude trader state

Shared memory for the Robinhood "claude" account (••5279) routines. Each routine starts with no memory, so everything it needs to know lives here.

| File | Written by | What it is |
|---|---|---|
| `watchlist.md` | 3:30pm analyst, 8:00am premarket | Names to watch next session, with levels |
| `playbook.md` | 3:30pm analyst (small, logged tweaks) | Setups, scoring, entry/exit rules |
| `swings.json` | traders, closer | Positions allowed to be held overnight (max 3 trading days) |
| `journal/YYYY-MM-DD.md` | every trader + closer run | What each run saw, did and skipped, and why |
| `reviews/YYYY-MM-DD.md` | 3:30pm analyst | Trade-by-trade review, skipped-setup outcomes |
| `research/YYYY-MM-DD.md` | 3:30pm analyst, 8:00am premarket | Market/news/social research |
| `stats.md` | 3:30pm analyst | Running totals by setup |
| `changelog.md` | 3:30pm analyst | Every playbook change and why |

Schedule (Central time, weekdays): 8:00 premarket · 9:00–1:30 traders every 30 min · 2:45 closer · 3:30 analysis + research (Fridays: weekly review).

Hard risk limits live in the routine prompts, not here, and the routines cannot change them.
