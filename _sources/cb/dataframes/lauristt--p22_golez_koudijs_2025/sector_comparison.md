# Dataframe: `lauristt/p22_golez_koudijs_2025:sector_comparison` - Sector comparison


```{raw} html
<p class="cb-freshness">Data updated <time class="cb-relative-time" datetime="2026-11-18T06:34:59+00:00" title="2026-11-18 06:34 UTC">2026-11-18</time></p>
```


Common-year within-industry versus market-wide payout comparisons with paired intervals. Lineage: raw source caches -> src/p22 cleaning modules -> analysis modules -> publication staging. Raw files and security-level observations are never published.


## DataFrame Glimpse

```
Rows: 2
Columns: 10
$ industry_id       <i64> 0, -1
$ comparison        <str> 'Industry-neutral', 'Market-wide'
$ n_obs             <i64> 31, 31
$ start             <i64> 1973, 1973
$ end               <i64> 2025, 2025
$ low_ER            <f64> 0.5131644204474145, 0.17585666580987683
$ high_ER           <f64> 0.39577535394944, 0.4305705896093122
$ low_minus_high_ER <f64> 0.11738906649797459, -0.25471392379943536
$ lower             <f64> -1.5665299840041556, -10.905313043755626
$ upper             <f64> 3.8162293000573446, 6.385228899601635


```



## Provenance



What this is, where it is, what made it and from what, as `index.json` records it.

| | |
|--------------------------------|--------------------------------------------------------------------------------------|
| What                           | Dataframe `lauristt/p22_golez_koudijs_2025:sector_comparison`, of pipeline `lauristt/p22_golez_koudijs_2025`     |
| Where                          | `_output/publication/sector_comparison.csv`                                                                 |
| Content                        | `sha256:95efe427238a5353415cdbb8b5a4395d87f29a9592687334dbcb48269e74a8d5` · 339 bytes · 2 rows · 10 columns                                                               |
| Built by                       | `doit` in `lauristt/p22_golez_koudijs_2025`                                 |
| Series                         | 10 columns documented                                             |



**Used by:** `lauristt/p22_golez_koudijs_2025:chart/sector_comparison`



## Dataframe Manifest

| Dataframe Name                 | Sector comparison                                                          |
|--------------------------------|--------------------------------------------------------------------------------------|
| Dataframe ID                   | [sector_comparison](../lauristt--p22_golez_koudijs_2025/sector_comparison.md)                                       |
| Sources                        | WRDS CRSP monthly CIZ and cash distributions, WRDS Compustat annual fundamentals, CRSP-Compustat link history, Kenneth French SIC industry mapping, FRED CPIAUCSL                                          |
| Providers                      | Golez and Koudijs, WRDS, Kenneth French, FRED                                        |
| Provider Links                 | https://doi.org/10.17632/fp6fryn7h3.1, https://wrds-www.wharton.upenn.edu/, https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html, https://fred.stlouisfed.org/series/CPIAUCSL                                   |
| Dataframe Path                 | `_output/publication/sector_comparison.csv`                                                        |


**Linked Charts:**


- [lauristt/p22_golez_koudijs_2025:chart/sector_comparison](../../charts/lauristt--p22_golez_koudijs_2025.sector_comparison.md)



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

