# bayesplot 1.0.0.9000

(GitHub issue/PR numbers in parentheses)

* Introduce `mcmc_recover_intervals` for comparing MCMC estimates to "true"
parameter values used to simulate the data. (#56)
* Add argument `divergences` to `mcmc_trace` function. For models fit using
HMC/NUTS this can be used to display divergences as a rug at the bottom of the
trace plot. (#42)
* Introduce `bayesplot_grid` function for juxtaposing plots and enforcing shared axis limits (#59)
* The `stat` argument for all `ppc_stat_*` functions now accepts a function
instead of only the name of a function. (#31)
* `xaxis_title(FALSE)` and `yaxis_title(FALSE)` now set axis titles to `NULL` 
rather than changing theme elements to element_blank. This makes it easier to 
add axis titles to plots that don’t have them by default. (#53)
* Images in vignettes should now render properly. Thanks to TJ Mahr. (#51)

# bayesplot 1.0.0

* Initial CRAN release