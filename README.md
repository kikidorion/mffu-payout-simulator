# Prop Futures Payout Simulator — MFFU Rapid 50K Rules

Free Monte Carlo simulator for prop futures payouts. Enter your own strategy
stats (win rate, average win/loss, trades per day) and stress-test them against
the full MFFU Rapid 50K account lifecycle:

- Evaluation: $3,000 target, $2,000 EOD trailing drawdown, 50% best-day consistency rule
- Funded: tighter intraday trailing drawdown, $2,100 buffer, 90% split, daily payouts (min $250)
- Optional reinvestment of payouts into new evals
- 900 simulated paths over 120 trading days, with 5/25/50/75/95 percentile bands

Reality-check sliders for the three things that quietly kill backtest dreams:
win-rate haircut vs backtest, per-trade commission + slippage (most backtests
are gross), and chop-day frequency.

**No backend, no tracking, no signup.** One static HTML file — everything runs
in your browser.

## Run it

Open `index.html` in a browser, or visit the hosted version on GitHub Pages.

## Disclaimer

Educational simulation only — not financial advice and not a guarantee of
results. Output reflects the assumptions you enter, nothing more. Not
affiliated with or endorsed by My Funded Futures (MFFU); rule parameters are
approximations of published 2026 terms — verify current rules with the firm
before purchasing an eval. Futures trading involves substantial risk of loss.
