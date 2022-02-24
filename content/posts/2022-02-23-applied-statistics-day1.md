---
title: applied-statistics-day1
date: 2022-02-23 05:19:00
tags:
    - Statistics
categories:
    - Statistics
keywords:
    - Statistics
---
This post includes the notes I learn from MPI statistics workshop (day1). The constructor of the course is Angelo Valleriani, from MPI. First he
recommend a reading:
[The Art of Statistics Learning from Data](https://www.thalia.de/shop/home/artikeldetails/A1041325654) (David Spiegelhalter). Other references, Probability and Statistical Inference (10 ed, Pearson) and Principles of Statistics (Dover edition, New York, 1979). 

**Sample (random collection from the population) vs. Population**
A quantity such as mean is called **parameter** when it referes to the eintire **population**. The same quantity is called **statistic** when it refers to a **sample**.

The concept of *point estimator* and *point estimate*. *Estimator* is from measurement, and *estimate* is after measurement. CAPITAL letters are random variables and small letters are numbers. 

? Minus one in degree of freedom

Discrete-type data, continuous-type data
Often, discrete type data are modeled as continous ones for mathematical convenience. Continous-type data are always truncated to some decimal point. Therefore it is important to first distinguish the data is discrete or continuous.

Histogram
- frequency histogram
- relative frequency histogram
- **density histogram**: obtained from relative frequency histogram by dividing the height of each bar by the width of the bar. Maybe it is the best way to visualzie the distribution of your data especially in continuous-type data.

?Kernel density estimator (KDE)  
For Continous-type data, the KDE is a method to derive a continuous line out of the data.

?Interpolation  
  
?**q-q plot** or **probabilty plot**
The probabilty plot helps understanding if the population follows a normal distribution.  

Central Limit Theorem  
CLT states that a large sum of independent random variables with finite mean and variance has an approximate normal distribution.   

t-interval for one mean  
When the **variance is not known** (which is usually the case), we have to modify our approach slightly. The t-distribution now substitutes the normal distribution.  

Confidence interval for the difference of two independent means  
When we have **two independent samples**, say from two different populations, sometimes we want to estimate the **difference of their population means**. We can still use the t-distribution but take care of some restrictions. **Let us assume that the CLT holds or the populations come from normal distributions**. 

Binomial distribution (to be continued)
