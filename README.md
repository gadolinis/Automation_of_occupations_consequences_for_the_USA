# Automation_of_occupations_consequences_for_the_USA

AI and Automation will wreak havoc among the workforce rending a large part of the population useless and without economic value in the next decade or two. Not only automation will take your jobs, but it will make the rich even richer.

## Project motivation

This project was inspired by Vilnius Coding School Data analyst project. I wanted to practice Python Pandas, Seaborn, Numpy and Matplotlib on Employment data from US Bureau of Labor Statistics and Risk of Automation. My initial questions were:

* Which occupations are the most sensitive and the most robust to automation (computerization)?
* What are the jobs lost in the US, if automation takes out occupations with automation probability equal to 0.7 or higher?
* Which US states are the most sensitive and the most robust to automation?
* Compare the most common occupations for automation in the US.

## Which occupations will flourish and which will disappear.

In the charts below you can see the most sensitive and most robust occupations and occupation categories for automation.

![name1](https://github.com/gadolinis/Automation_of_occupations_consequences_for_the_USA/blob/master/img/general_Occupation%20categories%20and%20the%20probability%20of%20automation%20by%20states.png)

![name2](https://github.com/gadolinis/Automation_of_occupations_consequences_for_the_USA/blob/master/img/general_Workers%20numbers%20in%20occupations%20with%205%20highest%20and%205%20lowest%20probabilities%20for%20automation.png)

If you are looking for job opportunities that are less likely to be affected by AI or automation, you can find all occupation probabilities here.

Probability higher than 0.7 representing a "high-risk category, meaning that associated occupations are potentially automatable over some unspecified number of years, perhaps a decade or two" according to the original research paper (The future of employment: How susceptible are jobs to computerisation? Carl Benedikt Frey, Michael A.Osborne). We can look to this probability as to a time frame, where higher probability occupations are likely to be automated sooner.

I assume that US lost job positions, which have a job automation probability of 0.7 or higher (threshold >= 0.7). Lets look, what are job loss in this scenario.

![name4](https://github.com/gadolinis/Automation_of_occupations_consequences_for_the_USA/blob/master/img/general_Lost%20jobs%20ratio%20per%20state%20when%20we%20lost%20jobs%20with%20automatisation%20probability%20equal%20to%200.7%20(Threshold)%20or%20higher.png)

As you see, every state loses around half of job positions. South Dakota and Nevada are the most sensitive and District of Columbia and Massachusetts are the most robust to automation. As you can see below, Nevada and South Dakota have the most occupations with high probability for automation. District of Columbia (DC) also has many occupations with low probability for automation like management, arts, protective service and this explains why DC is so robust to automation.

![name5](https://github.com/gadolinis/Automation_of_occupations_consequences_for_the_USA/blob/master/img/general_Occupation%20categories%20and%20probability%20of%20automatisation%20in%20S.%20Dakota%2C%20Nevada%2C%20DC%20and%20Massachusetts.png)

South Dakota and Nevada have most jobs losses. Lets look, what are biggest occupations they lost. Let's start with Nevada data.

![name8](https://github.com/gadolinis/Automation_of_occupations_consequences_for_the_USA/blob/master/img/general_The%20largest%20most%20likely%20automatable%20occupations%20in%20Nevada.png)

Now let's look to South Dakota

![name9](https://github.com/gadolinis/Automation_of_occupations_consequences_for_the_USA/blob/master/img/general_The%20largest%20most%20likely%20automatable%20occupations%20in%20South%20Dakota.png)

Massachusetts data

![name7](https://github.com/gadolinis/Automation_of_occupations_consequences_for_the_USA/blob/master/img/general_The%20largest%20most%20likely%20automatable%20occupations%20in%20Massachusetts.png)

District of Columbia has lowest sensitivity for automation. Let's check the data.

![name6](https://github.com/gadolinis/Automation_of_occupations_consequences_for_the_USA/blob/master/img/general_The%20largest%20most%20likely%20automatable%20occupations%20in%20District%20of%20Columbia.png)

In conclusion
1. The most robust occupations for automatisations: Saugiausios specialybės nuo automatizacijos: social service, management, computer and mathematical and medicine. The most sensitive: administrative support, production, farming, fishing, forestry, food serving related.
2. US would loss around half of all jobs, if automatisation take out occupations with automatisation probability equal to 0.7 or higher?
3. South Dakota and Nevada are the most sensitive and District of Columbia and Massachusetts are the most robust to automation.
4. Nevada and South Dakota have most occupations with high probability for automation. District of Columbia also has many occupations with low probability for automatisation like management, arts and protective service.

## Data sourse

https://www.kaggle.com/andrewmvd/occupation-salary-and-likelihood-of-automation

https://www.infoplease.com/us/states/state-population-by-rank

The future of employment: How susceptible are jobs to computerisation? Carl Benedikt Frey, Michael A.Osborne


