---
output:
  html_document: default
  pdf_document: default
---
# Bayesian Statistics

Here is a list of interactive applications related to the course *Bayesian Statistics course Level III/IV* .

To use these applications run *rstudio*, and set your workspace to be *Bayesian_Statistics* .

## How to get the files

In order to download the applications to your computer, do the following:

1. Run rstudio
  1. In the console run  
      * install.packages("rmarkdown")
  2. Go to File>New Project>Version Control>Git  
  3. In the section "Repository URL" type: 
      * https://github.com/georgios-stats/Bayesian_Statistics.git

## Applications

### Known distributions

Just some known distributions

Execute command

  > rmarkdown::run("./demo_distributions/demo_distributions.Rmd")

### Central limit Theorem

A demo about the central limit theorem

Execute command

  > rmarkdown::run("./demo_CLT/demo_CLT.Rmd")

### Weak law of large numbers

A demo about the weak law of large number

Execute command

  > rmarkdown::run("./demo_WLLN/demo_WLLN.Rmd")

### Conjugate priors

Explore the behaviour of the posterior distribution, with respect to the hyperparameters of the prior distributions, and the number of observables. 

Execute command

  > rmarkdown::run("./demo_ConjugatePriors/demo_ConjugatePriors.Rmd")


### Compare priors

Explore the behaviour of the posterior distribution, with respect to different priors (and their hyperparameters), and the number of observables. 

Execute command

  > rmarkdown::run("./demo_ConjugateJeffreysLaplacePriors/demo_ConjugateJeffreysLaplacePriors.Rmd")

### Mixture priors

Explore the behaviour of the mixture posterior distribution, with respect to mixture priors (and their hyperparameters). 

Execute command

  > rmarkdown::run("./demo_MixturePriors/demo_MixturePriors.Rmd")
  
  
  