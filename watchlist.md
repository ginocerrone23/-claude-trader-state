# Watchlist for Mon 2026-11-16 (built Fri 2026-11-13 3:30pm CT)

Levels come from Robinhood 5-min/daily historicals for 11/13 plus after-hours quotes at ~3:35pm CT. The 8:00am pre-market run must re-check every trigger against pre-market prices. **New rule (playbook 11/13):** a long entered more than 1R above its trigger is a chase, so skip it (or wait for a pullback setup with its own stop).

## Market bias: **NEUTRAL leaning DEFENSIVE**
- Friday: chip unwind (AMD -8.7%, SOX ~-4%), with the NVDA CEO fallout on day 2. SPY gapped to 760, flushed to 745.2 by 10:35 CT and closed 754.25 (-0.4%). QQQ closed 679.90 (-1.2%). PPI was cooler m/m (+0.3%), but the 10-year is still ~5.14% and December hike odds are ~85%.
- **After-hours was weak:** SPY 749.98 (-0.6%), QQQ 674.4 (-0.8%), NVDA 161.4, AMD 525 at 4:33pm ET. I found no headline for it, so expect a soft open.
- **Risk-on gate (needed for AI-beta longs, section A2):** SPY > **757.2** (Thu close) holding 30 min after 8:45 CT, QQQ > 683, NVDA > 160.
- **Defensive:** SPY < **745.2** (Fri low) means no new longs except low-beta OXY; use section B puts only.
- Between those it's chop: only A1 catalyst names, only first-hour triggers preferred, score ≥ 6 strictly. **No forced trades.**
- Rules in force: score ≥ 6, no fallback. Room to resistance ≥ 2R for the R:R point. No buys within 0.5R under an unbroken HOD. **No chase > 1R above the trigger (new).** Puts only on ≤ ~$25 underlyings, |delta| ≥ 0.15, premium ≤ $0.20, no option entries after 1:00pm CT.

## Key index levels
| | Fri high | Fri low | Fri close | Thu close | Notes |
|---|---|---|---|---|---|
| SPY | 760.12 | 745.20 | 754.25 | 757.12 | AH 749.98. Below 745.2 → 741.0 (Nov 9 low), then 732.7 (Nov 5 low). Above 760-763 → 775.6 |
| QQQ | 688.75 | 671.71 | 679.90 | 688.17 | AH 674.4. 683.6 = gap-fill. Below 671.7 → 662 (Nov 9 low) |
| IWM | ~278.0 | ~274.7 | 277.60 | 278.44 | Held up better than QQQ |
| NVDA (gauge) | ~163.2 | ~158.4 | 162.82 | 166.19 | Earnings **Tue 11/17 after the close**. 160 / 155 lines |

## Events (CT)
- **Mon:** no major US data confirmed (check for Empire State 7:30). Pre-market earnings: BIDU, **XPEV**, TSN, BEKE, ARMK, HTHT, POET. After close: POWL, ACM, XP, PAGS, RCAT.
- **Tue:** 7:30 retail sales. HD/DIS/**KLAR**/JD before the open. **NVDA after the close.**
- **Wed:** 1:00pm FOMC minutes. **Thu:** WMT before the open; Anthropic IPO expected (~11/19).

## AVOID
- NVDA stock (earnings Tue). Gauge only. **No swing in AI-beta names (IREN, APLD, CRWV, SMCI, CORZ, INTC, AMD proxies) held into Tue's close.**
- **KLAR: no swing** (earnings Tue AM); Monday intraday only, flat by the closer.
- Names reporting Mon after the close (POWL, ACM, XP, PAGS, RCAT): no positions into the close.
- > $200 names (AMD, AVGO, MU, TSLA, META, MSFT, AAPL, SPY, QQQ): gauges only. CBRS (~108) and MOD (~136): >$100 band, watch only.
- WSE: +2.7% intraday reversal to a close at its low. Skip.

## Names (priority order)
Sizing: shares = floor($200 / trigger). Risk $ = shares × (trigger − stop) ≤ $20. Trigger = a completed 5-min close beyond the level after 8:45 CT. **Chase limit** = trigger + 1R; above it, don't enter.

### A1. Catalyst / relative-strength longs (work in neutral tape)
| # | Ticker | Setup | Trigger | Stop | Target | Size / risk | Chase limit | R to res | Catalyst / notes | Swing? |
|---|---|---|---|---|---|---|---|---|---|---|
| 1 | NU | Day-2 continuation, break of Fri HOD | 13.26 | 12.94 | 13.90 | 15 sh / $4.8 | 13.58 | ≥ 2 (unfilled gap up to ~14.6; Oct range 14.4-15.4) | Q3 earnings +11.7%, closed 13.21 (97% of range). Liquid ($12, ~80M sh/day). Friday's stop zone 12.94-13.01 is the line | yes |
| 2 | LFTO | Day-2 continuation, HOD break | 24.75 | 23.90 | 26.45 | 8 sh / $6.8 | 25.60 | open (far above the 20-day high 18.97) | +30.7% on ~7x rel vol, closed 24.45 near HOD 24.70. Catalyst unverified. **Spread must be ≤ 0.2%** (was 0.2-0.5% Fri) | yes |
| 3 | HAWK | Day-2 continuation, HOD break | 18.25 | 17.55 | 19.65 | 10 sh / $7.0 | 18.95 | open (20-day high 15.76) | +24.1%, closed at HOD 18.23, higher lows all afternoon. Catalyst unverified. Spread was ~0.22%, so check it | yes |
| 4 | TNDM | 20-day-high breakout | 20.30 | 19.85 | 21.20 | 9 sh / $4.1 | 20.75 | open above 20.25 | +14.5%, closed 20.05 just under the 20-day high 20.25. Friday's first break failed (12:25 CT), so demand a clean close and spread ≤ 0.25% | yes |
| 5 | KLAR | HOD break (intraday only) | 13.85 | 13.50 | 14.18 | 14 sh / $4.9 | 14.20 | **~1R** to the 20-day high 14.18, so no R:R point | +8.6%, closed at HOD. **Earnings Tue AM: flat by Monday's close** | **no** |
| 6 | CHA | Trend continuation, new highs | 14.60 | 14.20 | 15.40 | 13 sh / $5.2 | 15.00 | open | +6.4%, closed 14.38 under HOD 14.56. Thin with a 0.3-0.5% spread, so it needs spread ≤ 0.2% | yes |
| 7 | VKTX | Triple-top / 20-day-high breakout | 30.15 | 29.40 | 31.65 | 6 sh / $4.5 | 30.90 | open above 30.10 | +6%, rejected 29.93-29.96 three times Fri. Biotech headline risk | yes |
| 8 | MBGL | Double-top break | 23.35 | 22.85 | 24.35 | 8 sh / $4.0 | 23.85 | open | Q3 beat Thu +16%, Fri inside day (22.66-23.31), closed 23.27. Thin | yes |
| 9 | XPEV | Earnings gap-and-go | 15-min OR high after 8:45 | OR low | 2R | ~21 sh | OR high + 1R | check the 10.36 20-day high | Reports Mon pre-market. Closed 9.37. Trade only with rel vol > 2x and the gap holding | no |
| 10 | OXY | Break of the Thu/Fri double top | 59.05 | 58.45 | 60.25 | 3 sh / $1.8 | 59.65 | 9 (20-day high 64.95) | Low beta, works in a defensive tape. Fri high 59.03 = Thu 58.98 | yes |

### A2. AI-beta longs: risk-on gate required, intraday only (NVDA earnings Tue)
| # | Ticker | Setup | Trigger | Stop | Target | Size / risk | Notes | Swing? |
|---|---|---|---|---|---|---|---|---|
| 11 | CORZ | 20-day-high breakout | 15.05 | 14.45 | 16.25 | 13 sh / $7.8 | Closed 14.53 near HOD 14.61 on a red tape (relative strength) | no (NVDA Tue) |
| 12 | INTC | Reclaim 60 | 60.00 | 59.00 | 62.00 | 3 sh / $3.0 | Strong last hour 57.0 → 59.66. Thu high 62.76 overhead (2.76R) | no |

### B. Cheap puts (defensive tape only: SPY < 745.2 or failing at 750 after a gap down; underlying ≤ ~$25; |delta| ≥ 0.15, premium ≤ $0.20; Nov-20/Nov-27 expiry; no entries after 1:00pm CT). **If the stock gaps through the trigger, don't chase: use the first 15-min low as the new trigger.**
| # | Ticker | Trigger (stock) | Invalidation | Target | Notes |
|---|---|---|---|---|---|
| 13 | IREN | < 17.35 | > 18.30 | 16.40 | -6.8%, Fri low 17.39, 20-day low 17.16 |
| 14 | APLD | < 15.00 | > 16.05 | 14.00 | -5.7%, Fri low 15.01 |
| 15 | SOFI | < 15.05 | > 15.55 | 14.55 | Fri low 15.08, lower highs all week |
| 16 | RGTI | < 9.45 | > 9.85 | 9.00 | -6.9%, closed near the low; Nov 5 low 9.19 |
| 17 | MARA | < 6.65 | > 7.10 | 6.20 | Fri low 6.65; BTC flat ~68k |

### Gauges (don't trade)
SPY, QQQ, IWM, NVDA, AMD (534, the unwind leader), SMH/SOX, HOOD (77.9, retail/crypto sentiment), COIN (127.6), PLTR (168), CBRS, MOD.

## Top 5 at the open
1. **NU** > 13.26 (12.94 / 13.90, 15 sh; chase limit 13.58)
2. **LFTO** > 24.75 (23.90 / 26.45, 8 sh; spread ≤ 0.2%)
3. **HAWK** > 18.25 (17.55 / 19.65, 10 sh)
4. **TNDM** > 20.30 (19.85 / 21.20, 9 sh)
5. **OXY** > 59.05 (58.45 / 60.25, 3 sh; works in any tape)

If SPY gaps down and loses 745.2, switch to section B (IREN < 17.35 and SOFI < 15.05 first). **Friday's lesson:** the best triggers (NU 8:40, CHA 8:55) fired in the first 30 minutes. The late, extended NU entry at 10:55 stopped out. Be ready at 9:00 and don't chase later.
