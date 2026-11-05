## Aaron Gómez

**Statistician and data scientist** · Mathematics, UNAM · Mexico City

I build statistical models that other people can check and rely on: explicit assumptions, honest uncertainty, and code anyone can rerun. My work spans clinical trials, observational health studies, national surveys and government administrative data.

### What I work on

- Bayesian longitudinal models (Stan) and clinical-trial data for a clinical-epidemiology consultancy.
- Statistical analysis for clinical research at Hospital Infantil de México Federico Gómez.
- Earlier: classification models for Mexico's working population (STPS) and pipelines for national household surveys (INEGI).
- Teaching assistant in 13 courses at UNAM's Facultad de Ciencias, from multivariate statistics and machine learning to survival analysis.

### Selected work

| Project | Question | Result |
|---|---|---|
| [**Randomised trial: diet during cancer treatment**](https://amaugomez.github.io/cervical-cancer-diet-rct/) · [code](https://github.com/AMauGomez/cervical-cancer-diet-rct) | Does an anti-inflammatory diet beat the standard low-residue diet for women receiving chemoradiotherapy for cervical cancer? (*Frontiers in Nutrition* 2026) | I directed the statistical analysis of the trial: 136 women randomised, attrition handled with intention-to-treat and per-protocol models, multiple imputation (35 datasets) and mixed models. Complete response 70.7% vs 54.8% (RR 1.29, 95% CI 0.92–1.8). |
| [**Quick count and survey estimation**](https://amaugomez.github.io/survey-sampling-mexico/) · [code](https://github.com/AMauGomez/survey-sampling-mexico) | How should 900 polling stations be sampled to estimate a national vote share, using all 163,666 stations of the 2021 election? | Stratifying by district gives a margin of error of ±0.87 points; concentrating the sample in 30 districts, ±3.9. The survey part reproduces INEGI's official housing estimates exactly. |
| [**Imputing counts with excess zeros**](https://amaugomez.github.io/mice-zero-inflated/) · [code](https://github.com/AMauGomez/mice-zero-inflated) | Which imputation model works best for a zero-inflated variable in 583,678 patient records? (BSc thesis) | Zero-inflated Poisson had the lowest error, but only because its imputations were too narrow: it kept about half of the true variance. |
| [**Maternal diet and congenital heart defects**](https://amaugomez.github.io/maternal-bvitamin-chd/) · [code](https://github.com/AMauGomez/maternal-bvitamin-chd) | Is a mother's combined B-vitamin intake associated with complex heart defects in her child? (*Nutrients* 2026) | Each unit of a PCA-based B-vitamin index: adjusted odds ratio 0.707 (95% CI 0.586–0.843). |

### Publications

- Vilchis-Gil J, **Gómez-Jiménez AM**, *et al.* Maternal Dietary B-Complex Vitamin Pattern and Risk of Complex Congenital Heart Defects in a Mexican Population. *Nutrients* 2026; 18(16): 2693. [doi:10.3390/nu18162693](https://doi.org/10.3390/nu18162693)
- Luvián-Morales J, *et al.*, **Gómez-Jiménez AM**, *et al.* Benefits of an anti-inflammatory diet compared to a low-residue diet during concurrent chemoradiation therapy for patients with locally advanced cervical cancer: a randomized clinical trial. *Frontiers in Nutrition* 2026. [doi:10.3389/fnut.2026.1835417](https://doi.org/10.3389/fnut.2026.1835417)

### Methods and tools

**Methods:** generalised linear and mixed models · survival analysis · Bayesian hierarchical models · classification · multiple imputation · survey sampling and complex designs · clinical-trial analysis · meta-analysis<br>
**Tools:** R · Stan · SQL · Python · SAS · Git · Quarto · LaTeX

[LinkedIn](https://www.linkedin.com/in/amaugomezjimenez) · [ORCID](https://orcid.org/0009-0003-1099-0431) · maugomez@ciencias.unam.mx
