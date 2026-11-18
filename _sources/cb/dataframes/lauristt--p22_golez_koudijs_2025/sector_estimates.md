# Dataframe: `lauristt/p22_golez_koudijs_2025:sector_estimates` - Sector estimates


```{raw} html
<p class="cb-freshness">Data updated <time class="cb-relative-time" datetime="2026-11-18T07:04:33+00:00" title="2026-11-18 07:04 UTC">2026-11-18</time></p>
```


Annual ER/EDG estimates, block intervals, sample sizes, denominator and quality flags. Lineage: raw source caches -> src/p22 cleaning modules -> analysis modules -> publication staging. Raw files and security-level observations are never published.


## DataFrame Glimpse

```
Rows: 3592
Columns: 29
$ n_obs                       <i64> 55, 20, 20, 20, 20
$ beta_return                 <f64> 0.0622390521466923, 0.257378997986428, 0.29640818968445454, 0.40427570796119, 0.2737153993154174
$ beta_growth                 <f64> -0.063269594791569, -0.04743039031290122, -0.0718987790618111, -0.04552909446211702, -0.014485575900880614
$ beta_dp                     <f64> 0.9111101622832923, 0.730180545198036, 0.6643465978954043, 0.5806308994708577, 0.750323807512171
$ rho                         <f64> 0.9631223819394363, 0.9492923953313945, 0.9486801304470955, 0.948127912808378, 0.947567169504729
$ denominator                 <f64> 0.12248941029248905, 0.306845161224573, 0.3697475828465038, 0.4494876371726447, 0.28901779350368084
$ ER                          <f64> 0.5081178201288864, 0.83879112500672, 0.8016501078994337, 0.899414521173829, 0.94705379899709
$ EDG                         <f64> 0.5165311404511567, 0.15457434663011682, 0.19445368245087077, 0.1012910938963815, 0.05012001415302525
$ coefficient_restriction     <f64> 1.0030192366457722, 0.997964227074756, 0.998559385899762, 1.0003171652506624, 0.999183181712617
$ window_start                <f64> 1971.0, 1971.0, 1972.0, 1973.0, 1974.0
$ window_end                  <f64> 2025.0, 1990.0, 1991.0, 1992.0, 1993.0
$ bootstrap_valid_fraction    <f64> 1.0, 1.0, 1.0, 1.0, 1.0
$ bootstrap_unstable_fraction <f64> 0.034, 0.006, 0.01, 0.024, 0.152
$ ER_lower                    <f64> -0.5439922097918454, -0.1898661089899469, -0.5067353944021116, -1.0419636504947947, -1.6567114583021842
$ ER_upper                    <f64> 0.8695111580112026, 1.085563975885765, 1.1611009888798316, 1.293534029756833, 3.324249502375393
$ EDG_lower                   <f64> 0.1659571640663557, -0.0859165470864478, -0.161427842244083, -0.290732226341291, -2.3335842194695124
$ EDG_upper                   <f64> 1.6389914393019387, 1.169295372974821, 1.51036389870935, 2.0357751381775357, 2.6464730103490313
$ quality_flags               <str> 'cash_dividends;annual_formation;revised_accounting', 'cash_dividends;annual_formation;revised_accounting', 'cash_dividends;annual_formation;revised_accounting', 'cash_dividends;annual_formation;revised_accounting', 'cash_dividends;annual_formation;revised_accounting;unstable_bootstrap'
$ industry_id                 <i64> -2, -2, -2, -2, -2
$ industry_name               <str> 'Paper-aligned market', 'Paper-aligned market', 'Paper-aligned market', 'Paper-aligned market', 'Paper-aligned market'
$ portfolio                   <str> 'Above 0.5', 'Above 0.5', 'Above 0.5', 'Above 0.5', 'Above 0.5'
$ window                      <str> 'full', '20', '20', '20', '20'
$ estimate_asof               <i64> 2025, 1990, 1991, 1992, 1993
$ frequency                   <str> 'annual', 'annual', 'annual', 'annual', 'annual'
$ firm_count                  <i64> 273, 295, 312, 323, 349
$ market_cap_coverage         <f64> 1.0, 1.0, 0.997625073107693, 0.9999103105605904, 1.0
$ payout_ratio                <f64> 0.715004727378019, 0.650751361525594, 0.6515867973941816, 0.660508920342297, 0.6861591420622637
$ dividend_yield              <f64> 0.0273798623365571, 0.0491204971535697, 0.0428593500912714, 0.0421407835065929, 0.0381802318478868
$ source_version              <str> '2026-11-17', '2026-11-17', '2026-11-17', '2026-11-17', '2026-11-17'


```



## Provenance



What this is, where it is, what made it and from what, as `index.json` records it.

| | |
|--------------------------------|--------------------------------------------------------------------------------------|
| What                           | Dataframe `lauristt/p22_golez_koudijs_2025:sector_estimates`, of pipeline `lauristt/p22_golez_koudijs_2025`     |
| Where                          | `_output/publication/sector_estimates.csv`                                                                 |
| Content                        | `sha256:dd2fca995386e374003de2511b2082a097c6cf575405dc09005a0eca600925a8` · 1,392,008 bytes · 3,592 rows · 29 columns                                                               |
| Built by                       | `doit` in `lauristt/p22_golez_koudijs_2025`                                 |
| Series                         | 29 columns documented                                             |





## Dataframe Manifest

| Dataframe Name                 | Sector estimates                                                          |
|--------------------------------|--------------------------------------------------------------------------------------|
| Dataframe ID                   | [sector_estimates](../lauristt--p22_golez_koudijs_2025/sector_estimates.md)                                       |
| Sources                        | WRDS CRSP monthly CIZ and cash distributions, WRDS Compustat annual fundamentals, CRSP-Compustat link history, Kenneth French SIC industry mapping, FRED CPIAUCSL                                          |
| Providers                      | Golez and Koudijs, WRDS, Kenneth French, FRED                                        |
| Provider Links                 | https://doi.org/10.17632/fp6fryn7h3.1, https://wrds-www.wharton.upenn.edu/, https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html, https://fred.stlouisfed.org/series/CPIAUCSL                                   |
| Dataframe Path                 | `_output/publication/sector_estimates.csv`                                                        |


**Linked Charts:**

- None


## Pipeline Manifest

| Pipeline Name                   | P22: Equity Duration and Predictability                       |
|---------------------------------|--------------------------------------------------------|
| Pipeline ID                     | [lauristt/p22_golez_koudijs_2025](../../../index.md)              |
| Maintainer                      | Lauris Li               |
| Contributors                    | Lauris Li, Yiyao Wang, Gary Miao, Luke Zhu |
| Repository                     | https://github.com/Lauristt/p22_golez_koudijs_2025                  |
| Pipeline Web Page               | <a href="https://lauristt.github.io/p22-equity-duration-site/">Pipeline Web Page</a> |
| OS Compatibility                | Windows, Linux, macOS |
| Linked Dataframes               |  [lauristt/p22_golez_koudijs_2025:annual_coverage](../../dataframes/lauristt--p22_golez_koudijs_2025/annual_coverage.md)<br>  [lauristt/p22_golez_koudijs_2025:author_summary](../../dataframes/lauristt--p22_golez_koudijs_2025/author_summary.md)<br>  [lauristt/p22_golez_koudijs_2025:baseline_decomposition](../../dataframes/lauristt--p22_golez_koudijs_2025/baseline_decomposition.md)<br>  [lauristt/p22_golez_koudijs_2025:cash_reconciliation](../../dataframes/lauristt--p22_golez_koudijs_2025/cash_reconciliation.md)<br>  [lauristt/p22_golez_koudijs_2025:coverage](../../dataframes/lauristt--p22_golez_koudijs_2025/coverage.md)<br>  [lauristt/p22_golez_koudijs_2025:data_checks](../../dataframes/lauristt--p22_golez_koudijs_2025/data_checks.md)<br>  [lauristt/p22_golez_koudijs_2025:forecast_ledger](../../dataframes/lauristt--p22_golez_koudijs_2025/forecast_ledger.md)<br>  [lauristt/p22_golez_koudijs_2025:forecast_loss_comparisons](../../dataframes/lauristt--p22_golez_koudijs_2025/forecast_loss_comparisons.md)<br>  [lauristt/p22_golez_koudijs_2025:forecast_metrics](../../dataframes/lauristt--p22_golez_koudijs_2025/forecast_metrics.md)<br>  [lauristt/p22_golez_koudijs_2025:forecast_validation](../../dataframes/lauristt--p22_golez_koudijs_2025/forecast_validation.md)<br>  [lauristt/p22_golez_koudijs_2025:industry_reference](../../dataframes/lauristt--p22_golez_koudijs_2025/industry_reference.md)<br>  [lauristt/p22_golez_koudijs_2025:payout_history](../../dataframes/lauristt--p22_golez_koudijs_2025/payout_history.md)<br>  [lauristt/p22_golez_koudijs_2025:portfolio_overlap](../../dataframes/lauristt--p22_golez_koudijs_2025/portfolio_overlap.md)<br>  [lauristt/p22_golez_koudijs_2025:published_comparison](../../dataframes/lauristt--p22_golez_koudijs_2025/published_comparison.md)<br>  [lauristt/p22_golez_koudijs_2025:sector_annual](../../dataframes/lauristt--p22_golez_koudijs_2025/sector_annual.md)<br>  [lauristt/p22_golez_koudijs_2025:sector_comparison](../../dataframes/lauristt--p22_golez_koudijs_2025/sector_comparison.md)<br>  [lauristt/p22_golez_koudijs_2025:sector_estimates](../../dataframes/lauristt--p22_golez_koudijs_2025/sector_estimates.md)<br>  [lauristt/p22_golez_koudijs_2025:table_1](../../dataframes/lauristt--p22_golez_koudijs_2025/table_1.md)<br>  [lauristt/p22_golez_koudijs_2025:table_2](../../dataframes/lauristt--p22_golez_koudijs_2025/table_2.md)<br>  [lauristt/p22_golez_koudijs_2025:table_4](../../dataframes/lauristt--p22_golez_koudijs_2025/table_4.md)<br>  [lauristt/p22_golez_koudijs_2025:table_5](../../dataframes/lauristt--p22_golez_koudijs_2025/table_5.md)<br>  [lauristt/p22_golez_koudijs_2025:table_6](../../dataframes/lauristt--p22_golez_koudijs_2025/table_6.md)<br>  [lauristt/p22_golez_koudijs_2025:table_7](../../dataframes/lauristt--p22_golez_koudijs_2025/table_7.md)<br>  [lauristt/p22_golez_koudijs_2025:updated_decomposition](../../dataframes/lauristt--p22_golez_koudijs_2025/updated_decomposition.md)<br>  [lauristt/p22_golez_koudijs_2025:updated_payout_history](../../dataframes/lauristt--p22_golez_koudijs_2025/updated_payout_history.md)<br>  [lauristt/p22_golez_koudijs_2025:updated_table_1](../../dataframes/lauristt--p22_golez_koudijs_2025/updated_table_1.md)<br>  [lauristt/p22_golez_koudijs_2025:updated_table_2](../../dataframes/lauristt--p22_golez_koudijs_2025/updated_table_2.md)<br>  [lauristt/p22_golez_koudijs_2025:updated_table_4](../../dataframes/lauristt--p22_golez_koudijs_2025/updated_table_4.md)<br>  [lauristt/p22_golez_koudijs_2025:updated_table_5](../../dataframes/lauristt--p22_golez_koudijs_2025/updated_table_5.md)<br>  [lauristt/p22_golez_koudijs_2025:updated_table_6](../../dataframes/lauristt--p22_golez_koudijs_2025/updated_table_6.md)<br>  [lauristt/p22_golez_koudijs_2025:updated_table_7](../../dataframes/lauristt--p22_golez_koudijs_2025/updated_table_7.md)<br>  [lauristt/p22_golez_koudijs_2025:validation_summary](../../dataframes/lauristt--p22_golez_koudijs_2025/validation_summary.md)<br>  [lauristt/p22_golez_koudijs_2025:var_sensitivity](../../dataframes/lauristt--p22_golez_koudijs_2025/var_sensitivity.md)<br>  |


**Build Commands:**
```
doit
```

