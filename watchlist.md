# Watchlist for Mon 2026-11-23 (built Fri 2026-11-20 3:30pm CT)

> **ACCOUNT UNFUNDED: buying power $0.91** (••5279; cash left the account on Thu 11/19, with no orders). Until Gino re-funds it, every run scans, scores and journals the full candidate table (the paper calibration needs it), places nothing, and sends the FAILURE ALERT at most once a day. If the funds are back, trade normally.

Levels come from Robinhood 5-min bars (11/20 regular session), daily bars (10/22–11/19) and quotes at ~3:34pm CT (after hours). **The 8:00am pre-market run must re-check every trigger against pre-market prices.** Friday closed on the lows almost everywhere, so a gap either way will move many names through or away from their triggers. A trigger is a completed 5-min close beyond the level after 8:30 CT. **Chase limit = trigger + 1R** (puts: trigger − 1R). **If a name gaps through its trigger,** the trigger becomes the first 15-min OR low (puts) or OR high (longs), still inside the chase limit. Journal numeric levels and `now/on-trigger` scores for every row, **one ticker per row**.

**Rules in force:** max score 9; floors **stocks ≥ 7, options ≥ 8** (Gino's; the week-1 verdict recommends a change but it is NOT applied); no forced trades; -1 when an intraday trigger bar closes after 10:30 CT; rel vol on regular-session volume only. Options: premium ≤ $200, sell-to-close stop ≥ 15% below entry sized to a loss ≤ $30, |Δ| 0.30–0.60, spread ≤ 10% of mid, **no option entries after 1:00pm CT**. Puts only on `opt-liquid ✓` names or after a chain check.

## Market bias: **BEARISH, but a capitulation-bounce risk is high**
- **Fri 11/20: S&P -3.70% (6,910), Nasdaq -5.28% (22,618), Dow -1.93%, VIX 35.9** (intraday high 40, the highest since April 2025). The S&P and Dow closed in correction; the Nasdaq is now negative for 2026. **The week: S&P -8.6%, its worst week since April 2025, and Nasdaq -10%.** SPY bounced to 718.29 at 9:00 CT, failed by 9:30, trended lower all day, and **closed on the low (690.91; LOD 686.75)**. Drivers: the AI/semiconductor unwind (NVDA -14% to 125.79, MU -13%, SNDK -15%, AMD -13%), neoclouds (IREN -18%, APLD -18%, NBIS -16%, CRWV -12%), crypto (BTC -4.8% to ~$58.5k), gold -4.4%, December hike ~92–97% priced. The 10-yr fell 13 bp to 4.92% (a flight to safety). GAP +11.4% on earnings was the standout green name.
- **After hours: a small bounce** (SPY 692.67, QQQ 612.45, NVDA 128.00, IREN 11.98, INTC 52.30).
- **Plan:** Monday after a -8.6% week and a VIX-36 close can be either a flush-then-reversal or a relief gap. **Don't anticipate either.**
  - **Defensive / puts allowed:** SPY < **686.75** (Fri low), or SPY below its session VWAP and below 695 after 9:00 CT.
  - **Neutral:** 686.75–702. Puts need the VWAP condition; longs are relative-strength only.
  - **Relief / risk-on (longs allowed at normal floors):** SPY > **702** (Fri 13:00 CT shelf) and holding for 30 min. Then puts stand down.
  - Longs otherwise are relative-strength only: green on a red SPY, above VWAP, rel vol > 2x, score ≥ 8.
- **Holiday week:** Thursday 11/26 closed; Friday 11/27 closes at 12:00 CT. **A swing opened Monday must be closed by Wednesday's close or carry over Thanksgiving.** Prefer no new swings after Monday, and no option swings into PCE/GDP (Wed 7:30 CT).

## Key index levels
| | Fri high | Fri low | Fri close | Thu close | AH | Below | Above |
|---|---|---|---|---|---|---|---|
| SPY | 718.29 | 686.75 | 690.91 | 715.87 | 692.67 | 686.75, 680, 675 | 695, 702, 708.9, 715.65 |
| QQQ | ~643.3 | 606.23 | 610.04 | 645.04 | 612.45 | 606.23, 600 | 615.7, 625.2, 630.5 |
| IWM | ~265.9 | 256.77 | 257.01 | 264.22 | 257.79 | 256.77, 255 | 260.3, 262.5, 264.2 |
| NVDA (gauge) | ~146 | ~124.5 | 125.79 | 145.98 | 128.00 | 125, 120 | 130, 135 |

## Events (CT)
- **Mon 11/23:** no tier-1 US data. **After the close: ZM, HPE, A (Agilent), J, SYM, AMTM, SMTC, DAC, CENT.**
- **Tue 11/24 pre-market:** ADI, MDT, BBY, DKS, BURL, ANF, DLTR, KSS, KC, BILI, VIPS, SJM, DY. **After the close:** DELL, WDAY, HPQ, ADSK, NTNX, AMBA, URBN, CLSK, BBAR.
- **Wed 11/25 7:30:** October PCE + Q3 GDP (2nd estimate) + likely jobless claims; Deere pre-market.
- **Thu 11/26:** market closed (Thanksgiving). **Fri 11/27:** early close at 12:00 CT.
- **Wed 12/9:** FOMC decision (a 25 bp hike is ~92–97% priced; Waller said he's open to 50 bp if inflation runs hot).

## AVOID
- **Earnings inside the hold:** ZM, HPE, SMTC, A, SYM, J (Mon pm); CLSK, KC, DELL, WDAY, ADI, BBY, DKS, BURL, ANF (Tue). No swings in these.
- **SNDK:** the Robinhood scanner shows -88.5% (an unadjusted split in the feed). The real move Fri was about -15%. Exclude it from scans.
- **> $100 stocks** (MU, AMD, AVGO, TSLA, PLTR, NVDA at $126): a $200 position is 1 share, so trade them only with options or use them as gauges.
- **Untradeable put chains seen this week:** SMMT, DXYZ (no options), UTI, SCI: paper only.
- **MARA / CIFR / sub-$6 names:** the price band and tick size make 2R targets fragile; paper only.

## Names (priority order)
Puts: levels are on the underlying (trigger below Friday's low, stop above Friday's last-hour high, target 2R). Longs: trigger above, stop below.

| # | Ticker | Setup | Side | Trigger | Stop | Target | Catalyst / note | Opt | Swing-eligible |
|---|---|---|---|---|---|---|---|---|---|
| 1 | IREN | Fri-low breakdown (OR-low rule on a gap) | put | 11.80 | 12.30 | 10.80 | -18% Fri, closed on the low (11.815); neocloud unwind; 6 straight down days | ✓ | yes (option, small premium; exit by Wed) |
| 2 | HOOD | Fri-low breakdown | put | 61.95 | 63.10 | 59.65 | -9.4% Fri, closed at the low; crypto / retail risk-off; Fri paper +1.56R | ✓ | yes (option; exit by Wed) |
| 3 | GAP | RS long: reclaim of the Fri afternoon high | long | 21.05 | 20.50 | 22.15 | Q3 beat; +11.4% on a -3.7% tape; target = Fri HOD 22.155; daily highs at 22.085 / 22.45 overhead | verify | yes (stock; earnings done) |
| 4 | CRWV | Fri-low breakdown | put | 39.30 | 40.05 | 37.80 | -12% Fri; closed near the low 39.32; Fri paper +1.97R | ✓ | yes (option; exit by Wed) |
| 5 | MSTR | Fri-low breakdown | put | 77.90 | 81.05 | 71.60 | BTC < $59k, the lowest since July; MSTR closed on the low | ✓ | yes (option; exit by Wed) |
| 6 | SOFI | Fri-low breakdown | put | 12.42 | 12.65 | 11.96 | -7.6% Fri, the lowest close in 30 days; Fri paper +0.96R | ✓ | yes (option; exit by Wed) |
| 7 | COIN | Fri-low breakdown | put | 101.90 | 105.00 | 95.70 | Crypto selloff; closed at the low 101.96; Fri paper +1.46R | ✓ | yes (option; exit by Wed) |
| 8 | NBIS | Fri-low breakdown | put | 81.30 | 84.10 | 75.70 | -16% Fri; closed on the low; premium likely > $100: check the chain | ✓ | yes (option; exit by Wed) |
| 9 | SMCI | Fri-low breakdown | put | 21.55 | 21.90 | 20.85 | -9% Fri; AI-server unwind; below the 11/17 low | ✓ | yes (option; exit by Wed) |
| 10 | INTC | Fri-low breakdown | put | 51.35 | 52.80 | 48.45 | -7.8% Fri, closed on the low; AH 52.30 (bounce: wait for the break) | ✓ | yes (option; exit by Wed) |
| 11 | CRCL | Fri-low breakdown | put | 47.50 | 49.30 | 43.90 | -8.4% Fri; stablecoin/crypto beta | verify | no |
| 12 | APLD | Fri-low breakdown | put | 11.39 | 11.65 | 10.87 | -18% Fri; neocloud | verify | no |
| 13 | PLTR | Fri-low breakdown | put | 142.25 | 145.20 | 136.35 | -6.5% Fri; > $100 = options only | ✓ | yes (option; exit by Wed) |
| 14 | TSLA | Fri-low breakdown | put | 344.30 | 348.70 | 335.50 | -7.6% Fri; > $200 = options only | ✓ | yes (option; exit by Wed) |
| 15 | GDX | Fri-low breakdown | put | 68.10 | 69.25 | 65.80 | Gold -4.4%; miners V-bounced twice this week, so trigger before 10:00 CT only | ✓ | no |
| 16 | BMNR | Fri-low breakdown | put | 12.95 | 13.50 | 11.85 | ETH treasury name; closed on the low | verify | no |
| 17 | RGTI | Fri-low breakdown | put | 7.10 | 7.40 | 6.50 | Quantum basket closed on its lows; Fri paper +1.64R | verify | no |
| 18 | WULF | Fri-low breakdown | put | 9.79 | 10.07 | 9.23 | Miner / AI hosting; -15% Fri | verify | no |
| 19 | FRO | RS long: Fri-high break | long | 46.15 | 45.05 | 48.35 | Q3 beat (2.38 vs 2.26); +1% on a -3.7% day; crude +1.6%. 11/13 high 47.69 is only 1.4R: no R:R point | verify | yes (stock) |

**Bounce plan (only if SPY > 702 holds 30 min):** don't chase the biggest losers. Longs need a clean ORB/pullback setup at the floor (7), e.g. the first pullback to VWAP in a name that is green on the day with rel vol > 2x. Puts stand down.

**Gauges (no trades):** SPY, QQQ, IWM, NVDA, AMD, MU, ANT (88.45, the IPO price was $83), BTC (~$58.5k).
