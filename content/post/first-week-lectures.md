+++
date = "2017-08-14T09:00:00-07:00"
title = "Week 1: Lecture Syllabus"
tags = ["lectures", "classification", "regression", "neural network", "first-week", "hypothesis testing", "experimental design", "basic topics"]
highlight = true
math = false
summary = """
Descriptions of the introductory data science material to be covered in the mornings of the first week. These introductory lecture topics will familiarize participants with domain-specific jargon and concepts, and serve as the starting point of a toolbox for the second-week projects.
"""

[header]
  caption = ""
  image = "posts/generic-11.jpg"

+++

## Focus

Interactive lectures on introductory topics in data science will comprise the
mronings of the first week of the workshop. The first three lectures will be
led by
[Isabell Konrad](https://www.ischool.berkeley.edu/people/isabell-konrad) and
will cover classification, regression, clustering and neural
networks. Thursday's lecture by [Yinshan Zhao](http://epims.med.ubc.ca/our-team/faculty/yinshan-zhao/) will cover hypothesis testing and experimental
design, while Friday's lecture by Michael Reid will showcase modern software
tools for data scientists.

For the first week schedule, please visit [this page](../../talk/first-week-schedule); and for first week notes, please visit the [GitHub repository](https://github.com/bcdataca/workshop-content/tree/master/1-first-week/notes) for the workshop.

## Syllabus

### Linear and Logistic regression.
We will understand the first machine learning algorithm Linear Regression. We
talk about train-test-split, normalization of the data, the problem of
overfitting and regularization. A short code example shows how to use these
tools in practice (using scikit-learn). We introduce classification in contrast
to regression, and discuss key metrics like accuracy, precision and recall. We
talk about the Logistic Regression classifier and show a short code example.

Notes and Jupyter notebooks for this content are available on the [Github repository](https://github.com/bcdataca/workshop-content/tree/master/1-first-week/1-regression-classification).

### Important classifiers.
The classifiers Decision Trees and K-Nearest-Neighbours will be covered, as
well as ensemble methods like Bagging and Random Forests. In a short code
example the application of the classifiers is demonstrated (scikit-learn).

Notes and Jupyter notebooks for this content are available on the [Github repository](https://github.com/bcdataca/workshop-content/tree/master/1-first-week/2-important-classisfiers).


### Neural Networks.
This lecture is about Neural Networks with various add-ons, as well as feature
engineering and a short code example in TensorFlow.

Notes and Jupyter notebooks for this content are available on the [Github repository](https://github.com/bcdataca/workshop-content/tree/master/1-first-week/3-neural-networks).


### Hypothesis testing and experimental design.
Firstly, we will discuss the purpose of hypothesis testing and learn how to do it. Through examples, we will introduce basic concepts, testing procedures, common misinterpretations and connection between hypothesis testing and estimation. Then we will discuss statistical considerations in study designs, such as sampling, controls, randomization, sample size and power. Finally, we will look into multiple testing procedures. 

### Modern Software Tools for Data Scientists.
This lecture will cover the “plumbing” of data science — the software used for data ingestion, cleaning, storage, and analysis. We will provide an overview of the tools currently used by enterprises ingesting hundreds of thousand events per second and handling petabytes of data. Attendees will have a hands-on introduction to the machine learning tools used in industry, including distributed processing with AWS and Apache Spark. We also look into the future at the new generation of native stream processing platforms, used for real-time machine learning.

Slides from this lecture are [available here](https://github.com/bcdataca/workshop-content/raw/master/1-first-week/5-software-tools/Software%20Tools%20in%20Data%20Science%20Presentation.pptx).
