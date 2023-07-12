---
layout: default
---
# Workshop Description
This workshop presents the basics behind understanding and using modern machine learning algorithms. We will discuss a framework for reasoning about when to apply various machine learning techniques, emphasizing questions of over-fitting/under-fitting, interpretability, supervised/unsupervised methods, and handling of missing data. The principles behind various algorithms—the why and how of using them—will be discussed, while some mathematical detail underlying the algorithms—including proofs—will not be discussed. Unsupervised machine learning algorithms presented will include k-means clustering, principal component analysis (PCA), multidimensional scaling (MDS), tSNE, and independent component analysis (ICA). Supervised machine learning algorithms presented will include support vector machines (SVM), lasso, elastic net, classification and regression trees (CART), boosting, bagging, and random forests. Imputation, regularization, and cross-validation concepts will also be covered. The R programming language will be used for occasional examples, though participants need not have prior exposure to R.
Prerequisites: Undergraduate-level linear algebra and statistics; basic programming experience (R/Matlab/Python).
## About the Instructor
![Alexander Ioannidis](/assets/img/alex.png){:style="max-width:30%;"}
Alexander Ioannidis is an Adjunct Professor in the Institute for Computational and Mathematical Engineering (CME) at Stanford. His research is in the Department of Biomedical Data Science at Stanford Medical School, where he focuses on computational methods for genomics and clinical data science with a particular focus on diverse populations, and at Galatea Bio, where he is vice president of data science. His Ph.D. is from Stanford in CME, and he also has an M.S. in Management Science & Engineering (Optimization) from Stanford. Prior to this he earned a bachelors in Chemistry and Physics from Harvard, an M.Phil in Computational Biology from the Dept. of Applied Math and Theoretical Physics at the University of Cambridge and conducted research for several years on quantum and superconducting computing logic at Northrop Grumman. In his free time, he enjoys sailing.
# Workshop Materials

## Pre-workshop Checklist
1. Sign up for [Piazza](https://piazza.com/stanford/summer2023/icme) (class code icme). We will be using Piazza to answer questions during the workshop.
2. You should have received a welcome email with the Zoom link and password. Please email us (hanakl [at] stanford [dot] edu) if you haven’t.
3. Familiarize yourself with the schedule and see you Monday July 31st at 1:00 pm PT!

## Schedule
ISL = [Introduction to Statistical Learning](https://www.dropbox.com/s/krvhmt7z8zxhl7f/ISLRv2_website.pdf?dl=0)
ESL = [Elements of Statistical Learning](https://hastie.su.domains/ElemStatLearn/)
### Day 1 Unsupervised Learning
#### Session 1 [//]: # (8 am - 9:25 am PST)
- Clustering (K-means, Hierarchical Clustering)
  - ISL: Section 12.4 and 12.5.4
#### Session 2 Unsupervised Learning [//]: # (9:35 am - 10 am PST)
- Dimensionality Reduction (PCA, ICA, MDS, SOM, tSNE) 
  - ISL: Section 12.2 and 12.5.1 (PCA)
  - ESL: 14.4 (Self-Organizing Maps, SOM)
  - ESL: Section 14.7.2 (ICA, advanced topic, skim only)
  - ESL: 14.8 (Multidimensional Scaling)
#### Session 3 Imputation [//]: # (10:15 am - 11 am PST)
- Imputation 
  - ISL: Section 12.3 and 12.5.2
  - ESL: Section 9.6 (Imputation)
### Day 2 Unsupervised Learning
#### Session 1 [//]: # (8 am - 9:25 am PST)
- Fundamental Techniques of Supervised Learning: Cross-validation, Regularization and Sparsity (lasso, ridge regression, elastic net) 
  - ISL: Section 5.1 and Section 13.2 (Cross-validation) 
  - ISL: Section 6.2 and 6.5.2 (Regularization and Sparsity)
  - ESL: Section 3.5.1 (Principal Components Regression)
#### Session 2 [//]: # (9:35 am - 11:00 am PST)  
- Classification and Regression Trees
  - ISL: Section 8.1
- Ensemble Methods (Boosting, Bagging, and Random Forests)
  - ISL: Section 5.2 and 5.3.4 (Bootstrap)
  - ISL: Section 8.2 and 8.3.1 - 8.3.4 (Boosting, Bagging, and Random Forests)
- Neural Nets teaser (regularization and deep learning) 
  - ISL: Section 10.1 - 10.2 and 10.7
## Additional Resources
- [An Introduction to Statistical Learning with Applications in R by Gareth James, Daniela Witten, Trevor Hastie, and Robert Tibshirani](https://www.dropbox.com/s/krvhmt7z8zxhl7f/ISLRv2_website.pdf?dl=0) 
  - The datasets for this book can be found [here](https://www.statlearning.com/resources-second-edition).
- [The Elements of Statistical Learning by Trevor Hastie, Robert Tibshirani, and Jerome Friedman](https://hastie.su.domains/ElemStatLearn/)  
  - This comprehensive reference presents more material, and at a higher mathematical level, than the preceding text. 
- [Convex Optimization by Boyd and Vandenberghe](https://stanford.edu/~boyd/cvxbook/), is an excellent introduction to convex optimization techniques.
- R
  - Download link for R programming language - [http://www.r-project.org/](http://www.r-project.org/)
  - Optional RStudio IDE - [http://www.rstudio.com/](http://www.rstudio.com/)
  - An excellent tutorial: [swirl](https://cran.r-project.org/web/packages/swirl/index.html).
  - If you want to dive deeper, look at the R for Data Science ([free](https://r4ds.had.co.nz/)) online text.
