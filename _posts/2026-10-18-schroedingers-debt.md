---
title: "Schroedinger's Debt"
date: 2026-10-18
permalink: /posts/2026/10/schroedingers-debt/
tags: [Student Debt, UK, Plan 2, Debt repayment]
output:
  md_document:
    variant: gfm
    preserve_yaml: true
---

## Intro

Your introduction here…

<figure>
<img
src="../../../../../../../../../../../assets/images/schroedingers-debt/parameters.png"
alt="Figure 1: An overview of the exogenous parameters used in the model." />
<figcaption aria-hidden="true"><strong>Figure 1</strong>: An overview of
the exogenous parameters used in the model.</figcaption>
</figure>

<figure>
<img
src="../../../../../../../../../../../assets/images/schroedingers-debt/pay_vs_inc_linear.png"
alt="Figure 2: Average annual gross income vs. total loan payments for the minimal repayment (blue) and the min + voluntary repayment scheme (orange) in real terms. When repaying smartly, higher earners can benefit from significant discounts on total loan cost." />
<figcaption aria-hidden="true"><strong>Figure 2</strong>: Average annual
gross income vs. total loan payments for the minimal repayment (blue)
and the min + voluntary repayment scheme (orange) in real terms. When
repaying smartly, higher earners can benefit from significant discounts
on total loan cost.</figcaption>
</figure>

<figure>
<img
src="../../../../../../../../../../../assets/images/schroedingers-debt/cost_by_payoff_year.png"
alt="Figure 3: Year of total repayment vs. total loan payments for the minimal repayment scheme, coloured by mean real salary in real terms. While lower earners benefit from the loan writeoffs, middle income earners make the highest interest payments over the life-time of the loan. High earners benefit by paying off the loan more quickly." />
<figcaption aria-hidden="true"><strong>Figure 3</strong>: Year of total
repayment vs. total loan payments for the minimal repayment scheme,
coloured by mean real salary in real terms. While lower earners benefit
from the loan writeoffs, middle income earners make the highest interest
payments over the life-time of the loan. High earners benefit by paying
off the loan more quickly.</figcaption>
</figure>

<figure>
<img
src="../../../../../../../../../../../assets/images/schroedingers-debt/cost_by_payoff_year_vol.png"
alt="Figure 4: Year of total repayment vs. total loan payments for the minimal + voluntary repayment scheme, coloured by mean real salary in real terms. Voluntary payments significantly lower the loan time until repayment, reducing accumulated interest and loan cost. Alpha = 0.67" />
<figcaption aria-hidden="true"><strong>Figure 4</strong>: Year of total
repayment vs. total loan payments for the minimal + voluntary repayment
scheme, coloured by mean real salary in real terms. Voluntary payments
significantly lower the loan time until repayment, reducing accumulated
interest and loan cost. Alpha = 0.67</figcaption>
</figure>

<div class="figure" style="text-align: center">

<img src="../../../../../../../../../../../assets/images/schroedingers-debt/cashflow_summary.png" alt="Cash-flow summary: (a) minimal loan repayment; (b) minimal + voluntary loan repayment. Alpha = 0.67" width="90%" /><img src="../../../../../../../../../../../assets/images/schroedingers-debt/cashflow_summary_vol.png" alt="Cash-flow summary: (a) minimal loan repayment; (b) minimal + voluntary loan repayment. Alpha = 0.67" width="90%" />
<p class="caption">
Cash-flow summary: (a) minimal loan repayment; (b) minimal + voluntary
loan repayment. Alpha = 0.67
</p>

</div>

<div class="figure" style="text-align: center">

<img src="../../../../../../../../../../../assets/images/schroedingers-debt/results.png" alt="Loan cost development and total distribution: (a) minimal loan repayment; (b) minimal + voluntary loan repayment. Alpha = 0.67" width="49%" /><img src="../../../../../../../../../../../assets/images/schroedingers-debt/results_vol.png" alt="Loan cost development and total distribution: (a) minimal loan repayment; (b) minimal + voluntary loan repayment. Alpha = 0.67" width="49%" />
<p class="caption">
Loan cost development and total distribution: (a) minimal loan
repayment; (b) minimal + voluntary loan repayment. Alpha = 0.67
</p>

</div>

<div class="figure" style="text-align: center">

<img src="../../../../../../../../../../../assets/images/schroedingers-debt/alpha_facets.png" alt="Total real loan cost over different values of alpha. Alpha is the proportion of savings used for voluntary payments in addition to the minimum." width="60%" />
<p class="caption">
Total real loan cost over different values of alpha. Alpha is the
proportion of savings used for voluntary payments in addition to the
minimum.
</p>

</div>

<div class="figure" style="text-align: center">

<img src="../../../../../../../../../../../assets/images/schroedingers-debt/income_allocation.png" alt="Expected yearly income allocation: (a) minimal loan repayment; (b) minimal + voluntary loan repayment. Alpha = 0.67" width="49%" /><img src="../../../../../../../../../../../assets/images/schroedingers-debt/income_allocation_vol.png" alt="Expected yearly income allocation: (a) minimal loan repayment; (b) minimal + voluntary loan repayment. Alpha = 0.67" width="49%" />
<p class="caption">
Expected yearly income allocation: (a) minimal loan repayment; (b)
minimal + voluntary loan repayment. Alpha = 0.67
</p>

</div>

<div class="figure" style="text-align: center">

<img src="../../../../../../../../../../../assets/images/schroedingers-debt/savings.png" alt="Expected real savings: (a) minimal loan repayment; (b) minimal + voluntary loan repayment. Alpha = 0.67" width="49%" /><img src="../../../../../../../../../../../assets/images/schroedingers-debt/savings_vol.png" alt="Expected real savings: (a) minimal loan repayment; (b) minimal + voluntary loan repayment. Alpha = 0.67" width="49%" />
<p class="caption">
Expected real savings: (a) minimal loan repayment; (b) minimal +
voluntary loan repayment. Alpha = 0.67
</p>

</div>

### Sensitivity analysis

<div class="figure" style="text-align: center">

<img src="../../../../../../../../../../../assets/images/schroedingers-debt/sensitivity_by_alpha.png" alt="Sensitivity of the results to the model parameters, by alpha." width="99%" />
<p class="caption">
Sensitivity of the results to the model parameters, by alpha.
</p>

</div>

**Table 1**: Local sensitivity analysis (α = 0.67)

| Indicator             |   Baseline | Sensitivity | per +1pp rho | per +1 yr T | per +5,000 I0 | per +10,000 down | per +0.5pp sav_rate | elast theta0 | elast rho0 | elast T | elast I0 | elast down | elast sav |
|:----------------------|-----------:|------------:|-------------:|------------:|--------------:|-----------------:|--------------------:|-------------:|-----------:|--------:|---------:|-----------:|----------:|
| mean_real_payments    |  89571.057 |      58.565 |     -200.280 |       0.000 |      -907.552 |        -1888.853 |                0.00 |        0.019 |     -0.020 |   0.000 |   -0.133 |     -0.011 |     0.000 |
| p05_real_payments     |  85699.975 |      50.848 |     -168.567 |       0.000 |      -756.290 |        -1478.175 |                0.00 |        0.017 |     -0.018 |   0.000 |   -0.116 |     -0.009 |     0.000 |
| p50_real_payments     |  89598.994 |      59.515 |     -201.313 |       0.000 |      -909.747 |        -1890.605 |                0.00 |        0.019 |     -0.020 |   0.000 |   -0.133 |     -0.011 |     0.000 |
| p95_real_payments     |  93266.750 |      66.770 |     -235.965 |       0.000 |     -1068.351 |        -2325.485 |                0.00 |        0.021 |     -0.023 |   0.000 |   -0.150 |     -0.012 |     0.000 |
| mean_payment_share    |      0.040 |       0.000 |        0.000 |      -0.002 |        -0.003 |           -0.001 |                0.00 |        0.019 |     -0.020 |  -1.316 |   -1.140 |     -0.011 |     0.000 |
| prob_repaid           |      1.000 |       0.000 |        0.000 |       0.000 |         0.000 |            0.000 |                0.00 |        0.000 |      0.000 |   0.000 |    0.000 |      0.000 |     0.000 |
| mean_payoff_year      |     10.588 |       0.038 |       -0.135 |       0.000 |        -0.604 |           -0.663 |                0.00 |        0.104 |     -0.115 |   0.000 |   -0.747 |     -0.031 |     0.000 |
| mean_real_writeoff    |      0.000 |       0.000 |        0.000 |       0.000 |         0.000 |            0.000 |                0.00 |           NA |         NA |      NA |       NA |         NA |        NA |
| mean_real_end_savings | 343331.653 |     -50.863 |      173.661 |   19264.497 |     20903.970 |         1684.267 |            19064.24 |       -0.004 |      0.005 |   1.683 |    0.798 |      0.002 |     0.444 |
| prob_shortfall        |      0.000 |       0.000 |        0.000 |       0.000 |         0.000 |            0.000 |                0.00 |           NA |         NA |      NA |       NA |         NA |        NA |

<!--
Render with:
rmarkdown::render("The_SD_Dilemma.Rmd",
  output_file = file.path(repo, "_posts", "2026-10-18-schroedingers-debt.md"))
-->
