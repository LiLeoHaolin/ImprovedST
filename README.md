# Computing Codes for the Paper "Improving the within-Node Estimation of Survival Trees while Retaining Interpretability"
### Haolin Li*, Yiyang Fan*, Jianwen Cai#


## Description

This repository contains computing codes for the paper "Improving the within-Node Estimation of Survival Trees while Retaining Interpretability". Please click [here](https://onlinelibrary.wiley.com/doi/abs/10.1111/biom.13821) for the full text of the paper.

## Folders

### 1-Data Generation

In this folder, we summarize the computing codes for generating survival data following a Weibull hazard model. The names of the code and the corresponding simulation scenarios in the paper are as follows,
(simulated data structure)

* *data_generation_1.r* - tree-based effect, 100 sample size, 80% event rate.
* *data_generation_2.r* - tree-based effect, 100 sample size, 50% event rate.
* *data_generation_3.r* - tree-based effect, 300 sample size, 50% event rate.
* *data_generation_4.r* - tree-based effect, 300 sample size, 20% event rate.
* *data_generation_5.r* - linear covariate effect, 100 sample size, 80% event rate.
* *data_generation_6.r* - linear covariate effect, 100 sample size, 50% event rate.
* *data_generation_7.r* - linear covariate effect, 300 sample size, 50% event rate.
* *data_generation_8.r* - linear covariate effect, 300 sample size, 20% event rate.
* *data_generation_9.r* - nonlinear covariate effect, 100 sample size, 80% event rate.
* *data_generation_10.r* - nonlinear covariate effect, 100 sample size, 50% event rate.
* *data_generation_11.r* - nonlinear covariate effect, 300 sample size, 50% event rate.
* *data_generation_12.r* - nonlinear covariate effect, 300 sample size, 20% event rate.

### 2-Analysis

In this folder, we summarize the computing codes for fitting the proposed survival tree ensemble method and comparing the concordance index with single tree approach. The names and descriptions of the files are as follows,
(input data structure, output)

* *analysis_1.r* - tree-based effect, 100 sample size, 80% event rate.
* *analysis_2.r* - tree-based effect, 100 sample size, 50% event rate.
* *analysis_3.r* - tree-based effect, 300 sample size, 50% event rate.
* *analysis_4.r* - tree-based effect, 300 sample size, 20% event rate.
* *analysis_5.r* - linear covariate effect, 100 sample size, 80% event rate.
* *analysis_6.r* - linear covariate effect, 100 sample size, 50% event rate.
* *analysis_7.r* - linear covariate effect, 300 sample size, 50% event rate.
* *analysis_8.r* - linear covariate effect, 300 sample size, 20% event rate.
* *analysis_9.r* - nonlinear covariate effect, 100 sample size, 80% event rate.
* *analysis_10.r* - nonlinear covariate effect, 100 sample size, 50% event rate.
* *analysis_11.r* - nonlinear covariate effect, 300 sample size, 50% event rate.
* *analysis_12.r* - nonlinear covariate effect, 300 sample size, 20% event rate.

## References

Fan, Y., Li, H., Cai, J. (2024+). Improving the within-Node Estimation of Survival Trees while Retaining Interpretability. Manuscript Submitted for Publication.
