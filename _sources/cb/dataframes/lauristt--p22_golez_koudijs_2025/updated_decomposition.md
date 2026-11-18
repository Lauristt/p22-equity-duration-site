# Dataframe: `lauristt/p22_golez_koudijs_2025:updated_decomposition` - Updated decomposition


```{raw} html
<p class="cb-freshness">Data updated <time class="cb-relative-time" datetime="2026-11-18T06:35:05+00:00" title="2026-11-18 06:35 UTC">2026-11-18</time></p>
```


Updated Figure 3 points. Stock-level and historical sample coverage differ; see the report. Lineage: raw source caches -> src/p22 cleaning modules -> analysis modules -> publication staging. Raw files and security-level observations are never published.


## DataFrame Glimpse

```
Rows: 9
Columns: 4
$ Payout <f64> 46.9701686094612, 98.4099292061957, 85.6386782994203, 46.8202498291858, 29.6900739415637
$ ER     <f64> 0.89270715203057, 0.342853778478057, 0.370817652291206, 0.547107905375019, 0.518825911709392
$ Source <str> 'time', 'time', 'time', 'cross', 'cross'
$ sample <str> '1945–2025', '1629–1945', '1629–2025', 'All', 'Low'


```



## Provenance



What this is, where it is, what made it and from what, as `index.json` records it.

| | |
|--------------------------------|--------------------------------------------------------------------------------------|
| What                           | Dataframe `lauristt/p22_golez_koudijs_2025:updated_decomposition`, of pipeline `lauristt/p22_golez_koudijs_2025`     |
| Where                          | `_output/publication/updated_decomposition.csv`                                                                 |
| Content                        | `sha256:d84e52cb5202113ea36500fe3596abac0a1468077c437938b7146eb4e568b692` · 464 bytes · 9 rows · 4 columns                                                               |
| Built by                       | `doit` in `lauristt/p22_golez_koudijs_2025`                                 |
| Series                         | 4 columns documented                                             |



**Used by:** `lauristt/p22_golez_koudijs_2025:chart/updated_decomposition`



## Dataframe Manifest

| Dataframe Name                 | Updated decomposition                                                          |
|--------------------------------|--------------------------------------------------------------------------------------|
| Dataframe ID                   | [updated_decomposition](../lauristt--p22_golez_koudijs_2025/updated_decomposition.md)                                       |
| Sources                        | Mendeley version 1: https://doi.org/10.17632/fp6fryn7h3.1, WRDS CRSP monthly CIZ and cash distributions, WRDS Compustat annual fundamentals, CRSP-Compustat link history, Kenneth French SIC industry mapping, FRED CPIAUCSL                                          |
| Providers                      | Golez and Koudijs, WRDS, Kenneth French, FRED                                        |
| Provider Links                 | https://doi.org/10.17632/fp6fryn7h3.1, https://wrds-www.wharton.upenn.edu/, https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html, https://fred.stlouisfed.org/series/CPIAUCSL                                   |
| Dataframe Path                 | `_output/publication/updated_decomposition.csv`                                                        |


**Linked Charts:**


- [lauristt/p22_golez_koudijs_2025:chart/updated_decomposition](../../charts/lauristt--p22_golez_koudijs_2025.updated_decomposition.md)



## Pipeline Manifest

| Pipeline Name                   | P22: Equity Duration and Predictability                       |
|---------------------------------|--------------------------------------------------------|
| Pipeline ID                     | [lauristt/p22_golez_koudijs_2025](../../../index.md)              |
| Maintainer                      | Lauris Li               |
| Contributors                    | Lauris Li, Yiyao Wang, Gary Miao, Luke Zhu |
| Repository                     | https://github.com/Lauristt/p22_golez_koudijs_2025                  |
| Pipeline Web Page               | <a href="https://lauristt.github.io/p22-equity-duration-site/">Pipeline Web Page</a> |
| OS Compatibility                | Windows, Linux, macOS |
| Linked Dataframes               |  [lauristt/p22_golez_koudijs_2025:baseline_decomposition](../../dataframes/lauristt--p22_golez_koudijs_2025/baseline_decomposition.md)<br>  [lauristt/p22_golez_koudijs_2025:cash_reconciliation](../../dataframes/lauristt--p22_golez_koudijs_2025/cash_reconciliation.md)<br>  [lauristt/p22_golez_koudijs_2025:coverage](../../dataframes/lauristt--p22_golez_koudijs_2025/coverage.md)<br>  [lauristt/p22_golez_koudijs_2025:data_checks](../../dataframes/lauristt--p22_golez_koudijs_2025/data_checks.md)<br>  [lauristt/p22_golez_koudijs_2025:payout_history](../../dataframes/lauristt--p22_golez_koudijs_2025/payout_history.md)<br>  [lauristt/p22_golez_koudijs_2025:portfolio_overlap](../../dataframes/lauristt--p22_golez_koudijs_2025/portfolio_overlap.md)<br>  [lauristt/p22_golez_koudijs_2025:sector_annual](../../dataframes/lauristt--p22_golez_koudijs_2025/sector_annual.md)<br>  [lauristt/p22_golez_koudijs_2025:sector_comparison](../../dataframes/lauristt--p22_golez_koudijs_2025/sector_comparison.md)<br>  [lauristt/p22_golez_koudijs_2025:sector_estimates](../../dataframes/lauristt--p22_golez_koudijs_2025/sector_estimates.md)<br>  [lauristt/p22_golez_koudijs_2025:table_1](../../dataframes/lauristt--p22_golez_koudijs_2025/table_1.md)<br>  [lauristt/p22_golez_koudijs_2025:table_2](../../dataframes/lauristt--p22_golez_koudijs_2025/table_2.md)<br>  [lauristt/p22_golez_koudijs_2025:table_4](../../dataframes/lauristt--p22_golez_koudijs_2025/table_4.md)<br>  [lauristt/p22_golez_koudijs_2025:table_5](../../dataframes/lauristt--p22_golez_koudijs_2025/table_5.md)<br>  [lauristt/p22_golez_koudijs_2025:table_6](../../dataframes/lauristt--p22_golez_koudijs_2025/table_6.md)<br>  [lauristt/p22_golez_koudijs_2025:table_7](../../dataframes/lauristt--p22_golez_koudijs_2025/table_7.md)<br>  [lauristt/p22_golez_koudijs_2025:updated_decomposition](../../dataframes/lauristt--p22_golez_koudijs_2025/updated_decomposition.md)<br>  [lauristt/p22_golez_koudijs_2025:updated_payout_history](../../dataframes/lauristt--p22_golez_koudijs_2025/updated_payout_history.md)<br>  [lauristt/p22_golez_koudijs_2025:updated_table_1](../../dataframes/lauristt--p22_golez_koudijs_2025/updated_table_1.md)<br>  [lauristt/p22_golez_koudijs_2025:updated_table_2](../../dataframes/lauristt--p22_golez_koudijs_2025/updated_table_2.md)<br>  [lauristt/p22_golez_koudijs_2025:updated_table_4](../../dataframes/lauristt--p22_golez_koudijs_2025/updated_table_4.md)<br>  [lauristt/p22_golez_koudijs_2025:updated_table_5](../../dataframes/lauristt--p22_golez_koudijs_2025/updated_table_5.md)<br>  [lauristt/p22_golez_koudijs_2025:updated_table_6](../../dataframes/lauristt--p22_golez_koudijs_2025/updated_table_6.md)<br>  [lauristt/p22_golez_koudijs_2025:updated_table_7](../../dataframes/lauristt--p22_golez_koudijs_2025/updated_table_7.md)<br>  |


**Build Commands:**
```
doit
```

