# STA 663: Intro to Statistical Learning
### Final Project - Spring 2025
### Hugh Ford

### Abstract:
This project aims to predict seasonal flu vaccine uptake using data from the National 2009 H1N1 Flu Survey (NHFS). Although seasonal flu vaccines are widely available in the U.S., not everyone chooses to get vaccinated. We first apply several imputation methods to handle missing data, ultimately opting for a complete case analysis. Next, we use logistic regression, classification trees, and random forest models to predict vaccination status based on 35 individual characteristics. Our comparison of these techniques indicates that the random forest consistently outperforms the others across key metrics. Feature importance analysis highlights perceived risk and belief in the vaccine’s effectiveness as significant predictors of vaccination status. Based on these findings, we recommend that public health campaigns focus on these factors to improve seasonal flu vaccination uptake.

### Directory:

* [Project rendered as pdf](/final-project-663.pdf)
* [Project write-up with annotated code in .qmd format](/final-project-663-codebook.qmd)
* [References in .bib format](/references.bib)
* .Rda files to skip computing imputation steps
    * [CART imputation](/flu_tree_imput.Rda)
    * [Random Forest imputation](/flu_rf.Rda)
    * [Chained Equations imputation](/flu_chained_impute.Rda)
    * [kNN imputation](/flu_knn_impute.Rda)
