---
layout: archive
title: "Projects"
permalink: /portfolio/
author_profile: true
---
### *Course Projects* 
---
{% include base_path %}
- **Conformalized Survival Analysis- A Review.**  [Report](/files/pdfs/Survival Project Report.pdf){: .btn--research} [Slides](/files/pdfs/Survival Project Slides.pdf){: .btn--research} 
 > In this project we review discuss the methodology involving inference using conformal prediction proposed by [Candès et al. (2023)](https://doi.org/10.1093/jrsssb/qkac004) which can be used with any survival prediction methods to produce calibrated, covariate-dependent lower predictive bounds on survival times. Since conformal prediction is a powerful but relatively new tool for inference, we discuss the basic concepts related to conformal prediction for more rudimentary models before motivating ourselves to apply similar techiques in the survival analysis regime. In this project we talk about generation of lower predictive bounds with almost exact coverage and discuss an algorithm adapted from equivalent regression model approach and its application in the survival model setup.


- **Conditional Calibration For False Discovery Rate Control Under Dependence- A Review.** [Slides](/files/pdfs/Multiple Testing Project Slides.pdf){: .btn--research}
 > Studied the theory & methodology proposed by the [Fithian, W. and Lei, L. (2022)](https://doi.org/10.1214/21-AOS2137) to adaptively calibrate separate rejection threshold for each p-value to control overall FDR under different dependence structures.

- **A Brief Review of Sparse Principal Components Analysis and its Generalization.**  [Report](/files/pdfs/Multivariate Project Report.pdf){: .btn--research} [Slides](/files/pdfs/Multivariate Project slides.pdf){: .btn--research} [Codes](https://github.com/shubha3/SPCA){: .btn--research}   
 > Principal Component Analysis is a widely studied methodology as it is a useful technique for dimension reduction. In this report, we discuss Sparse Principal Component Analysis (SPCA), which is a modification over PCA. This method is able to resolve the interpretation issue of PCA. Additionally, it provides sparse loadings to the principal components. The main idea of SPCA comes from the relationship between PCA problem and regression analysis. We also discuss GAS-PCA, which is a generalization over SPCA and this method performs better than SPCA, even in finite sample cases. Our report is mainly based on [Zou et al. (2006)](https://doi.org/10.1198/106186006X113430) and its extension 
  [Leng and Wang (2009)](https://doi.org/10.1198/jcgs.2009.0012).

- **Bayesian Forecasting of UEFA Champions League under alternative seeding schemes.**  [Report](/files/pdfs/Bayesian report.pdf){: .btn--research} [Slides](/files/pdfs/Bayesian slides.pdf){: .btn--research} [Codes](https://github.com/shubha3/MTH535A-Bayesian-Analysis){: .btn--research}    
 > Seeding rules plays an important role in determining the fate of teams competing in UEFA Champions League. In slight changes of seeding practices, weak teams (ranked according to UEFA coefficients) can stand to either benefit or lose out on chances in advancement in the tournament. We use probabilistic forecasting models to evaluate the effect of seeding. We review a Bayesian approach to account for the uncertainty involved with the parameters of the forecasting model. We perform a Monte Carlo simulation to estimate outcome probabilities by simulating the UEFA Champions League under alternative seeding regimes. We incorporate entropy in our analysis to evaluate the uncertainty in winning the tournament by all the teams under different seeding schemes. This project is an attempt to replicate the findings by [Corona et al. (2019)](https://doi.org/10.1016/j.ijforecast.2018.07.009).

- **Estimating the Distribution of Linear Regression Estimates using Fast and Robust Bootstrap.**  [Report](/files/pdfs/Non-para report.pdf){: .btn--research} [Slides](/files/pdfs/Non-para slides.pdf){: .btn--research} [Codes](https://github.com/shubha3/MTH535A-Bayesian-Analysis){: .btn--research}  
 > In this report we discuss the method of Fast Bootstrap to obtain an estimate of the distribution of robust regression estimates. The weighted average representation of MM-estimates has been very crucial to the formulation of our problem. This method is computationally less costly as for each bootstrap sample we do not run non-convex optimization algorithm. Rather, we only solve a system of linear equations. Robustness is achieved by using weights as a decreasing function of absolute value of the residuals. The breakdown point of the quantile estimates from this method is higher than classical bootstrap estimates. We illustrate the method using a simulation study and also by performing data analysis in two different data sets.

- **Efficient High-dimensional Robust  Variable Selection via Rank-based LASSO Methods.**  [Report](/files/pdfs/Robust Project 2 report.pdf){: .btn--research} [Slides](/files/pdfs/Robust Project 2 slides.pdf){: .btn--research} [Codes](https://github.com/shubha3/rankLASSO){: .btn--research}
 > Penalized variable selection is a popular approach for describing the relationship between the response, *Y* and explanatory variables, *X*. LASSO-based methods have received special attention throughout the literature of regression analysis. But stringent conditions are imposed on the *X-y* relation and on the error distribution. In this report, we present Rank-LASSO as a robust, superior method over the general LASSO, which can be used even when number of predictors is much larger than the sample size. The major properties of the Rank-LASSO has been presented in a non-asymptotic fashion, which makes it useful for the aforementioned case of *p >> n*. The report also shows the superiority of the thresholded modified version of Rank-LASSO in more general scenarios. Apart from theoretical results, we present numerical experiments for demonstrating that performance of the Rank-LASSO is substantially better than regular LAD-LASSO in terms of robust model selection problems. The report is primarily based on [Rejchel and Bogdan (2020)](https://jmlr.org/papers/v21/20-120.html).

- **Understanding Non-parametric Modal Regression via Kernel Density Estimation.**  [Report](/files/pdfs/Project 1 Report.pdf){: .btn--research} [Slides](/files/pdfs/Project 1 Ppt.pdf){: .btn--research} [Codes](https://github.com/shubha3/NPmodalReg){: .btn--research}
 > In this report we review non-parametric Modal Regression using Kernel Density Estimator. Instead of using conditional mean, Modal Regression uses conditional mode to summarize the relationship between the response and the explanatory variables. We describe the idea of Modal Regression and include a brief discussion regarding the superiority of Multi-modal regression over the Uni-modal case. The consistency properties of the proposed estimator and the idea of Confidence Sets have been reviewed. This report also includes an application of Prediction Sets in case of Bandwidth selection. Certain generalizations and extensions are also discussed. The report is primarily based on [Chen et al. (2016)](https://doi.org/10.1214/15-AOS1373).

- **A Study of Physicochemical Properties of Protein Tertiary Structure**  [Report](/files/pdfs/Group 5- Regression Analysis- Project Report.pdf){: .btn--research}
 > The main objective of the project is to properly explain protein’s tertiary structure which we have taken as RMSD (Root Mean Square Deviation) by a linear model of 9 other components given as F1, F2, F3, F4, F5, F6, F7, F8, F9 using different tools of regression analysis. We aim to model the relationship between response and the regressors using an MLR model. Along with an empirical evaluation, we will be performing a detailed mathematical analysis of different aspects of the model to establish its validity. This includes Residual analysis to check if our model assumptions hold true, tests for checking Multi-collinearity to check if there exists any
near-linear relationship among any subsets of the regressors, tests of significance to guarantee that the derived model parameters do make sense, and also variable selection to see if we can get the same result as our full model using only lesser number of regressors. To summarize, we are aiming to build a model of RMSD by identifying the most important factors (or regressors) through the regression analysis and model diagnostics.


---
### *Talks and Conferences*
---
{% include base_path %}
- **Power Analysis for Mediation Models: Methods and Results.** [Slides](files/pdfs/talk-nov9-deptpsych.pdf){: .btn--research}
  > Presentation of summer project results to [Phillips Lab](https://phillips.pitt.edu), Department of Psychiatry, University of Pittsburgh.
- **Simulated Power Calculations for Mediation Effects with Covariates.** [Poster](/files/pdfs/Keystone_Symposium_Poster_23.pdf){: .btn--research}
  > Joint Work with Heqiao Ruan and advised by Prof. Satish Iyengar. Poster presented at the inaugural Keystone State Statistics Symposium hosted by Penn State University, Oct 7-8, 2023.
  

