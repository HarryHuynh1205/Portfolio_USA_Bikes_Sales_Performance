# USA BIKE _ SALES PERFORMANCE _ PORTFOLIO

## TABLE OF CONTENT
1. [INTRODUCTION](#INTRODUCTION)
2. [KEY QUESTIONS](#KEY-QUESTIONS)
3. [SKILLS vs TOOLS](#SKILLS-vs-TOOLS)
4. [ANALYSIS vs INSIGHTS](#ANALYSIS-vs-INSIGHTS)
5. [VISUALIZATIONS](#VISUALIZATIONS)
6. [CONCLUSION](#CONCLUSION)
7. [HOW TO ACCESS THE PROJECT](#HOW-TO-ACCESS-THE-PROJECT)
8. [USING SQL QUERIES](#USING-SQL-QUERIES)

## 1. INTRODUCTION:

**Project Title:** USA Bike Sales Performance Analysis

**Overview:**
This is an example dataset for training uses only, comprising representative sample data on sales of bicycles within Europe and some select global regions from 2013 to 2023. However, In this data analysis project, I aimed to provide insights into the American’s Bike Shopping Tendency over the last decade (2013-2023). By analyzing various aspects of the sales data, I sought to uncover trends in customer demographics, product preferences, and regional performance which were crucial in the retail industry

**Why is this Data set?**
The dataset provides a detailed view of sales performance in the USA, offering insights into how demographic factors influence purchasing behavior. It is a great use case for retail analytics.

## 2. KEY QUESTIONS:
**Key Questions**

   1.Which age group contributed the most to bike sales?
   2.Who tended to buy Bikes more, Men or Women?
   3.What was the revenue distribution by states?
   4.What product categories and Sub-category were most profitable?

**Dataset**
The dataset contained one CSV Excel file with the following theme columns: 
**[USA_BikeSales_Data_Edited.csv](https://github.com/user-attachments/files/17879001/USA_BikeSales_Data_Edited.csv)**:

   1. **Customer Demographics**: Customer Age, Age Group, Gender, Country and State.
   2. **Product Details**: Product Category, Order Quantity, Unit Cost, Unit Price, Size, Material, Color, Warranty, Manufacturer, Discount and Eco Friendly,
   3. **Sales Metrics**: Revenue, Cost and Profit.
   4. **Delivery**: Rating, Shipping Weight, Delivery Time, Shipping Cost, Shipping Company, Shipping Type, Return Policy and Insurance.

The data link source from Kaggle: **[Global BikeSales Data](https://www.kaggle.com/datasets/hamedahmadinia/global-bike-sales-dataset-2013-2023)**

## 3. SKILLS vs TOOLS:
### 3.1 Tools:
  - Excel for data cleaning and formatting.
  - SQL for querying and joining data
  - Tableau for creating dashboards

### 3.2 Skills
**3.2.1 Data Cleaning/Preparation:**
In the initial data preparation phase, we performed the following tasks:
  - Data loading and inspection.
  - Data cleaning and formatting.
  - Narrow it down to the Bike Sales performance in USA

**3.2.2 Exploratory Data Analysis:**
**EDA** involved exploring the sales data to answer key questions, such as:

**3.2.2.1. SALES PERFORMANCE**
   1. Are there seasonal patterns in bike sales?
   2. What are the peak sales periods?
   3. Is there consistent year-over-year growth in revenue or sales volume, especially in COVID-19?
   4. Which states have the highest sales performance?
   5. Which products or product lines have the highest profit margins?

**3.2.2.2. CUSTOMER DEMOGRAPHICS**
   1. Who was more likely to buy bikes, male or female? 
   2. Which age groups?
   3. Which states were they?
    
**3.2.2.3. PRODUCT CATEGORY**
   1. Which product category was top seller?
   2. Which sub-category was the top1 and the top2?
   3. What kinds of sub-categories did male or female feel interested in?
    
**3.2.2.4. SIZE, COLOR and MATERIALS**
   1. What was the factor the customers usually chose best generally in USA?
   2. What was the factor chosen the most per state?

**3.2.2.5. WARRANTY vs SUSTAINABILITY**
   1. Did the customers care much about the warranty? Which one did they choose best?
   2. Did the customer focus on the sustainability?

**3.2.2.6. DELIVERY PROCESS**
   1. Which Shipping_Company was chosen most?
   2. Which Shipping_Type was selected best? 

**3.2.2.7. RATING**
   1. Which Shipping_Type and Shipping_Company got the lowest-satisfied rate?
   2. Any correlation between Rating and Shipping_Type or Shipping_Company?

**3.2.2.8. DISCOUNTS**
   1. How many discounts types?
   2. Did people tend to buy Bikes with the highest discounts?

**3.3 Data Analysis**
Include some interesting code/features worked with in **MySQL**:
   1. **SELECT** * **FROM** table 1 **WHERE** cond = 2;
   2. **SELECT** * **FROM** table 1 **WHERE** cond = 2 **GROUP BY** column1 **ORDER BY** column2
   3. **WINDOW_ETC**:
      + ROW_NUMBER()
      + RANK()
     
## 4. ANALYSIS vs INSIGHTS:
**Key Insights:**
   1. The Bike Sales Performance had been fluctuated and decreased lightly during the last decade, with a noticeable peak during the summer season and December.
   2. People from 35 to 63 years old were the main customers, particularly Men.
   3. Male customers make up a larger proportion of purchases, but female customers show higher average spending.
   4. Bikes Section was the best-performing category in terms of sales and revenue.
   5. Despite of selling Bike Section most, The profitability belonged to Accessories section, especially Helmet products.

## 5. VISUALIZATIONS:
The Tableau dashboard includes:
   1. A **Regional Map** visualizing sales performance by states.
   2. The _two_ **Bar Charts** showing age groups and gender contributions
   3. A **Line Chart** comparing total product category profits per month.
   4. A **Pie Chart** showing the highest detailed revenue of Category and its sub-category (Bike Sales)
   5. The **Six of Bar Charts** demonstrating the Best and Lowest Bikes by Revenue, Profit and Profit Margins
 **6. Data Visualization ([USA_BikeSales_Dashboard.twb](https://public.tableau.com/app/profile/harry.huynh/viz/USA_BikeSales/OverallDashboard)**
      
## 6. CONCLUSION:
The project identified adults aged  35 to 63 years old as the top contributors to sales figures, with Road Bikes being the most revenuable product category. Sales performance varied across USA states, with the West leading in revenue generation.

These findings provide a clear direction for marketing and product strategy. Focusing on Road Bikes and Mountain Bike which is potential and targeting the 35-63 and 25-34 age groups respectively that can drive sales growth. Regional analysis suggests that expanding inventory and marketing efforts in the West could yield higher returns.

_Recommendations:_
  - Design marketing campaigns tailored to the 35-63 and 25-34 age groups, emphasizing Road and Mountain bikes.
  - Consider introducing loyalty programs or discounts for some clothes and accessories to customers who bought bikes.
  - Expand advertising or amateur competitions in regions with high sales potential, particularly the West.

_Limitations:_
  - Should clarify for calculated units such as profit, revenue, cost, delivery_time, deliever_weight.
  - Should provide more information like Customer_id to know loyal customers
  - Have not found reasons of the low ratings. 
  - Should add locations for being more particular

## 7. HOW TO ACCESS TO THE PROJECT:

1.Download the dataset file from this repository: **[USA_BikeSales_Data_Edited.csv](https://github.com/user-attachments/files/17879001/USA_BikeSales_Data_Edited.csv)**
2.Open the Tableau Packaged Workbook **([USA_BikeSales_Dashboard.twb](https://public.tableau.com/app/profile/harry.huynh/viz/USA_BikeSales/OverallDashboard)** in Tableau Public.
3.View the dashboard here: Tableau Public Link.

**OVERVIEW USA BIKESALE DASHBOARD** 
![Overall Dashboard](https://github.com/user-attachments/assets/fbc72c32-40a0-43a7-a1ff-5638a10f64be)
**BEST vs WORST BEST PRODUCTS DASHBOARD** 
![Products Dashboard](https://github.com/user-attachments/assets/b0df1826-16a5-44ff-80a3-92a795bb69e9)

## 8. USING SQL QUERIES:

```sql
-- 1. CHECKING DUPLICATES
WITH Dupicates_ETC AS (
       SELECT `date`,
              country,
              state,
              revenue,
              profit,
              ROW_NUMBER () OVER (PARTITION BY `date`, customer_age, Age_group, customer_gender, Country, State, Product_category, Product, Order_quantity, Unit_cost, Unit_price, Profit, Revenue, Size, Color,                  Material, Warranty, Manufacturer, Rating, Shipping_weight, delivery_time, Discount, Eco_friendly, Shipping_cost, Shipping_Company, Shipping_Type, Insurance, Return_Policy) AS row_num
       FROM bikesales_usa )
SELECT *
FROM Dupicates_ETC
WHERE row_num >1;
-- (no dulicates)





-- 2. STANDARDIZE DATA
-- CHANGE THE `DATE` DATA
SELECT *
FROM bikesales_usa;

SELECT `date`,
       STR_TO_DATE(`date`,'%m/%d/%Y') As `Dates`
FROM bikesales_usa;

UPDATE bikesales_usa
SET `date` = STR_TO_DATE(`date`,'%m/%d/%Y');

ALTER TABLE bikesales_usa
MODIFY COLUMN `date` DATE;





-- EXPLORATORY DATA ANALYSIS (EDA)
-- 1. OVERALL    
-- 1.1 TOTAL STATES
SELECT count(distinct state) As Num_States
FROM bikesales_usa;

-- 1.2 TOTAL QUANTITY
SELECT Sum(Order_Quantity) AS Total_Quantity
FROM bikesales_usa;

-- 1.3 TOTAL PRODUCTS
SELECT count( distinct Product) AS Products
FROM bikesales_usa;

-- 1.4 TOTAL REVENUE
SELECT sum(Revenue) AS Total_Revenue
FROM bikesales_usa;

-- 1.5 TOTAL PROFITS
SELECT sum(profit) AS Total_Profits
FROM bikesales_usa;

-- 1.6  TOTAL COST
SELECT sum(cost) AS Total_Cost
FROM bikesales_usa;

-- 1.7 TOTAL ORDERS
SELECT count(`date`) AS Num_Orders
FROM bikesales_usa;





-- 2.1 REVENUE PER YEARS
SELECT YEAR(`date`) AS `Year`,
       sum(revenue) AS Total_Revenue
FROM bikesales_usa
GROUP BY YEAR(`date`)
ORDER BY YEAR(`date`);


-- 2.2 REVENUE PER  STATES
SELECT state,
       SUM(revenue) AS Total_revenue,
       SUM(profit) AS Total_Profit
FROM bikesales_usa
GROUP BY state
ORDER BY SUM(revenue) DESC, SUM(profit) DESC;
-- to find out the top 3 states using Bikes





-- 3. Revenue AGE GROUP vs REVENUE
SELECT Age_Group,
       SUM(revenue)  AS Total_revenue
FROM bikesales_usa
GROUP BY Age_Group
ORDER BY 2 DESC;
-- to find out which ages or age groups were our potential customers (for suitable promotions and marketing)





-- 4. GENDERS vs REVENUE
SELECT Customer_Gender,
       SUM(revenue)  AS Total_revenue
FROM bikesales_usa
GROUP BY Customer_Gender
ORDER BY 2 DESC;
-- to understand the which gender tend to use Bikes more





-- 5. REVENUE vs ALL PRODUCTS
-- 5.1 REVENUE vs CATEGORY
SELECT Product_Category,
       SUM(revenue) AS Total_revenue
FROM bikesales_usa
GROUP BY Product_Category
ORDER BY 2 DESC;
-- to investigate the bestseller category (BIKES)


-- 5.2 REVENUE vs SUB-CATEGORY
SELECT Product_Category,
       Sub_Category,
       SUM(revenue) AS Total_revenue
FROM bikesales_usa
GROUP BY Product_Category, Sub_Category
ORDER BY 3 DESC;
-- to make sure that BIKES was the best, which should make sense with its Sub-category


SELECT Product_Category,
       Sub_Category,
       SUM(revenue) AS Total_revenue
FROM bikesales_usa
WHERE Product_Category = 'Bikes'
GROUP BY Product_Category, Sub_Category
ORDER BY 3 DESC;


-- 5.3 REVENUE vs PRODUCTS
SELECT Product,
       Sub_Category,
       SUM(revenue) AS Total_revenue
FROM bikesales_usa
WHERE NOT Sub_Category LIKE '%bike%'
GROUP BY Product, Sub_Category
ORDER BY 3 DESC;
-- BIKES sector was dominant, I just want to understand more about the Top 2 Bestseller Sub-category (Helmets and Fenders)





-- SALES TRENDS
-- SALES TRENDS (STATE, YEARS) 
  WITH Sales_Trend_ETC AS (
       SELECT YEAR(`date`) AS `Years`,
              State, sum(revenue) AS Total_revenue,
              ROW_NUMBER() OVER(PARTITION BY YEAR(`date`) ORDER BY sum(revenue) DESC) AS now_num
       FROM bikesales_usa
       GROUP BY  YEAR(`date`), State ) 
SELECT *
FROM Sales_Trend_ETC
WHERE now_num <= 3;
-- Top 3 States had citizes who consumed the most (California, Washington, Oregon)





-- CUSTOMER DEMOGRAPHIC
-- AGE GROUP vs GENDERS 
  WITH Age_Gender_ETC AS (
       SELECT Age_Group,
              Customer_Gender,
              Product_Category,
              Sub_Category,
              sum(revenue) AS Total_revenue,
              ROW_NUMBER() OVER(PARTITION BY Age_Group, Customer_Gender ORDER BY sum(revenue) DESC) AS age_gender_row1
       FROM bikesales_usa
       WHERE Product_Category = 'Bikes'
       GROUP BY Age_Group, Customer_Gender, State, Product_Category, Sub_Category )
SELECT *
FROM Age_Gender_ETC
WHERE age_gender_row1 = 1;
-- BIKES was bestseller, but which age groups and which genders tended to buy it.


-- AGE GROUP vs GENDERS (NOT BIKE CATEGORY)
  WITH Age_Gender_ETC AS (
       SELECT Age_Group,
              Customer_Gender,
              Product_Category,
              Sub_Category,
              sum(revenue) AS Total_revenue,
              ROW_NUMBER() OVER(PARTITION BY Age_Group, Customer_Gender ORDER BY sum(revenue) DESC) AS age_gender_row2
       FROM bikesales_usa
       WHERE NOT Product_Category = 'Bikes'
       GROUP BY Age_Group, Customer_Gender, State, Product_Category, Sub_Category )
SELECT *
FROM Age_Gender_ETC
WHERE age_gender_row2 = 1;
-- Beside BIKES, How about other Sub-category consuming tendency? (Accessories: Helmets, Tire and Tubes)





-- PRODUCTS PREFERENCES
-- SIZES, COLORS vs MATERIALS
SELECT size,
       SUM(revenue) AS Total_revenue
FROM bikesales_usa
GROUP BY size
ORDER BY SUM(revenue) DESC;


SELECT color,
       SUM(revenue) AS Total_revenue
FROM bikesales_usa
GROUP BY color
ORDER BY SUM(revenue) DESC;


SELECT material,
       SUM(revenue) AS Total_revenue
FROM bikesales_usa
GROUP BY material
ORDER BY SUM(revenue) DESC;



-- ARRANGE SUB_CATEGORY BY THE PRODUCT WHICH HAD FAVOURITE (size, material, color)
   WITH size_color_material_ETC AS (
       SELECT size,
              color, material,
              Sub_Category,
              SUM(revenue) AS Total_revenue,
       RANK() OVER(PARTITION BY Sub_Category ORDER BY SUM(revenue) DESC) AS size_color_material_row
       FROM bikesales_usa
       GROUP BY size, color, material, Sub_Category)
SELECT *
FROM size_color_material_ETC
WHERE size_color_material_row =1;
-- I want to understand the favourite color which was chose by each Sub-Category, then update to store and prepare products for inventories



-- ARRANGE SUB_CATEGORY BY STATES WHICH HAD FAVOURITE (size, material, color)
   WITH size_color_material_ETC AS (
       SELECT size,
              color,
              material,
              State,
              SUM(revenue) AS Total_revenue,
       RANK() OVER(PARTITION BY State ORDER BY SUM(revenue) DESC) AS size_color_material_row1
       FROM bikesales_usa
       GROUP BY size, color, material, State )
SELECT *
FROM size_color_material_ETC
WHERE size_color_material_row1 <3;
-- to understand the size, color and material preference of each state





-- WARRANTY and CO_FRIENDLY
   WITH war_eco_manu_sub_ETC AS(
       SELECT Warranty,
              eco_friendly,
              Manufacturer,
              ROW_NUMBER() OVER (PARTITION BY Manufacturer ORDER BY sum(revenue) DESC) AS war_eco_manu_sub_num
       FROM bikesales_usa
       GROUP BY Warranty, eco_friendly, Manufacturer )
SELECT *
FROM war_eco_manu_sub_ETC
WHERE war_eco_manu_sub_num <=3;
-- to find out the Bikes consumption tendency (other criteria: warranty, eco_friendly) 






-- SHIPPING COST, TYPE and COMPANY
SELECT Shipping_Company,
       sum(Shipping_Cost) AS Total_Shipping_Cost
FROM bikesales_usa
GROUP BY Shipping_Company;
-- to find the best Shipping Company (almost the same firgures)


SELECT Shipping_Company,
       Shipping_Type,
       sum(Shipping_Cost) AS Total_Shipping_Cost
-- ROW_NUMBER() OVER(PARTITION BY Shipping_Company, Shipping_Type ORDER BY sum(Shipping_Cost) DESC)
FROM bikesales_usa
GROUP BY Shipping_Company, Shipping_Type
ORDER BY sum(Shipping_Cost) DESC;
-- Tried to add Shipping_Type in to get the differences (almost the same firgures, only GLS got twice in top 5)


SELECT Shipping_Company,
       rating,
       sum(Shipping_Cost) AS Total_Shipping_Cost
FROM bikesales_usa
WHERE rating <=3
GROUP BY Shipping_Company, rating
ORDER BY rating ASC, sum(Shipping_Cost) DESC;
-- SHIPPING COMPANY was a part of underrated rating, because top 5 SHIPPING COMPANY were also in the list


SELECT Shipping_Type,
       rating,
       sum(Shipping_Cost) AS Total_Shipping_Cost
FROM bikesales_usa
WHERE rating <=3
GROUP BY Shipping_Type, rating
ORDER BY rating ASC;
-- SHIPPING TYPE was also a part of underrated rating, because 4 TYPES were in the list
-- IT IS BIAS TO USE shipping_type AND shipping_company which were the reasons why the customer weren't satisfied


SELECT Shipping_Type,
       rating,
       sum(Shipping_Cost) AS Total_Shipping_Cost
FROM bikesales_usa
WHERE rating <=3
GROUP BY Shipping_Type, rating
ORDER BY rating ASC;






-- DISCOUNTS, DID PEOPLE BUY STAFFS WITH THE HIGHEST DISCOUNTS?
SELECT distinct discount
FROM bikesales_usa;
-- Having 30 types of discounts (from 0 to 29)

SELECT discount,
       sum(revenue) AS Total_revenue
FROM bikesales_usa
GROUP BY discount
ORDER BY sum(revenue) DESC;
-- Top 3 DISCOUNTS (15,18,11) while the highest discount was 29.






-- PROFITABILITY
-- PRFOT MARGIN (% revenue, profit per product)
SELECT  Product_Category,
       sub_category,
       sum(revenue) AS Total_revenue,
       sum(profit)  AS Total_profits,
       sum(profit)/sum(revenue)*100 AS Profit_Margin,
       RANK() OVER(PARTITION BY Product_Category ORDER BY sum(profit) DESC, sum(profit)/sum(revenue)*100 DESC) AS Profit_Margin_Rank
FROM bikesales_usa
GROUP BY sub_category, Product_Category;
-- While BIKE section was dominant both quantity and revenue, the top Profit margin belonging to Helmets, with Total_Profits and Profit_Margin (highest)





