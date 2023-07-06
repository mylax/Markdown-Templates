---
title: "Book Example"
date: "2018-05-18"
author: "Jaan Tollander de Balsch"
bibliography: "bibliography.bib"
link-citations: true
urlcolor: "blue"
---


- [Statistics](#statistics)
  - [variance vs bias tradeoff](#variance-vs-bias-tradeoff)
  - [math](#math)
  - [linear regression](#linear-regression)
  - [causal inference](#causal-inference)
  - [bayesian](#bayesian)
    - [credibility interval](#credibility-interval)
    - [MCMC](#mcmc)
    - [gibbs sampling](#gibbs-sampling)
  - [frequentist](#frequentist)
    - [confidence intervals](#confidence-intervals)
    - [power function vs operationscharachteristik](#power-function-vs-operationscharachteristik)
    - [quantile regression](#quantile-regression)
  - [non-parametric](#non-parametric)
- [Algorithms](#algorithms)
  - [recursive](#recursive)
  - [hashtable](#hashtable)
  - [linked lists](#linked-lists)
- [Engineering](#engineering)
  - [devops](#devops)
  - [Monitoring](#monitoring)
  - [quality checks](#quality-checks)
- [ML](#ml)
  - [interpretability](#interpretability)
  - [regularization](#regularization)
  - [categorical features](#categorical-features)
    - [dimensionality reduction](#dimensionality-reduction)
  - [loss functions](#loss-functions)
  - [clustering](#clustering)
  - [boosting](#boosting)
  - [data drift vs concept drift](#data-drift-vs-concept-drift)
  - [validation](#validation)
    - [stratified sampling](#stratified-sampling)
    - [target leakage in smote/undersampling/oversmapling](#target-leakage-in-smoteundersamplingoversmapling)
- [Deep Learning](#deep-learning)
  - [entity recognition](#entity-recognition)
  - [LLM](#llm)
  - [GNN](#gnn)
  - [convolution](#convolution)
  - [NLP](#nlp)
    - [n-gram, char-gram](#n-gram-char-gram)
    - [TFIDF](#tfidf)
    - [BERT](#bert)
- [soft skills](#soft-skills)
  - [presentation skills](#presentation-skills)
- [domain knowledge](#domain-knowledge)


# Statistics

## variance vs bias tradeoff

## math
convex vs non convex
CLT
LLN

## linear regression
assumptions
heteroskedacistity  GLS


## causal inference

## bayesian

### credibility interval

### MCMC

### gibbs sampling

## frequentist

### confidence intervals

What is a confidence interval?

Let's start by looking at the power function of the standard confidence interval.

$$X_{i}\sim \left( \mu,\sigma ^{2}\right)$$
Then by CLT

$$\overline{X}=\frac{1}{n}\sum_{i=1}^{n}x_{i} \sim\mathcal{N}(\mu,\frac{\sigma^2}{n})$$
$$\dfrac{\overline{X}-\mu}{\sigma }\sqrt{n} \sim\mathcal{N}(0,1)$$

Because

$$E\left( x_{i}\right) =E\left[ \dfrac{1}{n}\sum ^{n}_{i=1}x_{i}\right]=\dfrac{1}{n}E\left[ \sum x_{i}\right] =\dfrac{1}{n}\cdot nE\left[ x_{i}\right]=\mu$$
$$V\left[ \dfrac{1}{n}\sum ^{n}_{i=1}x_{i}\right] =\dfrac{1}{n^{2}}V\left[ \sum ^{n}_{i=1}x_{i}\right]=\dfrac{1}{n^{2}}nV\left( x_{i}\right) =\dfrac{\sigma ^{2}}{n}$$

Now we look at the probability to accept the null when the null is true.

$$P( \overline{X}-\dfrac{2\sigma }{n}\leq \mu \leq\overline{X}+\dfrac{2\sigma}{n}|H_{0}\;true)=P(-2\leq \dfrac{\left( \overline{x}-\mu \right) \sqrt{n}}{\sigma }\leq 2|H_{0}\;true)=0.95$$

Hence probability to reject the null when null is true is 
$$1 - 0.95 = 0.05 = \alpha $$

which is known as the type 1 error. We see that the classical confidence interval controls for the likelihood of rejecting the null when the null is true.

Can we find different confindence intervals that make sure our type 2 error is minimized?

### power function vs operationscharachteristik

### quantile regression



## non-parametric


# Algorithms

## recursive

## hashtable

## linked lists
Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Cauchy's integral formula [@dixon1971brief]

$$f(a)={\frac{1}{2πi}}∮_{γ}{\frac{f(z)}{z-a}}\,dz.$$

What about inline equations?

Duis aute irure dolor $\int x^2\,dx$ in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.


# Engineering

## devops
pyspark, kubernetes, airflow, etc.

## Monitoring

## quality checks



# ML


## interpretability
SHAP VALUES

## regularization

## categorical features

### dimensionality reduction
PCA eigendecompositon, svd, auto encoder
## loss functions
RMSE vs MAE vs Percentage MAE vs hubert loss

## clustering

## boosting

## data drift vs concept drift

## validation

### stratified sampling
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

Seen in above table, Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

### target leakage in smote/undersampling/oversmapling

# Deep Learning

## entity recognition

## LLM

## GNN

## convolution

## NLP

### n-gram, char-gram

### TFIDF

### BERT

# soft skills
celebrate coworker
why zalando
what in a manager
conflict with coworker
how to give feedback


## presentation skills

# domain knowledge

