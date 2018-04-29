# Analyze A/B Results Udacity Project

The repository contains my third project that I completed towards the Udacity Data Analyst Nanodegree. The purpose of this project was to conduct an A/B test on whether or not a e-commerce website company should implement a new page design, keep their old page or run the experiment for longer and hold off from making a decision.

## Research Question

Since this was an A/B test, the following null and alternative hypothesis were proposed:

* $H_{0}$ : $p_{new}$ - $p_{old} \leq 0$
* $H_{1}$ : $p_{new}$ - $p_{old}$ > 0

In plain English, our null proposes that the views of the new page - the views of the old page would be less than or equal to 0 and our alternative hypothesis proposes that this is greater than zero. Therefore is this a one-sided t-test.

## Viewing the analysis

You can view the analysis by looking at the Jupyter Notebook file or by examining the html file output.

## Libraries used

In this project, I implemented the following Python libraries:

* Pandas
* Numpy
* Random
* Matplotlib
* Statsmodels
