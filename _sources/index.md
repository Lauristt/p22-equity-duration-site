# P22: Equity Duration and Predictability


```{raw} html
<p class="cb-freshness">Code updated <time class="cb-relative-time" datetime="2026-11-18T16:00:48+00:00" title="2026-11-18 16:00 UTC">2026-11-18</time></p>
```


Last updated: {sub-ref}`today`



```{toctree}
:maxdepth: 1
:caption: Project guide

project_overview
```



## Table of Contents

```{toctree}
:maxdepth: 1
:caption: Notebooks 📖
Cleaned data and Sector ER Tracker tour <cb/notebooks/lauristt--p22_golez_koudijs_2025/data_tour>
```


```{toctree}
:maxdepth: 1
:caption: Notes 📝
cb/methodology.md
```


```{toctree}
:maxdepth: 1
:caption: Pipeline Charts 📈
cb/charts.md
```

```{postlist}
:format: "{title}"
```


```{toctree}
:maxdepth: 1
:caption: Pipeline Dataframes 📊
cb/dataframes/lauristt--p22_golez_koudijs_2025/annual_coverage.md
cb/dataframes/lauristt--p22_golez_koudijs_2025/author_summary.md
cb/dataframes/lauristt--p22_golez_koudijs_2025/baseline_decomposition.md
cb/dataframes/lauristt--p22_golez_koudijs_2025/cash_reconciliation.md
cb/dataframes/lauristt--p22_golez_koudijs_2025/coverage.md
cb/dataframes/lauristt--p22_golez_koudijs_2025/data_checks.md
cb/dataframes/lauristt--p22_golez_koudijs_2025/forecast_ledger.md
cb/dataframes/lauristt--p22_golez_koudijs_2025/forecast_loss_comparisons.md
cb/dataframes/lauristt--p22_golez_koudijs_2025/forecast_metrics.md
cb/dataframes/lauristt--p22_golez_koudijs_2025/forecast_validation.md
cb/dataframes/lauristt--p22_golez_koudijs_2025/industry_reference.md
cb/dataframes/lauristt--p22_golez_koudijs_2025/payout_history.md
cb/dataframes/lauristt--p22_golez_koudijs_2025/portfolio_overlap.md
cb/dataframes/lauristt--p22_golez_koudijs_2025/published_comparison.md
cb/dataframes/lauristt--p22_golez_koudijs_2025/sector_annual.md
cb/dataframes/lauristt--p22_golez_koudijs_2025/sector_comparison.md
cb/dataframes/lauristt--p22_golez_koudijs_2025/sector_estimates.md
cb/dataframes/lauristt--p22_golez_koudijs_2025/table_1.md
cb/dataframes/lauristt--p22_golez_koudijs_2025/table_2.md
cb/dataframes/lauristt--p22_golez_koudijs_2025/table_4.md
cb/dataframes/lauristt--p22_golez_koudijs_2025/table_5.md
cb/dataframes/lauristt--p22_golez_koudijs_2025/table_6.md
cb/dataframes/lauristt--p22_golez_koudijs_2025/table_7.md
cb/dataframes/lauristt--p22_golez_koudijs_2025/updated_decomposition.md
cb/dataframes/lauristt--p22_golez_koudijs_2025/updated_payout_history.md
cb/dataframes/lauristt--p22_golez_koudijs_2025/updated_table_1.md
cb/dataframes/lauristt--p22_golez_koudijs_2025/updated_table_2.md
cb/dataframes/lauristt--p22_golez_koudijs_2025/updated_table_4.md
cb/dataframes/lauristt--p22_golez_koudijs_2025/updated_table_5.md
cb/dataframes/lauristt--p22_golez_koudijs_2025/updated_table_6.md
cb/dataframes/lauristt--p22_golez_koudijs_2025/updated_table_7.md
cb/dataframes/lauristt--p22_golez_koudijs_2025/validation_summary.md
cb/dataframes/lauristt--p22_golez_koudijs_2025/var_sensitivity.md
```




```{toctree}
:maxdepth: 1
:caption: Pipeline Files 🗂️
cb/files/lauristt--p22_golez_koudijs_2025/final_report.md
```






## Pipeline Specs
| Pipeline Name                   | P22: Equity Duration and Predictability                       |
|---------------------------------|--------------------------------------------------------|
| Pipeline ID                     | [lauristt/p22_golez_koudijs_2025](./index.md)              |
| Maintainer                      | Lauris Li               |
| Contributors                    | Lauris Li, Yiyao Wang, Gary Miao, Luke Zhu |
| Repository                     | https://github.com/Lauristt/p22_golez_koudijs_2025                  |
| Pipeline Web Page               | <a href="https://lauristt.github.io/p22-equity-duration-site/">Pipeline Web Page</a> |
| Date of Last Code Update        | 2026-11-18 16:00:48 UTC           |
| OS Compatibility                | Windows, Linux, macOS |
| Linked Dataframes               |  [lauristt/p22_golez_koudijs_2025:annual_coverage](cb/dataframes/lauristt--p22_golez_koudijs_2025/annual_coverage.md)<br>  [lauristt/p22_golez_koudijs_2025:author_summary](cb/dataframes/lauristt--p22_golez_koudijs_2025/author_summary.md)<br>  [lauristt/p22_golez_koudijs_2025:baseline_decomposition](cb/dataframes/lauristt--p22_golez_koudijs_2025/baseline_decomposition.md)<br>  [lauristt/p22_golez_koudijs_2025:cash_reconciliation](cb/dataframes/lauristt--p22_golez_koudijs_2025/cash_reconciliation.md)<br>  [lauristt/p22_golez_koudijs_2025:coverage](cb/dataframes/lauristt--p22_golez_koudijs_2025/coverage.md)<br>  [lauristt/p22_golez_koudijs_2025:data_checks](cb/dataframes/lauristt--p22_golez_koudijs_2025/data_checks.md)<br>  [lauristt/p22_golez_koudijs_2025:forecast_ledger](cb/dataframes/lauristt--p22_golez_koudijs_2025/forecast_ledger.md)<br>  [lauristt/p22_golez_koudijs_2025:forecast_loss_comparisons](cb/dataframes/lauristt--p22_golez_koudijs_2025/forecast_loss_comparisons.md)<br>  [lauristt/p22_golez_koudijs_2025:forecast_metrics](cb/dataframes/lauristt--p22_golez_koudijs_2025/forecast_metrics.md)<br>  [lauristt/p22_golez_koudijs_2025:forecast_validation](cb/dataframes/lauristt--p22_golez_koudijs_2025/forecast_validation.md)<br>  [lauristt/p22_golez_koudijs_2025:industry_reference](cb/dataframes/lauristt--p22_golez_koudijs_2025/industry_reference.md)<br>  [lauristt/p22_golez_koudijs_2025:payout_history](cb/dataframes/lauristt--p22_golez_koudijs_2025/payout_history.md)<br>  [lauristt/p22_golez_koudijs_2025:portfolio_overlap](cb/dataframes/lauristt--p22_golez_koudijs_2025/portfolio_overlap.md)<br>  [lauristt/p22_golez_koudijs_2025:published_comparison](cb/dataframes/lauristt--p22_golez_koudijs_2025/published_comparison.md)<br>  [lauristt/p22_golez_koudijs_2025:sector_annual](cb/dataframes/lauristt--p22_golez_koudijs_2025/sector_annual.md)<br>  [lauristt/p22_golez_koudijs_2025:sector_comparison](cb/dataframes/lauristt--p22_golez_koudijs_2025/sector_comparison.md)<br>  [lauristt/p22_golez_koudijs_2025:sector_estimates](cb/dataframes/lauristt--p22_golez_koudijs_2025/sector_estimates.md)<br>  [lauristt/p22_golez_koudijs_2025:table_1](cb/dataframes/lauristt--p22_golez_koudijs_2025/table_1.md)<br>  [lauristt/p22_golez_koudijs_2025:table_2](cb/dataframes/lauristt--p22_golez_koudijs_2025/table_2.md)<br>  [lauristt/p22_golez_koudijs_2025:table_4](cb/dataframes/lauristt--p22_golez_koudijs_2025/table_4.md)<br>  [lauristt/p22_golez_koudijs_2025:table_5](cb/dataframes/lauristt--p22_golez_koudijs_2025/table_5.md)<br>  [lauristt/p22_golez_koudijs_2025:table_6](cb/dataframes/lauristt--p22_golez_koudijs_2025/table_6.md)<br>  [lauristt/p22_golez_koudijs_2025:table_7](cb/dataframes/lauristt--p22_golez_koudijs_2025/table_7.md)<br>  [lauristt/p22_golez_koudijs_2025:updated_decomposition](cb/dataframes/lauristt--p22_golez_koudijs_2025/updated_decomposition.md)<br>  [lauristt/p22_golez_koudijs_2025:updated_payout_history](cb/dataframes/lauristt--p22_golez_koudijs_2025/updated_payout_history.md)<br>  [lauristt/p22_golez_koudijs_2025:updated_table_1](cb/dataframes/lauristt--p22_golez_koudijs_2025/updated_table_1.md)<br>  [lauristt/p22_golez_koudijs_2025:updated_table_2](cb/dataframes/lauristt--p22_golez_koudijs_2025/updated_table_2.md)<br>  [lauristt/p22_golez_koudijs_2025:updated_table_4](cb/dataframes/lauristt--p22_golez_koudijs_2025/updated_table_4.md)<br>  [lauristt/p22_golez_koudijs_2025:updated_table_5](cb/dataframes/lauristt--p22_golez_koudijs_2025/updated_table_5.md)<br>  [lauristt/p22_golez_koudijs_2025:updated_table_6](cb/dataframes/lauristt--p22_golez_koudijs_2025/updated_table_6.md)<br>  [lauristt/p22_golez_koudijs_2025:updated_table_7](cb/dataframes/lauristt--p22_golez_koudijs_2025/updated_table_7.md)<br>  [lauristt/p22_golez_koudijs_2025:validation_summary](cb/dataframes/lauristt--p22_golez_koudijs_2025/validation_summary.md)<br>  [lauristt/p22_golez_koudijs_2025:var_sensitivity](cb/dataframes/lauristt--p22_golez_koudijs_2025/var_sensitivity.md)<br>  |


**Build Commands:**
```
doit
```


Replication and update of Golez and Koudijs (2025), *Equity duration and predictability*, Journal of Financial Economics **172**, 104114, plus **Sector ER Tracker**, the consultation-agreed extension confirmed by the team on November 18, 2026. [Paper DOI](https://doi.org/10.1016/j.jfineco.2025.104114).

Team: Yuting Li (Lauristt), Yiyao Wang (PriscillaWyy), Gary Miao (garymmmjw), and Luke Zhu (1143051639Luke). Each contributor uses their own Git identity.

## Build the complete submission

Requires Git, [uv](https://docs.astral.sh/uv/), Python 3.12, and a TeX distribution providing `pdflatex` and standard packages (`booktabs`, `longtable`, `pdflscape`, `lmodern`, `hyperref`). TeX Live works on Linux/Windows; MacTeX works on macOS. The full build needs your own WRDS access to CRSP, Compustat, CCM and OptionMetrics. No credentials or licensed input files are shipped.

```sh
git clone git@github.com:Lauristt/p22_golez_koudijs_2025.git
cd p22_golez_koudijs_2025
# While this work is under review:
git switch feature/sector-er-tracker
uv sync --frozen
cp .env.example .env
# Edit WRDS_USERNAME in .env and configure your own WRDS ~/.pgpass.
uv run doit
uv run doit checks
uv run python src/serve_review.py
```

Open <http://127.0.0.1:8000/> for ChartBook, `/sector/` for the agreed extension, and `/report/report.pdf` for the complete generated report. Nothing depends on the original author's local filesystem. For pip users: create a Python 3.12 virtual environment, install `requirements.txt`, and run `doit`.

The default `doit` target is `submission`: fetch → clean → replicate/update/extend → enforce validation → generate LaTeX/PDF and execute the notebook → stage aggregate publication outputs → build ChartBook. A repeat run skips unchanged analytical tasks; source-integrity and acceptance gates still run. `uv run doit site` builds the same full review site. With no WRDS access, `uv run doit replicate checks` runs the public original-sample replication and tests, but is **not** the complete submission. CI runs independent offline tests and registry checks in one job, and live-source replication/acceptance plus integration tests in another. A source outage fails the replication job while allowing the offline tests to report their results.

Raw downloads are cached and resumed; an initial full WRDS build can take time. The author-package downloader retries transient HTTP/network errors up to four attempts and validates all required member hashes before accepting an archive. If Mendeley remains unavailable, replication stops explicitly; run `uv run pytest -q` to check independent code using the inputs available locally. Do not bypass source hashes or loosen tolerances to work around an outage. A missing subscription or failed validation stops the dependent work rather than substituting data. The PDF build stops with an installation instruction if `pdflatex` is absent.

## What the pipeline delivers

- Assigned baseline Tables **1, 2, 4, 5, 6, 7** and Figures **1, 3**. Tables 8/9 are outside scope.
- Recent-data versions of the same exhibits. Annual outcomes end in **2025**; accessible OptionMetrics SPX data end in **August 2025**, and the stock cache reaches **September 2026**. Partial 2026 data are not treated as full-year outcomes.
- A paper-aligned stock-level cross-section using established dividend payers, January portfolio formation, terciles and absolute 0.5 payout groups. The available ten-year historical screen limits this reconstruction to **1970–2025**; it is compared against the authors' portfolios over common years rather than silently spliced onto incompatible units.
- The agreed **Sector ER Tracker**: historical SIC industries, within-industry payout groups, identical monthly industry weights on both sides, common-sample comparison with market-wide sorts, full-sample and trailing-window estimates, joint uncertainty and a richer two-state VAR sensitivity.
- Independent data checks, an explanatory validation table and coverage/reconciliation figure, an executed data-tour notebook, and one generated LaTeX document containing displayed results tables and all publication figures.
- Registered ChartBook dataframes, charts, notebook and report, with source metadata and raw-to-result lineage. Publication staging contains aggregate derived outputs, never individual stock/accounting records or source workbooks.

The former PayoutForecast proposal remains an explicitly labeled historical sensitivity appendix. It does not replace Sector ER Tracker.

## What Sector ER Tracker is for

An equity researcher can use it to assess whether payout-related valuation decomposition differences persist within industries and whether those comparisons survive uncertainty and specification changes. ER is a contribution to variation in log dividend-price ratios; it is **not** a return forecast, R-squared, Treasury-duration estimate or trading recommendation. A null result or wide interval is an informative product output.

The primary universe requires positive dividends in all ten preceding calendar years and ten available fiscal observations, plus usable earnings and time-valid CCM links. Negative cumulative earners are excluded. The broad nonpayer prototype and its controlled direction audit are documented separately; the original reversed ordering was not an exact replication of the paper's selection rules.

Cash dividends use ex-date amounts and cumulative share factors to adjust for splits. Monthly portfolio units withdraw cash, and annual returns include those withdrawals. Stock weights drift between January formations; terminal delisting proceeds are reinvested pro rata in survivors. Industry sleeves are recombined with identical equal weights each month. Accounts become usable at the latest of fiscal date plus six months, preliminary date, and final date; records older than two years are not carried forward. Historical revisions remain, so this is pseudo-real-time.

## Validation and scientific limitations

`config/published_benchmarks.json` retains the original published-rounding rule: absolute tolerance **0.0051**, exact integer counts, no fitting to target cells. The baseline has reproduced **264** independently computed numeric cells. **Two historical Table 4 smoothing entries remain author-supplied constants**, because early earnings and the separate estimation file are absent; they are excluded from independent acceptance counts. The postwar nominal-growth ratio is now recomputed; its real-growth counterpart is separately disclosed because the paper describes the summaries as real. The two historical entries remain an unresolved replication limitation.

`config/data_validation.json` retains the registered cash/annual-construction gates: numerical identities and weight sums, unique stock-month keys, cash-event matching, and agreement between cash-event yields and independent total/ex-distribution return fields. Every check writes its observation and tolerance. Coverage and filter counts are reported rather than forced to an invented target. Failed gates stop acceptance. The added omission-ledger gate checks a structural identity (zero unexplained omissions); it is a remediation check, not a retrospective claim of preregistration.

The earlier strip-rebuild price diagnostics used exploratory thresholds after viewing historical results. The return correlation is explicitly diagnostic (not marked passed). Missing historical strip prices and returns stay missing; only complete calendar windows enter the overlap estimates. They are explicitly not presented as blind preregistered validation. The current stock rebuild also differs from the authors' prepared portfolios in available history, reporting lag and eligibility. Its overlap correlations, missing earnings years and sample counts are exposed. Missing realized earnings invalidate earnings-dependent summaries; they are not filled with invented values. These limits prevent honestly claiming every rubric item is fully resolved.

The primary uncertainty calculation uses a joint stationary time-series bootstrap with expected block length five annual pairs and a committed seed. Calendar gaps force block restarts, and all four comparison portfolios share draws. Intervals do not cover model misspecification or historical data revisions. Near-zero denominators and discounted terminal-condition failures remain visible. The richer VAR uses the matrix long-run mapping, not the scalar formula applied to a multivariable regression.

## Configuration, reproducibility and sources

Copy `.env.example` to ignored `.env` for **machine facts and credentials only**: `DATA_DIR`, `OUTPUT_DIR`, `WRDS_USERNAME`. Passwords stay in the WRDS/libpq password file. `PGPASSFILE` may point to your own alternative credential file. Do not put secrets in commands, notebooks or Git.

`START_DATE` and `END_DATE` are committed constants in `src/settings.py`; `.env`, environment and command-line date overrides are ignored. The sector annual endpoint derives from END_DATE and is checked against complete source coverage. Workstream lookbacks, stock retrieval cutoff and bootstrap settings are committed JSON configuration. Updating data requires a reviewed configuration change, not each machine's clock. Author and Goyal downloads have fixed source hashes. All raw inputs are additionally locked by expected SHA-256 in config/source_snapshot.json; the full pipeline fails on missing, changed or unexpected files. Historical vendors can revise data, so a fresh pull may fail the lock and require a reviewed refresh. See [Source snapshots](SOURCE_SNAPSHOTS.md) for reproduction and explicit refresh commands. Generated scientific artifacts avoid run-time timestamps; the local append-only build history is operational metadata.

Sources: [Mendeley package v1](https://doi.org/10.17632/fp6fryn7h3.1), pinned Goyal annual data (`config/update_sources.json`), WRDS CRSP/Compustat/CCM/OptionMetrics, [Kenneth French industry definitions](https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html), and [FRED CPIAUCSL](https://fred.stlouisfed.org/series/CPIAUCSL). Every registered dataframe has source descriptions and links in `chartbook.toml`.

Data cleaning is separate from analysis: `ingest.py`, `update_data.py` and `sector/clean.py` produce tidy inputs; `history.py`, `strips.py`, `portfolios.py`, `cross_update.py` and the sector analysis modules estimate results. `submission.py` renders the final artifacts. Source data, PDFs of the paper, credentials and generated reports are ignored by Git.

Retain `.cruft.json`, which records initialization with `cruft create https://github.com/backofficedev/cookiecutter_chartbook`. `uv.lock` pins dependencies; `requirements.txt` is its pip export. Refresh it after a dependency change with `uv export --no-hashes --no-dev --format requirements-txt --output-file requirements.txt`.

## Publication and collaboration

The source repository remains private. The generated site is published separately at https://lauristt.github.io/p22-equity-duration-site/ from the public `Lauristt/p22-equity-duration-site` repository. After building and inspecting locally, run `uv run doit publish` with Git/gh authentication to update only its `gh-pages` branch. No WRDS credentials are needed in GitHub Actions, and no raw caches are uploaded. Publication is explicit, never part of an ordinary build. Substantive source changes remain on the feature branch and require teammate review; the graded main-branch snapshot must be merged by the team before its deadline. Do not rewrite shared history or overwrite a teammate's Git identity.

[Sector methodology](docs_src/research/sector_tracker.md) · [Rubric status](docs_src/research/rubric_status.md)
