# Aggie-Hacks-x-Google-Cloud-Hackathon

## Data Preprocessing

Our team utilized the Household pulse survey data that is collected by the United States Census Bureau. In this survey, respondents enter in their characteristics, and answer a series of questions regarding their sentiment on the COVID-19 pandemic, and how their lives have been impacted.

The data is available 
[through this link.](https://www.census.gov/programs-surveys/household-pulse-survey/datasets.html)
The Census began collecting this survey data in April 2020, shortly after the COVID pandemic became widespread in the United States. Since then, they have been collecting this data biweekly. However, the Census does not consolidate the data files each time that they conduct this survey. There were 27 different CSV files with data collected at different points during the pandemic that our team had to consolidate. Furthermore, while certain questions in every biweekly survey, other questions were added and removed throughout the collection process. For example, questions regarding the COVID Vaccine were added in December 2020 surveys as the vaccine started to become available to the public in the U.S

Our code is provided in the preprocessing.ipynb file.

## Exploratory Data Analysis

Next did a deep dive into the data in order to find trends among subsets. In the file EDA.ipynb we documented our code as we analyzed various demographic groupings to see how they relate to opinions about the COVID-19 vaccine.

In order to run the Tableau Dashboard, please connect to the Finaldata3 Parquet file in the data folder.

## Conclusions

Though vaccine sentiment has been improving over time, we note that there are prevailing differences between different subgroups. We list the reasons for these differences, and recommend policy outreach to ensure that vaccine sentiment is improving across all measured groups. COVID-19 response is a global, collaborative effort, and requires that all subgroups are on board.
