# Awesome Biostatistics [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome biostatistics resources, tools, and libraries for clinical trials, epidemiology, survival analysis, and statistical methods in medical research.

Biostatistics applies statistical methods to medical and biological research, with applications in clinical trials, epidemiology, public health, genomics, and pharmaceutical development.

## Contents

- [Clinical Trial Design & Analysis](#clinical-trial-design--analysis)
- [Survival Analysis](#survival-analysis)
- [Meta-Analysis](#meta-analysis)
- [Epidemiological Methods](#epidemiological-methods)
- [Statistical Software Packages](#statistical-software-packages)
- [Longitudinal Data Analysis](#longitudinal-data-analysis)
- [Sample Size & Power Analysis](#sample-size--power-analysis)
- [Causal Inference](#causal-inference)
- [Missing Data Methods](#missing-data-methods)
- [Bayesian Biostatistics](#bayesian-biostatistics)
- [Regulatory & Guidelines](#regulatory--guidelines)
- [Reproducible Research](#reproducible-research)
- [Learning Resources](#learning-resources)
- [Journals & Publications](#journals--publications)
- [Community & Organizations](#community--organizations)
- [Contribute](#contribute)

## Clinical Trial Design & Analysis

Tools and resources for designing and analyzing randomized controlled trials.

- [blockrand](https://CRAN.R-project.org/package=blockrand) - R package for generating randomization lists for block random clinical trials.
- [clinfun](https://CRAN.R-project.org/package=clinfun) - Clinical trial design and data analysis functions including Simon's two-stage design.
- [gsDesign](https://CRAN.R-project.org/package=gsDesign) - Group sequential clinical trial design and analysis.
- [rpact](https://CRAN.R-project.org/package=rpact) - Confirmatory adaptive clinical trial design and analysis.
- [TrialSize](https://CRAN.R-project.org/package=TrialSize) - R functions for sample size estimation in clinical trials.
- [nQuery](https://www.statsols.com/nquery) - Sample size and power calculation software for clinical trials.
- [PASS](https://www.ncss.com/software/pass/) - Power analysis and sample size software with 1000+ procedures.
- [East](https://www.cytel.com/products/east) - Software for adaptive and group sequential clinical trial designs.

## Survival Analysis

Methods and tools for time-to-event data analysis.

- [survival](https://CRAN.R-project.org/package=survival) - Core R package for survival analysis including Cox models and Kaplan-Meier curves.
- [survminer](https://CRAN.R-project.org/package=survminer) - Visualization of survival analysis results with ggplot2.
- [cmprsk](https://CRAN.R-project.org/package=cmprsk) - Competing risks regression models and cumulative incidence functions.
- [flexsurv](https://CRAN.R-project.org/package=flexsurv) - Flexible parametric survival and multi-state models.
- [coxme](https://CRAN.R-project.org/package=coxme) - Mixed effects Cox proportional hazards models.
- [survRM2](https://CRAN.R-project.org/package=survRM2) - Restricted mean survival time analysis for comparing survival curves.
- [lifelines](https://lifelines.readthedocs.io/) - Python library for survival analysis including Cox models and AFT models.
- [Survival Software](http://www.survival-analysis.com/) - Collection of survival analysis programs and resources.

## Meta-Analysis

Tools for systematic review and meta-analysis of clinical studies.

- [meta](https://CRAN.R-project.org/package=meta) - General package for fixed and random effects meta-analysis.
- [metafor](https://CRAN.R-project.org/package=metafor) - Comprehensive meta-analysis package with meta-regression capabilities.
- [netmeta](https://CRAN.R-project.org/package=netmeta) - Network meta-analysis for comparing multiple treatments.
- [MetaStan](https://CRAN.R-project.org/package=MetaStan) - Bayesian meta-analysis using Stan.
- [rmeta](https://CRAN.R-project.org/package=rmeta) - Simple tools for meta-analysis including forest plots.
- [RevMan](https://training.cochrane.org/online-learning/core-software/revman) - Cochrane's Review Manager for systematic reviews and meta-analyses.
- [Comprehensive Meta-Analysis](https://www.meta-analysis.com/) - Commercial software for meta-analysis with extensive graphics.
- [OpenMeta\[Analyst\]](http://www.cebm.brown.edu/openmeta/) - Open-source, cross-platform software for advanced meta-analysis.

## Epidemiological Methods

Statistical methods for observational studies and disease surveillance.

- [Epi](https://CRAN.R-project.org/package=Epi) - Functions for epidemiological data analysis including rates and SMR.
- [epiR](https://CRAN.R-project.org/package=epiR) - Tools for analysis of epidemiological data including screening tests.
- [epitools](https://CRAN.R-project.org/package=epitools) - Epidemiology tools for data and graphics including odds ratios and risk ratios.
- [EpiModel](https://CRAN.R-project.org/package=EpiModel) - Mathematical modeling of infectious disease dynamics.
- [surveillance](https://CRAN.R-project.org/package=surveillance) - Temporal and spatio-temporal modeling and monitoring of epidemic phenomena.
- [EpiEstim](https://CRAN.R-project.org/package=EpiEstim) - Estimate time varying reproduction numbers from epidemic curves.
- [Epi Info](https://www.cdc.gov/epiinfo/) - CDC's public domain statistical software for epidemiology.
- [OpenEpi](https://www.openepi.com/) - Open-source epidemiologic statistics for public health.

## Statistical Software Packages

Core statistical software commonly used in biostatistics.

### R Packages

- [Hmisc](https://CRAN.R-project.org/package=Hmisc) - Frank Harrell's miscellaneous functions for data analysis, high-level graphics, and utility operations.
- [rms](https://CRAN.R-project.org/package=rms) - Regression modeling strategies including validation and calibration.
- [tableone](https://CRAN.R-project.org/package=tableone) - Create "Table 1" to describe baseline characteristics.
- [gtsummary](https://CRAN.R-project.org/package=gtsummary) - Presentation-ready data summary and analytic result tables.
- [finalfit](https://CRAN.R-project.org/package=finalfit) - Quickly create elegant regression results tables and plots.

### Python Libraries

- [statsmodels](https://www.statsmodels.org/) - Statistical modeling and econometrics in Python.
- [scipy.stats](https://docs.scipy.org/doc/scipy/reference/stats.html) - Statistical functions and probability distributions.
- [pingouin](https://pingouin-stats.org/) - Open-source statistical package for Python.
- [biostatspy](https://github.com/PaulC91/biostatspy) - Python tools for biostatistical analysis.

### Commercial Software

- [SAS](https://www.sas.com/) - Industry standard for clinical trials and regulatory submissions.
- [Stata](https://www.stata.com/) - Complete statistical software package widely used in epidemiology.
- [SPSS](https://www.ibm.com/products/spss-statistics) - Statistical package for social sciences with medical applications.

## Longitudinal Data Analysis

Methods for repeated measures and panel data.

- [nlme](https://CRAN.R-project.org/package=nlme) - Linear and nonlinear mixed effects models.
- [lme4](https://CRAN.R-project.org/package=lme4) - Linear, generalized linear, and nonlinear mixed models.
- [gee](https://CRAN.R-project.org/package=gee) - Generalized estimating equations for longitudinal data.
- [geepack](https://CRAN.R-project.org/package=geepack) - Generalized estimating equations package with improved features.
- [mmrm](https://CRAN.R-project.org/package=mmrm) - Mixed models for repeated measures with focus on clinical trials.
- [JMbayes2](https://CRAN.R-project.org/package=JMbayes2) - Joint models for longitudinal and survival data.
- [lcmm](https://CRAN.R-project.org/package=lcmm) - Latent class mixed models for longitudinal data.
- [panelr](https://CRAN.R-project.org/package=panelr) - Panel data analysis in R with various estimators.

## Sample Size & Power Analysis

Tools for study planning and power calculations.

- [pwr](https://CRAN.R-project.org/package=pwr) - Basic functions for power analysis including t-tests, ANOVA, and proportion tests.
- [WebPower](https://CRAN.R-project.org/package=WebPower) - Statistical power analysis for complex designs including mediation and SEM.
- [PowerUpR](https://CRAN.R-project.org/package=PowerUpR) - Power analysis tools for multilevel randomized experiments.
- [longpower](https://CRAN.R-project.org/package=longpower) - Sample size calculations for longitudinal data.
- [clusterPower](https://CRAN.R-project.org/package=clusterPower) - Power calculations for cluster randomized trials.
- [samplesize](https://CRAN.R-project.org/package=samplesize) - Sample size calculation for various study designs.
- [G*Power](https://www.psychologie.hhu.de/arbeitsgruppen/allgemeine-psychologie-und-arbeitspsychologie/gpower) - Free power analysis program with graphical interface.
- [GLIMMPSE](https://glimmpse.samplesizeshop.org/) - Online tool for power and sample size for general linear multivariate models.

## Causal Inference

Methods for estimating causal effects from observational data.

- [MatchIt](https://CRAN.R-project.org/package=MatchIt) - Nonparametric preprocessing for parametric causal inference.
- [WeightIt](https://CRAN.R-project.org/package=WeightIt) - Weighting for covariate balance in observational studies.
- [twang](https://CRAN.R-project.org/package=twang) - Toolkit for weighting and analysis of nonequivalent groups.
- [PSweight](https://CRAN.R-project.org/package=PSweight) - Propensity score weighting for causal inference.
- [CausalImpact](https://CRAN.R-project.org/package=CausalImpact) - Causal inference using Bayesian structural time-series models.
- [dagitty](https://CRAN.R-project.org/package=dagitty) - Graphical analysis of structural causal models using directed acyclic graphs.
- [DoWhy](https://microsoft.github.io/dowhy/) - Python library for causal inference with explicit assumptions.
- [EconML](https://econml.azurewebsites.net/) - Machine learning methods for estimating heterogeneous treatment effects.

## Missing Data Methods

Techniques for handling incomplete data.

- [mice](https://CRAN.R-project.org/package=mice) - Multiple imputation by chained equations.
- [Amelia](https://CRAN.R-project.org/package=Amelia) - Multiple imputation for multivariate missing data.
- [missForest](https://CRAN.R-project.org/package=missForest) - Nonparametric missing value imputation using random forest.
- [VIM](https://CRAN.R-project.org/package=VIM) - Visualization and imputation of missing values.
- [missMethods](https://CRAN.R-project.org/package=missMethods) - Methods for missing data including MCAR tests.
- [naniar](https://CRAN.R-project.org/package=naniar) - Data structures, summaries, and visualizations for missing data.
- [fancyimpute](https://github.com/iskandr/fancyimpute) - Python library for matrix completion and imputation.
- [MissingDataGUI](https://CRAN.R-project.org/package=MissingDataGUI) - GUI for exploring missing data patterns.

## Bayesian Biostatistics

Bayesian methods and software for medical research.

- [brms](https://CRAN.R-project.org/package=brms) - Bayesian regression models using Stan with R formula syntax.
- [rstanarm](https://CRAN.R-project.org/package=rstanarm) - Applied regression modeling via Stan with pre-compiled models.
- [bayesplot](https://CRAN.R-project.org/package=bayesplot) - Plotting for Bayesian models with excellent MCMC diagnostics.
- [BayesFactor](https://CRAN.R-project.org/package=BayesFactor) - Computation of Bayes factors for common designs.
- [bayestestR](https://CRAN.R-project.org/package=bayestestR) - Indices of effect existence and significance in Bayesian models.
- [Stan](https://mc-stan.org/) - Platform for statistical modeling and high-performance statistical computation.
- [JAGS](https://mcmc-jags.sourceforge.io/) - Just Another Gibbs Sampler for Bayesian hierarchical models.
- [WinBUGS](https://www.mrc-bsu.cam.ac.uk/software/bugs/) - Bayesian inference using Gibbs sampling.

## Regulatory & Guidelines

Standards and guidelines for biostatistical analysis.

- [ICH E9](https://www.ich.org/page/efficacy-guidelines) - Statistical principles for clinical trials guideline.
- [FDA Guidance Documents](https://www.fda.gov/regulatory-information/search-fda-guidance-documents) - Statistical guidance for drug and device trials.
- [EMA Guidelines](https://www.ema.europa.eu/en/human-regulatory/research-development/scientific-guidelines/clinical-efficacy-safety/clinical-efficacy-safety-biostatistics) - European Medicines Agency biostatistics guidelines.
- [CDISC Standards](https://www.cdisc.org/standards) - Clinical Data Interchange Standards Consortium data standards.
- [CONSORT Statement](http://www.consort-statement.org/) - Guidelines for reporting randomized trials.
- [STROBE Statement](https://www.strobe-statement.org/) - Guidelines for reporting observational studies in epidemiology.
- [TRIPOD Statement](https://www.tripod-statement.org/) - Transparent reporting of multivariable prediction models.
- [SPIRIT Statement](https://www.spirit-statement.org/) - Standard protocol items for clinical trials.

## Reproducible Research

Tools for creating reproducible biostatistical analyses.

- [rmarkdown](https://CRAN.R-project.org/package=rmarkdown) - Dynamic documents combining R code, narrative, and results.
- [knitr](https://CRAN.R-project.org/package=knitr) - Elegant, flexible, and fast dynamic report generation.
- [targets](https://CRAN.R-project.org/package=targets) - Pipeline toolkit for reproducible computation at scale.
- [drake](https://CRAN.R-project.org/package=drake) - Data analysis workflow management system.
- [workflowr](https://CRAN.R-project.org/package=workflowr) - Organized, reproducible, and shareable research workflow.
- [Jupyter](https://jupyter.org/) - Interactive notebooks supporting multiple programming languages.
- [Quarto](https://quarto.org/) - Open-source scientific and technical publishing system.
- [Docker](https://www.docker.com/) - Containerization platform for reproducible computational environments.

## Learning Resources

### Books

- [Biostatistics for Dummies](https://www.wiley.com/en-us/Biostatistics+For+Dummies-p-9781118553985) - Introductory biostatistics for non-statisticians.
- [Design and Analysis of Clinical Trials](https://www.wiley.com/en-us/Design+and+Analysis+of+Clinical+Trials%3A+Concepts+and+Methodologies%2C+3rd+Edition-p-9781118273161) - Comprehensive guide to clinical trial methodology.
- [Statistical Methods in Medical Research](https://www.wiley.com/en-us/Statistical+Methods+in+Medical+Research%2C+5th+Edition-p-9781119991335) - Peter Armitage's classic textbook on medical statistics.
- [Regression Modeling Strategies](https://link.springer.com/book/10.1007/978-3-319-19425-7) - Frank Harrell's comprehensive guide to statistical modeling.
- [Modern Epidemiology](https://www.wolterskluwer.com/en/solutions/ovid/modern-epidemiology-1229) - Kenneth Rothman's foundational epidemiology text.

### Online Courses

- [Harvard PH525x Data Analysis for Life Sciences](https://www.edx.org/course/data-analysis-for-life-sciences) - Series on biostatistics and data analysis.
- [Coursera Biostatistics Specialization](https://www.coursera.org/specializations/biostatistics) - Johns Hopkins University biostatistics courses.
- [UCLA IDRE Statistics](https://stats.oarc.ucla.edu/) - Excellent tutorials on statistical software and methods.
- [Statistical Rethinking](https://xcelab.net/rm/statistical-rethinking/) - Richard McElreath's Bayesian statistics course.
- [FDA Biostatistics Training](https://www.fda.gov/training-and-continuing-education) - Free training materials from FDA.

### Websites & Blogs

- [Statistical Modeling, Causal Inference, and Social Science](https://statmodeling.stat.columbia.edu/) - Andrew Gelman's blog.
- [Frank Harrell's Blog](https://www.fharrell.com/) - Statistical Thinking blog by Frank Harrell.
- [Datamethods](https://discourse.datamethods.org/) - Discussion forum for statistical methods.
- [Cross Validated](https://stats.stackexchange.com/) - Statistics Stack Exchange Q&A.
- [The Analysis Factor](https://www.theanalysisfactor.com/) - Resources for applied statistics.

## Journals & Publications

- [Statistics in Medicine](https://onlinelibrary.wiley.com/journal/10970258) - Leading journal for medical statistics.
- [Biometrics](https://academic.oup.com/biometrics) - Journal of the International Biometric Society.
- [Biostatistics](https://academic.oup.com/biostatistics) - Journal focusing on biostatistical methods.
- [Journal of Biopharmaceutical Statistics](https://www.tandfonline.com/toc/lbps20/current) - Focus on pharmaceutical and clinical trial statistics.
- [Epidemiology](https://journals.lww.com/epidem/pages/default.aspx) - Leading journal in epidemiological methods.
- [American Journal of Epidemiology](https://academic.oup.com/aje) - Oxford journal on epidemiologic methods and practice.
- [Clinical Trials](https://journals.sagepub.com/home/ctj) - Journal focused on clinical trial design and analysis.
- [Pharmaceutical Statistics](https://onlinelibrary.wiley.com/journal/15391612) - Statistics applied to pharmaceutical research.

## Community & Organizations

- [American Statistical Association](https://www.amstat.org/) - Professional organization with biostatistics sections.
- [International Biometric Society](https://www.biometricsociety.org/) - Global network of biostatisticians.
- [Society for Clinical Trials](https://www.sctweb.org/) - Professional society for clinical trialists.
- [International Society for Clinical Biostatistics](https://www.iscb.info/) - European focus on clinical biostatistics.
- [International Society for Bayesian Analysis](https://bayesian.org/) - Global Bayesian statistics community.
- [Pharmaceutical Users Software Exchange](https://www.pharmasug.org/) - Community for SAS users in pharma.
- [R/Pharma Conference](https://rinpharma.com/) - Annual conference on R in pharmaceutical industry.
- [PSI](https://www.psiweb.org/) - Statisticians in the Pharmaceutical Industry organization.

## Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.
