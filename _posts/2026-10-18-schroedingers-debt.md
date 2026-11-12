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
When Erwin Schroedinger studied Physics at the early 20th century in
Vienna, tuition fees, or what at the time was known as “Kollegiengeld”,
for what would be the equivalent of today’s integrated master’s degree
amounted to around 3’000 EUR - 5’000 EUR (inflation adjusted). Despite
the Habsburg empire already nearing the later stages of its
decline, public finances still stretched far enough to make higher
education accessible. Unfortunately, the same cannot be said for the UK.

Had he been born between 1994 and 2003 in
England, he would not been privy to the same privileges and most likely
would have been forced to become a recipient of the UK government’s Plan
2 student loan.

Upon completion of his studies he would have found himself in a similar
situation to many graduates in England and Wales confronted with the
deceptively simple question: should he pay off the loan as quickly as
possible, or pay the minimum in accordance with his Plan 2 agreement?

The answer to this question depends on the loan structure. Plan 2
graduates repay 9% of earnings above a threshold (£29’385 for 2026/27,
frozen for three years from April 2027), pay interest that runs from RPI
up to RPI+3 percentage points depending on income (capped at 6% for
2026/27), and have whatever remains cancelled 30 years after they are
first due to repay.

The final point is what makes the question challenging: If you earn
little, you never payoff the debt in its entirety, and the outstanding
debt is written-off by the end of the term, incentivising minimum loan
payments; if on the other hand you earn more, you might end up payoff
the loan in it’s entirety before the end of the 30 year deadline, making
it worthwhile to make payments quickly to avoid high interest costs. But where
is the threshold where this regime switch kicks in, and how might you
end up paying if you have the capital to make advance payments?

This article aims to answer these questions with a collection of (hopefully) illustrative
plots. Given the uncertainty underlying future events, it aims to answer this question doing a stochastic (random) simulation of
the factors influencing the loans structure (income trajectories over
30y, RPI, living expenses, inflation, UK-tax bands, savings
incl. capital gains).

PLEASE NOTE: This article is still work in progress.

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

| Indicator             |   Baseline | Sensitivity | per +1pp rho | per +1 yr T | per +5,000 I0 | per +10,000 down | per +0.5pp sav_rate | elast theta0 | elast rho0 | elast T | elast I0 | elast sav |
|:----------------------|-----------:|------------:|-------------:|------------:|--------------:|-----------------:|--------------------:|-------------:|-----------:|--------:|---------:|----------:|
| mean_real_payments    |  92026.419 |      70.976 |     -241.093 |       0.000 |     -1064.766 |        -4038.223 |                   0 |        0.022 |     -0.024 |   0.000 |   -0.150 |     0.000 |
| p05_real_payments     |  87546.309 |      59.365 |     -197.988 |       0.000 |      -877.620 |        -3127.332 |                   0 |        0.020 |     -0.020 |   0.000 |   -0.130 |     0.000 |
| p50_real_payments     |  92012.189 |      71.561 |     -239.077 |       0.000 |     -1051.829 |        -4006.852 |                   0 |        0.023 |     -0.023 |   0.000 |   -0.149 |     0.000 |
| p95_real_payments     |  96442.619 |      93.393 |     -281.276 |       0.000 |     -1275.965 |        -5032.544 |                   0 |        0.028 |     -0.026 |   0.000 |   -0.172 |     0.000 |
| mean_payment_share    |      0.042 |       0.000 |        0.000 |      -0.002 |        -0.004 |           -0.002 |                   0 |        0.023 |     -0.024 |  -1.312 |   -1.158 |     0.000 |
| prob_repaid           |      1.000 |       0.000 |        0.000 |       0.000 |         0.000 |            0.000 |                   0 |        0.000 |      0.000 |   0.000 |    0.000 |     0.000 |
| mean_payoff_year      |     11.533 |       0.041 |       -0.154 |       0.000 |        -0.660 |           -1.396 |                   0 |        0.103 |     -0.120 |   0.000 |   -0.744 |     0.000 |
| mean_real_writeoff    |      0.000 |       0.000 |        0.000 |       0.000 |         0.000 |            0.000 |                   0 |           NA |         NA |      NA |       NA |        NA |
| mean_real_end_savings | 332805.586 |     -61.154 |      207.522 |   18962.129 |     20765.681 |         3585.646 |               18619 |       -0.005 |      0.006 |   1.709 |    0.811 |     0.448 |
| prob_shortfall        |      0.000 |       0.000 |        0.000 |       0.000 |         0.000 |            0.000 |                   0 |           NA |         NA |      NA |       NA |        NA |

<!--
Render with:
rmarkdown::render("The_SD_Dilemma_git2.0.Rmd",
  output_file = path.expand("~/dev/actuarly/Actuarly.github.io/_posts/2026-10-18-schroedingers-debt.md"))
-->
