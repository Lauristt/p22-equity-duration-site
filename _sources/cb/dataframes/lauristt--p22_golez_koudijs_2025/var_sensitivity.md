# Dataframe: `lauristt/p22_golez_koudijs_2025:var_sensitivity` - Two-state VAR sensitivity


```{raw} html
<p class="cb-freshness">Data updated <time class="cb-relative-time" datetime="2026-11-18T07:04:33+00:00" title="2026-11-18 07:04 UTC">2026-11-18</time></p>
```


sector/annual.csv -> sector/robustness.py; aggregate cash portfolio states from CRSP, Compustat and FRED.


## DataFrame Glimpse

```
Rows: 46
Columns: 10
$ n_obs                      <i64> 54, 54, 54, 54, 54
$ start                      <i64> 1972, 1972, 1972, 1972, 1972
$ end                        <i64> 2025, 2025, 2025, 2025, 2025
$ ER                         <f64> 0.4990956605462944, 0.5213690261391897, 0.5387207935162177, 0.476227252026515, 0.5029217478457867
$ EDG                        <f64> 0.524687262063459, 0.49566436904800965, 0.47648988840850554, 0.539628295640226, 0.499153056031584
$ discounted_spectral_radius <f64> 0.8680922747263977, 0.8861872903493666, 0.9013079333603156, 0.845488892515314, 0.881020746449853
$ quality_flags              <str> ';sensitivity_point_estimate_only', ';sensitivity_point_estimate_only', ';sensitivity_point_estimate_only', ';sensitivity_point_estimate_only', ';sensitivity_point_estimate_only'
$ industry_id                <i64> -2, -2, -2, -2, -2
$ industry_name              <str> 'Paper-aligned market', 'Paper-aligned market', 'Paper-aligned market', 'Paper-aligned market', 'Paper-aligned market'
$ portfolio                  <str> 'Above 0.5', 'All', 'Below 0.5', 'High', 'Low'


```



## Provenance



What this is, where it is, what made it and from what, as `index.json` records it.

| | |
|--------------------------------|--------------------------------------------------------------------------------------|
| What                           | Dataframe `lauristt/p22_golez_koudijs_2025:var_sensitivity`, of pipeline `lauristt/p22_golez_koudijs_2025`     |
| Where                          | `_output/publication/var_sensitivity.csv`                                                                 |
| Content                        | `sha256:5863a128a720811a88ff89779e1e595e87ad09611752202d30e0c3dc13dcf690` · 5,573 bytes · 46 rows · 10 columns                                                               |
| Built by                       | `doit` in `lauristt/p22_golez_koudijs_2025`                                 |
| Series                         | 10 columns documented                                             |





## Dataframe Manifest

| Dataframe Name                 | Two-state VAR sensitivity                                                          |
|--------------------------------|--------------------------------------------------------------------------------------|
| Dataframe ID                   | [var_sensitivity](../lauristt--p22_golez_koudijs_2025/var_sensitivity.md)                                       |
| Sources                        | WRDS CRSP/Compustat; FRED CPIAUCSL                                          |
| Dataframe Path                 | `_output/publication/var_sensitivity.csv`                                                        |


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

