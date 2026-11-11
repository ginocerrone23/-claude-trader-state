# Playbook

Hard limits (account, $200/position, $20 max loss per trade, $40/day, 4 positions, 2 swings, buy-only options) are set in the routine prompts and override anything here. The 3:30pm analyst may edit this file, logging each change in changelog.md.

## Candidate sources (every run)
1. `watchlist.md` names first (priority order).
2. Robinhood scanners: top gainers, unusual volume, new highs.
3. Core list: SPY, QQQ, IWM, AAPL, NVDA, TSLA, AMD, META, AMZN, MSFT, PLTR, COIN, SMCI, SOFI, MARA.
Evaluate at least 10 names. Prefer price > $5, tight spread, high volume.

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
Take score >= 6. From 10:00am CT, if nothing has been opened today, take the best score >= 4.

## Execution
- Limit orders at/near the ask. Bracket order when possible, else a stop right after the fill.
- Trail the stop to breakeven once up 1R.
