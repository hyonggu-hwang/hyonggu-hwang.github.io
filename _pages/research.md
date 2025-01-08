---
title: ""
permalink: /research/
author_profile: false
---
## Research Interests
Corporate finance, household finance, industrial organization, structural estimation

<hr> 

## Predoctoral Research
* <strong>University of Chicago, Department of Economics (2024)</strong><br>
  <details>
  <summary>Full-time RA for [Alexander Torgovitsky](https://a-torgovitsky.github.io), 2024</summary>
  <br> 

    Before starting graduate school at UIUC Gies, I briefly (for about six months) worked as a research assistant for Professor Alexander Torgovitsky on an econometrics proejct studying whether experiments can validate structural models. 
    <br>
    I was in charge of reviewing and profiling a program written in Julia that solved a dynamic model of labor supply. My report included a summary of this model and a detailed description of how we solved the model using backward induction. Although I did not write the original code, I contributed to speeding up the program and choosing the most appropriate non-linear optimization solver and algorithm for our problem. Overall, I learned how one can write and solve a behavioral model involving stochastic utility shocks and gained experience in estimating a structural model. 
    <br>
    I also worked on developing a pipeline for the project using task management softwares such as Snakemake, Nextflow and Scriptflow. Wikipedia defines these as softwares used for composing and executing a series of computational and data manipulation steps (i.e. workflows) in a scientific application. Since the project involved a very large number of simulations and estimations, I developed code scripts for orchestrating job submissions on the university computer networks. 

  </details>

* <strong>University of Chicago, Becker Friedman Institute(2024)</strong><br>
  <details>
  <summary>Predoctoral RA for [Alexander Torgovitsky](https://a-torgovitsky.github.io) and [Pietro Tebaldi](https://www.pietrotebaldi.com), 2020-2022</summary>
  <br> 

    I work with Professor Alexander Torgovitsky at the University of Chicago to develop an R package for semiparametric demand estimation. The econometric method embodied in this project is an extension of the nonparametric discrete choice model presented in [Tebaldi, Torgovitsky, and Yang (Econometrica 2023)](https://onlinelibrary.wiley.com/doi/abs/10.3982/ECTA17215). The nonparametric model relaxes distributional assumptions about the latent valuations behind a consumer's utility, whereas in traditional approaches, the valuations are specified to be in a parametric family. (For example, the logit model requires that the latent valuations follow type I extreme value distribution.) The semiparametric model is similar in that it leaves the distribution of valuations unspecified, but it differs from the nonparametric model in that it parametrizes the impact of observable consumer- and product-specific characteristics on indirect utility with a linear function. 
    <br>
    The model allows one to compute sharp bounds for the target parameter of interest, whether it be counterfactual choice shares of a certain product or consumer surplus. In characterizing these bounds, Tebaldi et al. (2019) establishes the idea of a minimal relevant partition (MRP), which refers to a collection of sets within the space of latent valuations that would lead to identical choice behavior under all relevant empirical and counterfactual prices. Tebaldi et al. (2019) further proves that bounds for target paramters can be characterized simply in terms of how the unknown distribution of valuations places mass on the sets in the MRP. Using this result, the semiparametric model uses linear programming to develop and compute estimators of the bounds.
    <br>
    I have contributed to the project in the following ways. On the programming side of things, I wrote code for setting up the linear programming models and for visualizing the MRP sets under different price combinations (i.e. consumer choice decisions given different markets). I have also been in charge of profiling the functions in our package, which means that I conduct performance tests using R packages such as 'profvis' and identify any bottlenecks in our code. I then compare different solutions to the problem and aim to enhance the speed of our algorithm or resolve memory issues. In many cases, this has been achieved by parallelizing or vectorizing parts of our code. 
    <br>
    I have also worked on creating simulations and comparing the results against our theoretical expectations. For example, I would vary the coefficient on the characteristic-covariate in the standard indirect utility model (i.e. vary the degree of impact that a product- or consumer-specific characteristic has on the consumer's utility). Such a change in utility may alter choice decisions and result in a different compositition of the MRP, which may lead to varying bounds for the target parameters as well. I have learned that a simulation exercise such as this one can also be useful for discovering unforseen glitches and enhancing an algorithm. 
    <br>
    Lastly, I am involved with the general building of the package. This includes keeping program files well maintained on GitHub, writing unit tests, and composing 'roxygen' descriptions for the pacakge manual. Another interesting, less everyday aspect of package development was to review and compare existing R packages for demand estimation. This was beneficial in that we could determine the types of data structure that our potential users would feel most familiar with and also weigh the pros and cons of the most widely used interfaces. 
  </details>

* <strong>College of Wooster</strong><br>
  Undergraduate RA positions
  
   for Matthew Histen, [Brooke Krause](https://sites.google.com/view/brookekrause/home) and [Marian Frazier](https://wooster.edu/bio/mafrazier/), 2017-2020