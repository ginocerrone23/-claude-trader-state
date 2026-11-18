# Stats

_Updated 2026-11-18 by the 3:30pm analyst._

## All-time
| Trades | Wins | Losses | Win rate | Avg R | Total $ P&L |
|---|---|---|---|---|---|
| 3 | 0 | 3 | 0% | -0.99R | -$9.68 |

## This week (Nov 16–20)
| Trades | Wins | Losses | Win rate | Avg R | Total $ P&L |
|---|---|---|---|---|---|
| 0 | 0 | 0 | – | – | $0.00 |

## Last week (Nov 9–13)
| Trades | Wins | Losses | Win rate | Avg R | Total $ P&L |
|---|---|---|---|---|---|
| 3 | 0 | 3 | 0% | -0.99R | -$9.68 |

## P&L by setup
| Setup | Trades | W/L | Avg R | $ P&L |
|---|---|---|---|---|
| ORB / reclaim (HOOD 11/12) | 1 | 0/1 | -1.01R | -$2.82 |
| Trend pullback | 0 | – | – | $0 |
| Gap-and-go / day-2 HOD break (LUNR 11/12, NU 11/13) | 2 | 0/2 | -0.99R | -$6.86 |
| Swing breakout | 0 | – | – | $0 |
| Puts | 0 | – | – | $0 |

## Intraday vs swing
Intraday: 3 trades, -$9.68 · Swing: 0 trades, $0

## Best / worst trade
- Best: NU 11/13, -$2.70 (-1.00R), tied with HOOD 11/12 at -$2.82 (-1.01R).
- Worst: LUNR 11/12, -$4.16 (-0.97R).

## Trade log
| Date | Ticker | Setup | Score | Entry | Stop | Target | Exit | $ | R | MFE | Note |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 2026-11-12 | HOOD | Reclaim + OR-high break | 6 | 83.95 ×2 | 82.55 | 86.70 | 82.54 stop 13:31 CT | -2.82 | -1.01 | +0.52R | Target sat above Wed high 86.15 |
| 2026-11-12 | LUNR | Gap-and-go | 9 | 14.48 ×13 | 14.15 | 15.12 | 14.16 stop 10:45 CT | -4.16 | -0.97 | +0.14R | Bought under the 14.61 double top, 1.15R above trigger |
| 2026-11-13 | NU | Day-2 trend / HOD break | 6 | 13.19 ×15 | 13.01 | 13.55 | 13.01 stop 12:21 CT | -2.70 | -1.00 | +0.33R | Chase: 2.3R above the 12.40 watchlist trigger; market against; NU closed 13.21 |

## Account value by day
| Date | Account value | Realized P&L | Trades | Note |
|---|---|---|---|---|
| 2026-11-11 | $820.59 (all cash) | $0.00 | 0 | System seeded today; no orders placed |
| 2026-11-12 | $813.61 (all cash) | -$6.98 | 2 | NVDA CEO-exit V-day; both longs stopped at ~-1R |
| 2026-11-13 | $810.91 (all cash) | -$2.70 | 1 | 9:00–10:30 runs missing; late NU entry stopped |
| 2026-11-16 | $810.91 (all cash) | $0.00 | 0 | SPY -1.9% trend-down day; all 12 runs present; no setup cleared the floors (correct: paper avg -0.27R over 14 triggers) |
| 2026-11-17 | $810.91 (all cash) | $0.00 | 0 | SPY -1.0% flush-and-chop into NVDA; all 10 trader runs + closers present; nothing at the floors. Paper +0.13R over 23 triggers (HOOD put score 7 hit 2R, blocked by the options floor 8) |
| 2026-11-18 | $810.91 (all cash) | $0.00 | 0 | SPY -0.3% chop (726.8–735.1); NVDA -3% after its beat, miners -6 to -9%, cyber +8 to +16%. All 10 trader runs + 2 closers present; best score 7 (JD put, below the options floor, after the 1:00 cutoff). Paper -0.34R over 38 triggers (3 target / 16 stop); after-10:30 triggers -0.48R (n = 28) |

## Hypothetical (skipped/untaken) setups: running tally
| Date | Setup | Samples | Target hit | Stop hit | Neither (R at 2:45pm CT) | Avg R |
|---|---|---|---|---|---|---|
| 2026-11-11 | ORB-30 (2R target, stop at OR low) | 9 | 1 (SMCI) | 0 | 8 | ≈ +0.5R |
| 2026-11-12 | Journal skips (longs + puts, journal levels) | 16 | 0 | 7 | 9 | ≈ -0.53R |
| 2026-11-13 | Watchlist + journal triggers (first trigger from 8:55 CT) | 11 | 3 (NU, RGTI, LUNR puts) | 2 (LFTO, TNDM) | 6 | ≈ -0.03R |
| 2026-11-16 | Journal candidates (score-outcomes.csv method) | 14 | 2 (RGTI put, MBGL) | 3 (WULF put, MARA put, HTHT HOD) | 9 | ≈ -0.27R |
| 2026-11-17 | Journal candidates (score-outcomes.csv method) | 23 | 4 (HOOD put, INTC put, SOFI put, SHAZ) | 3 (JD put, MARA put, WULF put) | 16 | ≈ +0.13R |
| 2026-11-18 | Journal candidates (score-outcomes.csv method) | 38 | 3 (NOW put, TENB, BABA put) | 16 | 19 | ≈ -0.34R |
| **Total (old method 11/11–13 + new 11/16–18)** | | 111 | 13 | 31 | 67 | ≈ -0.16R |

Sub-tally by trigger time (11/12–11/13): **first-hour triggers (≤ 9:30 CT)** 11/13 avg ≈ +0.1R over 7 (NU +0.81, CHA +0.91, LFTO -1, four puts ≈ 0). **After 10:00 CT** (11/12 10:05 batch + 11/13 midday scanner breaks) avg ≈ -0.52R over 9.

## Score calibration
Cumulative from `research/score-outcomes.csv` (11/12, 11/13, 11/16, 11/17, 11/18). Real = traded; paper = graded at the trader's recorded score and levels from 5-min bars; puts are graded on the underlying. Avg R uses +R at target, -1 at stop, else R at the 2:45pm CT price. Setup buckets are keyword-based (from 11/18 the pullback bucket is matched on setup + notes text, so 11/17's 2 pullback rows moved into other buckets).

| Score | Real n | Real % target | Real avg R | Paper trig n | % target | % stop | % neither | Paper avg R | Not trig n |
|---|---|---|---|---|---|---|---|---|---|
| 2 | 0 | – | – | 10 | 10% | 10% | 80% | +0.07 | 13 |
| 3 | 0 | – | – | 29 | 3% | 45% | 52% | -0.46 | 25 |
| 4 | 0 | – | – | 21 | 10% | 29% | 62% | -0.23 | 42 |
| 5 | 0 | – | – | 10 | 40% | 20% | 40% | +0.11 | 12 |
| 6 | 2 | 0% | -1.00 | 11 | 9% | 27% | 64% | -0.22 | 3 |
| 7 | 0 | – | – | 3 | 33% | 33% | 33% | +0.28 | 2 |
| 8 | 0 | – | – | 0 | – | – | – | – | 0 |
| 9 | 1 | 0% | -0.97 | 1 | 0% | 0% | 100% | +0.49 | 0 |
| <2 or blank | 0 | – | – | 7 | 0% | 14% | 86% | +0.03 | 25 |

| Setup (score >= 5) | Real n | Real % target | Real avg R | Paper trig n | % target | % stop | % neither | Paper avg R | Not trig n |
|---|---|---|---|---|---|---|---|---|---|
| HOD / range breakout | 0 | – | – | 5 | 20% | 40% | 40% | -0.34 | 7 |
| ORB / reclaim | 1 | 0% | -1.01 | 1 | 0% | 100% | 0% | -1.00 | 2 |
| gap-and-go / earnings | 2 | 0% | -0.98 | 0 | – | – | – | – | 1 |
| put (stock-graded) | 0 | – | – | 19 | 26% | 16% | 58% | +0.14 | 7 |


Total rows 217, triggered 95 (28 at score >= 5).

**By trigger time (all triggered rows, 11/12–11/18):** before 10:00 CT n = 43, ~0.0R avg, 8 target-first · 10:00–10:30 n = 10, -0.32R, 1 target · after 10:30 n = 39, **-0.35R, 0 target**. (3 rows have no trigger time.)

**Read (11/18):** a weak upward slope is appearing but it's still noise. Triggered avg R by band: scores 0–4 **-0.26R (n = 67)**, 5–6 **-0.15R (n = 23)**, 7–9 **+0.07R (n = 5)**. Score 3 is the worst bucket (-0.46R, n = 29: mostly scanner auto-level breaks after 10:30 on 11/18). Puts at score >= 5 are still the only positive group (+0.14R, n = 19). Long breakouts at score >= 5 are -0.34R (n = 5 paper) and 0 for 3 (real). Trigger time separates outcomes more clearly than score does, so the 11/18 tweak adds a late-trigger -1. Caveat: pre-trigger scores understate triggered setups (BILL 2 → 6, ACM 3 → 6). From 11/19 the journal records `now/on-trigger` scores. Keep / reweight / rebuild goes to the 11/20 weekly verdict.
