# Playbook

Hard limits (account, $200/position, $20 max loss per trade, $40/day, 4 positions, 2 swings, buy-only options) are set in the routine prompts and override anything here. The 3:30pm analyst may edit this file, logging each change in changelog.md.

## Candidate sources (every run)
1. `watchlist.md` names first (priority order).
2. Robinhood scanners: top gainers, unusual volume, new highs.
3. Core list: SPY, QQQ, IWM, AAPL, NVDA, TSLA, AMD, META, AMZN, MSFT, PLTR, COIN, SMCI, SOFI, MARA.
Evaluate at least 10 names. Prefer price > $5, tight spread, high volume.
- **Price band (added 2026-11-11):** for stock trades prefer $5–$100 so a $200 position is at least 2 whole shares. Skip stock entries above $200: one share breaks the position cap, and fractional shares cannot reliably carry a stop or bracket. Use those names (MU, AMD, AVGO, SPY, QQQ…) as sector and market gauges, or trade them with options inside the limits.

## Intraday setups (long; bearish = buy puts)
- **ORB**: completed 5-min bar closes above the first 15-min high with rising volume. Stop: opening-range midpoint (or low). Target 2R.
- **Trend pullback**: above VWAP / rising 20-period 5-min average, pulls back to it and turns up. Stop: below the pullback low. Target 1.5–2R.
- **Gap-and-go**: news catalyst, relative volume > 1.5x, holds above premarket high. Stop: below premarket high / first 5-min low. Target 2R.

## Swing setups (hold up to 3 trading days)
Designate a trade as a swing only when the thesis is multi-day:
- Daily close above a 20-day closing high on above-average volume.
- Fresh catalyst (earnings beat already reported, upgrade, contract) with a strong close near the high of day.
- Stock swing: GTC stop on the daily chart (below the breakout day's low or the 20-day average), loss at stop <= $20.
- Option swing: buy a call/put with expiration >= 14 calendar days out, premium paid <= $20 total.
- Never hold a swing through an earnings report.

## Scoring (0-10)
+3 matches a setup above cleanly · +2 on the watchlist with a catalyst · +2 relative volume > 2x · +1 market (SPY/QQQ) trending the same way · +1 reward:risk >= 2 · -2 spread > 0.2% · -3 earnings within the hold period.
Take score >= 6. **No forced trades (Gino, 2026-11-11):** a no-trade day beats a poor trade. There is no time-of-day fallback and no lowering the threshold to create activity.
- **No chase (added 2026-11-13):** a long is a chase if the entry is more than **1R above its trigger**. R uses the watchlist's trigger-to-stop distance; for scanner names, the breakout level to the stop. Skip it, and only re-enter on a separate pullback setup (pullback to VWAP / rising 20-period average) with its own stop below the pullback low. This applies to the first run of the day too: when a watchlist trigger fired before the run started, it is only takeable inside trigger + 1R.
- **Room to resistance (added 2026-11-12):** measure R:R to the nearest overhead level: HOD, an untested double top, or the prior-day high/close. Award the +1 R:R point only if that level is >= 2R away. Don't buy within 0.5R below an unbroken HOD or double top. Wait for a completed 5-min close above it, then use that close as the trigger.

## Execution
- Limit orders at/near the ask. Bracket order when possible, else a stop right after the fill.
- Trail the stop to breakeven once up 1R.
- **Puts (added 2026-11-12):** with the $20 premium cap, only consider puts on underlyings priced about **$25 or less**. Use a weekly or next-week contract with |delta| >= 0.15 and premium <= $0.20. On higher-priced names, a <= $20 contract is a far-OTM lottery, so log the bearish read and skip it. Example (11/12 close): SOFI ~$15.6, Nov-20 14.5P $0.12 (delta -0.17), 15P $0.23 (delta -0.29).

## Journal (added 2026-11-11)
Every trader and closer run appends to `journal/YYYY-MM-DD.md` (New York date) **before** it ends, even when it does nothing or a tool fails. Use this format:
`### HH:MM CT — trader|closer` then: market read (SPY/QQQ vs prior close and VWAP), the names evaluated with score and setup, actions (order ids, fill, stop, target), **skips with the trigger/stop that would have applied**, open positions, and errors. Commit and push right away. If git fails, keep trading and include the failure in the next run's entry. The 3:30pm review can't grade anything without this.
