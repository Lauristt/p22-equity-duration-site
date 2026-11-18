# Dataframe: `lauristt/p22_golez_koudijs_2025:forecast_ledger` - Legacy forecast ledger


```{raw} html
<p class="cb-freshness">Data updated <time class="cb-relative-time" datetime="2026-11-18T07:02:24+00:00" title="2026-11-18 07:02 UTC">2026-11-18</time></p>
```


Clean annual U.S. source -> extension_inputs.py -> expanding-window extension.py; annual aggregate observations only.


## DataFrame Glimpse

```
Rows: 126
Columns: 11
$ model             <str> 'Historical mean', 'Dividend yield', 'Payout interaction', 'Historical mean', 'Dividend yield'
$ origin_year       <i64> 1980, 1980, 1980, 1981, 1981
$ target_year       <i64> 1981, 1981, 1981, 1982, 1982
$ train_start       <i64> 1946, 1946, 1946, 1946, 1946
$ train_end         <i64> 1980, 1980, 1980, 1981, 1981
$ train_n           <i64> 35, 35, 35, 36, 36
$ actual            <f64> -0.13514702450226593, -0.13514702450226593, -0.13514702450226593, 0.14779414896879356, 0.14779414896879356
$ forecast          <f64> 0.05529501927068375, 0.08888528911127316, 0.16284293140519032, 0.05000496249921292, 0.12743960160197412
$ error             <f64> -0.19044204377294968, -0.2240323136135391, -0.29798995590745625, 0.09778918646958064, 0.020354547366819437
$ payout_first_year <i64> 1970, 1970, 1970, 1971, 1971
$ payout_last_year  <i64> 1979, 1979, 1979, 1980, 1980


```



## Provenance



What this is, where it is, what made it and from what, as `index.json` records it.

| | |
|--------------------------------|--------------------------------------------------------------------------------------|
| What                           | Dataframe `lauristt/p22_golez_koudijs_2025:forecast_ledger`, of pipeline `lauristt/p22_golez_koudijs_2025`     |
| Where                          | `_output/publication/forecast_ledger.csv`                                                                 |
| Content                        | `sha256:514d1d9f7523a05452cf3d087a345b8a782c7fd41804073fe52887a938840bde` · 14,040 bytes · 126 rows · 11 columns                                                               |
| Built by                       | `doit` in `lauristt/p22_golez_koudijs_2025`                                 |
| Series                         | 11 columns documented                                             |



**Used by:** `lauristt/p22_golez_koudijs_2025:chart/forecast_predictions`



## Dataframe Manifest

| Dataframe Name                 | Legacy forecast ledger                                                          |
|--------------------------------|--------------------------------------------------------------------------------------|
| Dataframe ID                   | [forecast_ledger](../lauristt--p22_golez_koudijs_2025/forecast_ledger.md)                                       |
| Sources                        | Mendeley v1 Data_US_1871_2022.xls                                          |
| Dataframe Path                 | `_output/publication/forecast_ledger.csv`                                                        |


**Linked Charts:**


- [lauristt/p22_golez_koudijs_2025:chart/forecast_predictions](../../charts/lauristt--p22_golez_koudijs_2025.forecast_predictions.md)



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

