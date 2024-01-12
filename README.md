# Analyzing Vancouver Crime in Relation to Wealth using Hypothesis Testing 
STAT 201 202 - Emily Wang, Faraz Hosseinian-Tehrani, Giuliana Kim, Yiran Xiong

### Introduction

In recent years, the picturesque city of Vancouver has been grappling with a mounting concern of crime, with a notable surge in theft cases, which has become an increasingly prevalent issue that poses challenges to the safety and security of its residents. CTV news reported on October 27th of this year that 258 arrests were made in a 2-week period as the Vancouver police department continued the shoplifting crackdown[1]. On October 30th, the B.C. Coalition called for immediate government action on theft, vandalism, and violent crime, and its members say they have reached "epidemic proportions'' across the province[2].

Given the prevalent issue, in our project, we will answer the question: “How do proportions of theft among all crimes differ between neighbourhoods in Vancouver?”. We will be using the crime data set[3] from 2003 to 2023 released by the VPD, to investigate the proportions of robbery, theft of motor vehicles, theft from automotives, and theft under $5,000. The two neighbourhoods we will be comparing are Strathcona (often referred to as Downtown Eastside), the poorest neighbourhood in Vancouver, according to Wikipedia[4] and CBC[5], and Kerrisdale, which is one of the richest neighbourhoods in Vancouver[6][7]. Our location parameter of interest will be the difference of proportions between the two neighbourhoods, and our scale parameter of interest will be the standard deviation. We believe that these two parameters will help us answer our question at hand - comparing the proportions of theft in the two neighbourhoods.

An article published by CBC stated that there were higher incidences of violent crime in poor Vancouver neighbourhoods, and higher incidences of theft in wealthier Vancouver neighbourhoods[8]. Based on this report, we would expect the proportion of theft in Strathcona to be different than the proportion of theft in Kerrisdale.

### Hypotheses

Null Hypothesis: The proportion of thefts relative to all crimes is equal between Strathcona and Kerrisdale.

Alternate Hypothesis: The proportion of thefts relative to all crimes is not equal between Strathcona and Kerrisdale.

### Methods

Our report conducts a data analysis of crime data from two Vancouver communities, Kerrisdale and Strathcona, with a focus on the proportion of theft-related crimes in these areas. From our process, we first perform a hypothesis test to determine whether the proportions of theft to other crimes are statistically different between Kerrisdale and Strathcona. We will either reject or fail to reject the null hypothesis, which is that the proportion of thefts relative to all crimes is equal between Strathcona and Kerrisdale, by calculating the p-value and comparing it to a significance value of 5%. We will then calculate a 95% confidence interval for the true difference in proportion between the two neighbourhoods. The hypothesis test and confidence intervals will be obtained through both asymptotic and bootstrapping methods.

Several factors strengthen our report and make it reputable. Firstly, our crime data comes directly from the Vancouver Police Department. Using official data lends credibility to the analysis. Secondly, our report analyses the data by summarizing and creating informative plots to visualize the distribution of crime types over the years in Kerrisdale and Strathcona. The tidy data format and analysis make the data easier to understand and work with.
