
# Generalized Linear Regression (GLM)

In this biological project, we are interested in analyzing the effects of different characteristics of female crabs on the number of their satellites.
Each female crab in the study had a male crab attached to her in her nest.
The study investigated factors that affect whether the female crab had any other males, called satellites, residing nearby her.
The data is from the Horseshoe Crab Research Database. 
Explanatory variables thought possibly to affect this included the female crab's color, spine condition, weight, and carapace width.
The outcome for each female crab is her number of satellites. We will look at the response has a binary random variable:
0 = no satellites, 1 = at least one satellite

>>>>>>> 

## Study Case

To create a model that predicts the probability of having at least one satellite for a crab accurately. 

##  Goal

To accurately predict the likelihood of obtaining the satellite for each crab. 

## Challenges

The first challenge of conducting this study was the existence of some outliers, those points are removed when we clean data using Excel.
The second challenge was finding the most relevant characteristics, we focused on the significant variables to proceed with the analysis.

## Techniques

1. The Correlation plot got us an idea that how the variables are related. And we could find some pair-related variables thus we kept only one of them in the model.

2. The AIC and BIC criteria helped us to end up with two final models.

3. The final model was selected by ANOVA.

4. The prediction model is finally made using Binomial GLM.

5. GGplot is the easy-to-use package in R to create all the cool plots.

## What else I might do

I like to do another analysis by fitting a model that accounts for the discreteness of the outcome, such as Poisson GLM. I will then be able to compare the models.  

