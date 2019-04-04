# bayes-clustering-classification
Collection of Bayesian clustering and classification techniques with the Fifa dataset.

Authors: Manuel Rodríguez, Sergio Arias and Antonio Miranda (me).

This R Markdown takes a lot to compile in a regular laptop, so I have included the compiled HTML to visualize the results in case you are only interested in having a look at the results. 

The project is a complete analysis of the Fifa dataset (https://www.kaggle.com/kevinmh/fifa-18-more-complete-player-dataset#complete.csv). The steps are: 
1. Introduction: motivation of the work and that stuff.
2. Quick Dataset preparation. 
3. Descriptive Analysis: find out the main characteristics of the different attributes and classes of the dataset.
4. Bayesian clustering: Finite mixture of Gaussians
5. Bayesian classification: Naive Bayes, Logistic Regression (and comparison with frequentist approach), Probit Regression, Gaussian Processes, Linear Discriminant Analysis and Quadratic Discriminant Analysis.
6. Conclusions.

R version 3.5.1

Packages: 
 + MCMCglmm_2.26
 + mixAK_5.1
 + kernlab_0.9-26
 + dplyr_0.7.6
 + MASS_7.3-50
 + caret_6.0-80
 + Zelig_5.1.6
 + MCMCpack_1.4-3
 + e1071_1.7-0
 + factoextra_1.0.5
 + VGAM_1.0-5
