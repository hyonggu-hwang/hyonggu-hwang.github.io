---
title: ""
permalink: /research/
author_profile: false
---
## Research Interests

Corporate finance, household finance, industrial organization, structural estimation


## Predoctoral Research
* <strong>University of Chicago, Department of Economics</strong><br>
Full-time RA for [Alexander Torgovitsky](https://a-torgovitsky.github.io), 2024 <br>
  <details>
  <summary>Dynamic model of labor supply</summary>
  <br> 

    Before starting graduate school at UIUC Gies, I briefly (for about six months) worked as a research assistant for Professor Alexander Torgovitsky on an econometrics proejct studying whether experiments can validate structural models. 
    <br>
    
    I was in charge of reviewing and profiling a program written in Julia that solved a dynamic model of labor supply. My report included a summary of this model and a detailed description of how we solved the model using backward induction. Although I did not write the original code, I contributed to speeding up the program and choosing the most appropriate non-linear optimization solver and algorithm for our problem. Overall, I learned how one can write and solve a behavioral model involving stochastic utility shocks and gained experience in estimating a structural model. 
    <br>

    I also worked on developing a pipeline for the project using task management softwares such as Snakemake, Nextflow and Scriptflow. Wikipedia defines these as softwares used for composing and executing a series of computational and data manipulation steps (i.e. workflows) in a scientific application. Since the project involved a very large number of simulations and estimations, I developed code scripts for orchestrating job submissions on the university computer networks. 

  </details>

* <strong>University of Chicago, Becker Friedman Institute</strong><br>
Predoctoral RA for [Alexander Torgovitsky](https://a-torgovitsky.github.io) and [Pietro Tebaldi](https://www.pietrotebaldi.com), 2020-2022 <br>
  <details>
  <summary>Semiparametric demand estimation</summary>
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

  <details>
  <summary>Insurer competition in U.S. Medicare Advantage markets</summary>
<br> 

    Working with Professor Pietro Tebaldi at Columbia University and his coauthors, I contribute to a project that investigates the value of adding a 'public option' to health insurance exchanges. We consider the Medicare Advantage (MA) program, under which Medicare beneficiaries can opt out of Traditional Medicare (TM) program and enroll in a private-sector insurance plan. The MA program was implemented to diversify the consumer's choice set and to reduce healthcare costs through increased insurer competition. To provide some context, I breifly discuss below the institutional detail of the two programs.   
<br> 
    
    There are a few notable differences between TM and MA. First, coverage: TM only includes Medicare Part A (inpatient) and Part B (outpatient) and requires a separate enrollment for Part D (prescription drug), whereas MA plans are bundled with Parts A, B, and D and usually offer additional benefits such as hearing, dental, or vision. Second, cost structure: TM adopts a fee-for-service payment model and does not have a yearly limit on out-of-pocket costs, whereas MA plans usually do impose such limits for Part A and B services. Lastly, access to providers: TM allows beneficiaries to use any doctor or hospital that takes Medicare, whereas the choice of MA beneficiaries are constrained by the MA plan's provider network and service area.  
<br> 
    
    An interesting aspect of the MA program is the price negotiation that occurs between insurers and providers. Under TM, providers are reimbursed with a fee (calculated by a formula) for each service provided to the beneficiary. They cannot negotiate the payment rate but may choose to reject the rate and opt out of Medicare. On the contrary, under MA, providers have bargaining power against insurers and can form networks with other providers. In this unique setting, insurer competition becomes an important determinant of negotiated hospital prices and overall welfare in the U.S. healthcare industry. Ho and Lee (2017) identify and quantify this mechanism in much detail.  
<br> 
    
    I have contributed to the demand estimation side of the project by augmenting the model presented in Curto, Einav, Levin, and Bhattacharya (2021). We estimate a nested logit model of MA plan demand that accounts for hospital networks and their heterogeneity across plans. To do so, I work with large administrative data sets provided by the Centers for Medicare & Medicaid Services on plan bid, benefits, enrollment, and penetration rates across U.S. counties, while also managing data on hospital and physician networks. The compiled data allow us to derive the demand elasticities which are needed to observe equilibrium outcomes in counterfactual excercies and policy experiments.

  </details>

* <strong>College of Wooster, Departments of Economics and Mathematics</strong><br>
Undergraduate Research Experience ([Link to senior thesis](https://openworks.wooster.edu/cgi/viewcontent.cgi?article=11861&context=independentstudy))
  <details>
  <summary>Undergraduate research positions</summary>
<br> 
    At the College of Wooster, I worked as a departmental research assistant for three different projects, and as a student researcher for the Applied Methods and Research Experience (AMRE) program. 
<br> 
    In Fall 2019, I worked with Professor Marian Frazier of the Statistics & Data Science department to analyze the socio-economic factors of becoming a vegetarian. We considered a logit model using the U.S. National Health and Nutrition Examination Survey (NHANES) data provided by the Centers for Disease Control and Prevention. 
<br> 
    In Spring 2018, I worked with Professor Brooke Krause of the Economics department and contributed to the program evaluation of the Trias project as part of GAAP2. The project studied how enhancement in livestock empowered Tanzanian women to gain economic autonomy and cope with domestic violence. 
<br> 
    In Fall 2017, I worked with Professor Matthew Histen of the Economics department to study historic factors of long-term economic growth, such as political systems, technological inventions, natural disasters, religion, or military size.
<br> 
    In Summer 2019, I worked as a student researcher for Wooster Community Hospital in a team of two more math majors and Professors Jen Bowen (mathematics) and Drew Pasteur (applied statistics). We developed models of physical therapy outcome as measured by the patient's preceived improvement score for different areas of injury. Our models considered demographic characteristics, injury severity, clinical history, comorbidities, and socio-economic factors. Our findings were presented at the American Society of Shoulder and Elbow Therapists conference and at the Applied Methods and Research Experience symposium at the College of Wooster.  

    </details>

  <details>
  <summary>Senior thesis on fire service provision</summary>
<br> 
    Title: A Theory of Fire Service Provision: With an empirical analysis of response time, suppression time, and service output
<br> 
    Advisors: Jim Burnell (Economics), Marian Frazier (Statistics)
<br> 
    Funding: Henry J. Copeland Independent Study Grant ($1490.40), April 2019
<br> 
    Abstract: I introduce a two-stage theoretical framework of fire services that justifies the status of response time as a factor input. In the first stage, the provincial government distributes a budget to its cities, resulting in varied numbers of firefighters and fire engines in each city. In the second stage, each city fire department places its fire stations at spatially optimal locations that minimize expected response times. When a fire occurs, the outputs from these two stages are actualized into dispatch level, response time, and suppression time. These intermediate outputs are then transformed into inputs for producing service output, which I measure in terms of fire spread. Using data on 49,000 fire dispatches that occurred in Gyeonggi Province, South Korea in 2014- 2018, I estimate a set of models for the above outputs. I find evidence for increasing returns to population scale and an 1.9% increase in the number of severe fire outcomes associated with a one-minute delay in response times.

  </details>