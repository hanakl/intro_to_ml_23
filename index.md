---
layout: default
---

# Workshop Description
This workshop presents the basics behind understanding and using modern machine learning algorithms. We will discuss a framework for reasoning about when to apply various machine learning techniques, emphasizing questions of over-fitting/under-fitting, interpretability, supervised/unsupervised methods, and handling of missing data. The principles behind various algorithms—the why and how of using them—will be discussed, while some mathematical detail underlying the algorithms—including proofs—will not be discussed. Unsupervised machine learning algorithms presented will include k-means clustering, principal component analysis (PCA), multidimensional scaling (MDS), tSNE, and independent component analysis (ICA). Supervised machine learning algorithms presented will include support vector machines (SVM), lasso, elastic net, classification and regression trees (CART), boosting, bagging, and random forests. Imputation, regularization, and cross-validation concepts will also be covered. The R programming language will be used for occasional examples, though participants need not have prior exposure to R.

Prerequisites: Undergraduate-level linear algebra and statistics; basic programming experience (R/Matlab/Python).

## About the Instructor
![Alexander Ioannidis](/assets/img/alex.png){:style="max-width:30%;"}


Alexander Ioannidis earned his Ph.D. in Computational and Mathematical Engineering and Masters in Management Science and Engineering both at Stanford University. He is a research fellow working on developing novel machine learning techniques for medical and genomic applications in the Department of Biomedical Data Science at Stanford. Prior to this he earned a bachelors in Chemistry and Physics from Harvard, an M.Phil from the University of Cambridge and conducted research for several years on novel superconducting and quantum computing architectures. In his free time, he enjoys sailing.

# Workshop Materials

## Pre-workshop Checklist
1. Sign up for Piazza (class code icme). We will be using Piazza to answer questions during the workshop.
2. You should have received a welcome email with the Zoom link and password. Please email us (hanakl [at] stanford [dot] edu) if you haven’t.
3. Familiarize yourself with the schedule and see you Monday August 8th at 8:00 am PT!

## Schedule
ISL = [Introduction to Statistical Learning](https://www.dropbox.com/s/krvhmt7z8zxhl7f/ISLRv2_website.pdf?dl=0)
ESL = [Elements of Statistical Learning](https://hastie.su.domains/ElemStatLearn/)
### Day 1 Unsupervised Learning
#### Session 1 (8 am - 9:25 am PST)
1. Overview of Machine Learning [slides](https://drive.google.com/file/d/1vB9ffg3j08f8NrIIUhs7SkAuZmkZT1QK/view)
- ISL: Chapter 2

2. Clustering (K-means, Hierarchical Clustering) [slides](https://drive.google.com/file/d/1C2eFJ_2FDCW66KtJUUscvUVRqnmVSn32/view)
- ISL: Section 12.4 and 12.5.4
- [Gap Statistic paper](https://gwalther.su.domains/gap)

#### Session 2 Unsupervised Learning (9:35 am - 10 am PST)

1. Dimensionality Reduction (PCA, ICA, MDS, SOM, tSNE) [slides](https://drive.google.com/file/d/1oucIfBGFgUqG7bUouHb5Vnxe1XiREv0M/view)
- ISL: Section 12.2 and 12.5.1 (PCA)
- ESL: 14.4 (Self-Organizing Maps, SOM)
- ESL: Section 14.7.2 (ICA, advanced topic, skim only)
- ESL: 14.8 (Multidimensional Scaling)
- PCA code in R and corresponding dataset (chemical levels in olive oils from different regions)
- SOM code in R (OS X users must first install [X Quartz](https://www.xquartz.org/))
- Paper on FastICA, skim sections 1 "Motivation" and 7 "Applications of ICA" for an overview of ICA, section 6 describes the FastICA algorithm, section 7.2 and figures 13-14 describe the example of sales across retail outlets, (here)
- MDS example, see "America’s Broken Politics”  (article, New York Times) and [http://voteview.com/polarized_america.htm]

#### Session 3 Imputation (10:15 am - 11 am PST)

1. Imputation [slides](https://drive.google.com/file/d/1vD-YCpV6xOqZOtRxZpSf9TTqtaZgN15X/view)
- ISL: Section 12.3 and 12.5.2
- ESL: Section 9.6 (imputation)

### Day 2 Unsupervised Learning

#### Session 1 (8 am - 9:25 am PST)

-Fundamental Techniques of Supervised Learning: Cross-validation, Regularization and Sparsity (lasso, ridge regression, elastic net) [slides]
"Many Psychology Findings Not as Strong as Claimed, Study Says" (article, New York Times)
Kaggle Machine Learning competitions (a great place to get ideas)
https://www.kaggle.com/

Kaggle's official blog

Compilation of past winning Kaggle solutions

ISL: Section 5.1 and Section 13.2 (Cross-validation) 

ISL: Section 6.2 and 6.5.2 (Regularization and Sparsity)

ESL: Section 3.5.1 (Principal Components Regression)

#### Session 2 (9:35 am - 11:00 am PST)  

1. Classification and Regression Trees
- ISL: Section 8.1
- [R Code for CART example](https://drive.google.com/file/d/0BzqeP3J9B8lZVDV0UjdzVFU4ZTQ/view?usp=sharing) and [corresponding dataset](https://drive.google.com/file/d/0BzqeP3J9B8lZMkdUOTVINUFnNVk/edit?usp=sharing)

2. Ensemble Methods (Boosting, Bagging, and Random Forests)
- ISL: Section 5.2 and 5.3.4 (Bootstrap)
- ISL: Section 8.2 and 8.3.1 - 8.3.4 (Boosting, Bagging, and Random Forests)

3. Neural Nets teaser (regularization and deep learning) [slides](https://drive.google.com/file/d/1YgxMhRlwwmDJS2Bs7XG26hmuHKTx1F26/view)
- ISL: Section 10.1 - 10.2 and 10.7

## Additional Resources

An Introduction to Statistical Learning with Applications in R by Gareth James, Daniela Witten, Trevor Hastie, and Robert Tibshirani. 

The full pdf is freely available from the authors here.

The datasets for this book can be found here.

The Elements of Statistical Learning by Trevor Hastie, Robert Tibshirani, and Jerome Friedman.  

This comprehensive reference presents more material, and at a higher mathematical level, than the preceding text. 

The full pdf is freely available from the authors at the above link.

Convex Optimization by Boyd and Vandenberghe, is an excellent introduction to convex optimization techniques.


