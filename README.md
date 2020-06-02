主要目標：找R package: Sample Size Calculation for GEE Model

 202005搜尋結果：沒有找到任何R package for GEE

次要目標：找R package: Sample Size Calculation

| Package | Function | Description |
| --- | --- | --- |
|



pwr | cohen.ES() | Conventional effects size |
| ES.h() | Effect size calculation for proportions |
| ES.w1(P0, P1) | Effect size calculation in the chi-squared test for goodness of fit |
| ES.w2(P) | Effect size calculation in the chi-squared test for association |
| pwr.2p.test() | Power calculation for two proportions (same sample sizes) |
| pwr.2p2n.test() | Power calculation for two proportions (different sample sizes) |
| pwr.anova.test() | Power calculations for balanced one-way analysis of variance tests |
| pwr.chisq.test() | power calculations for chi-squared tests |
| pwr.f2.test() | Power calculations for the general linear model |
| pwr.norm.test() | Power calculations for the mean of a normal distribution (known variance) |
| pwr.p.test() | Power calculations for proportion tests (one sample) |
| pwr.r.test() | Power calculations for correlation test |
| pwr.t.test() | Power calculations for t-tests of means (one sample, two samples and paired samples) |
| pwr.t2n.test() | Power calculations for two samples (different sizes) t-tests of means |
| samplesizeCMH | Calculates the power and sample size for Cochran-Mantel-Haenszel tests. There are also several helper functions for working with probability, odds, relative risk, and odds ratio values. |
| simr | Power Analysis for Generalised Linear Mixed Models by Simulation |
| longpower | 目前僅可計算GLMM的sample size (two level model) |
| samplesize | Sample Size Calculation for Various t-Tests and Wilcoxon-Test |
|
clusterPower | Calculate power for cluster randomized trials (CRTs) that compare two means, two proportions, or two counts using closed-form solutions. In addition, calculate power for cluster randomized crossover trials using Monte Carlo methods. For more information, see Reich et al. (2012) |
| NPHMC | Sample Size Calculation for the Proportional Hazards Mixture Cure Model |
| binomSamSize | Confidence Intervals and Sample Size Determination for a Binomial Proportion under Simple Random Sampling and Pooled Sampling |

1. longpowerpackage當中lmmpower function可計算GEE sample size－two level model

[https://cran.r-project.org/web/packages/longpower/longpower.pdf](https://cran.r-project.org/web/packages/longpower/longpower.pdf)

1. GEE Calculator Shiny App – Paired Data (Twins)

[https://djprice.shinyapps.io/gee\_calculator/](https://djprice.shinyapps.io/gee_calculator/)

1. 2018\_Li\_Sample size Determination for GEE Analyses of Stepped Wedge Cluster Randomized Trial (有提供R Code及Supplementary)

[https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6461045/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6461045/)

1. Simr package的powercurve function 可計算Generalized Linear Mixed Models 中 sample size

[https://cran.r-project.org/web/packages/simr/simr.pdf](https://cran.r-project.org/web/packages/simr/simr.pdf)

1. Package samplesize [(有提供Example Code與 參數說明)](https://cran.r-project.org/web/packages/samplesize/samplesize.pdf)

- Abstract：Computes sample size for Student&#39;s t-test and for the Wilcoxon-MannWhitney test for categorical data. The t-test function allows paired and unpaired (balanced / unbalanced) designs as well as homogeneous and heterogeneous variances. The Wilcoxon function allows for ties.

1. Package pwr[(有提供Example Code與 參數說明)](https://cran.r-project.org/web/packages/pwr/pwr.pdf)

[(來源2)](https://cran.r-project.org/web/packages/pwr/vignettes/pwr-vignette.html)

- Abstract：The basic idea of calculating power or sample size with functions in the pwr package is to _leave out_ the argument that you want to calculate. If you want to calculate power, then leave the power argument out of the function. If you want to calculate sample size, leave n out of the function. Whatever parameter you want to calculate is determined from the others.You select a function based on the statistical test you plan to use to analyze your data. If you plan to use a two-sample t-test to compare two means, you would use the pwr.t.test function for estimating sample size or power. All functions for power and sample size analysis in the pwr package begin with pwr. Functions are available for the following statistical tests:
- 支援這些檢定的計算樣本數:

![](RackMultipart20200602-4-1corexm_html_b1585a6f740d405.png)

1. Package NPHMC [(Example Code與參數說明)](https://cran.r-project.org/web/packages/NPHMC/NPHMC.pdf)

- Abstract：calculating sample size of a survival trial with or without cure fractions

1. Package samplesizeCMH[(Example Code 與 參數說明)](https://cran.r-project.org/web/packages/samplesizeCMH/samplesizeCMH.pdf)

- Abstract：Sample Size Calculation for the Cochran-Mantel-Haenszel Test

1. Package binomSamSize[(Example Code 與 參數說明)](https://cran.r-project.org/web/packages/binomSamSize/binomSamSize.pdf)

- Abstract：Confidence Intervals and Sample Size Determination for a Binomial Proportion under Simple Random Sampling and Pooled Sampling
