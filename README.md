# Weigthing-Survey-Data-with-Alteryx
I illustrate the process of weighting (‘raking’) survey data and conducting a linear regression-weighted least squares analysis with Alteryx. 


Overview of Use Case:

In this article, we are going to illustrate the process of weighting (‘raking’) survey data and conducting a linear regression-weighted least squares analysis with Alteryx. We are going to adopt the actual data we collected in one of our research studies which examines the impact of Syrian refugees on fear of crime in Turkey.
 

Describe the business challenge or problem you needed to solve: 

According to the United Nations, the world is witnessing the highest levels of displacement on record making the refugee problem a global one. The current use case involves the survey data administered by the authors as a part of scientific research to evaluate the impact of Syrian refugees on fear of crime in Turkey. Since the beginning of the Syrian crisis, millions of refugees fled the country and they took refuge in other countries, especially the proximate ones. Turkey is one of them and currently hosting the largest number of (Syrian) refugees. The social consequences of such a large number of refugees are worth studying in many aspects. 

Most surveys are likely to have the problem of under/over representation with certain characteristics. Survey weighting aims at re-balancing the data to reflect the population more accurately and compensating the differences between the sample and target population. It is also known as sample balancing or raking the data. To this end, we need to calculate a survey weight for each respondent in terms of one or multiple demographic variables and then include this new weight variable into the regression analysis. The regression will take the weight into account while calculating the regression coefficients. 

 
Describe your working solution: 

We use survey data collected via Twitter from 786 respondents from 53 different provinces of Turkey. In addition to that we also integrated to our dataset the demographic statistics which were obtained from Turkish Statistical Institute (TUIK). 

 
