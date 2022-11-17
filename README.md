
# Project 2: Ames Housing Data and Kaggle Challenge
## Yanda DSI 33
# Contents
 -  ### Background and Problem Statement
 -  ### Data Cleaning
 -  ### EDA and Data Visualisation
 -  ### Initial Model (Baseline)
 -  ### Feature Engineering
 -  ### Final Model
 -  ### Conclusion 

 ## Background
Real Sky is a real estate development company situated in the US. However, the company has been steadily losing profit on the houses they have been building. They are competing with other real estate companies such as Blue Note that uses traditional methods of engineering new development plans. Real Sky has approached us, their in-house Data Scientist team, to create a machine learning model to give them the competitive edge against Blue Note.

### Dataset
Data set contains information from the Ames Assessor’s Office used in computing assessed values for individual residential properties sold in Ames, IA from 2006 to 2010. The dataset is then seperated into a `train.csv` and a `test.csv`.

# Problem Statement:
## What *core features* should Real Sky, focus on to *increase the sale price of homes* for a higher profit for their next development project?

To solve this problem statement, we will be employing a regression model to pinpoint predictive core variables that influence saleprices. We will also be ultilizing RMSE.

## Conclusion and Recommendations
Using the Ridge Regression model with a R2 score of 0.83 with a RMSE error of 29196 (scored on Kaggle), we have predicted the core feautres that affect sale price. The top core features that had a high coefficient values on saleprice are overall quality, exterial quality, bsmt quality, ground living area, kitchen quality and garage area. An increase in overall quality, exterial quality, basement quality, ground living area and kitchen quality has a positive influence on increasing the sale price. Real Sky should focus on funneling more of their expenses on improving this features in their next development project to increase the saleprice of their houses. They should also advertise this features. Real Sky should also seek to procure land in areas such as Stone Brooke, Northridge Heights and Northridge neighborhoods for higher saleprice of new houses.

## Limitations
There is insufficient data to fully analyse factors that affect the sale price. Such data like proximity to amenities (i.e distance to malls, schools and public transport), recession and political background can affect the saleprice negatively or positively. 
There was also high amounts of missing data found in the dataset, which were filled with median and mode. This might skew the predictive results of the features.

 
