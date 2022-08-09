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
1. Sign up for [Piazza](https://www.piazza.com/stanford/summer2022/icmeintrotoml/home) (class code icme). We will be using Piazza to answer questions during the workshop.
2. You should have received a welcome email with the Zoom link and password. Please email us (hanakl [at] stanford [dot] edu) if you haven’t.
3. Familiarize yourself with the schedule and see you Monday August 8th at 8:00 am PT!

## Schedule
ISL = [Introduction to Statistical Learning](https://www.dropbox.com/s/krvhmt7z8zxhl7f/ISLRv2_website.pdf?dl=0)

[Coding examples from ISL](https://www.statlearning.com/resources-second-edition)

ESL = [Elements of Statistical Learning](https://hastie.su.domains/ElemStatLearn/)
### Day 1 Unsupervised Learning [[recording](https://stanford.zoom.us/rec/share/9-JzruY9MMXdu9R3AzqUSWRPAnKrHq-Tg8e1Ga2t7Mt4wLSCmiS-TqbtstF-6MSz.JkstSD383jSJs0zn?startTime=1659970930000)]
### Day 2 Supervised Learning [[recording](https://stanford.zoom.us/rec/share/G8KwWDCz_Y2g-uAmieD1xwsJewthmYCzQryi3PYHcfqgd3yoUTKiwjS55A9KNNOu.Zuk20th2kDvr3nKc?startTime=1660056060000)]
#### Session 1 (8 am - 9:25 am PST)

- Clustering (K-means, Hierarchical Clustering) [[slides](https://drive.google.com/file/d/1qpU8PX3AIbNdgPrCMnuvhBk8NfSBbxr5/view?usp=sharing)]
  - ISL: Section 12.4 and 12.5.4
    -  Gap Statistic [paper](https://hastie.su.domains/Papers/gap.pdf)

#### Session 2 Unsupervised Learning (9:35 am - 10 am PST)

- Dimensionality Reduction (PCA, ICA, MDS, SOM, tSNE) [[slides](https://drive.google.com/file/d/1ZBDJLOTP-pFKReROLWr7NmURnKyisL59/view?usp=sharing)]
  - ISL: Section 12.2 and 12.5.1 (PCA)
    - Example PCA [code](https://drive.google.com/file/d/1yA-5HbcGnNutZjZyryFhBCZFj1falWdq/view?usp=sharing) for olive oil [data](https://drive.google.com/file/d/1O8VxEw71uXu1HuXnonj_FYidktv-9ZQM/view?usp=sharing)
  - ESL: 14.4 (Self-Organizing Maps, SOM)
    - Example SOM [code](https://drive.google.com/file/d/1VbIKAGp1iVBQAf4VhqRF8ew6hB0HyVw_/view?usp=sharing) OS X users must first install [X Quartz](https://www.xquartz.org/)
  - ESL: Section 14.7.2 (ICA, advanced topic, skim only)
    - Paper on FastICA, skim sections 1 "Motivation" and 7 "Applications of ICA" for an overview of ICA, section 6 describes the FastICA algorithm, section 7.2 and figures 13-14 describe the example of sales across retail outlets [[here](http://mlsp.cs.cmu.edu/courses/fall2012/lectures/ICA_Hyvarinen.pdf)]
  - ESL: 14.8 (Multidimensional Scaling, MDS)
    - MDS example, see "America’s Broken Politics”  [[article](https://www.nytimes.com/2014/11/06/opinion/nicholas-kristof-americas-political-dysfunction.html), New York Times] and [[voteview](https://legacy.voteview.com/political_polarization_2015.htm)]

#### Session 3 Imputation (10:15 am - 11 am PST)

- Imputation [[slides](https://drive.google.com/file/d/1Uq7LNWM3wmF1q-W_zBOX3SZDjQNtvQlr/view?usp=sharing)]
  - ISL: Section 12.3 and 12.5.2
  - ESL: Section 9.6 (Imputation)

### Day 2 Unsupervised Learning [[recording](https://stanford.zoom.us/rec/play/rUTb918sqmTz5pT8jkNTyirTYV46uBvgvJ_10lFjRPWeD1kPomwwYfwUIpHdjKO7mlgphcmLNmdiT029.osmXkhxkJrGNBOcZ?startTime=1660056060000&_x_zm_rtaid=7cs-p6r4TkGlQtlIrMLUTQ.1660082845826.60c4498b0f19b7ab366b6ca897e0793c&_x_zm_rhtaid=453)]

#### Session 1 (8 am - 9:25 am PST)

- Fundamental Techniques of Supervised Learning: Cross-validation, Regularization and Sparsity (lasso, ridge regression, elastic net) [[slides](https://drive.google.com/file/d/1Q4qTAr6PcHgA4J_ClYR_F1pW8ZNHxlLp/view?usp=sharing)]
  - ISL: Section 5.1 and Section 13.2 (Cross-validation)
    - Many Psychology Findings Not as Strong as Claimed, Study Says" [(New York Times)](https://www.nytimes.com/2015/08/28/science/many-social-science-findings-not-as-strong-as-claimed-study-says.html)
  - ISL: Section 6.2 and 6.5.2 (Regularization and Sparsity)
  - ESL: Section 3.5.1 (Principal Components Regression)

#### Session 2 (9:35 am - 11:00 am PST)  

- Classification and Regression Trees [[slides](https://drive.google.com/file/d/1nlXE3P8Qaak6KtpAAygNWl3RasR46kYF/view?usp=sharing)]
  - ISL: Section 8.1
  - CART example R [code](https://drive.google.com/file/d/0BzqeP3J9B8lZVDV0UjdzVFU4ZTQ/view?usp=sharing) and [data](https://drive.google.com/file/d/0BzqeP3J9B8lZMkdUOTVINUFnNVk/edit?usp=sharing)

- Ensemble Methods (Boosting, Bagging, and Random Forests) (see above slides)
  - ISL: Section 5.2 and 5.3.4 (Bootstrap)
  - ISL: Section 8.2 and 8.3.1 - 8.3.4 (Boosting, Bagging, and Random Forests)
  - Kaggle [blog](https://medium.com/kaggle-blog/profiling-top-kagglers-bestfitting-currently-1-in-the-world-58cc0e187b)

- Neural Nets teaser (regularization and deep learning)[[slides](https://drive.google.com/file/d/1u3rKfjaiVT2bVB31652A1og-Hg2F7fMd/view?usp=sharing)]
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


