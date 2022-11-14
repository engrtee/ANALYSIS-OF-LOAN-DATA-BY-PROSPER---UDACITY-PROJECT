# (Loan Data by Prosper)
## by Ilesanmi Tosin

## Dataset

> The dataset used in this analysis is the Loan data by Prosper. The data is provided as a csv file with 113,937 loans with 81 variables on each loan.  It was downloaded from the project workspace in Udacity site using a link for project resources. 

>The following data wrangling steps were carried out on the project to clean the dataset and prepare it for analysis.


> 1.Standardization of the loan status columns to show Completed and non remittance as status

> 2.Conversion of the loan origination date datatype from object to datetime

> 3.Listing Category is Decoded using data from the data dictionary.

> 4.Renaming of the Prosper Rating (Alpha) and the Listingcategory(numeric) columns to Prosper Rating and Listing Category         columns respectively

> 5.Cleaning operation was performed on the columns with missing values


> 6.To enable analysis by loan origination year, creating a new column from loan origination date to hold the loan origination     year.

> The final structure of the dataset after wrangling operations had been carried out is 25000 loans and 14 features


## Summary of Findings

>1. I observed a steady increase in defaulted loans from 2009 up until 2012 after which there was steep decline till 2014 suggesting that there was a huge number of loans disbursed within the first four years ie from 2009 till 2012 and the year with the highest default rate is 2012
>2. A very noteworthy and interesting finding from this dataset was the fact that against the normal popular opinion , fully employed personnel accounted for the highest number of loan defaulters as they took the highest number of loans while the others took less loans with lower default rate. It goes a great deal to show that a steady pay is not enough reason for a loan to be granted.

>3. It was also observed that even though those with income ranges of 100k and above had the highest loan amount every other income range below this had a higher number of defaulters which is quite interesting as one would have expected that the higher the loan amount the more difficult it would be to pay back on time.


## Key Insights for Presentation

> Although the majority of loans are given to employed individuals, this dataset revealed that most of the loan defaulters actually fall within this class.This analysis also reveals that borrowers with incomes between 25k and 49k are more likely to default on their loans than other categories. Also loans given out in the following categores which are weddings, baby adoption and debt consolidation have a considerably higher default rate than other categories,  so the business may need to take this into consideration when considering loan requests from this categories.
It was also observed loan listings with Prosper ratings HR, D, or E, happen to have a higher number of defaulters as against the others.. Additionally, borrowers with higher BorrowerRates are more likely to default.