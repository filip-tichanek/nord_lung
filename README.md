# lungs

This Repository shows R code and source data used in the publication [***Survival in Lung Cancer in the Nordic Countries Through A Half Century***](https://www.dovepress.com/articles.php?article_id=83415), published in the [Clinical Epidemiology](https://www.dovepress.com/clinical-epidemiology-journal) journal

All data used were downloaded from the [NORDCAN website](https://nordcan.iarc.fr/en). The NORDCAN data include the estimates of 1-year and 5-years survival and their confidence intervals, based on the Pohar Perme estimator. This code utilizes the pre-calculated NORDCAN data (including the pre-calculated confidence intervals) to get continuous survival estimates and estimation of the magnitude of the change (slope) across a continuous timescale. The code also estimates 95% credible intervals for both the survival rate and the magnitude of change. This is done via Generalized Additive Models in the Bayesian framework  with [brms package](https://cran.r-project.org/web/packages/brms/index.html)

Please, cite the original article when using this R code


