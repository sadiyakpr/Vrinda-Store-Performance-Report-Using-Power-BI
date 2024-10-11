# Vrinda-Store-Performance-Report-Using-Power-BI

### Dashboard PDF : 

[powerBIDashBoard2 (1).pdf](https://github.com/user-attachments/files/17335830/powerBIDashBoard2.1.pdf)

## Problem Statement

This dashboard helps better understand the performance of a clothing store. It allows the company to know its total revenue, states with the highest revenue share, and much more.

Using the dashboard the state of the store is accessed, and further factors to be improved are discovered, not only to maintain the performance but also to boost its performance in areas it lags.

### Steps followed 

- Step 1: Load data into Power BI Desktop, dataset is an Excel file.

  The following are the labels in the original dataset before transformation and loading,

     - Index
     - Order ID
     - Cust ID
     - Gender
     - Age
     - Date
     - Status
     - Channel
     - SKU
     - Category
     - Size
     - Quantity
     - Currency
     - Amount
     - ship-city
     - ship-state
     - ship-postal code
     - ship-country
     - B2B

- Step 2: Open the Power Query Editor and standardize the values for the column. Since, 1 and one, 2 and two are the same.
  - Follow the same for "column Gender".
- Step 3: Remove unnecessary columns.
  - Remove "column ship-country" since all the shipments were with one country, "India".
  - Remove "column currency" since all the transactions were in Indian rupees.
  
- Step 4: Calculated column was created in which, customers were grouped into various age groups.
  - Teenager (>=18)
  - Adult (>=30)
  - Senior (>=50)
        
- Step 5: It was observed that in none of the columns errors or empty values were present.
- Step 6: Change default column names to convenient and concise labels.
- Step 7: Click "Close & Apply" once all transformations are completed. Power BI does not make changes to the original raw dataset.
- Step 8: Create visualizations for the modeled dataset. This helps derive insights from the dataset. This is done in the report view section on Power BI.
- Step 9: Give a one-line summary on the top of the canvas using a text box. The report summary is "Vrinda Store Performance."
- Additionally, a sub-title could be added, to the report, it is "2022."
- Step 10: Produce visualizations for the following factors,

  (a) Total revenue store makes

  (b) Revenue by each month
  
  (c) Order count by each month

  (d) Top 5 states generating maximum revenue

  (e) Top 3 channels generating maximum revenue

  (f) Gender-based revenue share

  (g) Order count by age group

  (h) Order count by gender

- Step 11: Visual filter (Slicer) were added for months.

- Step 12: One card visuals was added to the canvas, representing the total revenue of the store.

Snap of card visuals,

-- Total revenue of store,

![Screenshot 2024-10-11 055808](https://github.com/user-attachments/assets/a5ae6309-5e8b-4405-b94a-3c6911ce7d6e)

-- Top 3 channels that make up the highest share in revenue,

![Screenshot 2024-10-11 055834](https://github.com/user-attachments/assets/749dd7fb-8cf4-4659-897a-47fb74f60da6)



-- Share in revenue by gender,

![Screenshot 2024-10-11 041648](https://github.com/user-attachments/assets/359cf46b-5f73-4a02-aace-dbda61490695)

- Step 13: A real-time geographical map was added, representing the top 5 states generating maximum revenue.

- Step 14: A line chart was added to represent the monthly trends in revenue and order count.
  
- Step 15: A clustered column chart was added to the report design area to represent order count by age group and gender.
  
- Step 16: The report was then published to Power BI Service.

![Screenshot 2024-10-11 035233](https://github.com/user-attachments/assets/a613157b-dc77-4387-b483-bbe648f2d50a)

# Snapshot of Dashboard (Power BI Service)

![Screenshot 2024-10-11 055357](https://github.com/user-attachments/assets/a09cb300-b612-46e7-b0e3-9d9b60771f07)

# Report Snapshot (Power BI DESKTOP)

![Screenshot 2024-10-11 055233](https://github.com/user-attachments/assets/b5f89d63-189b-46d0-a6bb-36a56a7dfe67)

# Insights

A single-page report was created on Power BI Desktop & it was then published to Power BI Service.

The following inferences can be drawn from the dashboard,

### [1] Total store revenue 

    21.2 Million Rupees

### [2] Top 5 states 

     Rank 1: Maharashtra
   
    Rank 2: Karnataka
   
    Rank 3: Uttar Pradesh
   
    Rank 4: Telangana

    Rank 5: Tamil Nadu

   Ranking based on share in revenue. These ratings will change if different visual filters are applied.
           
### [3] Top 3 channels

    Rank 1: Amazon (35.4%)
   
    Rank 2: Myntra (23.3%)
   
    Rank 3: Flipkart (21.5%)

 Ranking based on share in revenue. These ratings will change if different visual filters are applied.
  
  ### [4] Revenue share by gender
  
    Rank 1: Women (64.05%)

    Rank 2: Men (35.95%)

Ranking based on share in revenue. These ratings will change if different visual filters are applied.
 
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
  
The ranking is based on the number of orders. These ratings will change if different visual filters are applied.  

   ### [6] Revenue and order count by month
   
  -- Revenue
  
    Lowest revenue-making month: December 2022
  
    Highest revenue-making month: March 2022

  -- Order count
  
    Lowest order count-making month: December 2022
  
    Highest order count-making month: March 2022

This may change if different visual filters are applied.
