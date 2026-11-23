# Watchlist for Mon 2026-11-23 (built Fri 2026-11-20 3:30pm CT)

> **ACCOUNT UNFUNDED: buying power $0.91** (••5279; cash left the account on Thu 11/19, with no orders). Until Gino re-funds it, every run scans, scores and journals the full candidate table (the paper calibration needs it), places nothing, and sends the FAILURE ALERT at most once a day. If the funds are back, trade normally.

Levels come from Robinhood 5-min bars (11/20 regular session), daily bars (10/22–11/19) and quotes at ~3:34pm CT (after hours). **The 8:00am pre-market run must re-check every trigger against pre-market prices.** Friday closed on the lows almost everywhere, so a gap either way will move many names through or away from their triggers. A trigger is a completed 5-min close beyond the level after 8:30 CT. **Chase limit = trigger + 1R** (puts: trigger − 1R). **If a name gaps through its trigger,** the trigger becomes the first 15-min OR low (puts) or OR high (longs), still inside the chase limit. Journal numeric levels and `now/on-trigger` scores for every row, **one ticker per row**.

**Rules in force:** max score 9; floors **stocks ≥ 7, options ≥ 8** (Gino's; the week-1 verdict recommends a change but it is NOT applied); no forced trades; -1 when an intraday trigger bar closes after 10:30 CT; rel vol on regular-session volume only. Options: premium ≤ $200, sell-to-close stop ≥ 15% below entry sized to a loss ≤ $30, |Δ| 0.30–0.60, spread ≤ 10% of mid, **no option entries after 1:00pm CT**. Puts only on `opt-liquid ✓` names or after a chain check.

## Market bias (PRE-MARKET 8:00am CT UPDATE): **RELIEF GAP, risk-on open. The Fri-low put plan is VOID.**
- **Pre-market vs Fri close (Robinhood, 8:05 CT):** SPY 718.7 (**+4.2%**), QQQ 649.9 (**+6.8%**), IWM 264.8 (+3.2%). Futures: NQ +3-3.5%, ES ~+2.5%. Drivers: Asian regulators stabilizing markets (Taiwan short-sale curbs, China margin easing, Korea backstop), AI-financing fears easing, hike-size fears ebbing. Sentiment fragile: Nasdaq-100 still ~18% off its high, SOX -17% on the week, thin holiday liquidity, PCE Wed 7:30 CT.
- **SPY is already above the 702 "relief" line**, so per the bounce plan **puts stand down** until SPY loses 702 *and* session VWAP. Every Fri-low put trigger is 8-30% below pre-market: dead.
- **Regimes today:**
  - **Relief (default):** SPY > 702 and holding. Longs at normal floors (stocks >= 7, options >= 8), ORB/first-pullback-to-VWAP setups, rel vol > 2x. Don't chase the biggest gappers at the open.
  - **Gap-fade / failed bounce:** SPY back < **704.3** (50% of the gap) then < **702** and under VWAP: fade-puts re-armed on the names flagged "fade" below, using the 50%-gap level as the trigger. Full fill is 689.8.
  - **Defensive:** SPY < 686.75 (Fri low): original defensive rules.
- **Gap rule:** a trigger is the first completed 5-min close beyond the 15-min OR high (longs) / OR low (puts) after 8:45 CT; chase limit = trigger + 1R. Do not buy the pre-market high without an OR. Numeric stops below are references from pre-market prices; recompute from the OR at 8:45.
- **Holiday week unchanged:** Thu closed, Fri closes 12:00 CT. Swings opened today must exit by Wed close; no option swings into PCE/GDP Wed 7:30 CT. Prefer intraday.
- **Account still UNFUNDED ($0.91, checked 8:05 CT): paper only, FAILURE ALERT once/day.**

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
- **Earnings inside the hold:** ZM, HPE, SMTC, A, SYM, J, DAC (Mon pm); CLSK, KC, DELL, WDAY, ADI, BBY, DKS, BURL, ANF, DLTR, KSS, HPQ, ADSK, NTNX, URBN (Tue). No swings in these. HPE +13.9% and DELL +21.6% pre-market ahead of their prints: no entries.
- **CRWD:** reported this morning (EPS 0.34 vs 0.31) but -5.4% pre-market while the tape is +4%: weak. Skip longs; possible fade only if it loses its PM low, paper-only.
- **SNDK:** feed shows an unadjusted split (-88%); PM 90.3 vs 79.2 close looks like a normal +14%. Exclude from scans anyway until the analyst checks.
- **> $100 stocks** (MU, AMD, AVGO, TSLA, PLTR, NVDA, ZS, ARM, TSM, ORCL): options only or gauge.
- **Untradeable put chains seen:** SMMT, DXYZ, UTI, SCI: paper only.
- **MARA / CIFR / CLSK / sub-$6 names:** tick size makes 2R fragile; paper only.
- **Chasing PM highs** on +20-30% gappers (CRWV, NBIS, IREN, SMCI, APLD, ZS): wait for the OR.

## Names (priority order), pre-market refreshed 8:00am CT
PM = pre-market price at 8:05 CT; Gap = vs Fri close. "Fade 50%" = (Fri close + PM)/2, the fade-put trigger if the bounce fails. Longs: trigger = 15-min OR high, stop = OR low / VWAP loss, target 2R.

| # | Ticker | PM | Gap | Primary setup | Ref stop / target idea | Fade 50% (put trig.) | Catalyst / note | Opt | Swing |
|---|---|---|---|---|---|---|---|---|---|
| 1 | ZS | 238.9 | +22.6% | long: ORB / first pullback to VWAP | stop OR low; target 2R | n/a | Q1 EPS 1.23 vs 0.95 est; > $200 = options only; sector (CRWD -5% on its report) mixed | verify | no |
| 2 | MU | 688.3 | +15.8% | long: pullback to VWAP | options only (> $100) | 641 | Leader of the chip bounce; gauge + options | ✓ | no (intraday) |
| 3 | HOOD | 68.46 | +10.1% | long: ORB | stop OR low; ref 66.5 | 65.3 | Fri paper short winner; crypto/retail beta bounces | ✓ | no |
| 4 | IREN | 14.53 | +22.9% | long ORB or fade | wide: check chain premium | 13.18 | Neocloud bounce after -18%; extended | ✓ | no |
| 5 | CRWV | 51.18 | +29.5% | **fade** primary / long only on a clean ORB | stop above PM high | 45.35 | +30% gap on -12% day; most extended | ✓ | no |
| 6 | NBIS | 103.0 | +26.7% | **fade** primary | stop above PM high | 92.2 | Premium likely > $100: chain check | ✓ | no |
| 7 | MSTR | 89.09 | +14.5% | long ORB (BTC-led) | ref stop 86.5 | 83.4 | Watch BTC (~$58-60k); crypto confirms or kills | ✓ | no |
| 8 | COIN | 109.7 | +7.6% | long ORB | ref stop 107.5 | 105.8 | Crypto beta | ✓ | no |
| 9 | INTC | 57.50 | +12.1% | long: pullback | ref stop 55.8 | 54.4 | Semis relief; Fri AH 52.3 | ✓ | no |
| 10 | SMCI | 25.96 | +19.9% | **fade** primary | stop above PM high | 23.8 | Extended AI-server gap | ✓ | no |
| 11 | SOFI | 13.61 | +9.0% | long ORB | ref stop 13.25 | 13.05 | Fri low-close name; high retail interest | ✓ | no |
| 12 | PLTR | 156.2 | +8.9% | long ORB (options) | options only | 150 | > $100 | ✓ | no |
| 13 | ARM | 177.0 | +16.3% | long: pullback | options only | 164.6 | Chip IP leader bounce | verify | no |
| 14 | TSM | 365.3 | +14.6% | long: pullback / gauge | options only | 342 | Asia stabilization measures | verify | no |
| 15 | GAP | 21.26 | +1.5% | RS long: break of Fri HOD 22.155 area | stop ~20.5; target 22.15 / 22.45 | n/a | Q3 beat; RS name, lags the gap so RS edge is gone: needs rel vol > 2x | verify | stock; no overnight |
| 16 | FRO | 46.29 | +2.4% | RS long: Fri-high 46.15 hold | stop 45.05; target 48.35 | n/a | Crude -2.3% (USO 136.4) = headwind; weak RS today | verify | no |
| 17 | APLD | 13.85 | +20.5% | **fade** primary | stop above PM high | 12.7 | Neocloud | verify | no |
| 18 | WULF | 11.44 | +16.0% | fade primary | stop above PM high | 10.6 | Miner / AI hosting | verify | no |
| 19 | RKLB | 51.09 | +12.5% | long ORB | ref stop 49.7 | 48.3 | Momentum space bounce, not on prior list | verify | no |
| 20 | OKLO | 22.00 | +10.8% | long ORB | ref stop 21.2 | 20.9 | Nuclear momentum | verify | no |
| 21 | ORCL | 115.1 | +13.7% | long: pullback (options) | options only | 108.1 | AI-financing proxy: if it holds the gap, the tape stays risk-on; gauge | ✓ | no |
| 22 | TSLA | 366.7 | +6.0% | long ORB (options) | options only | 356 | > $200 | ✓ | no |

**Gauges (no trades):** SPY 718.7, QQQ 649.9, IWM 264.8, NVDA ~161 (feed shows +28%: verify at the open, likely stale/odd print), AMD 454 (+7%), AVGO 309.6 (+1.7%, lagging), GLD 334.8 (+3.7%), USO 136.4, BTC.

**Pre-market update 2026-11-23 8:00am CT:** Overnight regime flipped from capitulation to relief: SPY +4.2%, QQQ +6.8% pre-market (Asian market-stabilization steps, easing AI-financing and hike-size fears). All Fri-low put triggers voided; the list is rebuilt to 22 names: bounce longs (ORB / first pullback) as default, "fade" puts only if SPY loses 704.3 then 702 and VWAP. Added ZS (post-earnings +22.6%), ARM, TSM, RKLB, OKLO, ORCL; dropped GDX (gold -4.4% thesis reversed, GLD +3.7%), CRCL, BMNR, RGTI (paper-only / thin) as primaries; CRWD on avoid. Only earnings events today: CRWD/ZS (am, done), ZM/HPE/A/SMTC/SYM/J/DAC (pm). No tier-1 data. Wed 7:30 CT PCE+GDP. Account unfunded ($0.91): paper only. No swings open.
