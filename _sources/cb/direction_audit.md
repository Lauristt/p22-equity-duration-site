# Why the first Sector ER Tracker reversed the paper's direction

Investigation date: November 18, 2026. This audit does not change the production configuration or the displayed sector results.

## Finding

The prototype was not a like-for-like stock-level replication. Its most consequential tested mismatch was admitting firms with zero dividends in their trailing history. Requiring positive common dividends in each of the ten preceding fiscal observations, while leaving the other construction choices unchanged, restores the direction in the market-wide median comparison. That does not establish a statistically reliable effect or complete the stock-level replication.

The original Table 7 replication using the authors' supplied portfolios already reproduces their direction: ER is 1.0408 for the low tercile and 0.5409 for the high tercile. Those are different inputs from the new WRDS portfolio construction.

## Controlled results

All rows below use the same outcome years, 1975–2025, monthly portfolio construction, effective-distribution proxy, and scalar ER estimator. The screens use Compustat common dividends over consecutive fiscal years with the prototype's existing availability lag. This approximates, but does not exactly reproduce, the paper's calendar-year CRSP dividend screen.

| Construction | Low ER | High ER | Low minus high |
| --- | ---: | ---: | ---: |
| Original prototype: nonpayers allowed, median split | 0.349 | 0.750 | -0.401 |
| Positive dividends in all ten fiscal years, median split | 0.740 | 0.663 | +0.077 |
| Positive dividends in all ten fiscal years, bottom/top terciles | 0.602 | 0.595 | +0.007 |

The corrected median difference has a paired block-bootstrap 95% interval of [-0.417, 1.287]; the corrected tercile interval is [-0.772, 1.001]. Both span zero. In the original low group, firms with no dividends in any of the ten fiscal years account for about 30.1% of market capitalization on average across months in 1975–2025; about 50.9% fails the all-ten-years payer screen. The corresponding high-group failure share is about 5.1%.

Requiring dividends in at least five of the ten fiscal years yields 0.803 versus 0.620 under the median split, but 0.579 versus 0.645 under terciles. This is sensitivity evidence, not grounds to select whichever specification produces the preferred direction.

## Explanations tested

1. **Sign or regression coding error:** not supported by the checks. Applying the sector estimator to the authors' supplied portfolios preserves their positive low-minus-high ordering. Its rho uses predictor dates, whereas the authors use all level dates; this changes the full-sample low estimate by about 0.0014, not its direction. The baseline replication separately matches the authors' convention.
2. **Shorter historical sample:** weakens the paper's pattern, but does not reverse it in the authors' portfolios. Using 1975–2022 outcomes with our rho convention gives low/high ER of 0.610/0.502, a +0.108 difference. Their full 1946–2022 regression sample gives approximately +0.499.
3. **Adding 2023–2025:** does not explain the original reversal. Our unscreened median portfolios already give 0.393/0.765, a -0.373 difference, over 1975–2022.
4. **Dividend-paying history:** sufficient to reverse the market-wide median ordering in the controlled test above. The paper's Section 3.4.2 and footnote 20 explicitly explain why a low-payout portfolio dominated by nonpayers is problematic: a few dividend initiations or changes can dominate the dividend-price ratio and growth series. Low payout among established dividend payers is a different comparison from nonpayers versus mature dividend payers.
5. **Median versus tercile sorting:** matters substantially once the payer screen is applied. Matching the paper's relative-sort cutoffs leaves a much smaller positive effect in this later sample.

## Remaining differences and limits

The paper rebalances annually; the prototype re-sorts and rebalances monthly. Its monthly CIZ return difference is an effective distribution rather than validated cash dividends. Our accounting source, conservative fiscal reporting lag, issuer treatment, restricted common-share universe and negative-earnings exclusion are not an exact reconstruction of the authors' stock-level procedure. The paper assigns negative cumulative earners to high payout; it also reports that excluding them barely changes its own results. These remaining differences have not been individually isolated here.

The package's Table_6_7_Cross_Section.m starts with already constructed annual portfolios; it does not supply the underlying stock sorting routine. Matching its regressions is therefore not proof of matching its stock-level construction.

No corrected industry-neutral claim follows from this audit: the controlled reruns concern market-wide portfolios. The existing industry-neutral table remains based on the broader prototype universe. The earlier suggestion that its narrowing demonstrates an industry-composition explanation was premature; its underlying market-wide comparison first needs a paper-compatible benchmark.

## Recommended next step

Build an explicit paper-aligned stock-level benchmark: established dividend payers, annual formation, terciles and absolute 0.5 sorts, documented real dividend/earnings units, and cash-distribution reconciliation. First compare it against the authors' portfolios through 2022. Then extend through 2025 and add within-industry sorts on the same eligible universe. Retain the broader nonpayer universe as a separately labeled robustness experiment. Do not tune thresholds to recover the desired sign.

## Reproduction and evidence

Run `PYTHONPATH=src uv run python -m p22.sector.investigate` from the repository root after the baseline and sector data are cached. The audit does not download or edit inputs. It produces `benchmark.csv`, six annual variant panels and an eligible stock-month diagnostic cache under OUTPUT_DIR/sector_investigation (normally `_output/sector_investigation`), all excluded from Git.

Sources inspected: the local published paper, Section 3.4.2, footnotes 20–21 and Table 6 notes (printed pages 8–10); the authors' `Table_6_7_Cross_Section.m` and `Portfolios_Cross_Section.xlsx`; and this repository's sector construction and estimation modules. No paper screenshots or restricted observations are committed.
