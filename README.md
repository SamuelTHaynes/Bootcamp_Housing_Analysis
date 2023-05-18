# Bootcamp_Housing_Analysis

## Datasets we used:
-	Historical Median House Monthly House Sales Prices
>-	https://www.redfin.com/news/data-center/
-	Historical Rental Rates Johnson County Kansas
>-https://www.apartmentlist.com/research/category/data-rent-estimates
-	Historical S&P Monthly closing information
>-	https://www.investing.com/indices/us-spx-500-historical-data


## Research Questions to answer

- As a renter, does it make sense for me to buy a house in the near term (i.e. 2 or so years) in Johnson County Kansas?
- As an owner, does it make sense for me to sell my house in the near term in Johnson County Kansas?
    - What is the trend of the median home price?
    - What is the trend of rental rates?

- Are there factors that are influencing the median price of single-family homes?
    - Does the S&P have an impact on the median sales price of a single-family home?
    - Does the level of inventory have an impact on the median sales price of a single-family home?
    - Does the length of time homes stay on the market have an impact on the sales price of a single-family home?
    - Do the number of new listings have an impact on the sales price of a single-family home?
    - What is the difference between the actual purchase price and the listing price of a single-family home?
    - What is the trend of rental prices for a 2-bedroom apartment in relationship to the trend of the median price of a single-family home?

## File Breakdown
- Raw Data
    - JOCO_Data.csv for House prices analysis
    - Apartment_List_Rent_Estimates_2023_04.csv for rent price analysis
    - S&P 500 5 Year Historical Data.csv for S&P 500 data analysis
- Extraced/Cleaned Data
    - JOCO_Median_Prices.csv
- Analysis
    - Median_Housing_Data.ipynb
    - S&P_To_Median_Home_Price_Comparison.ipynb
    - Johnson County Median Rent analysis.ipynb
- Other Documentations/Materials
    - Project Track.docx documentation for project
    - .getignore to remove unneccessary files
    - README.MD this file

## Data Cleanup
- JOCO_Data.csv was cleaned by using the filters inside of Excel to only get the data for Johnson County Kansas. I selected only the columns for the data that we needed. Then filtered for data since 2018. (Sam)
- Apartment_List_Rent_Estimates_2023_04.csv My data went back 5 years already. The most challenging part was "melting" the dataframe created from the csv. The dates in the original dataset were column headers, so I had to use the melt function to assign a date to each row of data. (Nick)
- S&P 500 5 Year Historical Data.csv was filtered to only data from the last 5 years. (Kevin)

## Task Breakdown
- Find historical data sources for home prices, availability, listings, sale prices, inventory, rent prices, s&p data
- Download and clean data
- Develop graphs that display trends and correlations
- Develop Power Point presentation with graphs, etc
- Update ReadMe


## Power Point Presentation
- Can be found on Google Drive at https://docs.google.com/presentation/d/1_OYWotFamjCkhTYD7UruuC7bzEqcp39V/edit#slide=id.p1
