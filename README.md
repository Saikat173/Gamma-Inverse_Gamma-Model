# Gamma-Inverse_Gamma-Model
Having prior as Inverse-Gamma distribution and likelihood as Gamma, how to draw samples from Posterior distribution, check convergence, estimator & Credible Interval.
1. For drawing samples, I have used R-stan (you need to install Rtool 4.0 ; for reference: https://cran.r-project.org/bin/windows/Rtools/rtools40.html)
2. Checking convergence:
     a) using R_hat
     b) Trace Plots
     c) Autocorrelogram
     d) Use multiple starting points
3. 95% Credible Interval
4. Histogram of Posterior distribution (How prior belief has shifted(or updated) histogram of likelihood
