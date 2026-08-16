India Intraday Screener PRO V4.1 — Data Integrity Upgrade

Fixes:
- NIFTY index VWAP no longer displays NaN when index volume is unavailable; regime uses price + EMA20/EMA50.
- Stock setups with invalid VWAP/ATR/RSI/RVOL data are rejected rather than generating a signal.
- Scoring is continuous (not binary) so candidates can have genuinely different scores.
- Entry, SL, T1/T2 and quantity remain risk-based.
- Data-bar timestamp is shown for every candidate.
- NO TRADE is returned when nothing passes the rules.

Recommended beginner settings: 5m, minimum score 80, RVOL 1.5, risk ₹200, minimum R:R 2, Long + Short.
IMPORTANT: Public web market data can be delayed, stale, incomplete or rate-limited. Verify every setup and the live price/volume in INDmoney before placing any order. The screener does not place orders and does not guarantee profit.
