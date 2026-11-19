# Watchlist for Fri 2026-11-20 (built Thu 2026-11-19 3:30pm CT)

> **ACCOUNT UNFUNDED: buying power $0.91** (••5279 went $810.91 → $510.91 → $0.91 between 10:05 and 11:05 CT Thu, with no orders: cash transfers out). Until Gino re-funds it, every run scans, scores and journals the full candidate table (the paper calibration still needs it), places nothing, and doesn't repeat the FAILURE ALERT more than once a day. If funds are back, trade normally.

Levels come from Robinhood 5-min bars (11/19 RTH), daily bars (10/20–11/18) and quotes at ~3:35pm CT (after hours). **The 8:00am pre-market run must re-check every trigger against pre-market prices**: many puts sit at Thursday's close, and several are already through their trigger after hours (MSTR, CRWV, NBIS, COIN, CRCL). A trigger is a completed 5-min close beyond the level after 8:45 CT. **Chase limit = trigger + 1R** (puts: trigger − 1R). **If a name gaps through its trigger,** the trigger becomes the first 15-min OR low (puts) or OR high (longs), still inside the chase limit. Journal numeric levels and `now/on-trigger` scores for every row.

**Rules in force (playbook 11/19):** max score 9; floors **stocks ≥ 7, options ≥ 8**; no forced trades; -1 when an intraday trigger bar closes after 10:30 CT. **New 11/19:** rel vol is measured on regular-session volume only (see playbook), and there's a scanner-expression cheat sheet. Options: premium ≤ $200, sell-to-close stop ≥ 15% below entry sized to a loss ≤ $30, |Δ| 0.30–0.60, spread ≤ 10% of mid, **no option entries after 1:00pm CT**. Puts only on `opt-liquid ✓` names or after a chain check.

## Market bias: **BEARISH** (but stretched; watch for an opex/oversold bounce)
- Thu: S&P -2.0% (6th straight loss), Dow -1,101 (below 50,000), Nasdaq -2.25%, Russell -2.2%, **VIX 28.4** (highest since March). SPY's +1% gap (739.90) failed in the first 5 minutes. It broke down as **ANT (Anthropic) opened at ~10:48 CT** ($111.50 open, $83 IPO, closed $97.17) and **closed on the low (715.84)**. NVDA reversed +4.7% → -3.3%; AMD -7.7% (short report), NBIS -9%, CRWV -6%, crypto names at lows. AH: SPY 714.2, QQQ 642.2, INTU -11%, ROST -7%, ESTC -7%.
- Macro is hostile: 10-yr 5.05%, ~90% December hike odds, Philly Fed 6.3 (vs 18 expected), gold at a 14-month low.
- **Friday = monthly options expiration.** Expect pinning and whipsaw after 11:00 CT. Weekend gap risk: **prefer no new swings on Friday** (they'd hold over a weekend in a VIX-28 tape).
- **Defensive / puts allowed:** SPY < **715.65** (Thu low) or SPY below its session VWAP and below 722 after 9:00 CT. **Neutral:** 715.65–725.70. **Risk-on (longs normal):** SPY > **725.70** (Thu 9:35 flush low / Thu breakdown level) and holding 30 min. Longs otherwise are relative-strength only (green on a red SPY, above VWAP, rel vol > 2x, score ≥ 8).

## Key index levels
| | Thu high | Thu low | Thu close | Wed close | AH | Below | Above |
|---|---|---|---|---|---|---|---|
| SPY | 739.90 | 715.65 | 715.84 | 730.20 | 714.20 | 715.65, 710, 700 (no daily support in 30 days) | 722, 725.7, 730.2 |
| QQQ | 676.46 | 644.34 | 645.10 | 659.51 | 642.19 | 644.34, 640, 630 | 646.64 (11/17 low), 653.05, 659.5 |
| IWM | 271.80 | 263.74 | 264.21 | 270.12 | 263.60 | 263.74, 260 | 267.9, 270.1 |
| NVDA (gauge) | 158.13 | 145.71 | 146.01 | 150.96 | 144.35 | 145.71, 140 | 150.4, 155 |

## Events (CT)
- **9:00** UMich final November sentiment (prelim 51.0). Fed: Waller and Cook are listed (TD calendar: 8:25 and 12:15 with no time zone; read as ET = **7:25 and 11:15 CT**, unconfirmed).
- **Monthly opex** all day. Anthropic IPO settlement closes Friday.
- **Earnings reactions at the open:** INTU (-11% AH, > $200 gauge), ROST (-7%, > $200 gauge), **ESTC (-7% AH → put watch, #14)**, KEYS (-1%), GAP (+1%, beat), GLOB (+4%). Pre-market Fri: BJ, BKE, FRO, IESC (none on the list).
- Next week: ZM and HPE report Mon 11/23 after the close. Thanksgiving closed Thu 11/26; half day Fri 11/27.

## AVOID
- **ANT** day 2: IPO price discovery (92.72–114.99 Thu), likely no listed options yet. Gauge only.
- **ZM** (earnings Mon after the close: no Friday swing), INTU / ROST / WSM / NVDA / AMD / PLTR / SPY / QQQ (> $100–200 underlyings: one share or $200+ premiums; gauges only).
- AAOI, SMMT (options untradeable), CLRO, SLS (pumps), AES (deal pin), BILL (deal-pin risk), UGI (-7.7% Thu: utility, no catalyst we can read, options unchecked), SNEX (-27%, thin), STUB/Vivid Seats (+63% spike).
- New Friday swings in general (weekend gap risk; see bias).

## Names (priority order)
Sizing: longs `shares = floor($200 / trigger)`, risk $ = shares × |trigger − stop| ≤ $20 (RS longs ≤ $10). Puts: levels are on the **stock** (trigger below, stop above, target below); the option is sized so the premium is ≤ $200 and the loss at a sell-to-close stop ≥ 15% below entry is ≤ $30. **First-hour triggers are strongly preferred** (after 10:30 the -1 penalty applies). All put targets are 2R; R:R room was checked against Thu's last-hour range and prior daily lows (none of these names has a prior low within 2R below: they're at multi-week or multi-month lows).

### A. Puts (defensive tape only). Score 8 needs setup 3 + watchlist catalyst 2 + rel vol > 2x 2 + market 1 (+ R:R 1).
| # | Ticker | Setup | Trigger (stock) | Stop (stock) | Target | Opt-liquid | Catalyst / notes | Swing? |
|---|---|---|---|---|---|---|---|---|
| 1 | **MSTR** | LOD breakdown | < 85.95 | 88.25 | 81.35 | ✓ | BTC $61.5K (-3%), extreme fear; closed on its LOD 86.02; **AH 85.68 (already through: use the 15-min OR low)** | no |
| 2 | **CRWV** | AI-infra breakdown | < 44.70 | 46.20 | 41.70 | verify | -6% Thu after the ANT open; LOD 44.77; 11/5 low 40.58 below the target; **AH 44.16 (through)** | no |
| 3 | **IREN** | LOD breakdown | < 14.15 | 14.72 | 13.01 | ✓ | Faded +9% → -5.5% after the ANT open; LOD 14.18; 3-month lows; AH 14.21 | no |
| 4 | **NBIS** | AI-infra breakdown | < 96.40 | 99.85 | 89.50 | verify | -9.4% Thu (115.18 → 96.54); **AH 95.40 (through)**. A wide R: favour the OR-low rule | no |
| 5 | **SOFI** | Breakdown of the 14.07 double bottom | < 13.49 | 13.81 | 12.85 | ✓ | Broke the Tue/Wed 14.07–14.08 lows Thu and closed on the LOD 13.52; AH 13.46 | no |
| 6 | **HOOD** | ANT-distribution fade | < 68.45 | 70.20 | 64.95 | ✓ | Gapped to 74.04 on ANT retail flow and closed 68.65 (below Wed's close); LOD 68.56; 11/17 low 67.25 is 0.7R below (it's a speed bump, not a 2R block) | no |
| 7 | **COIN** | Crypto breakdown | < 108.70 | 111.00 | 104.10 | verify | Closed on its LOD 108.80; AH 107.90 (through); 3rd straight lower low | no |
| 8 | **CRCL** | Crypto breakdown | < 51.75 | 53.45 | 48.35 | verify | Closed on its LOD 51.82; **AH 50.75 (through)**; multi-month lows | no |
| 9 | **NOW** | Software 52-week-low break | < 88.05 | 89.45 | 85.25 | ✓ | New 52-week low 88.13 Thu; software weakness (INTU -11% AH, ESTC -7% AH) | no |
| 10 | **GDX** | Gold breakdown | < 71.85 | 73.05 | 69.45 | ✓ | Gold at a 14-month low (-2.5% Thu); LOD 71.91 into the close | no |
| 11 | **SMCI** | AI-hardware breakdown | < 23.65 | 24.40 | 22.15 | verify | LOD 23.71 (11/17 low 23.29 is 0.5R below: speed bump) | no |
| 12 | **PATH** | Multi-month low break | < 11.19 | 11.47 | 10.63 | verify | New low 11.22 Thu; software sympathy | no |
| 13 | **MARA** | Crypto miner breakdown | < 6.19 | 6.43 | 5.71 | verify | LOD 6.21; 11/5 low 5.69 is the target zone. Tiny premiums: check |Δ| 0.30–0.60 | no |
| 14 | **ESTC** | Post-earnings gap-down continuation | first 15-min OR low (AH 70.5) | 15-min OR high | 2R below | verify | Beat (0.94 vs 0.68) but -8% Thu and -7% AH; only if the gap holds below Thu's 76.09 low and the OR is ≤ 3% wide | no |

### B. Longs (relative strength only unless SPY > 725.70 holds 30 min). RS-long score 8 = setup 3 + watchlist catalyst 2 + rel vol 2 + R:R 1 (no market point in a weak tape), and no late penalty.
| # | Ticker | Setup | Trigger | Stop | Target | Size / risk | Chase limit | Catalyst / notes | Swing? |
|---|---|---|---|---|---|---|---|---|---|
| 15 | **PDD** | Day-2 earnings HOD break | 87.40 | 85.40 | 91.40 | 2 sh / $4.0 | 89.40 | Q3 beat 3.14 vs 2.69, +11% Thu, held 85.4–86.3 through the selloff; Thu HOD 87.38 (no close above it all day). No daily resistance above 85.4 in 30 days | no (Friday; was yes) |
| 16 | **TU** | Multi-month-high breakout | 10.88 | 10.58 | 11.48 | 18 sh / $5.4 | 11.18 | TELUS +13% Thu (2nd big-volume day after 11/16's 47M); closed 10.79 near its HOD 10.87; catalyst not confirmed | no |
| 17 | **JD** | Green-on-red HOD break | 25.90 | 25.55 | 26.60 | 7 sh / $2.5 | 26.25 | +2.8% while SPY -2% (China consumer bid with PDD); closed 25.62 off the HOD 25.86; the 11/17 gap (25.75 → 27.54) is open above | no |
| 18 | **VVV** | Earnings-day HOD break | 38.05 | 36.80 | 40.55 | 5 sh / $6.3 | 39.30 | +10.4% Thu after in-line EPS (0.42) and guidance; HOD 38.00; 11/5 high 36.92 cleared | no |
| 19 | **INTC** | Green-on-red last-hour high | 56.80 | 55.35 | 59.70 | 3 sh / $4.4 | 58.25 | +1.8% on a -2% day (one of the few green chips). Thu HOD 59.44 is 1.8R away: **no R:R point until a close > 59.44** | no |
| 20 | **GME** | Green-on-red HOD break | 27.55 | 26.90 | 28.85 | 7 sh / $4.6 | 28.20 | +2.5% Thu on 2x rel vol; HOD 27.50; no catalyst (meme flow) so no watchlist-catalyst point → caps at 6 as an RS long | no |

### Gauges (don't trade)
SPY, QQQ, IWM, VIX, NVDA (146.01; AH 144.35), AMD (489, short report), ANT (97.17; Thu range 92.72–114.99), PLTR (153.59), INTU (AH 276), ROST (AH 205), BTC ($61.5K), PANW, GLD.

## Top 5 at the open
1. **MSTR put** < 85.95 (or the 15-min OR low if it gaps below): crypto at lows, ✓ liquid.
2. **IREN put** < 14.15: AI-infra fade, ✓ liquid, low premium.
3. **SOFI put** < 13.49: broke a double bottom Thu, ✓ liquid.
4. **CRWV put** < 44.70 (chain check first): AI-infra was the weakest group after the ANT open.
5. **PDD long** > 87.40 (RS only, score ≥ 8, rel vol > 2x, SPY red but PDD green and above VWAP).
Puts need SPY in the defensive zone (< 715.65 or < VWAP and < 722). If SPY gaps up and holds > 725.70 (an opex/oversold squeeze), drop section A and use B only. **A no-trade day is acceptable.**
