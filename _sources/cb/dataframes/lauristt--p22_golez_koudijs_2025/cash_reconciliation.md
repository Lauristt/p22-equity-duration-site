# Dataframe: `lauristt/p22_golez_koudijs_2025:cash_reconciliation` - Cash reconciliation


```{raw} html
<p class="cb-freshness">Data updated <time class="cb-relative-time" datetime="2026-11-18T06:34:52+00:00" title="2026-11-18 06:34 UTC">2026-11-18</time></p>
```


Paying-stock-month cash yield versus independently recorded total/ex-distribution return difference. Lineage: raw source caches -> src/p22 cleaning modules -> analysis modules -> publication staging. Raw files and security-level observations are never published.


## DataFrame Glimpse

```
Rows: 67
Columns: 4
$ year   <i64> 1960, 1961, 1962, 1963, 1964
$ median <f64> 0.0002625895765472324, 0.00021721499746664343, 0.00029627450980392045, 0.000200476510067115, 0.00019149486521181057
$ max    <f64> 0.0440458732394366, 0.02221960330578512, 0.080495979020979, 0.02183523529411765, 0.021692
$ p95    <f64> 0.0018773252873562993, 0.0014470560837913885, 0.0021127428571428644, 0.00191958367262152, 0.0017979853535353557


```



## Provenance



What this is, where it is, what made it and from what, as `index.json` records it.

| | |
|--------------------------------|--------------------------------------------------------------------------------------|
| What                           | Dataframe `lauristt/p22_golez_koudijs_2025:cash_reconciliation`, of pipeline `lauristt/p22_golez_koudijs_2025`     |
| Where                          | `_output/publication/cash_reconciliation.csv`                                                                 |
| Content                        | `sha256:346d6c2fee97086312356b5dd4aa93cc6bb9b047175087ba6f29f3b23324cd56` · 4,606 bytes · 67 rows · 4 columns                                                               |
| Built by                       | `doit` in `lauristt/p22_golez_koudijs_2025`                                 |
| Series                         | 4 columns documented                                             |



**Used by:** `lauristt/p22_golez_koudijs_2025:chart/data_validation`



## Dataframe Manifest

| Dataframe Name                 | Cash reconciliation                                                          |
|--------------------------------|--------------------------------------------------------------------------------------|
| Dataframe ID                   | [cash_reconciliation](../lauristt--p22_golez_koudijs_2025/cash_reconciliation.md)                                       |
| Sources                        | WRDS CRSP monthly CIZ and cash distributions, WRDS Compustat annual fundamentals, CRSP-Compustat link history, Kenneth French SIC industry mapping, FRED CPIAUCSL                                          |
| Providers                      | Golez and Koudijs, WRDS, Kenneth French, FRED                                        |
| Provider Links                 | https://doi.org/10.17632/fp6fryn7h3.1, https://wrds-www.wharton.upenn.edu/, https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html, https://fred.stlouisfed.org/series/CPIAUCSL                                   |
| Dataframe Path                 | `_output/publication/cash_reconciliation.csv`                                                        |


**Linked Charts:**


- [lauristt/p22_golez_koudijs_2025:chart/data_validation](../../charts/lauristt--p22_golez_koudijs_2025.data_validation.md)



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

