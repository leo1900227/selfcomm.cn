---
title: "读书笔记-A PRIMER ON PARTIAL LEAST SQUARES STRUCTURAL EQUATION MODELING (PLS-SEM)"
date: 2018-11-03T15:43:48+08:00
lastmod: 2019-01-03T15:43:48+08:00
draft: false
tags: 
categories: 
author: "Lin"

# You can also close(false) or open(true) something for this content.
# P.S. comment can only be closed
# comment: false
toc: true
autoCollapseToc: true
# You can also define another contentCopyright. e.g. contentCopyright: "This is another copyright."
contentCopyright: '<a href="https://github.com/gohugoio/hugoBasicExample" rel="noopener" target="_blank">See origin</a>'
# reward: false
# mathjax: false
---

[TOC]

# Chapter 1: An Introduction to Structural Equation Modeling

Chapter Preview

## What Is Structural Equation Modeling?

- 第二代统计技术

## Considerations in Using Structural Equation Modeling

1. **Composite Variables**

   `Composite value = w1 · x1 + w2 · x2 + … + w5 · x5`

2. **Measurement**

   - The logic of using several individual variables to measure an abstract concept such as restaurant satisfaction is that the measure will be more accurate.
   - *single-item constructs*  : While this is a good way to make the questionnaire shorter, it also reduces the quality of your measurement.  

3. **Measurement Scales**

   - *four types of measurement scales* :nominal, ordinal, interval, and ratio 

4. **Coding**

5. **Data Distributions**



## Structural Equation Modeling With Partial Least Squares Path Modeling

### Path Models With Latent Variables

### Measurement Theory

### Structural Theory

### PLS-SEM, CB-SEM, and Regressions Based on Sum Scores

![](http://bit.ly/2CKTcRA)

### Data Characteristics

- ***10 times rule*** : the minimum sample size should be 10 times the maximum number of arrowheads pointing at a latent variable anywhere in the PLS path model. 
- *statistical power analyses* : [G*Power](http://www.gpower.hhu.de/ )  

### Model Characteristics

- 数据不是正态分布也可以，但是极端值、强影响点、多重共线性问题还是要处理

- The PLS-SEM algorithm generally requires metric data on a ***ratio or interval scale for the measurement model indicators***. But the method also works well with ordinal scales with equidistant data points (i.e., quasi-metric scales; Sarstedt & Mooi, 2014) and with binary coded data. The use of binary coded data is often a means of including categorical control variables or moderators in PLS-SEM models. In short, ***dummy-coded indicators*** can be included in PLS-SEM models but require special attention (see some note of caution by Hair, Sarstedt, Ringle, et al., 2012) and ***should not be used as the ultimate dependent variable.*** 

Organization of Remaining Chapters

## Summary

- **Understand the meaning of structural equation modeling (SEM) and its relationship to multivariate data analysis.** SEM is a second-generation multivariate data analysis method. Multivariate data analysis involves the application of statistical methods that simultaneously analyze multiple variables representing measurements associated with individuals, companies, events, activities, situations, and so forth. SEM is used to either explore or confirm theory. Exploratory modeling involves developing theory while confirmatory modeling tests theory. There are two types of SEM—one is covariance-based, and the other is variance-based. CB-SEM is used to confirm (or reject) theories. Variance-based structural equation modeling (i.e., PLS-SEM) is primarily used for exploratory research and the development of theories. 
- **Describe the basic considerations in applying multivariate data analysis.** Several considerations are necessary when applying multivariate analysis, including the following five elements: (1) composite variables, (2) measurement, (3) measurement scales, (4) coding, and (5) data distributions. A composite variable (also called variate) is a linear combination of several variables that are chosen based on the research problem at hand. Measurement is the process of assigning numbers to a variable based on a set of rules. Multivariate measurement involves using several variables to indirectly measure a concept to improve measurement accuracy. The anticipated improved accuracy is based on the assumption that using several variables (indicators) to measure a single concept is more likely to represent all the different aspects of the concept and thereby result in a more valid measurement of the concept. The ability to identify measurement error using multivariate measurement also helps researchers obtain more accurate measurements. Measurement error is the difference between the true value of a variable and the value obtained by a measurement. A measurement scale is a tool with a predetermined number of closed-ended responses that can be used to obtain an answer to a question. There are four types of measurement scales: nominal, ordinal, interval, and ratio. When researchers collect quantitative data using scales, the answers to the questions can be shown as a distribution across the available (predefined) response categories. The type of distribution must always be considered when working with SEM. 
- **Comprehend the basic concepts of partial least squares structural equation modeling (PLS-SEM).** Path models are diagrams used to visually display the hypotheses and variable relationships that are examined when structural equation modeling is applied. Four basic elements must be understood when developing path models: (1) constructs, (2) measured variables, (3) relationships, and (4) error terms. Constructs are latent variables that are not directly measured and are sometimes called unobserved variables. They are represented in path models as circles or ovals. Measured variables are directly measured observations (raw data), generally referred to as either indicators or manifest variables, and are represented in path models as rectangles. Relationships represent hypotheses in path models and are shown as arrows that are single-headed, indicating a predictive/causal relationship. Error terms represent the unexplained variance when path models are estimated and are present for endogenousconstructs and reflectively measured indicators. Exogenous constructs and formative indicators do not have error terms. Path models also distinguish between the structural (inner) model and the measurement (outer) models. The role of theory is important when developing structural models. Theory is a set of systematically related hypotheses developed following the scientific method that can be used to explain and predict outcomes. Measurement theory specifies how the latent unobservable variables (constructs) are modeled. Latent variables can be modeled as either reflective or formative. Structural theory shows how the latent unobservable variables are related to each other. Latent variables are classified as either endogenous or exogenous. 
- **Explain the differences between covariance-based structural equation modeling (CB-SEM) and PLS-SEM and when to use each.** Compared to CB-SEM, PLS-SEM emphasizes prediction while simultaneously relaxing the demands regarding the data and specification of relationships. PLS-SEM maximizes the endogenous latent variables’ explained variance by estimating partial model relationships in an iterative sequence of OLS regressions. In contrast, CB-SEM follows a different measurement philosophy than does PLS-SEM, which calculates proxies to represent the latent variables of interest. In contrast, CB-SEM estimates model parameters so that the discrepancy between the estimated and sample covariance matrices is minimized. Instead of following a common factor model logic as CB-SEM does, PLS-SEM calculates composites of indicators that serve as proxies for the concpets under research. The method is not constrained by identification issues, even if the model becomes complex—a situation that typically restricts CB-SEM use—and does not require accounting for most distributional assumptions. Moreover, PLS-SEM can better handle formative measurement models and has advantages when sample sizes are relatively small. Researchers should consider the two SEM approaches as complementary and apply the SEM technique that best suits their research objective, data characteristics, and model setup

# Chapter 2: Specifying the Path Model and Examining Data

Chapter Preview

## Stage 1: Specifying the Structural Model

Mediation
Moderation
Higher-Order and Hierarchical Component Models

## Stage 2: Specifying the Measurement Models

Reflective and Formative Measurement Models
Single-Item Measures and Sum Scores

## Stage 3: Data Collection and Examination

Missing Data
Suspicious Response Patterns
Outliers
Data Distribution

## Case Study Illustration—Specifying the PLS-SEM Model

### Application of Stage 1: Structural Model Specification

### Application of Stage 2: Measurement Model Specification

### Application of Stage 3: Data Collection and Examination

Path Model Creation Using the SmartPLS Software
Summary
Review Questions
Critical Thinking Questions
Key Terms
Suggested Readings

# Chapter 3: Path Model Estimation

Chapter Preview

## Stage 4: Model Estimation and the PLS-SEM Algorithm

How the Algorithm Works
Statistical Properties
Algorithmic Options and Parameter Settings to Run the Algorithm
Results
Case Study Illustration—PLS Path Model Estimation (Stage 4)
Model Estimation
Estimation Results
Summary
Review Questions
Critical Thinking Questions
Key Terms
Suggested Readings

# Chapter 4: Assessing PLS-SEM Results Part I: Evaluation of Reflective Measurement

Models
Chapter Preview
Overview of Stage 5: Evaluation of Measurement Models
Stage 5a: Assessing Results of Reflective Measurement Models
Internal Consistency Reliability
Convergent Validity
Discriminant Validity
Case Study Illustration—Reflective Measurement Models
Running the PLS-SEM Algorithm
Reflective Measurement Model Evaluation
Summary
Review Questions
Critical Thinking Questions
Key Terms
Suggested Readings

# Chapter 5: Assessing PLS-SEM Results Part II: Evaluation of the Formative Measurement

Models
Chapter Preview

## Stage 5b: Assessing Results of Formative Measurement Models

Step 1: Assess Convergent Validity
Step 2: Assess Formative Measurement Models for Collinearity Issues
Step 3: Assess the Significance and Relevance of the Formative Indicators
Bootstrapping Procedure
Case Study Illustration—Evaluation of Formative Measurement Models
Extending the Simple Path Model
Reflective Measurement Model Evaluation
Formative Measurement Model Evaluation
Summary
Review Questions
Critical Thinking Questions
Key Terms
Suggested Readings

# Chapter 6: Assessing PLS-SEM Results Part III: Evaluation of the Structural Model

Chapter Preview

## Stage 6: Assessing PLS-SEM Structural Model Results

Step 1: Collinearity Assessment
Step 2: Structural Model Path Coefficients
Step 3: Coefficient of Determination (R2 Value)
Step 4: Effect Size f2
Step 5: Blindfolding and Predictive Relevance Q2
Step 6: Effect Size q2

## Case Study Illustration—How Are PLS-SEM Structural Model Results Reported?

Summary
Review Questions
Critical Thinking Questions
Key Terms
Suggested Readings

# Chapter 7: Mediator and Moderator Analysis

Chapter Preview
Mediation
Introduction
Types of Mediation Effects
Testing Mediating Effects
Measurement Model Evaluation in Mediation Analysis
Multiple Mediation
Case Study Illustration—Mediation
Moderation
Introduction
Types of Moderator Variables
Modeling Moderating Effects
Creating the Interaction Term
Results Interpretation
Moderated Mediation and Mediated Moderation
Case Study Illustration—Moderation
Summary
Review Questions
Critical Thinking Questions
Key Terms
Suggested Readings

# Chapter 8: Outlook on Advanced Methods

Chapter Preview
Importance-Performance Map Analysis
Hierarchical Component Models
Confirmatory Tetrad Analysis
Dealing With Observed and Unobserved Heterogeneity
Multigroup Analysis
Uncovering Unobserved Heterogeneity
Measurement Model Invariance
Consistent Partial Least Squares
Summary
Review Questions
Critical Thinking Questions
Key Terms
Suggested Readings 