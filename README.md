## 1. Introduction

  <img width="851" height="480" alt="Image" src="https://github.com/user-attachments/assets/92c0338a-0352-4dc3-a89f-66bda2f20726" />

This project presents a comprehensive retail analysis for **BB Store's - a fashion retailer located in the central of Ho Chi Minh City**. In recent periods, the store has experienced growth challenges due to limited leadership direction and a lack of innovative strategies. These challenges have raised critical questions around revenue performance and product strategy.

As a Data Analyst, my objective is to assess the store’s current business performance, evaluate product-related factors and customer conversion rates, and provide data-driven insights. The findings will support strategic decision-making for stakeholders and guide the development of a growth plan for the brand in the **Offline retail** segment.

Before starting the analysis process, I provide a summary of the key contents of the report to help you clearly understand the main sections I will address:

  <img width="849" height="475" alt="Image" src="https://github.com/user-attachments/assets/e75a3def-5f6f-462a-bf63-e64c4619f2d5" />

## 2. Implementation Process

### 2.1. Defining Objectives and Stakeholders

The first step was to clearly define the business objectives, rooted in the core challenges the store is facing, and to identify the key stakeholders who require actionable insights. This process began with several guiding questions:
- **What are the actual problems the business is facing?**
  - What has caused the store’s recent struggles in achieving growth? - a decline in revenue growth, an inability to develop new products, or a lack of ability to attract customers to directly compete with market rivals?
- **What is the goal of this analysis?**
  - Help the business achieve its desired growth targets in the future, potentially by adjusting business strategies or product offerings. The ultimate aim is to increase revenue and profit, attract new customers, and retain existing ones.
- **Who are the primary stakeholders?**
  - Company leadership, product development department, and sales department.
- **What are they interested in?**
  - Company leadership: Overall revenue, new customer acquisition rate, conversion rate, average transaction value, and top-performing product categories.
  - Product development department: Whether the products meet market demand, which products are the core offerings or require improvement, and whether they align with the store’s targeted customer segments.
  - Sales department: Total revenue and profit by time of the week, peak value periods, current customer conversion rate, strategies for customer retention and acquisition, and identification of products generating the most revenue.
- **How will this analysis help them solve their problems?**
  - Company leadership: Gain a clear picture of the store’s current situation to evaluate and act upon proposed recommendations.
  - Product team: Identify the true value each product brings, enabling them to restructure the product portfolio to align with the business strategy.
  - Sales team: Increase revenue and profit, and improve customer conversion rates.

### 2.2. Establishing Measurement Metrics

After clarifying the objectives and identifying the challenges the business is facing, developing a set of performance metrics aligned with these factors plays a critical role in assessing operational performance. These metrics provide concrete data to pinpoint issues, rather than relying on subjective assumptions.

The metrics will be categorized into three groups, corresponding to the evaluation objectives defined in the “Defining Objectives and Stakeholders" step.

- **Sales Performance:**
  - Total Revenue: Within a specific period (daily, weekly, monthly, quarterly).
  - Average Order Value (AOV) or Average Transaction Value (ATV)
  - Units per Transaction (UPT): Number of products sold per transaction.
  - Conversion Rate: Percentage of visitors who make a purchase.
  - Gross Margin: Percentage of revenue retained after subtracting production costs.
  - Discount Rate: Average and by inventory category.
- **Product Performance:**
  - Product category revenue (amount and percentage) (e.g., shirts, pants, dresses, …)
  - Product type revenue (amount and percentage) (e.g., party wear, office wear, …)
  - Inventory category revenue (amount and percentage) (e.g., New Arrival Batch 1, Hero, Premium, Regular)
  - Top 10 Bestsellers
  - Top 10 Worst Sellers
  - Average Product Price
  - Price Distribution to evaluate the price ranges customers usually purchase from.
- **Customer**
  - New vs. returning customer rate

### 2.3. Data Consolidation

Based on the predefined performance metrics, the next step is to identify and determine the data that can be used to measure each metric. Due to the store’s confidentiality requirements, my project is only permitted to use data from January 1, 2024 to May 26, 2024. Subsequently, I identify the available data sources for extraction to support the analysis, and the collected data will be consolidated into two Excel files named as follows:

- **DAILY SALES:**
  - Date: The date on which sales transactions are conducted.
  - Weekday: The day of the week for the sales date.
  - Number of Bill: The number of invoices processed on that day.
  - Unit: The total number of products sold.
  - APT (Average Price per Transaction): The average value per transaction.
  - UPT (Units per Transaction): The average number of products sold per transaction.
  - Traffic: The number of customers visiting the store.
  - Conversion Rate: The percentage of visitors who make a purchase.
  - Revenue: Total sales revenue for the day.
  - Target by Day: The daily sales revenue target.
- **TRANSACTION DATA**
  - Date: The date on which sales transactions are conducted.
  - SKU-1: Product code by model (excluding size and color).
  - SKU-2: Product code by size and color.
  - Product Category: Product category (e.g., Set, Shirt, Pants, …).
  - Product Type: Product type (e.g., party wear, office wear, lifestyle).
  - Order ID: Unique identifier for each sales transaction.
  - Units: Number of products in the order.
  - Discount: Discount amount applied to the order.
  - Revenue: Total revenue from the order.
  - Merchandise Type: Type of merchandise (e.g., regular goods).
  - Customer Type: Customer type (e.g., new or returning customer).

### 2.4. Report Analytics and Visualization

I consolidate all the analyses I have conducted into a report titled [BB Sotre_Reporting.pdf](https://github.com/quachquoccuong2904/BB-Stores-Retail-Analysis/blob/main/BB%20Store_Reporting.pdf). In addition, I also create a visual report in the **Visualization sheet** titled [BBStore_Dashboard.xlsx](https://github.com/quachquoccuong2904/BB-Stores-Retail-Analysis/blob/main/BBStore_Dashboard.xlsx) to help stakeholders clearly understand the overall picture of the business.

## 3. Conclusion and Recommendations

This analysis goes beyond identifying the issues the store is facing; I also present several practical recommendations to help stakeholders achieve their objectives and expectations, while guiding the store’s long-term development. These recommendations, along with an analysis of the advantages and challenges of their implementation, are presented in the final pages of the report.

  <img width="851" height="481" alt="Image" src="https://github.com/user-attachments/assets/879ba11c-0b91-48ff-8b4a-7e234388dee8" />
