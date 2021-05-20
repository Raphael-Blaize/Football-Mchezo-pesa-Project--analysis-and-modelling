# Football-Mchezo-pesa-Project--analysis-and-moddelling

## Links to the various tools used 

## Links to the various tools used 

Dataset - [Source link](https://drive.google.com/open?id=1BYUqaEEnFtAe5lvzJh9lpVpR2MAvERUc)
Python Notebook - [Notebook]("https://colab.research.google.com/drive/1OQvv2j5OQ9FyrYvx0k3j5FxVzOgxGjIW?usp=sharing")


## Dataset Description

You have been recruited as a football analyst in a company - Mchezopesa Ltd and tasked to accomplish the task below.

A prediction result of a game between team 1 and team 2, based on who's home and who's away, and on whether or not the game is friendly (include rank in your training).

You have two possible approaches (as  shown below) given the datasets that will be provided

Input: Home team, Away team, Tournament type (World cup, Friendly, Other)

Approach 1: Polynomial approach

What to train given:

Rank of home team
Rank of away team
Tournament type
Model 1: Predict how many goals the home team scores.

Model 2: Predict how many goals the away team scores.

Approach 2: Logistic approach

Feature Engineering: Figure out from the home team’s perspective if the game is a Win, Lose or Draw (W, L, D)

#### -- Project Status: [Completed]

## Project Intro/Objective

A prediction result of a game between team 1 and team 2, based on who's home and who's away, and on whether or not the game is friendly (include rank in your training).

### Methods Used
* Descriptive Statistics
* Data Visualization
* Data Analysis
* EDA Analysis
* Machine learning Algorithms
* Kfold cross-validation
* Multicollinearity tests
* Heteroskdasticity tests
   
### Technologies
* Python
* Pandas,Numpy,Gooogle Colab


```python
import pandas as pd # python library that import datasets into a working env and does so much more such as helping in cleaning datasets etc
import numpy as np # offers comprehensive mathematical functions etc
```

 * Data Preprocessing Methods used
    *  Boxplots to get rid of outliers in the data
    *  No null/missing values in the dataset 
    *  No duplicates in the dataset
    *  Concatinating and Merging of columns in the dataset
    *  Dropping of unnecessary columns in the dataset
    *  Creating Dummy variabels
    *  Label  Encoding 
    *  Changing of Date type columns 
    
 * Data Analysis used
      * Univariate Analysis 
          * Frequency Distibutions
          * Bar graphs
          * Descriptive Statistics
              * Standard deviation
              * Mean
              * Variance
              * Skewness
              * Kurtosis
       * Bivariate Analysis
           * Stacked column chart to understand the variables better and how the correlate
           * scatterplots
       * Univariate Analysis 
           * Pair plots
  * Modelling
       * Multicollinearity  tests
           * Using VIF to check for multicollinearity in our dataset
       * Heteroskdestacity tests
            * Residual plots
            * Bartlett's test
       * Machine Learning algorithms
            * Polynomial Regression
            * Logistic Regression
       * K-fold cross validation
       * Grid-search 

   
## Needs of this project
- data exploration/descriptive statistics
- data processing/cleaning - involves taking care of missing data, outliers and duplicates before after merging the datasets
- Data Analysis 
- Modelling


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate

## License
[GPL](https://www.gnu.org/licenses/gpl-3.0.en.html)




           

