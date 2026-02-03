# AI_MI_Intern_T12
# Customer Segmentation Dataset Summary
# Project Overview
This dataset contains detailed profiles of 2,240 customers, including their demographics, household information, purchasing behavior, and interactions with marketing campaigns. It is primarily used for **Customer Personality Analysis** to help a business better understand its customers and modify products according to the specific needs, behaviors, and lifestyles of different customer segments.
# Dataset Profile
* **Total Records:** 2,240
* **Total Features:** 29
* **Missing Values:** Only the `Income` column contains missing values (24 records).
# Feature Categories
# 1. Customer Demographics
* `ID`: Unique identifier for each customer.
* `Year_Birth`: Customer's birth year.
* `Education`: Educational level (Graduation, PhD, Master, Basic, 2n Cycle).
* `Marital_Status`: Marital status (Single, Together, Married, Divorced, Widow, Alone, Absurd, YOLO).
* `Income`: Yearly household income.
# 2. Household Information
* `Kidhome`: Number of children in the household.
* `Teenhome`: Number of teenagers in the household.
# 3. Customer Relationship
* `Dt_Customer`: Date of customer's enrollment with the company.
* `Recency`: Number of days since the customer's last purchase.
* `Complain`: 1 if the customer complained in the last 2 years, 0 otherwise.
# 4. Product Spending (Amount spent in the last 2 years)
* `MntWines`: Amount spent on wine.
* `MntFruits`: Amount spent on fruits.
* `MntMeatProducts`: Amount spent on meat.
* `MntFishProducts`: Amount spent on fish.
* `MntSweetProducts`: Amount spent on sweets.
* `MntGoldProds`: Amount spent on gold products.
# 5. Purchase Channels
* `NumDealsPurchases`: Number of purchases made with a discount.
* `NumWebPurchases`: Number of purchases made through the company’s website.
* `NumCatalogPurchases`: Number of purchases made using a catalog.
* `NumStorePurchases`: Number of purchases made directly in stores.
* `NumWebVisitsMonth`: Number of visits to the company’s website in the last month.
# 6. Marketing Campaigns
* `AcceptedCmp1` to `AcceptedCmp5`: 1 if the customer accepted the offer in the respective campaign, 0 otherwise.
* `Response`: 1 if the customer accepted the offer in the last campaign, 0 otherwise (often used as the target variable).
# Key Statistics
* **Average Income:** ~$52,247
* **Average Year of Birth:** 1968
* **Average Spending on Wine:** $303.94 (highest spend category)
* **Campaign Success:** Approximately 14.9% of customers responded to the most recent marketing campaign.
