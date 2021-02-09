<a id='section_6'></a>




<h1 align = "center">1990 California Housing Prices</h1>
<p align = "center">Author: Gilbert Noriega</p>

[About the Project](#section_1) || [Data Dictionary](#section_2) ||  [Project Plan](#section_4) || [How to Reproduce](#section_5)


<br>

<a id='section_1'></a>
## About the Project
> In this project, we will use California Housing Prices from the 1990 California census to predict the median housing price for districts. 
___

<br>

## Background
> The district housing prices are currently estimated manually by experts. This team gathers up-to-date information about a district and when they cannot get the median housing prices, they estimate using a complex set of rules. This is costly and time-consuming, and their estimates are not that great. In cases where they manage to find out the actual median housing price, they often realize that their estimates were off by more than 20%. 

___

<br>

>*Acknowledgement: This Project is from the Hands-On Machine Learning book by O'Reilly

___

<br>

## Goals
>It is your task to train a model to predict a district's median housing price, given other data about the district.
  
[back to the top](#section_6)

___

<br>

<a id='section_2'></a>
## Data Dictionary

| Features | Definition |
| :------- | :-------|
| longitude | longitude coordinate |
| latitude | latitude coordinate |
| housing_median_age | median age for houses in the district |
| total_rooms | numver of rooms in the district |
| total_bedrooms | number of bedrooms in the district |
| population | number of people living in the district |
| households | number of houses in the district |
| median_income | median_income of the residents in tens of thousands |
| ocean_proximity | how close the district is to the bay |



<br>

|  Target  | Definition |
|:-------- |:---------- |
|  median_house_value  | median values of houses in a district |

<br>



[back to the top](#section_6)
___

<br>

<a id='section_4'></a>
## Project Plan: Breaking it Down

>- acquire
>    - acquire data
>    - turn into a pandas dataframe
>    - summarize the data
>    - plot distribution
>
>- prepare
>    - address data that could mislead models
>    - create features
>    - scale the data
>    - split into train, validate, test
>
>- explore
>    - retrieve correlation values of all variables
>    - create correlation charts
>    - document and consider the results for modeling
>
>- model and evaluation
>    - find which features are most influential 
>    - try different algorithms
>    - evaluate on train
>    - evaluate on validate
>    - fine tune hyperparameters
>    - select best model and test to verify
>
>- conclusion
>    - summarize findings
>    - provide next steps


[back to the top](#section_6)

___

<br>

<a id='section_5'></a>
## How to Reproduce

>1. Download csv from [here](https://github.com/gilbert-noriega-ii/california-housing-prices/raw/main/datasets/housing/housing.csv)
>2. Run a jupyter notebook importing the necessary libraries and functions.
>3. Follow along in final_notebook.ipynb or forge your own exploratory path. 

[back to the top](#section_6)
