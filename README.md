# Vrinda-Store-Performance-Report-Using-Power-BI

### Dashboard PDF : 

[powerBIDashBoard2 (1).pdf](https://github.com/user-attachments/files/17335830/powerBIDashBoard2.1.pdf)

## Problem Statement

This dashboard helps understand the performance of a clothing store better. It helps the company know its total revenue, states with highest share in revenue and much more.

Using the dashboard the state of store is accessed, further factors to be improved are discovered, not only to maintain the performance but also to boost its performance in areas it lags.

### Steps followed 

- Step 1: Load data into Power BI Desktop, dataset is an excel file. The following are the labels in the original dataset before transformation and loading,

   (a) Index

   (b) Order ID

   (c) Cust ID
   
   (d) Gender
   
   (e) Age
   
   (f) Date
   
   (g) Status
   
   (h) Channel
   
   (i) SKU

   (j) Category
   
   (k) Size

   (l) Quantity

   (m) Currency

   (n) Amount

   (o) ship-city

   (p) ship-state

   (q) ship-postal code

   (r) ship-country

   (s) B2B

- Step 2: Open power query editor & in view tab under Data preview section, select "column Quantity" and standardize the values for the column. Since, 1 and one, 2 and two are same.
  - Follow the same for "column Gender".
- Step 3: Remove unecessary columns.
  - Remove "column ship-country" since all the shipment were with one country, "India".
  - Remove "column currency" since all the transactions were in indian rupees.
  
- Step 4: Calculated column was created in which, customers were grouped into various age groups.
  - Teenager (>=18)
  - Adult (>=30)
  - Senior (>=50)
        
- Step 5: It was observed that in none of the columns errors or empty values were present.
- Step 6: Change default column names to convenient and consize labels.
- Step 7: Click "Close & Apply" once all transformations are completed. Power BI does not make changes to the original raw dataset.
- Step 8: Create visualisations for the modelled dataset. This helps derive insights from the dataset. This is done in the report view section on Power BI.
- Step 9: Give a one line summary on the top of the canvas using a text box. The report summary is "Vrinda Store Performance."
- Additionally, a sub-title could also be added; for the report, it is "2022."
- Step 10: Produce visualisations for the following factors,

  (a) Total revenue store makes

  (b) Revenue by each month
  
  (c) Order count by each month

  (d) Top 5 states generating maximum revenue

  (e) Top 3 channels generatiing maximum revenue

  (f) Gender based revenue share

  (g) Order count by age group

  (h) Order count ny gender

- Step 11: Visual filters (Slicers) were added for two fields named "Month".

- Step 12: One card visuals was added to the canvas, representing total revenue of store.

Snap of card visuals,

-- Total revenue of store,

![Screenshot 2024-10-11 055808](https://github.com/user-attachments/assets/63a50728-f08c-4c1e-aada-70647f787f15)

-- Top 3 channels that make up highest share in store revenue,

![Screenshot 2024-10-11 055834](https://github.com/user-attachments/assets/cd04a7d6-0057-4f20-a5a3-c8c03db96899)

-- Share in store revenue by gender,

![Screenshot 2024-10-11 041648](https://github.com/user-attachments/assets/580e9cb2-7f8f-4a74-800e-4baf5d38fd97)

- Step 13: A real-time geographical map was added, representing top 5 states generating maximum revenue.

- Step 14: A line chart was added to representing monthly trend for revenue and order count.
  
- Step 15: A clustered column chart was added to the report design area to represent order count by age group and gender.
  
- Step 16: The report was then published to Power BI Service.

![Screenshot 2024-10-11 035233](https://github.com/user-attachments/assets/a613157b-dc77-4387-b483-bbe648f2d50a)

# Snapshot of Dashboard (Power BI Service)

![Screenshot 2024-10-11 055357](https://github.com/user-attachments/assets/a09cb300-b612-46e7-b0e3-9d9b60771f07)

# Report Snapshot (Power BI DESKTOP)

![Screenshot 2024-10-11 055233](https://github.com/user-attachments/assets/b5f89d63-189b-46d0-a6bb-36a56a7dfe67)

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard,

### [1] Total store revenue = 21.2 million rupees

### [2] Top 5 states 

   Rank 1: Maharashtre
   
   Rank 2: Karnataka
   
   Rank 3: Uttar Pradesh
   
   Rank 4: Telangana

   Rank 5: Tamil Nadu

   Ranking based on share in revenue. These ratings will change if different visual filters will be applied.
           
### [3] Top 3 channels

   Rank 1: Amazon (35.4%)
   
   Rank 2: Myntra (23.3%)
   
   Rank 3: Flipkart (21.5%)

 Ranking based on share in revenue. These ratings will change if different visual filters will be applied.
  
  ### [4] Revenue share by gender
  
  Rank 1: Women (64.05%)

  Rank 2: Men (35.95%)

Ranking based on share in revenue. These ratings will change if different visual filters will be applied.
 
  ### [5] Order count by age group and gender

  --By age group: Teenager
  
  Rank 1: Women (0%)

  Rank 2: Men (0%)

  --By age group: Adult
  
  Rank 1: Women (55.72%)

  Rank 2: Men (24.67%)
  
  --By age group: Senior
  
  Rank 1: Women (5.91%)

  Rank 2: Men (13.70%)

  Ranking based on the number of orders. These ratings will change if different visual filters will be applied.  

   ### [6] Revenue and order count by month
   
  -- Revenue
  
  Lowest revenue making month: December 2022
  
  Highest revenue making month: March 2022

  -- Order count
  
  Lowest order count making month: December 2022
  
  Highest order count making month: March 2022

This may change if different visual filters will be applied.
