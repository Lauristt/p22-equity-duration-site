# Dataframe: `lauristt/p22_golez_koudijs_2025:portfolio_overlap` - Portfolio overlap


```{raw} html
<p class="cb-freshness">Data updated <time class="cb-relative-time" datetime="2026-11-18T07:04:33+00:00" title="2026-11-18 07:04 UTC">2026-11-18</time></p>
```


Independent comparison against authors supplied portfolios on common historical years. Lineage: raw source caches -> src/p22 cleaning modules -> analysis modules -> publication staging. Raw files and security-level observations are never published.


## DataFrame Glimpse

```
Rows: 6
Columns: 9
$ portfolio                      <str> 'All', 'Low', 'Medium', 'High', 'Below 0.5'
$ years                          <i64> 53, 53, 53, 53, 53
$ first_year                     <i64> 1970, 1970, 1970, 1970, 1970
$ last_year                      <i64> 2022, 2022, 2022, 2022, 2022
$ dp_correlation                 <f64> 0.9964230127873145, 0.9777530521388403, 0.989365553383618, 0.986913426827242, 0.992700664943497
$ return_correlation             <f64> 0.9985208564125506, 0.992451972336007, 0.993122424453496, 0.994152323016242, 0.997088794106618
$ growth_correlation             <f64> 0.8702429425094376, 0.30890142581059116, 0.663038920931951, 0.717096644514233, 0.7691147713532216
$ missing_rebuilt_earnings_years <i64> 0, 3, 0, 3, 0
$ mean_firm_count_ratio          <f64> 0.9894793573683147, 0.9953760014868517, 0.98484486077778, 0.988235596451471, 0.9983111281927156


```



## Provenance



What this is, where it is, what made it and from what, as `index.json` records it.

| | |
|--------------------------------|--------------------------------------------------------------------------------------|
| What                           | Dataframe `lauristt/p22_golez_koudijs_2025:portfolio_overlap`, of pipeline `lauristt/p22_golez_koudijs_2025`     |
| Where                          | `_output/publication/portfolio_overlap.csv`                                                                 |
| Content                        | `sha256:518295571fac1440bbc28c25de3e3928ef0531eec287f32dd9b89895332e8449` · 728 bytes · 6 rows · 9 columns                                                               |
| Built by                       | `doit` in `lauristt/p22_golez_koudijs_2025`                                 |
| Series                         | 9 columns documented                                             |





## Dataframe Manifest

| Dataframe Name                 | Portfolio overlap                                                          |
|--------------------------------|--------------------------------------------------------------------------------------|
| Dataframe ID                   | [portfolio_overlap](../lauristt--p22_golez_koudijs_2025/portfolio_overlap.md)                                       |
| Sources                        | Mendeley version 1: https://doi.org/10.17632/fp6fryn7h3.1, WRDS CRSP monthly CIZ and cash distributions, WRDS Compustat annual fundamentals, CRSP-Compustat link history, Kenneth French SIC industry mapping, FRED CPIAUCSL                                          |
| Providers                      | Golez and Koudijs, WRDS, Kenneth French, FRED                                        |
| Provider Links                 | https://doi.org/10.17632/fp6fryn7h3.1, https://wrds-www.wharton.upenn.edu/, https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html, https://fred.stlouisfed.org/series/CPIAUCSL                                   |
| Dataframe Path                 | `_output/publication/portfolio_overlap.csv`                                                        |


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

