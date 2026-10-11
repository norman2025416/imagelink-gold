# Imagelink Gold

A single-page web app that reads gold, silver and Bitcoin prices and applies fixed structure rules:
break and retest, liquidity sweep and reclaim, consolidation, head and shoulders, double top and bottom.
It shows the entry, stop, TP1, TP2, a confidence score, a backtest of the last week, and today's US news in South Africa time.

It also reads the daily trend, the previous day's high and low, and the London and New York opening ranges. The backtest covers the last week automatically and 180 days on request, and splits results by setup, by daily trend and by time of day. The backtest has no spread or slippage.

- Everything runs in the browser. There is no server and no stored password.
- The optional "deep analysis" uses a Claude API key that each user saves in their own browser. Never put a key in this repository.
- Analysis only. It does not place trades and is not financial advice.

Open `index.html`, or visit the GitHub Pages address of this repository.
