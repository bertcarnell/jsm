# jsm2024

The Joint Statistical Meetings (JSM) were held in Portland, Oregon Aug 3-8, 2024.

![JSM Logo](img/jsm_2024_logo.png)

## NISS Luncheon (8/4 1200)

### Veridical Data Science

Talked with Professor Bin Yu (UC Berkeley) about her book: [Veridical Data Science](https://vdsbook.com/).

### AI in Practice:  Transitions and Tools

Dr. Nancy McMillan, Battelle

### Harvard Data Science Review

Xiao-Li Meng showed this great resource [here](https://hdsr.mitpress.mit.edu/) and [here](https://datascience.harvard.edu/)

## Recent Developments in Causal Inference (8/4 1600)

### A Meta-Learning Method fo Estimation of Causal Excursion Effects to Assess Time-Varying Moderation

Micro-randomized Trials - The idea that you can treat a longitudinal study where the same treatment is applied multiple times and treat it like a raondomized trial.

Applications to Next Best Offer are possible.

Jieru Shi - University of Michigan

Need to learn more about doubly robust estimators for causal inference:  They estimate the Averate Treatment Effect using both regression and inverse probability weighting methods.

### Other Presentation

Beeswarm plots [here](https://r-graph-gallery.com/beeswarm.html) and [here](https://shap.readthedocs.io/en/latest/example_notebooks/api_examples/plots/beeswarm.html)

Can we add this to the torndado package?

## 2024 ASA Statistics in Marketing Doctoral Research Award Finalists Presentation (8/4 0830)

### A Scalable Recommendation Engine for New Users and Items - Boya Xu - Duke

### Optimal Comprehensible Targeting

Method to make decision tree-type comprehensible targeting narratives.  - Walter Zhang

Price Elasticity

### Real Time Personalization in Dynamic Environments - Hong Deng

### Selecting Data and Parameter Granularities:  A Bayesian Dual-Network Clustering Approach - Mingyung Kim - Wharton School

### Targeted Marketing with Large Batches - Keyan Li - MIT



## Bayesian Causal Inference (8/5 1030)

### A Semiparametric Bayesian Approach for Extreme Quantile Treatment Effects for Heavy-tailed data - Arnab  Aich

Could be useful for balances

### Bayesian Causal Prediction:  Multivariate Graphical Dynamic Models - Luke Vrotsos - Duke

Great talk on how to do Bayesian Synthetic controls.

With Mike West at Duke

references:

- [Comparative Politics and the Synthetic Control](https://economics.mit.edu/sites/default/files/publications/Comparative%20Politics%20and%20the%20Synthetic%20Control.pdf)
- [The Economic Costs of Conflict: A Case Study of the Basque Country](https://economics.mit.edu/sites/default/files/publications/The%20Economic%20Costs%20of%20Conflict.pdf)
- [Inferring causal impact using Bayesian structural time-series models](https://arxiv.org/abs/1506.00356)
- [GPU Accelerated Bayesian Learning and Forcasting in Simultaneous Graphical Dynamic Linear Models](https://projecteuclid.org/journals/bayesian-analysis/volume-11/issue-1/GPU-Accelerated-Bayesian-Learning-and-Forecasting-in-Simultaneous-Graphical-Dynamic/10.1214/15-BA946.pdf)
    - [code](https://github.com/lutzgruber/gpuSGDLM)

### Bayesian Sensitivity Analysis for Extending Inferences to a Target Population without Positivity - Jun Lu - University Illinois

### Causally Sound Priors for Binary Experiments - Nicholas Irons - U Washington

### Horeshoe Priors for Sparse Dirichlet-Multinomial Models - Yuexi Want - University of Illinois

### Incorporate external control data into RCT using propensity score stratification and mixture prior - Xun Xu - U Texas



## Advanced Statistical Methods in Non-parametric Statistics and Causal Inference for Complex Data Structures (8/5 1400)

### Identifying Significant Mediators in High Dimensional Causal Graphical Models with FDR Control - Xiufan Yu, Notre Dame

### De-confounding Causal Inference using Latent Multiple-Mediator Pathways - Yubai Yuan - Penn State

### Causal Inference on Distribution Functions - Dehan Kong - U Toronto

[paper](https://arxiv.org/abs/2101.01599)
[code](https://github.com/kongdehanstat/causaldistributionfunction)

### Nonlinear Global Frechet Regression for Random Objects via Weak Conditional Expectation - Satarupa Bhattacharjee - Penn State

### Smoothed Robust Phase Retrieval - Zhong Zheng - Penn State


## The Application of Generative Models in Marketing Research and Practice (8/6 1030)

### Using GPT for Market Research - Ayelet Israeli - Harvard Business School

- Used GPT as a random customer sampling mechanism and examined the distribution of its responses
- When prompted as a random customer, GPT exhibits behaviors consistent with economic theory (price elasticity)
- GPT-based estimates are realistic and consistent with values obtained from existing research

### Using Multimodal LLM to Extract and Discover Features from Ad Images - Poppy Zhang, Meta

Trained a classifier to extrat the important parts of an image for Meta customers

[nielsen study](https://www.nielsen.com/insights/2017/when-it-comes-to-advertising-effectiveness-what-is-key/)

Lots of other Insights from Nielsen
 - [here](https://www.nielsen.com/insights/)
 - [here](https://www.nielsen.com/insights/2022/roi-report/)
 - [here](https://www.nielsen.com/insights/2024/are-you-investing-performance-marketing-for-right-reasons/)

Multi-model LLM

[LLAVA](https://llava-vl.github.io/)

Results:  Top Advertisers (controlling for sales region, industry, and campaign size)

- show price (negative)
- contain promotion
- show positive emotion
- show experience of using the product
- comparative
- show endorsement
- use humor
- visually complext (negative)

## IMS Medallion Lecture:  Winners with Confidence:  Discrete Argmin Inference Using Cross-Validated Exponential Mechanism - Ji Zhu (8/6 1400)

[paper](https://arxiv.org/abs/2408.02060)

Idea was how to say which machine learning results were actually significantly different from each other

## Robust Causal Inference (8/7 0830)

### Adaptive Experiments with Delayed Outcomes - Waverly Wei - USC

Create adaptive experiments where you measure some things early, and then other measures later, and you want to adaptively change the experiment

### Bias Correction for Randomization-Based Average Treatment Effect Estimation in Inexactly Matched Observational Studies - Siyu Heng - NYU

### Design-based causal inference for balanced incomplete block designs - Nicole Pashley - Rutgers

[Nicole Pashley](https://sites.google.com/view/npashley/home?authuser=0)
[Taehyeon Koo](https://taehyeonkoo.github.io/)

### Random distribution shift and causal inference - Zhonghua Liu - Columbia



## New Methods in Causal Inference and Reinforcement Learning for Personalized Decision-Making (8/7 1030)

### The promises of multiple outcomes - Linbo Wang - U Toronto

[website](https://sites.google.com/site/linbowangpku/home)
[paper](https://arxiv.org/abs/2012.05849)
[slides](https://drive.google.com/file/d/1jwkefODWm7KBSzl0RNMUT9MABIC8YbIE/view)

### Balancing Personalization and Pooling: Decision-making and Statistical Inference with Limited Time Horizons - Yongyi Guo

### Did We Personalize? Assessing Personalization by an Online Reinforcement Learning Algorithm Using Resampling - Raaz Dwivendi - UC Berkeley

### Further Results on Target Trials and Structural Nested Models: Emulating RCTs using Observational Longitudinal Data - Anish Agarwal - Columbia



## Causal Inference on Networks and Complex Data Structures (8/7 1400)

### Analyzing Political Polarization in the Presence of Partially Observed Social Networks - Sharmodeep Bhattacharyya, Oregon State University

### Causal Inference Under Network Interference with Noise - Daniel Sussman, Boston University

### Exploratory Data Analysis, Confirmatory Data Analysis and Replication in the Same Observational Study: A Two Team Cross-Screening Approach to Studying the Effect of Unwanted Pregnancy on Mothers' Later Life Outcomes - Dylan Small, University of Pennsylvania

### Nonsense Associations in Markov Random Fields - Elizabeth Ogburn, Johns Hopkins University


## COPSS Distinguished Achievement Award and Lectureship (8/7 1600)

#### Pre-Training and the Lasso

[paper](https://arxiv.org/abs/2401.12911)
[paper](https://arxiv.org/html/2401.12911v1)
[similar presentation - same slides](https://www.youtube.com/watch?v=zIGc5Z2MaYM)
[ptLasso](https://github.com/erincr/ptLasso/)
[web](https://erincr.github.io/ptLasso/)
[Erin Craig](https://www.erincraig.me/)












