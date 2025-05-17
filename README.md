# Sales Performance Analysis Project

## Introduction
Sales data is more than just numbers—it reflects how well a business meets customer demand, manages logistics, and adapts to market trends. This project analyzes a rich sales dataset to uncover patterns in profitability, shipping efficiency, customer segmentation, and more. Through detailed analysis using Python and visualization tools, the goal is to provide actionable insights that drive business performance and customer satisfaction.

---

## Project Overview
This project showcases my ability to analyze and visualize sales performance using Python. It includes preparing the dataset, conducting thorough data exploration, and building insightful visualizations to summarize findings. The analysis is complemented by a Power BI dashboard for interactive exploration of the data. The notebook file where this analysis was done can be gotten [Here](https://colab.research.google.com/drive/1lcm9vW6VO56u1bdVR_L-bHVqzrVlbTPI?usp=sharing)

---

## Dataset Description
The dataset used includes key sales information:

- **Order Date & Ship Date** – For analyzing shipping duration  
- **Category & Sub-Category** – To understand product performance  
- **Sales, Profit & Discount** – For profitability and pricing insights  
- **Customer Segment** – To evaluate demand across buyer types  
- **Country, Region & Market** – For geographical performance analysis  

**Dataset link**: [Superstore Sales Dataset on Kaggle](https://www.kaggle.com/datasets/laibaanwer/superstore-sales-dataset/data)

---

## Objectives
- Analyze **sales trends** over time  
- Evaluate **shipping efficiency**  
- Identify **top-selling products and categories**  
- Explore **geographic and market-based sales performance**  
- Assess **sub-category level trends**  
- Understand **customer segment behaviors**  
- Measure **profitability and discount impacts**

---

## Tools Used
- **Python**: Pandas, Matplotlib, Seaborn  
- **Jupyter Notebook**  
- **Power BI**

---

## Data Preparation and Cleaning
- Checked data types and corrected formatting  
- Split profit values into profit vs. loss for clarity  
- Calculated discount amounts and net sales  
- Computed shipping duration as the difference between Order Date and Ship Date  
- Cleaned missing values and ensured dataset readiness for analysis

---

## Exploratory Data Analysis (EDA)

### 1. Sales Trends Over Time
Sales showed a consistent increase year over year, indicating healthy growth.

![Sales Trend Over Time](https://github.com/felido01/sales_performance/blob/9c4e90f749d8c4a44a3b9963e0bd1f43a1854bf1/newplot%20(6).png)

---

### 2. Top-Selling Products and Categories
- Apple Smart Phone, Full Size was the top-selling product  
- Other high performers included smartphones from Cisco, Motorola, and Nokia  
- Technology dominated in both sales and profitability  

![Top Products](path/to/top_products_bar_chart.png)  
![Sales by Category](path/to/sales_by_category_pie_chart.png)

---

### 3. Shipping Efficiency
- Calculated average shipping time by priority  
- Order priority correlates well with shipping duration  

![Shipping Duration by Priority](path/to/shipping_duration_boxplot.png)

---

### 4. Geographic Sales Trends
- The United States had the highest sales volume  
- Central region led in both sales and profits  
- Strong performance in Oceania and Southeast Asia  

![Sales by Region](path/to/region_sales_bar_chart.png)  
![Market Map](path/to/sales_map_visual.png)

---

### 5. Sub-Category Insights
- Phones, Chairs, and Copiers were top-performing  
- Labels and Fasteners had low performance  

![Sub-Category Performance](path/to/subcategory_performance_chart.png)

---

### 6. Customer Segment Analysis
- Consumer segment had the highest sales and profit  
- Corporate and Home Office followed closely  

![Sales by Segment](path/to/segment_sales_bar_chart.png)

---

### 7. Discount and Profitability Analysis
- Discounts over 50% often led to losses  
- Strong correlation between discount rate and profit reduction  

![Discount vs Profit](path/to/discount_vs_profit_scatterplot.png)

---

## Dashboard
Interactive Power BI dashboard for this analysis:  
🔗 [**View Dashboard**](https://app.powerbi.com/links/PSaHjGBs_9?ctid=a36e1a13-c829-4154-8635-f2516711db50&pbi_source=linkShare)  
> *(Requires Power BI account to access)*

---

## Key Findings
- **Technology** is the highest-grossing and most profitable category  
- **Furniture** has moderate sales but high losses  
- High discounts negatively impact profits  
- Shipping times align well with order priority  
- Regional and customer segmentation can guide targeted strategies

---

## Recommendations

### ✅ Revisit Discount Strategy
- Limit excessive discounts on high-demand products  
- Use strategic promotions on low-performing sub-categories

### ✅ Boost Demand for Low-Selling Products
- Promote products like Labels and Fasteners with campaigns

### ✅ Enhance Logistics
- Streamline supply chain for improved delivery times

### ✅ Expand High-Profit Segments
- Focus marketing and inventory on Technology and top-selling items

### ✅ Focus on Regional Strategy
- Use localized campaigns in underperforming regions like Canada and parts of Europe

### ✅ Collect More Customer Data
- Use surveys or feedback tools to gather demographic insights

---

## Challenges Encountered
- Lack of **cost columns** limited margin precision  
- Missing **customer demographics** hindered segmentation  
- High discounts lacked **contextual metadata** (e.g., promo events)

---

## Conclusion
This analysis highlights how effective data analytics can uncover trends, identify inefficiencies, and guide business strategies. By refining discount policies, focusing on profitable segments, and optimizing logistics, businesses can boost revenue while improving customer experience.

---

**Data Analyst**: Felix Idowu  
**Project Repository**: *[Add GitHub link here]*  
