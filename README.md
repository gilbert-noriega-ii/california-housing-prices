<a id='section_6'></a>




<h1 align = "center">1990 California Housing Prices</h1>
<p align = "center">Author: Gilbert Noriega</p>

[About the Project](#section_1) || [Data Dictionary](#section_2) ||  [Initial Hypotheses/Thoughts](#section_3) || [Project Plan](#section_4) || [How to Reproduce](#section_5)


<br>

<a id='section_1'></a>
## About the Project
> 
___

<br>

## Background
> 

___

<br>

>*Acknowledgement: This Project is from the Hands-On Machine Learning book by O'Reilly

___

<br>

## Goals
>
  
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

<a id='section_3'></a>
## Initial Hypothesis & Thoughts

>### Thoughts
>
> - 
> - 

<br>

>### Hypothesis
> - Hypothesis 1: 
>   - H<sub>0</sub>: 
>   - H<sub>a</sub>: 
>
> - Hypothesis 2: 
>   - H<sub>0</sub>: 
>   - H<sub>a</sub>: 
>
> - Hypothesis 3: 
>   - H<sub>0</sub>: 
>   - H<sub>a</sub>: 


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
>    - create a prepare.py to automate the process
>
>- explore
>    - plot correlation values of all variables
>    - test each hypothesis
>    - document and consider the results for modeling
>
>- model and evaluation
>    - set the baseline
>    - find which features are most influential 
>    - try different algorithms: 
>    - evaluate on train
>    - evaluate on validate
>    - select best model and test to verify
>    - create a model.py to automate the process
>
>- conclusion
>    - summarize findings
>    - provide next steps


[back to the top](#section_6)

___

<br>

<a id='section_5'></a>
## How to Reproduce

>1. Download csv from [here](insert link)
>2. Install [prepare.py](insert link), [explore.py](insert link) and [model.py](insert link) into your working directory.
>3. Run a jupyter notebook importing the necessary libraries and functions.
>4. Follow along in final_notebook.ipynb or forge your own exploratory path. 

[back to the top](#section_6)
