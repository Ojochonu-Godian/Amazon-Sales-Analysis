# AMAZON SALES ANALYSIS

## INTRODUCTION
This dataset contains Amazon's Sales Information including the ORDER ID, PRODUCT, QUANTITY ORDERED, PRICE EACH, ORDER DATE and PURCHASE ADDRESS. I used python to clean and carryout **Exploratory Data Analysis** on the dataset after which I created a clean dataset and export to Power BI for the final dashbord.
### Content of the Notebook
1. Data Preparation and cleaning
2. Exploratory Data Analysis
3. Conclusion

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
#### IMPORTING LIBRARIES
![Amazon1](https://github.com/Ojochonu-Godian/Amazon-Sales-Analysis/assets/104824781/b6ff08c1-79db-4f32-a34c-010f4b6debff)

#### CONVERTING "ORDER DATE" TO DATETIME FORMAT
![Amazon2](https://github.com/Ojochonu-Godian/Amazon-Sales-Analysis/assets/104824781/5511ad48-6c2d-4dce-bc0d-d8130afe3777)

### EXPLORATORY DATA ANALYSIS
In this project I would like to give data driven answers to the following business questions;
* What is the best year for sales? How much was earned that year?
* What was the best month for sales? How much was earned that month?
* What City had the highest number of sales?
* What time should we display advertisement to maximize likelihood of customer's buying product?
* What products are most often sold together?
* What product sold the most? Why do you think it sold the most?

### What is the best year for sales? How much was earned that year?
![Amazon3](https://github.com/Ojochonu-Godian/Amazon-Sales-Analysis/assets/104824781/cfa6e352-3a51-4efc-88fc-bfee39c41925)

The best year for sale was 2019 with a total revenue of 34,456,867.6 USD. The business recorded a sharp decrease in revenue in the year 2020.
### What was the best month for sales? How much was earned that month?
![Amazon4](https://github.com/Ojochonu-Godian/Amazon-Sales-Analysis/assets/104824781/53fb5141-3641-4085-ad0c-e58150f90acb)

The Month of December was the best month for sale, possibly due to festivities and holidays. 4,608,295.70 USD revenue was recorded.
### What City had the highest number of sales?

![Amazon5](https://github.com/Ojochonu-Godian/Amazon-Sales-Analysis/assets/104824781/0b1918f4-b969-45cf-af61-f35798c5554d)

From the chart above, It can be seen that San Francisco(CA) recorded the highest number of sales in revenue.

### What time should we display advertisement to maximize likelihood of customer's buying product?

![Amazon6](https://github.com/Ojochonu-Godian/Amazon-Sales-Analysis/assets/104824781/1fb64aaa-f133-4ae0-9f37-614a13238b20)

From the chart above, the best time for advertisement are between 11am to 12noon and 6pm to 8pm.

### What products are most often sold together?

![Amazon7](https://github.com/Ojochonu-Godian/Amazon-Sales-Analysis/assets/104824781/8a23a97f-9138-4433-b843-98866ded024b)

The top two products mostly sold together are the iPhone and the Lightening Charging Cable.

### What product sold the most? Why do you think it sold the most?
![Amazon8](https://github.com/Ojochonu-Godian/Amazon-Sales-Analysis/assets/104824781/5bdf37cb-6a98-4fb7-ad4e-d7e48be604f0)

The AAA Batteries(4 pack) and AA Batteries(4 park) are the top selling products by quantity ordered, this may be due to their raltively low prices as seen below.

![Amazon9](https://github.com/Ojochonu-Godian/Amazon-Sales-Analysis/assets/104824781/fe8f0e47-39e6-45bf-a84f-8815d305fae3)

### Insights
1. The best year for sales is 2019. A total earning of 34,456,867 USD was made that year.
2. A total revenue of 4,608,295.70 USD was made in December, making it the best month for sales.
3. San Francisco(CA) recorded the highest number of sales.
4. The recommended time for display of advertisement is between 11am to 12noon, and 7pm.
5. iPhone and Lightning Charging Cable are the two items most commonly sold together.
6. AAA Batteries and AA Batteries are the most sold products probably due to their low prices.

### Dashboard
The final dashboard was developed by exporting the clean dataset to PowerBI.

[AmazonSalesAnalysisEgene.pdf](https://github.com/Ojochonu-Godian/Amazon-Sales-Analysis/files/11553070/AmazonSalesAnalysisEgene.pdf)
