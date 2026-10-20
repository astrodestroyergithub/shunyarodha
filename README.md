# Shunyarodha — Zerodha Clone (Netlify Deployment Package)

**Shunyarodha** is a responsive, multi-view stock broking and investment platform inspired by [Zerodha](https://zerodha.com).

## Included Features
- **Flagship Landing Page**: Hero showcase, *Trust with Confidence* 4-pillar breakdown, interactive *Shunyarodha Ecosystem* explorer, press strip, *Unbeatable Pricing* (`₹0` Account Opening, `₹0` Equity Delivery, `₹20` Intraday & F&O), and *Varsity / TradingQ&A* education showcase.
- **Live NSE/BSE Market Ticker**: Real-time simulated streaming quotes for `NIFTY 50`, `SENSEX`, `BANK NIFTY`, and `INDIA VIX` with pause/resume control.
- **Interactive e-KYC Account Opening (`Signup`)**: 3-step paperless onboarding flow with mobile OTP auto-fill, PAN & segment selection, and instant Client ID generation.
- **Interactive Brokerage & Statutory Tax Calculator (`Pricing`)**: Real-time breakdown of Turnover, Brokerage, STT/CTT, Exchange Transaction Charges (NSE/BSE), SEBI Turnover fees, 18% GST, Stamp Duty, Points to Breakeven, and Net P&L across Intraday, Delivery, Futures, and Options.
- **Varsity Education & Coin Direct MF SIP Calculator (`Varsity`)**: 6 interactive learning modules with comprehension quizzes plus a Direct vs Regular Mutual Fund commission savings calculator.
- **Support Portal (`Support`)**: Live topic filter, instant FAQ reader, and interactive support ticket creator.
- **Kite 3.0 Web Trading Terminal (`Kite Terminal`)**: Full split-screen trading workspace with searchable NSE watchlist, 20-level Bid/Ask Market Depth, multi-timeframe Chart.js price chart, Buy/Sell order ticket (MIS/CNC, Market/Limit/GTT), live Margin & Nudge checks, Executed Orders book, Demat Holdings with Overtrading **Kill Switch**, and instant UPI Fund Deposit simulator.

## How to Host on Netlify (2 Easy Ways)

### Method 1: Netlify Drop (Fastest — 10 Seconds)
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop).
2. Drag and drop `shunyarodha-netlify.zip` (or the unzipped folder) directly onto the browser window.
3. Your site will be live immediately with HTTPS!

### Method 2: Git Repository / Netlify CLI
1. Push this folder to a GitHub/GitLab repository or run `netlify deploy --prod --dir=.`.
2. `netlify.toml` and `_redirects` are pre-configured at the root for automatic SPA routing and asset caching.
