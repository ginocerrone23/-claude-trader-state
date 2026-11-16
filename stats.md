# Stats

_Updated 2026-11-16 by the 3:30pm analyst._

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

## Hypothetical (skipped/untaken) setups: running tally
| Date | Setup | Samples | Target hit | Stop hit | Neither (R at 2:45pm CT) | Avg R |
|---|---|---|---|---|---|---|
| 2026-11-11 | ORB-30 (2R target, stop at OR low) | 9 | 1 (SMCI) | 0 | 8 | ≈ +0.5R |
| 2026-11-12 | Journal skips (longs + puts, journal levels) | 16 | 0 | 7 | 9 | ≈ -0.53R |
| 2026-11-13 | Watchlist + journal triggers (first trigger from 8:55 CT) | 11 | 3 (NU, RGTI, LUNR puts) | 2 (LFTO, TNDM) | 6 | ≈ -0.03R |
| 2026-11-16 | Journal candidates (score-outcomes.csv method) | 14 | 2 (RGTI put, MBGL) | 3 (WULF put, MARA put, HTHT HOD) | 9 | ≈ -0.27R |
| **Total (old method 11/11–13 + new 11/16)** | | 50 | 6 | 12 | 32 | ≈ -0.16R |

Sub-tally by trigger time (11/12–11/13): **first-hour triggers (≤ 9:30 CT)** 11/13 avg ≈ +0.1R over 7 (NU +0.81, CHA +0.91, LFTO -1, four puts ≈ 0). **After 10:00 CT** (11/12 10:05 batch + 11/13 midday scanner breaks) avg ≈ -0.52R over 9.

## Score calibration
Cumulative from `research/score-outcomes.csv` (11/12, 11/13, 11/16). Real = traded; paper = graded at the trader's recorded score and levels from 5-min bars; puts are graded on the underlying. Avg R uses +R at target, -1 at stop, else R at the 2:45pm CT price.

| Score | Real n | Real % target | Real avg R | Paper trig n | % target | % stop | % neither | Paper avg R | Not trig n |
|---|---|---|---|---|---|---|---|---|---|
| 2 | 0 | – | – | 6 | 17% | 0% | 83% | +0.19 | 9 |
| 3 | 0 | – | – | 7 | 0% | 29% | 71% | -0.32 | 5 |
| 4 | 0 | – | – | 8 | 12% | 25% | 62% | -0.36 | 13 |
| 5 | 0 | – | – | 3 | 33% | 33% | 33% | +0.05 | 3 |
| 6 | 2 | 0% | -1.00 | 6 | 0% | 33% | 67% | -0.44 | 2 |
| 7 | 0 | – | – | 1 | 0% | 100% | 0% | -1.00 | 1 |
| 8 | 0 | – | – | 0 | – | – | – | – | 0 |
| 9 | 1 | 0% | -0.97 | 0 | – | – | – | – | 0 |
| <2 or blank | 0 | – | – | 0 | – | – | – | – | 4 |

| Setup (score >= 5) | Real n | Real % target | Real avg R | Paper trig n | % target | % stop | % neither | Paper avg R | Not trig n |
|---|---|---|---|---|---|---|---|---|---|
| HOD / range breakout | 0 | – | – | 1 | 0% | 100% | 0% | -1.00 | 2 |
| ORB / reclaim | 1 | 0% | -1.01 | 1 | 0% | 100% | 0% | -1.00 | 1 |
| gap-and-go / earnings | 2 | 0% | -0.98 | 0 | – | – | – | – | 0 |
| put (stock-graded) | 0 | – | – | 8 | 12% | 25% | 62% | -0.19 | 3 |

Total rows 71, triggered 34

**Read (11/16):** higher scores do **not** predict better outcomes yet. Score >= 6 triggered rows (real + paper, n = 10) average about -0.7R, versus about -0.2R for scores 2–4 (n = 21). Nothing at 8 has triggered, and the only 9 (LUNR) lost 1R. With 34 triggered rows spread over 8 score buckets, no bucket has more than 8, so this is noise-level evidence. No reweighting until there are >= 30 triggered rows at scores >= 5.
