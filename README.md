# Project 4: Causal Inference

### [Project Description](doc/project4_desc.md)

Term: Spring 2021

+ Team #3
+ Projec title: Causal Inference Algorithms Evaluation
+ Team members
	+ Fang, Zi zf2258@columbia.edu
	+ Gao, Catherine cyg2107@columbia.edu
	+ Sang, Siyuan ss6165@columbia.edu
	+ Washington, Eve esw2175@columbia.edu

+ Project summary: In this project, we evaluate three causal inference algorithms to compute the average treatment effect (ATE) on two distict datasets and compare their computational efficiency and performance. One dataset contains high dimensional data and another contains low dimensional data. We will use L1 penalized logistic regression to estimate the propensity scores for these two datasets then apply the three methods to calcualte ATE for each dataset. Below is a summary of the results:

| **Algorithm** | **Propensity Score Estimation** | 
|:-------------|:-------:|
| Propensity Scores Matching (full)    | L1 penalized logistic regression|
| Doubly Robust Estimations  | L1 penalized logistic regression| 
| Stratification | L1 penalized logistic regression| 

	
**Contribution statement**: 

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.


```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
