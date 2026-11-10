## Aaron Gómez

**Statistician & data scientist · credit risk and statistical modeling** · Mathematics, UNAM · Mexico City

I build statistical models that other people can check and rely on: explicit assumptions, honest uncertainty, and code anyone can rerun. My recent projects are in credit risk and loan pricing (survival models for default, out-of-time validation, portfolio loss simulation against the Basel formula); my paid work and publications are in clinical trials, health data and national surveys.

### What I work on

- **Statistical consultant** (part-time, remote) for a Canada-based clinical-epidemiology research team: I fit and validate Bayesian longitudinal models in Stan on individual-patient trial data (convergence diagnostics, cross-validated model comparison), build R pipelines that turn 12 years (2010–2021) of Mexican health-system administrative records into analysis-ready panel data, and estimate national prevalences from ENSANUT under its complex survey design.
- **Collaborating statistician** for clinical research at Hospital Infantil de México Federico Gómez (co-author, *Nutrients* 2026).
- Earlier, **statistics intern** in INEGI's research directorate: weighted estimation on national household and employment microdata (ENIGH, ENOE), and a job-quality index for the Ministry of Labour (STPS) built as a latent variable with principal components, complemented with regression and cluster analysis.
- Teaching assistant in 13 courses at UNAM's Facultad de Ciencias, from multivariate statistics and machine learning to survival analysis. I teach Statistical Inference and Regression around real-data case studies ([pedestrian crashes](https://amaugomez.github.io/cdmx-pedestrian-crashes/), [mortgage pricing](https://amaugomez.github.io/mortgage-pricing-regression/)).

### Selected work

| Project | Question | Result |
|---|---|---|
| [**Mortgage credit risk**](https://amaugomez.github.io/mortgage-credit-risk/) · [code](https://github.com/AMauGomez/mortgage-credit-risk) | Why did 2006 mortgages default almost six times more than 2017 ones? 100,000 Freddie Mac loans followed for up to 20 years (Python, SQL). | About 86% of the gap is the economy, not the borrowers. Competing-risks survival (naive Kaplan-Meier nearly doubles the default probability), a Cox model validated out of time (ranking transfers, calibration does not), and a Monte Carlo of portfolio losses that matches the Basel capital formula, with importance sampling and MCMC. |
| [**Do mortgage brokers charge more?**](https://amaugomez.github.io/mortgage-pricing-regression/) · [code](https://github.com/AMauGomez/mortgage-pricing-regression) | What sets the rate on a US mortgage? 46,190 loans originated in 2024. | Not the channel: brokers −0.5 bp vs retail (95% CI −1.9 to +0.9) for the same risk, while a FICO of 660–679 costs +23 bp. Nonparametric tests, regression diagnostics, ANCOVA and MANCOVA show brokers write larger, higher-LTV loans at the same rate; a raw comparison gets the correspondent gap backwards. |
| [**Randomised trial: diet during cancer treatment**](https://amaugomez.github.io/cervical-cancer-diet-rct/) · [code](https://github.com/AMauGomez/cervical-cancer-diet-rct) | Does an anti-inflammatory diet beat the standard low-residue diet for women receiving chemoradiotherapy for cervical cancer? (*Frontiers in Nutrition* 2026) | I directed the statistical analysis of the trial: 136 women randomised, attrition handled with intention-to-treat and per-protocol models, multiple imputation (35 datasets) and mixed models. Complete response 70.7% vs 54.8% (RR 1.29, 95% CI 0.92–1.8). |
| [**Pedestrian crashes in Mexico City**](https://amaugomez.github.io/cdmx-pedestrian-crashes/) · [code](https://github.com/AMauGomez/cdmx-pedestrian-crashes) | Is someone hit by a car every 30 minutes at rush hour? Tested with two years of emergency-call records (C5). | Every 36.6 minutes (95% CI 34.6–38.8): the claim overstates the frequency by about 22%. Getting there meant catching three data traps: a window bias that passed every diagnostic, crashes confirmed twice, and seasonal heterogeneity. A negative binomial frequency GLM with exposure is then validated out of sample. |
| [**Quick count and survey estimation**](https://amaugomez.github.io/survey-sampling-mexico/) · [code](https://github.com/AMauGomez/survey-sampling-mexico) | How should 900 polling stations be sampled to estimate a national vote share, using all 163,666 stations of the 2021 election? | Stratifying by district gives a margin of error of ±0.87 points; concentrating the sample in 30 districts, ±3.9. The survey part reproduces INEGI's official housing estimates exactly. |
| [**Imputing counts with excess zeros**](https://amaugomez.github.io/mice-zero-inflated/) · [code](https://github.com/AMauGomez/mice-zero-inflated) | Which imputation model works best for a zero-inflated variable in 583,678 patient records? (BSc thesis) | Zero-inflated Poisson had the lowest error, but only because its imputations were too narrow: it kept about half of the true variance. |
| [**Maternal diet and congenital heart defects**](https://amaugomez.github.io/maternal-bvitamin-chd/) · [code](https://github.com/AMauGomez/maternal-bvitamin-chd) | Is a mother's combined B-vitamin intake associated with complex heart defects in her child? (*Nutrients* 2026) | Each unit of a PCA-based B-vitamin index: adjusted odds ratio 0.707 (95% CI 0.586–0.843). |

### Publications

- Vilchis-Gil J, **Gómez-Jiménez AM**, *et al.* Maternal Dietary B-Complex Vitamin Pattern and Risk of Complex Congenital Heart Defects in a Mexican Population. *Nutrients* 2026; 18(16): 2693. [doi:10.3390/nu18162693](https://doi.org/10.3390/nu18162693)
- Luvián-Morales J, *et al.*, **Gómez-Jiménez AM**, *et al.* Benefits of an anti-inflammatory diet compared to a low-residue diet during concurrent chemoradiation therapy for patients with locally advanced cervical cancer: a randomized clinical trial. *Frontiers in Nutrition* 2026. [doi:10.3389/fnut.2026.1835417](https://doi.org/10.3389/fnut.2026.1835417)

### Methods and tools

**Methods:** credit risk (PD, competing risks, Cox models with out-of-time validation, Vasicek/Basel portfolio loss simulation) · generalised linear models, including frequency models with exposure · ANOVA/ANCOVA/MANCOVA · survival analysis · Bayesian models and MCMC · multiple imputation · survey sampling and complex designs · clinical-trial analysis · meta-analysis · machine learning (PCA, k-means and hierarchical clustering, discriminant analysis, SVM, k-NN)<br>
**Tools:** R · Python · SQL · Stan · Git · Quarto · LaTeX

[LinkedIn](https://www.linkedin.com/in/amaugomezjimenez) · [ORCID](https://orcid.org/0009-0003-1099-0431) · maugomez@ciencias.unam.mx
