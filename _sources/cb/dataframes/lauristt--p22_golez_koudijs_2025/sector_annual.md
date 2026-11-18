# Dataframe: `lauristt/p22_golez_koudijs_2025:sector_annual` - Sector annual


```{raw} html
<p class="cb-freshness">Data updated <time class="cb-relative-time" datetime="2026-11-18T06:34:47+00:00" title="2026-11-18 06:34 UTC">2026-11-18</time></p>
```


Clean complete-year cash portfolio units, real returns, earnings and dividend-price ratios. Individual stock data are not staged. Lineage: raw source caches -> src/p22 cleaning modules -> analysis modules -> publication staging. Raw files and security-level observations are never published.


## DataFrame Glimpse

```
Rows: 2495
Columns: 19
$ industry_id                 <i64> -2, -2, -2, -2, -2
$ industry_name               <str> 'Paper-aligned market', 'Paper-aligned market', 'Paper-aligned market', 'Paper-aligned market', 'Paper-aligned market'
$ portfolio                   <str> 'Above 0.5', 'Above 0.5', 'Above 0.5', 'Above 0.5', 'Above 0.5'
$ year                        <i64> 1970, 1971, 1972, 1973, 1974
$ segment                     <i64> 0, 0, 0, 0, 0
$ price_unit                  <f64> 1.0538166051342155, 1.1678342387577088, 1.316604609883115, 1.12025603387595, 0.8106072276498076
$ effective_distribution_unit <f64> 0.040195264187568726, 0.039939787699135, 0.04422092665651435, 0.04987249875448683, 0.05242335218720883
$ real_price_unit             <f64> 0.0264778041491009, 0.028414458363934518, 0.030978931997249763, 0.024195594684145783, 0.015618636370901882
$ start_price_unit            <f64> 1.0, 1.0538166051342155, 1.1678342387577088, 1.316604609883115, 1.12025603387595
$ real_earnings_unit          <f64> 0.0014979059955431981, 0.0016177534592497819, 0.002030951280850176, 0.002358098694622134, 0.002405179842373822
$ real_distribution_unit      <f64> 0.001009931260994189, 0.000971770990246594, 0.0010404923919179847, 0.00107715980031289, 0.001010083857171654
$ r                           <f64> 0.035644735575973835, 0.104219372555076, 0.119444617861134, -0.20358044283673676, -0.375039244120872
$ dp                          <f64> -3.2664245326319588, -3.375533221966237, -3.3936133055749056, -3.1118428161722322, -2.73843148609306
$ dividend_yield              <f64> 0.0381425610412064, 0.03419987732301908, 0.03358709693447008, 0.044518839663763334, 0.06467170585093324
$ payout_ratio                <f64> 0.621243951198484, 0.621002366740336, 0.634026322271631, 0.620102943144859, 0.613293455323696
$ firm_count                  <i64> 188, 199, 311, 317, 305
$ market_cap_coverage         <f64> 1.0, 1.0, 1.0, 1.0, 1.0
$ accounting_cap_coverage     <f64> 0.996803086837044, 0.9980572904829, 0.999664979091156, 0.9998986457320687, 0.9992032796208935
$ quality_flags               <str> 'cash_dividends;annual_formation;revised_accounting', 'cash_dividends;annual_formation;revised_accounting', 'cash_dividends;annual_formation;revised_accounting', 'cash_dividends;annual_formation;revised_accounting', 'cash_dividends;annual_formation;revised_accounting'


```



## Provenance



What this is, where it is, what made it and from what, as `index.json` records it.

| | |
|--------------------------------|--------------------------------------------------------------------------------------|
| What                           | Dataframe `lauristt/p22_golez_koudijs_2025:sector_annual`, of pipeline `lauristt/p22_golez_koudijs_2025`     |
| Where                          | `_output/publication/sector_annual.csv`                                                                 |
| Content                        | `sha256:532a296489e821c4154b477e026e52edf0add95c8f5aa7a17640417c09954663` · 753,309 bytes · 2,495 rows · 19 columns                                                               |
| Built by                       | `doit` in `lauristt/p22_golez_koudijs_2025`                                 |
| Series                         | 19 columns documented                                             |





## Dataframe Manifest

| Dataframe Name                 | Sector annual                                                          |
|--------------------------------|--------------------------------------------------------------------------------------|
| Dataframe ID                   | [sector_annual](../lauristt--p22_golez_koudijs_2025/sector_annual.md)                                       |
| Sources                        | WRDS CRSP monthly CIZ and cash distributions, WRDS Compustat annual fundamentals, CRSP-Compustat link history, Kenneth French SIC industry mapping, FRED CPIAUCSL                                          |
| Providers                      | Golez and Koudijs, WRDS, Kenneth French, FRED                                        |
| Provider Links                 | https://doi.org/10.17632/fp6fryn7h3.1, https://wrds-www.wharton.upenn.edu/, https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html, https://fred.stlouisfed.org/series/CPIAUCSL                                   |
| Dataframe Path                 | `_output/publication/sector_annual.csv`                                                        |


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
| Linked Dataframes               |  [lauristt/p22_golez_koudijs_2025:baseline_decomposition](../../dataframes/lauristt--p22_golez_koudijs_2025/baseline_decomposition.md)<br>  [lauristt/p22_golez_koudijs_2025:cash_reconciliation](../../dataframes/lauristt--p22_golez_koudijs_2025/cash_reconciliation.md)<br>  [lauristt/p22_golez_koudijs_2025:coverage](../../dataframes/lauristt--p22_golez_koudijs_2025/coverage.md)<br>  [lauristt/p22_golez_koudijs_2025:data_checks](../../dataframes/lauristt--p22_golez_koudijs_2025/data_checks.md)<br>  [lauristt/p22_golez_koudijs_2025:payout_history](../../dataframes/lauristt--p22_golez_koudijs_2025/payout_history.md)<br>  [lauristt/p22_golez_koudijs_2025:portfolio_overlap](../../dataframes/lauristt--p22_golez_koudijs_2025/portfolio_overlap.md)<br>  [lauristt/p22_golez_koudijs_2025:sector_annual](../../dataframes/lauristt--p22_golez_koudijs_2025/sector_annual.md)<br>  [lauristt/p22_golez_koudijs_2025:sector_comparison](../../dataframes/lauristt--p22_golez_koudijs_2025/sector_comparison.md)<br>  [lauristt/p22_golez_koudijs_2025:sector_estimates](../../dataframes/lauristt--p22_golez_koudijs_2025/sector_estimates.md)<br>  [lauristt/p22_golez_koudijs_2025:table_1](../../dataframes/lauristt--p22_golez_koudijs_2025/table_1.md)<br>  [lauristt/p22_golez_koudijs_2025:table_2](../../dataframes/lauristt--p22_golez_koudijs_2025/table_2.md)<br>  [lauristt/p22_golez_koudijs_2025:table_4](../../dataframes/lauristt--p22_golez_koudijs_2025/table_4.md)<br>  [lauristt/p22_golez_koudijs_2025:table_5](../../dataframes/lauristt--p22_golez_koudijs_2025/table_5.md)<br>  [lauristt/p22_golez_koudijs_2025:table_6](../../dataframes/lauristt--p22_golez_koudijs_2025/table_6.md)<br>  [lauristt/p22_golez_koudijs_2025:table_7](../../dataframes/lauristt--p22_golez_koudijs_2025/table_7.md)<br>  [lauristt/p22_golez_koudijs_2025:updated_decomposition](../../dataframes/lauristt--p22_golez_koudijs_2025/updated_decomposition.md)<br>  [lauristt/p22_golez_koudijs_2025:updated_payout_history](../../dataframes/lauristt--p22_golez_koudijs_2025/updated_payout_history.md)<br>  [lauristt/p22_golez_koudijs_2025:updated_table_1](../../dataframes/lauristt--p22_golez_koudijs_2025/updated_table_1.md)<br>  [lauristt/p22_golez_koudijs_2025:updated_table_2](../../dataframes/lauristt--p22_golez_koudijs_2025/updated_table_2.md)<br>  [lauristt/p22_golez_koudijs_2025:updated_table_4](../../dataframes/lauristt--p22_golez_koudijs_2025/updated_table_4.md)<br>  [lauristt/p22_golez_koudijs_2025:updated_table_5](../../dataframes/lauristt--p22_golez_koudijs_2025/updated_table_5.md)<br>  [lauristt/p22_golez_koudijs_2025:updated_table_6](../../dataframes/lauristt--p22_golez_koudijs_2025/updated_table_6.md)<br>  [lauristt/p22_golez_koudijs_2025:updated_table_7](../../dataframes/lauristt--p22_golez_koudijs_2025/updated_table_7.md)<br>  |


**Build Commands:**
```
doit
```

