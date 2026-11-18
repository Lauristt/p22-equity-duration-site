# Sector ER Tracker

The team confirmed this as the consultation-agreed extension on November 18, 2026. It is part of `uv run doit`; PayoutForecast remains a legacy sensitivity appendix.

The intended user is an equity researcher comparing payout-related valuation decompositions across industries. ER is the expected-return contribution to dividend-price variation, not an expected return, trading signal or R-squared. The tracker reports uncertainty and model instability rather than promising an industry ranking.

## Data and construction

WRDS CRSP monthly CIZ data run through September 2026; complete annual outcomes end in 2025. Compustat, time-valid CCM links, historical SIC, French 12 industries and FRED CPI complete the inputs. The fixed extraction vintage and analysis settings are committed in `config/sector.json`. Credentials and storage roots are machine configuration only.

`sector/clean.py` performs cleaning separately from portfolio construction and estimation. Actual USD cash dividends are adjusted with ex-date and prior-month cumulative share factors. Missing factors invalidate the affected cash observation. Total-minus-ex-distribution returns provide an independent diagnostic, not the primary dividend measure.

January portfolios use lagged capitalization and accounting available after a conservative reporting lag. Payout is ten consecutive fiscal years of dividends divided by net income. Positive dividends in ten prior calendar years and ten available fiscal observations are required. Annual memberships remain fixed; weights drift with ex-distribution returns. Delisting proceeds are reinvested in surviving holdings. Industry-neutral sides have identical monthly one-twelfth industry weights. Accounting is counted once per issuer. Historical accounting revisions prevent a point-in-time claim.

`annual_portfolios.py` constructs price-only units with withdrawn cash dividends and CPI-deflated annual outcomes. Missing months break history; regressions do not bridge gaps. The cash-history requirement makes the reconstructed stock sample shorter than the authors' sample. Earnings-dependent statistics use finite, sufficiently covered earnings observations; missing earnings are never replaced by zero.

## Estimation and validation

`estimate.py` uses matching consecutive annual pairs in return, dividend-growth and dividend-price regressions. Full-sample and 20/30/40-year windows are declared in configuration. Both payout comparisons use exactly the same outcome years. Conditional intervals use 500 paired stationary-block draws, expected block length five, fixed seed, and restarts at calendar gaps. Short observed runs remain eligible for resampling. Shares outside zero and one are retained; denominator and terminal-condition failures are flagged.

`robustness.py` adds a two-state VAR with lagged dividend growth. This is specification sensitivity, not a separate significance test. `data_quality.py` evaluates predeclared numerical gates on actual data and produces a coverage/reconciliation figure and table. `cross_update.py` compares rebuilt portfolios with authors' portfolios on overlapping years; discrepancies remain visible and are not claimed as exact replication.

See the generated report and website for current results, coverage and uncertainty. The historical `sector_direction_audit.md` documents the earlier effective-distribution prototype; it does not describe the current primary construction.
