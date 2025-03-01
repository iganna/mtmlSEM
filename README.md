# mtmlSEM

Construction and estimation of mtmlSEM models :)

## Description

There are a plethora of methods for genome-wide association studies. However, only a few of them may be classified as multi-trait and multi-locus, i.e. consider the influence of multiple genetic variants to several correlated phenotypes. We propose a multi-trait multi-locus model which employs structural equation modeling (SEM) to describe complex associations between SNPs and traits - multi-trait multi-locus SEM (mtmlSEM). The structure of our model makes it possible to discriminate pleiotropic and single-trait SNPs of direct and indirect effect. 
We also propose an automatic procedure to construct the model using factor analysis and the maximum likelihood method. For estimating a large number of parameters in the model, we performed Bayesian inference and implemented Gibbs sampling. An important feature of the model is that it correctly copes with non-normally distributed variables, such as some traits and variants.


## Pipeline

To construct the model and add SNPs then, use the following scripts:
`pipeline_spart.py` and `pipeline_add_snps.py`.
To optimise parameters and get predictions, follow the next notebooks:
`mcmc_estimate.ipynb` and `mcmc_predict.ipynb`


## References

A.A.Igolkina et al., *Multi-trait multi-locus SEM model discriminates SNPs of different effects*

## Authors

**Anna Igolkina** [e-mail](mailto:igolkinaanna11@gmail.com).    
**Georgy Meshcheryakov**


## License information

Scripts licensed under the [MIT license](https://opensource.org/licenses/MIT).

