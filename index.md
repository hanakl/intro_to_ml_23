---
layout: default
---
# Workshop Description
Welcome to Responsible AI in Practice! How do we develop machine learning models and systems taking fairness, accuracy, explainability, robustness, and privacy into account? How do we operationalize models in production, and address their governance, management, and monitoring? Given the increasing role played by artificial intelligence (AI) applications in determining our day-to-day experiences and the rapid adoption of AI systems in high-stakes domains such as hiring, lending, and healthcare, it’s become imperative to build and deploy AI systems in a responsible manner. In this course, we will first motivate the need for adopting a “responsible AI by design” approach when developing AI / machine learning (ML) models and systems for different consumer and enterprise applications. We will present an overview of responsible AI and associated techniques and tools, with a focus on model explainability, fairness, and privacy in AI. Then, we will focus on the application of explainability, fairness assessment/unfairness mitigation, and privacy techniques in industry, wherein we present practical challenges/guidelines for using such techniques effectively and lessons learned from deploying models for several web-scale machine learning and data mining applications. We will emphasize that topics related to responsible AI are socio-technical, that is, they are topics at the intersection of society and technology. The underlying challenges cannot be addressed by technologists alone; we need to work together with all key stakeholders --- such as customers of a technology, those impacted by a technology, and people with background in ethics and related disciplines --- and take their inputs into account while designing these systems. In this course, you’ll get a first hand feel for responsible AI industry case studies, and discover the challenges underlying responsible AI in practice! Join us for an interactive learning experience that includes engaging presentations, collaborative group exercises, slido polls & quizzes, and even a “homework” to probe deeper between the two sessions.
## Class Outcomes
This course is aimed at attendees with a wide range of interests and backgrounds, including researchers interested in knowing about techniques and tools for model explainability, fairness, and privacy in AI as well as practitioners interested in implementing responsible AI models for web-scale machine learning and data mining applications. We will not assume any prerequisite knowledge, and present the intuition underlying various explainability, fairness, and privacy notions and techniques to ensure that the material is accessible to all attendees. To knowledgeably appreciate what can go wrong when developing AI/ML systems and how such problems are addressed, it's helpful to have a conceptual understanding of machine learning and how it differs from computer software developed by explicit programming. Previous exposure to machine learning at the level of the companion "Introduction to Machine Learning" workshop in this series should suffice. Beginners to ML will do well to read the transcript from this link: The Ethical Algorithm, with Michael Kearns. Warning: it will take a careful reader at least 15, if not 30 minutes or more!

## About the Instructor
![Alexander Ioannidis](/assets/img/alex.png){:style="max-width:30%;"}
Krishnaram Kenthapadi is the Chief AI Officer & Chief Scientist of Fiddler AI, an enterprise startup building a responsible AI and ML monitoring platform. Previously, he was a Principal Scientist at Amazon AWS AI, where he led the fairness, explainability, privacy, and model understanding initiatives in the Amazon AI platform. Prior to joining Amazon, he led similar efforts at the LinkedIn AI team, and served as LinkedIn’s representative in Microsoft’s AI and Ethics in Engineering and Research (AETHER) Advisory Board. Previously, he was a Researcher at Microsoft Research Silicon Valley Lab. Krishnaram received his Ph.D. in Computer Science from Stanford University in 2006. He serves regularly on the senior program committees of FAccT, KDD, WWW, WSDM, and related conferences, and co-chaired the 2014 ACM Symposium on Computing for Development. His work has been recognized through awards at NAACL, WWW, SODA, CIKM, ICML AutoML workshop, and Microsoft’s AI/ML conference (MLADS). He has published 50+ papers, with 4500+ citations and filed 150+ patents (70 granted). He has presented tutorials on privacy, fairness, explainable AI, responsible AI, and model monitoring at forums such as KDD ’18 ’19 '22, WSDM ’19, WWW ’19 ’20 '21, FAccT ’20 '21 ‘22, AAAI ’20 '21, and ICML '21, and instructed a course on AI at Stanford.
# Workshop Materials
##

## Pre-workshop Checklist
1. Sign up for [Piazza](https://piazza.com/stanford/summer2023/icme) (class code icme). We will be using Piazza to answer questions during the workshop.
2. You should have received a welcome email with the Zoom link and password. Please email us (hanakl [at] stanford [dot] edu) if you haven’t.
3. Familiarize yourself with the schedule and see you Monday July 31st at 1:00 pm PT!

## Schedule
ISL = [Introduction to Statistical Learning](https://www.dropbox.com/s/krvhmt7z8zxhl7f/ISLRv2_website.pdf?dl=0)
ESL = [Elements of Statistical Learning](https://hastie.su.domains/ElemStatLearn/)
### Day 1 Unsupervised Learning
#### Session 1 (1:00 pm - 2:25 pm PST)
- Clustering (K-means, Hierarchical Clustering)
  - ISL: Section 12.4 and 12.5.4

#### Session 2 Unsupervised Learning (2:35 pm - 3:00 pm PST)
- Dimensionality Reduction (PCA, ICA, MDS, SOM, tSNE) 
  - ISL: Section 12.2 and 12.5.1 (PCA)
  - ESL: 14.4 (Self-Organizing Maps, SOM)
  - ESL: Section 14.7.2 (ICA, advanced topic, skim only)
  - ESL: 14.8 (Multidimensional Scaling)

#### Session 3 Imputation (3:15 pm - 4:00 pm PST)
- Imputation 
  - ISL: Section 12.3 and 12.5.2
  - ESL: Section 9.6 (Imputation)

### Day 2 Unsupervised Learning
#### Session 1 (1:00 pm - 2:25 pm PST)
- Fundamental Techniques of Supervised Learning: Cross-validation, Regularization and Sparsity (lasso, ridge regression, elastic net) 
  - ISL: Section 5.1 and Section 13.2 (Cross-validation) 
  - ISL: Section 6.2 and 6.5.2 (Regularization and Sparsity)
  - ESL: Section 3.5.1 (Principal Components Regression)

#### Session 2 (2:35 pm - 4:00 pm PST)  
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
