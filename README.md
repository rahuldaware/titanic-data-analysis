# Analysing Titanic Dataset to find connection between various demographic parameters with chance of survival

  The sinking of the RMS Titanic is one of the most infamous shipwrecks in history.  On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.

  One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.

This project focuses on data analysis of Titanic passengers' information and infer some conclusions. This project is a part of "Introduction to Data Analysis" course of Data Analyst Nanodegree program from Udacity.

## Project Description
In this project, we try to analyse various factors that affected survival chance from Titanic Disaster. All the observations are are available in Jupyter notebook (titanic-data-analysis.ipynb). Also the conclusions made from the observations are mentioned below.

## Dataset Description

The dataset was obtained from Kaggle website. Here is the link : [Titanic Dataset](https://d17h27t6h515a5.cloudfront.net/topher/2016/September/57e9a84c_titanic-data/titanic-data.csv)

Variable Description is available on this link : [Dataset Description](https://www.kaggle.com/c/titanic/data)

## Conclusion

  The dataset obtained had missing values in the age column. This hinders the analysis to some extent. Our analysis related to age would hae been more accurate if those missing values are present. To find the missing values, we need to perform more investigation or add random values.

The conclusions below are made from the observations available in the Jupyter notebook.

  1. Only 38% of people could make it back from Titanic.
  2. Class 1 had 216, Class 2 had 184 and Class 3 had 491 passengers.
  3. There were 577 males and 314 females onboard.
  4. The age of people was normally distributed with mean at 29.64 years.
  5. The average fare of Class 1 was 84.15, Class 2 was 20.66 and Class 3 was 13.68.
  6. 168 passengers boarded from Cherbourg, 77 passengers boarded from Queenstown, and 644 passengers boarded from Southampton.
  7. 537 people were travelling alone without any family members onboard.
  8. We tried to find out if there is a relationship between class of travel and survival. This test will prove if higher class passengers were preferred to use rescue boats or not. From analysis, we found out that there is a relationship. There was 62.96% chance of survival if passenger had ticket from Class 1, 47.28% chance from Class 2 and 24.23% chance from Class 3.
  9. In the next analysis, we tried to find out if females were preferred to rescue than males. We found out very strong relation between sex and survival. 74.2% of females survived as opposed to only 18.89% males.
  10. Finally, we tried to find if children (age below 18) were preferred to rescue than adults. There was a higher survival rate for children marginally. 53.98% children survived as opposed to 37.89% adults.
