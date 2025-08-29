# slegers-et-al-2025b
Exploring the relationship between first-week mortality and performance after the first week in broiler chickens

This repository includes the R script to run the following analyses:
- Negative binomial mixed-effect model to analyze factors associated with first-week mortality (FWM)
- Negative binomial mixed-effect model to analyze the association between FWM and later mortality
- Linear mixed-effect models to analyze the association between FWM and either DG or FCR

These analyses were performed in Databricks, using R v4.2.2 (R Core Team, 2022). The following R packages are used: dplyr v1.0.10 (Wickham et al., 2022), ggplot2 v3.4.0 (Wickham, 2009), lme4 v1.1-37 (Bates et al., 2015), lmerTest v3.1-3 (Kuznetsova et al., 2017), lsmeans v2.30-2 (Lenth, 2016), glmmTMB v1.1.12 (Brooks et al., 2017), and performance v0.15.0 (Lüdecke et al., 2021).

## References:

- Bates, D., M. Mächler, B. Bolker, and S. Walker. 2015. Fitting Linear Mixed-Effects Models Using lme4. J. Stat. Softw. 67:1–48.
- Brooks, M. E., K. Kristensen, K. J. van Benthem, A. Magnusson, C. W. Berg, A. Nielsen, H. J. Skaug, M. Mächler, and B. M. Bolker. 2017. glmmTMB Balances Speed and Flexibility Among Packages for Zero-inflated - Generalized Linear Mixed Modeling. R J. 9:378–400.
- Kuznetsova, A., P. B. Brockhoff, and R. H. B. Christensen. 2017. lmerTest Package: Tests in Linear Mixed Effects Models. J. Stat. Softw. 82:1–26.
- Lenth, R. V. 2016. Least-Squares Means: The R Package lsmeans. J. Stat. Softw. 69:1–33.
- Lüdecke, D., M. S. Ben-Shachar, I. Patil, P. Waggoner, and D. Makowski. 2021. performance: An R Package for Assessment, Comparison and Testing of Statistical Models. J. Open Source Softw. 6:3139.
- R Core Team. 2022. R: The R Project for Statistical Computing. R Foundation for Statistical Computing, Vienna, Austria.
- Wickham, H. 2009. ggplot2: Elegant Graphics for Data Analysis. Springer, New York, NY.
- Wickham, H., R. François, L. Henry, K. Müller, and D. Vaughan. 2022. dplyr: A Grammar of Data Manipulation. Available at https://cran.r-project.org/web/packages/dplyr/index.html (verified 24 July 2023).

