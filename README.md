# AMAZON SALES ANALYSIS

## ITRODUCTION
This dataset contains Amazon's Sales Information including the ORDER ID, PRODUCT, QUANTITY ORDERED, PRICE EACH, ORDER DATE and PURCHASE ADDRESS. I used python to clean and carryout **Exploratory Data Analysis** on the dataset after which I created a clean dataset and export to Power BI for the final dashbord.
### Content of the Notebook
1. Data Preparation and cleaning
2. Exploratory Data Analysis
3. Conclusion

## Exploratory Data Analysis
In this project I would like to give data driven answers to the following business questions;
* What is the best year for sales? How much was earned that year?
* What was the best month for sales? How much was earned that month?
* What City had the highest number of sales?
* What time should we display advertisement to maximize likelihood of customer's buying product?
* What products are most often sold together?
* What product sold the most? Why do you think it sold the most?

## DATA SOURCING
I got the dataset from [DataDNA Dataset Challenge - December 2022](https://pomerolpartners.com/dataset_challenge/december-2022/)

## DATA CLEANING AND PROCESSING
After loading the dataset I moved on to clean and process the data using in the following steps;
* I created a copy of the dataset before cleaning to protect the authenticity of the original data.
* I discovered an issue in the **Order Date** data type, It was an object and I changed it into a datetime format as appropriate.
* No column of the dataset had any missing data.
* To answer the business questions I had to create additional columns.
* I did feature engineering to add the required columns that would be helpful for my analysis.
* After which I carried out exploratory data analysis.

## SKILLS DEMONSTRATED
For this project I performed data cleaning and visualization using python libraries as seen below;
#### * IMPORTING LIBRARIES

![Amazon1](https://github.com/Ojochonu-Godian/Amazon-Sales-Analysis/assets/104824781/b6ff08c1-79db-4f32-a34c-010f4b6debff)

### Insights
1. The best year for sales is 2019. A total earning of 34,456,867 USD was made that year.
2. A total revenue of 4,608,295.70 USD was made in December, making it the best month for sales.
3. San Francisco(CA) recorded the highest number of sales.
4. The recommended time for display of advertisement is between 11am to 12noon, and 7pm.
5. iPhone and Lightning Charging Cable are the two items most commonly sold together.
6. AAA Batteries and AA Batteries are the most sold products probably due to their low prices.
