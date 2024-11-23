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
   **Customer Demographics**: Customer Age, Age Group, Gender, Country and State.
   **Product Details**: Product Category, Order Quantity, Unit Cost, Unit Price, Size, Material, Color, Warranty, Manufacturer, Discount and Eco Friendly,
   **Sales Metrics**: Revenue, Cost and Profit.
   **Delivery**: Rating, Shipping Weight, Delivery Time, Shipping Cost, Shipping Company, Shipping Type, Return Policy and Insurance.

The data link source from Kaggle: **[Global BikeSales Data]((https://www.kaggle.com/datasets/hamedahmadinia/global-bike-sales-dataset-2013-2023))**

## 3. SKILLS vs TOOLS:
### Tools:
  - Excel for data cleaning and formatting.
  - SQL for querying and joining data
  - Tableau for creating dashboards

### Skills
**Data Cleaning/Preparation:**
In the initial data preparation phase, we performed the following tasks:
  - Data loading and inspection.
  - Data cleaning and formatting.
  - Narrow it down to the Bike Sales performance in USA

**Exploratory Data Analysis:**
**EDA** involved exploring the sales data to answer key questions, such as:

**1. SALES PERFORMANCE**
   1. Are there seasonal patterns in bike sales?
   2. What are the peak sales periods?
   3. Is there consistent year-over-year growth in revenue or sales volume, especially in COVID-19?
   4. Which states have the highest sales performance?
   5. Which products or product lines have the highest profit margins?

**2. CUSTOMER DEMOGRAPHICS**
   1. Who was more likely to buy bikes, male or female? 
   2. Which age groups?
   3. Which states were they?
    
**3. PRODUCT CATEGORY**
   1. Which product category was top seller?
   2. Which sub-category was the top1 and the top2?
   3. What kinds of sub-categories did male or female feel interested in?
    
**4. SIZE, COLOR and MATERIALS**
   1. What was the factor the customers usually chose best generally in USA?
   2. What was the factor chosen the most per state?

**5. WARRANTY vs SUSTAINABILITY**
   1. Did the customers care much about the warranty? Which one did they choose best?
   2. Did the customer focus on the sustainability?

**6. DELIVERY PROCESS**
   1. Which Shipping_Company was chosen most?
   2. Which Shipping_Type was selected best? 

**7. RATING**
   1. Which Shipping_Type and Shipping_Company got the lowest-satisfied rate?
   2. Any correlation between Rating and Shipping_Type or Shipping_Company?

**8. DISCOUNTS**
   1. How many discounts types?
   2. Did people tend to buy Bikes with the highest discounts?

**Data Analysis**
Include some interesting code/features worked with in **MySQL**:
   1. SELECT * FROM table 1WHERE cond = 2;
   2. SELECT * FROM table 1WHERE cond = 2 GROUP BY column1 ORDER BY column2
   3. Window_ETC:
      + ROW_NUMBER()
      + RANK()
     
## ANALYSIS vs INSIGHTS:
Key Insights:
   1. The Bike Sales Performance had been fluctuated and decreased lightly during the last decade, with a noticeable peak during the summer season and December.
   2. People from 35 to 63 years old were the main customers, particularly Men.
   3. Male customers make up a larger proportion of purchases, but female customers show higher average spending.
   4. Bikes Section was the best-performing category in terms of sales and revenue.
   5. Despite of selling Bike Section most, The profitability belonged to Accessories section, especially Helmet products.

## VISUALIZATIONS:
The Tableau dashboard includes:
   1. A Regional Map visualizing sales performance by states.
   2. The two Bar Charts showing age groups and gender contributions
   3. A Line Chart comparing total product category profits per month.
   4. A Pie Chart showing the highest detailed revenue of Category and its sub-category (Bike Sales)
   5. The Six of Bar Charts demonstrating the Best and Lowest Bikes by Revenue, Profit and Profit Margins.
 **6. Data Visualization (Tableau)**

## CONCLUSION:
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

## HOW TO ACCESS TO THE PROJECT:

1.Download the dataset file from this repository: **[USA_BikeSales_Data_Edited.csv](https://github.com/user-attachments/files/17879001/USA_BikeSales_Data_Edited.csv)**
2.Open the Tableau Packaged Workbook **([USA_BikeSales_Dashboard.twb](https://public.tableau.com/app/profile/harry.huynh/viz/USA_BikeSales/OverallDashboard)** in Tableau Public.
3.View the dashboard here: Tableau Public Link.

**OVERVIEW USA BIKESALE DASHBOARD** 

**BEST vs WORST BEST PRODUCTS DASHBOARD** 

## 8. USING SQL QUERIES:
