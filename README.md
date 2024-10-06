# Data-Cleaning-Using-Excel
##### How to clean a dirty data on Excel

## INTRODUCTION:

The dataset requires cleaning, analysis, and visualization. It also requires data-driven recommendations and suggestions to enhance overall sales.

## BACKGROUND:

This very project aims to leverage data analytics to derive actionable insights, enhance decision-making, and optimize sales strategies in the Coca-Cola (USA). Coca-Cola is a global company which has an extensive dataset detailing its sales across various regions, channels, and periods.

## DATA OVERVIEW:

The Coca-Cola Sales Dataset encompasses the following key variables:

Date: A record of the date of each sale.

Region: Categorizing sales by geographical regions.

Product Line: Differentiating between Coca-Cola products (e.g., Coca-Cola Classic, Diet Coke, etc.).

Sales Volume (Liters): Quantifying the volume of Coca-Cola products sold.

Revenue: Calculation of the amount generated from sales.

## OBJECTIVES:

### Temporal Analysis:

Examine sales trends over time to identify seasonality and potential patterns.

Determine peak sales periods and strategize promotions accordingly.

### Regional Performance:

Evaluate sales performance across different regions.

Identify high-performing regions and areas for improvement.

### Product Line Analysis:

Assess the sales performance of individual product lines.

Identify products that contribute significantly to revenue.

### Correlation Analysis:

Explore relationships between sales volume, revenue, and external factors (e.g., marketing campaigns, promotions, or economic indicators). To get our Key Performance Indications (KPIs).

## TOOL USED:

Microsoft Excel was the only tool used to carry out the tasks of Cleaning, Analyzing, and Visualization this dataset.

## NOW LETS GET TO WORK!

For this project, the first step was to Obtain and Study the dataset. The dataset was provided in Microsoft Excel format. I just double-tapped the folder to open Excel.
As you can see from the image below, the dataset came in extremely dirty with errors and formats
I want to retain the dirty data after cleaning so I copied it in its raw state and pasted it to another sheet in the same work book.  I highlighted everything before copying it.

![image](https://github.com/user-attachments/assets/756ce004-1dce-4c14-9e5c-d2197c030c35)



The image below is the result of the copied dataset. I pasted to a worksheet I named “CLEANED DATA” because that is where I want to clean it.

![image](https://github.com/user-attachments/assets/d3ca0d81-942a-41d3-a2d9-af066cedc73e)




Notice that at the top of the image below, some headers are missing. After studying the dataset, I was able to decipher what the missing headers were.

![image](https://github.com/user-attachments/assets/409dfc3d-e5e5-463d-8c7b-cb0c3b4fc761)



The raw data came with formats as you can see those colors are not required so I had to clear formats by clicking on the ‘editing’ sign in the Home Ribbon then I selected 

![image](https://github.com/user-attachments/assets/e0b738aa-b396-4ffd-8c95-61104a91fe28)



I also had to clear blanks as some cells in the dataset were empty, so the first thing I did was to go the the Home Ribbon, click on the find icon and then the “go to special”

![image](https://github.com/user-attachments/assets/bf24e89a-8bcb-4736-8313-8545924df3b7)



As you can see below, after clicking on go to special, I selected BLANKS. After which I went to DELETE and selected Delete Sheet Rows. After that, my dataset was fully free from formats and ready for further cleaning.

![image](https://github.com/user-attachments/assets/ae152f3d-ce72-4ec3-b43d-661e2abb357b)

![image](https://github.com/user-attachments/assets/f2b9c23b-cb46-4c78-bd85-082d7ebc7ee7)





That is all for clearing of data formats. Now lets get to the other phase of data cleaning;

**Step1:** The Date was in a numerical format, so I changed it to Short Date format by going to ‘General’ and selecting ‘Short Date’

![image](https://github.com/user-attachments/assets/37c1b30d-9cef-4854-ae18-c3cf17a51b9b)



**Step2:** In this step, I had to use “Find and Replace” to change the Products column from Upper case to ‘Proper’

![image](https://github.com/user-attachments/assets/c78363fd-4d2e-47f1-94c0-cb44e330c5f2)



**Step3:** The next step is to add another column to calculate the Revenue. This calculation involves multiplying the price per unit by the units sold.

![image](https://github.com/user-attachments/assets/91cf6d28-2af6-4971-923d-8bc6fee464e5)



**Step4:** This step involves determining the Operating Cost. I inserted an another column to calculate the operating cost. I got the value by subtracting the operating profit from the revenue.

![image](https://github.com/user-attachments/assets/9a2ac79f-3e50-4cce-bbc7-621c670d2597)



**STEP5:** This column was in General format, so I changed it to Percentage format by going to ‘General’ and selecting ‘Percentage’

![image](https://github.com/user-attachments/assets/13dd394b-f290-4940-a585-32fce03ab7a5)



**STEP6:** This column was in General format, so I changed it to Currency format by going to ‘General’ and selecting ‘Currency’

![image](https://github.com/user-attachments/assets/4ad7e623-b005-4310-898f-4b5ab2bab4a4)



**KEY FEATURES/COLUMNS:** The key columns relevant for the sales performance analysis are:

a) Retailer

b) Date

c) Region

d) Product

e) Price per unit

f) Unit sold

g) Revenue

The metrics required to be generated from these columns to be able to provide insights and recommendations are:

Sales trends over time to identify seasonality and potential patterns
Evaluate sales performance across different regions.
Product performance by Unit sold and Revenue
Products with the most sales
Retailer with the most sales
Region with the most revenue

**ANALYSIS:**
This is the point where pivot table is created. Pivot table is an excel function that helps with data analysis and the creation of charts for analysis.

I created the pivot table by going to my cleaned data, clicking on a cell, then clicked on INSERT-PIVOT TABLE-ALREADY EXISTING WORKSHEET- I went back to my worksheet and clicked a cell and the pivot table came up. Images are shown below

![image](https://github.com/user-attachments/assets/9cfc1427-64d8-46b4-807f-dd521224695b)

![image](https://github.com/user-attachments/assets/a2c0f140-c9df-439e-a86f-d546aa6fe848)

![image](https://github.com/user-attachments/assets/ff1d945d-e7ea-4b16-8750-c5ae7594ca2b)

Now, back to our Analysis:

**Sales Trends over time**

Examining sales trends over time is crucial to identify seasonality and potential patterns. I achieved this by creating a pivot table, placing the invoice date on the axis, and revenue/units sold in the values. So, I utilized the pivot table to generate a line and column chart, illustrating the sales trend from January to December of 2022 and 2023.

![image](https://github.com/user-attachments/assets/11b700d6-ede5-41c4-b42e-b0fdd6224c80)



**Sales Performance by Regions**
To assess sales performance in various regions, I made another pivot table. In this pivot table, I compared the Region column with the Revenue column

![image](https://github.com/user-attachments/assets/88d8b8e7-c2c7-420c-b2fd-3d17083db56c)



**Product Performance by Unit sold and Revenue**
In this pivot table, I compared the Product column with the Units Sold and Revenue column.

![image](https://github.com/user-attachments/assets/44f11d8d-e537-44fa-93cb-29f8f1895418)



**Sales Performance by Retailer**
I compared the Retailer column with the Revenue column to identify which retailer has the most sales/revenue

![image](https://github.com/user-attachments/assets/0f09468f-53eb-4470-8cdf-91996bc6bb1c)



**Insight Summary:**

A. The total revenue generated is $12,039,296

B. The total number of units sold is 24,843,680

C. The sales revenue shows some slowness in sales and then increases gradually to peak in July 2023, which is the highest peak of sales revenue

D. The product with the highest Revenue and Unit Sales is Coca-Cola

E. The best-performing region is WEST region

**CONCLUSIONS:**

Given that Coca-Cola has been the most profitable product, the company should prioritize increasing its production and consider reducing the price per unit to attract a larger customer base.
Focusing on supplying enough products to the top-performing city and directing more resources towards targeted advertising in those locations is essential for success. Both the company and distributors should collaborate to ensure ample product availability in these areas.
The company should consider refining its sales approach, either by lowering product costs or adopting a promotion where customers buy five products and receive an extra one. This strategy is likely to attract more customers. Additionally, the company should concentrate on improving its marketing efforts.
Empowering top retailers with adequate discounts and exploring collaborations with manufacturers or suppliers to create exclusive products in high-performing regions can further enhance the company’s success.




