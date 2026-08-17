India Intraday Screener PRO V5.0

Safety-first intraday decision-support PWA.

V5.0 upgrades:
- Strict qualification gates: score, RVOL, VWAP, EMA trend, RSI, candle, breakout/proximity, regime and R:R.
- Near-Miss Watchlist shows stocks that almost qualified and exactly which rules failed.
- Why No Trade diagnostics count the main failed filters across the scan.
- NO TRADE is a valid outcome; the screener never forces a signal.
- Risk-based quantity remains tied to the configured risk per trade.
- Keeps NIFTY index VWAP as N/A when index volume is unavailable instead of fabricating a value.
- Shows data-bar timestamp for candidates.

Beginner defaults:
5m | score 80 | RVOL 1.5 | risk ₹200 | minimum R:R 2.0 | Long + Short

Important:
This is educational decision-support software, not a guarantee of profit. Yahoo Finance data may be delayed, unavailable, rate-limited or incomplete. Verify live price, volume, VWAP, entry, stop, target and quantity in INDmoney/NSE before any order. Never force a trade because the watchlist contains a near-miss.

Deploy:
Upload index.html, manifest.webmanifest and sw.js to the GitHub Pages repository and commit to the publishing branch.


V5.0 CHANGE: Expanded the scan universe from 62 to 200 unique NSE stock symbols.
The universe is anchored to NSE's individual-security derivatives list, with additional liquid large-cap/Next-50 candidates. Relative-volume, price, market-regime and strategy rules still decide which stocks qualify; a larger universe does NOT mean a trade will be produced every day.
