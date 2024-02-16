# Utrecht-Regression
In the pursuit of formulating a prognostic framework for the market valuation of residences within the Utechert locale, the focal point rests upon delineating the retail worth as the reliant variable. Diverse factors serve as the autonomous variables within this framework, encompassing attributes such as “lot.len”, “lot.width”, “lot.area”, “buildyear”, “taxvalue”, “zipcode”, “monument”, “energyeff”, “bedroom”, “bathrooms”, and “balcony”. 

#### Table of Contents  
[Purpose and variable description](#headers)  
[Emphasis](#emphasis)  
...snip...    
<a name="headers"/>
## Variable Description
Dependent variable :

retail value: the market value of a house. 
Quantitative, Continuous, Euros
Predictors:
id: a number between 0 and 100000 that is a unique identifier for each house. 
Qualitative, Categorical

zip code: Each house has a zipcode corresponding to the area the house is in. 
Qualitative, Categorical

lot-len: the length in meters of the plot of land the house is built on.
Quantitative, Continuous, Square Meters

lot-width: the width in meters of the plot of land the house is built on. 
Quantitative, Continuous, Square Meters

Lot-area: the total area of the plot of land on which the house is built. 
Quantitative, Continuous, Square meters

house-area: The living area of the house is in square meters.
Quantitative, Continuous, Square meters

Garden-size: The size of the garden in square meters.
Quantitative, Continuous, Square meters

x-coor: the x-coordinate describing the location of the house.
Qualitative, Categorical

y-coor: the y-coordinate describing the location of the house. 
Qualitative, Categorical

build year: The year that the house was built.
Quantitative, Discrete

bathrooms: Number of bathrooms in the house
Quantitative , Discrete

energy-eff: This value is either 0 or 1. If it is 1, that means that the house is energy efficient. 
Qualitative, Categorical

monument: Some houses in Utrecht, especially older houses, are considered monuments. 
Qualitative, Categorical

<a name="Variable Distribution"/>
# Predicted variables distribution
<img width="259" alt="image" src="https://github.com/AbdelrahmanShehataS/Utrecht-Regression/assets/125851664/c57c61f5-e5cb-4827-b65c-fc7aa62d6af2">


The histogram shows that the retail values, which is our predicted variable, are roughly distributed like a normal curve with a slight skewness to the right. The bandwidth of the graph is set to 100k. 
