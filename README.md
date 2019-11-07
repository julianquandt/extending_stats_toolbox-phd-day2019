# Extending the Statistical Toolbox @ BSI PhD-Day 2019

# Content

This is the repository of __Extending the Statistical Toolbox__ @ BSI PhD-Day 2019.

1. The PowerPoint Slides as PPTX and PDF
1. `R`-code producing the plots used on the slides
1. Additional material (`R`-code and ready-to-read .html version) on Bayesian Mixed-Effects Models in `brms`. The material has more information than is mentioned on the slides.
More extensive slides on this topic (that contain all the topics mentioned in the material) can be found [HERE](https://github.com/julianquandt/brms-intro-SIPS2019).

[__Download all files__](https://github.com/julianquandt/extending_stats_toolbox-phd-day2019/archive/master.zip)

# Reading List

## Introduction to Bayesian Statistics

### Books

- [Statistical Rethinking](https://xcelab.net/rm/statistical-rethinking/) <-- This is a must-read IMO!
    - [Web lectures about the book](https://www.youtube.com/watch?v=4WVelCswXo4&list=PLDcUM9US4XdNM4Edgs7weiyIguLSToZRI)
    - [all the r-code in the book done in tidyverse and brms instead](https://bookdown.org/ajkurz/Statistical_Rethinking_recoded/)
- [Doing Bayesian Data Analysis](https://www.elsevier.com/books/doing-bayesian-data-analysis/kruschke/978-0-12-405888-0)
- [Bayesian Data Analysis: The Bible of Bayesian Data Analysis](http://www.stat.columbia.edu/~gelman/book/)

### Papers and Tutorials

- [How to become a Bayesian in eight easy steps: An annotated reading list](https://link.springer.com/article/10.3758/s13423-017-1317-5)
- [Toward a principled Bayesian workflow in cognitive science](https://arxiv.org/abs/1904.12765)

### brms specific

- [Overview of brms](https://cran.r-project.org/web/packages/brms/vignettes/brms_overview.pdf)
- [another one](https://cran.r-project.org/web/packages/brms/vignettes/brms_multilevel.pdf)
- [and a very practical one](https://cran.r-project.org/web/packages/brms/vignettes/brms_multilevel.pdf)
- [Model families 1](https://cran.r-project.org/web/packages/brms/vignettes/brms_families.html#beta-models)
- [Model families 2](https://rdrr.io/cran/brms/man/brmsfamily.html)


## On the topics mentioned in the presentation

### Critique of current implementation of NHST

- [The Statistical Significance Filter Leads to Overoptimistic Expectations of Replicability](https://www.sciencedirect.com/science/article/pii/S0749596X18300640)
- [Redefine Statistical Significance](https://www.nature.com/articles/s41562-017-0189-z)
- [Abandon Statistical Significance](https://www.tandfonline.com/doi/full/10.1080/00031305.2018.1527253)
- [Why Psychologists Must Change the Way They Analyze Their Data](https://www.ejwagenmakers.com/2011/WagenmakersEtAl2011_JPSP.pdf)
- [A Practical Solution to the Pervasive Problems with p values](https://www.ejwagenmakers.com/2007/pValueProblems.pdf)

### Why Bayes Factors are Better...

- [The philosophy of Bayes factors and the quantification of statistical evidence](http://www.philos.rug.nl/~romeyn/paper/2015_morey_et_al_-_bayes_factors.pdf)
- [Sequential hypothesis testing with Bayes factors: Efficiently testing mean differences](https://www.ncbi.nlm.nih.gov/pubmed/26651986)
- [How Bayes factors change scientific practice](https://www.sciencedirect.com/science/article/pii/S0022249615000607)
- [Four reasons to prefer Bayesian analyses over significance testing](https://link.springer.com/article/10.3758/s13423-017-1266-z)

### ...But why they are Not

#### Problems with Bayes Factors

- [Avoiding Model Selection in Bayesian Social Research](http://www.stat.columbia.edu/%7Egelman/research/published/avoiding.pdf)
- [Dance of the Bayes factors ](http://daniellakens.blogspot.com/2016/07/dance-of-bayes-factors.html)
- [Incorporating Bayes factor into my understanding of scientific information and the replication crisis](https://statmodeling.stat.columbia.edu/2018/03/10/incorporating-bayes-factor-understanding-scientific-information-replication-crisis/)
- [If you think p-values are problematic, wait until you understand Bayes Factors](http://datacolada.org/78a)
- [Bayes Factors bias the estimate when using them in sequential sampling](http://www.timvanderzee.com/sequential-sampling-with-bayes-factors-effects-on-error-rates-and-parameter-bias/)
- [The Default Bayesian Test is Prejudiced Against Small Effects](http://datacolada.org/35)


#### Seeming advantages are often also possible in the Frequentist Framework

- [Equivalence Testing for Psychological Research: A Tutorial](https://journals.sagepub.com/doi/full/10.1177/2515245918770963)
- [Improving Inferences about Null Effects with Bayes Factors and Equivalence Tests](https://www.ncbi.nlm.nih.gov/pubmed/29878211)
- [Examining Non-Significant Results with Bayes Factors and Equivalence Tests](http://daniellakens.blogspot.com/2017/01/examining-non-significant-results-with.html)
- [Performing high‐powered studies efficiently with sequential analyses](https://onlinelibrary.wiley.com/doi/abs/10.1002/ejsp.2023)


### Beyond NHST and Bayes Factors

- [Statistical Rethinking](https://xcelab.net/rm/statistical-rethinking/) <-- Again read this!
- [Choosing Prediction Over Explanation in Psychology: Lessons From Machine Learning](https://www.ncbi.nlm.nih.gov/pubmed/28841086)
- [It’s not so hard to move away from hypothesis testing and toward a Bayesian approach of “embracing variation and accepting uncertainty.”](https://statmodeling.stat.columbia.edu/2017/04/05/not-hard-move-away-hypothesis-testing-toward-bayesian-approach-embracing-variation-accepting-uncertainty-actually-approach-easier-approach/)
- [Increasing Transparency Through a Multiverse Analysis.](https://www.ncbi.nlm.nih.gov/pubmed/27694465)
- [Moving Towards the Post p < 0.05 Era via the Analysis of Credibility](https://www.tandfonline.com/doi/full/10.1080/00031305.2018.1543136)


## Stay Tuned

- [Andrew Gelman's blog (mainly arguing that we do everything wrong)](https://statmodeling.stat.columbia.edu/)
- [JASP blog by Wagenmakers and co. (stuff on Bayes Factors and open science)](https://www.bayesianspectacles.org/)
- [Solomon Kurz' blog (lots of fun bayesian stuff)](https://solomonkurz.netlify.com/post/)
- On twitter follow [EJ Wagenmakers](https://twitter.com/EJWagenmakers), [Paul Bürkner](https://twitter.com/paulbuerkner), [Matti Vuorre](https://twitter.com/vuorre), [Shravan Vasishth](https://twitter.com/shravanvasishth), [Richard McElreath](https://twitter.com/rlmcelreath?lang=en)
