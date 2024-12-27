# Online-Sales-Data-Dashboard-Using-Power-BI

The objective of this project was to analyze the sales performance of Madhav Ecommerce across various dimensions such as geography, product categories, payment methods, and customer segments. The goal was to uncover actionable insights that could help in driving business decisions, optimizing sales strategies, and enhancing profitability.

# Methodology
**Data Collection:**

- Extracted sales data for Madhav Ecommerce from the provided dataset.
- The data included variables like sales amount, profit, quantity, customer information, product categories, payment methods, and monthly performance.

**Data Cleaning & Processing:**

- Ensured data accuracy and consistency by handling missing values, removing duplicates, and standardizing formats.
- Segmented the data by relevant dimensions such as state, product category, and payment method for detailed analysis.

**Exploratory Data Analysis (EDA):**

- Conducted a thorough EDA to identify trends, patterns, and outliers in the data.
- Utilized visualizations such as bar charts, pie charts, and line graphs to represent sales distribution across different dimensions.
- Analyzed monthly performance to understand seasonal trends and peaks in profit.

**Dashboard Creation:**

- Developed an interactive Power BI dashboard that presents the key findings in a visually appealing manner.
- Included filters and drill-down capabilities to allow for more granular exploration of the data by clients.

 # Source:
The data utilized in this project comes from a comprehensive dataset that captures various aspects of sales, customer demographics, and transactional details for Madhav Ecommerce. This dataset serves as the foundation for the analysis conducted in Power BI, enabling the extraction of valuable insights that drive business decisions.

For more information about the dataset and to access the data used in this analysis, please visit the following link: 
https://www.kaggle.com/datasets/saadharoon27/madhav-store-dataset/data

# Technology Used

- **Power BI:** Utilized for data visualization and dashboard creation, enabling interactive exploration of sales data.

## Elements Used in Power BI for Visualization

### 1. **KPI Cards**
   - **Purpose:** 
     - KPI (Key Performance Indicator) cards provide an at-a-glance summary of the overall business performance, including total sales, total profit, quantity sold, and average order value.
     - They serve as a quick reference for the most critical metrics, helping stakeholders quickly understand the business's financial health.

### 2. **Bar Chart: Sum of Amount by State**
   - **Purpose:** 
     - This chart displays the distribution of sales revenue across different states, highlighting the regions with the highest sales contributions.
     - It helps in identifying key markets and regions where sales strategies can be focused or expanded.

### 3. **Pie Chart: Sum of Quantity by Category**
   - **Purpose:** 
     - The pie chart visualizes the proportion of total sales quantity across different product categories.
     - This helps in understanding which categories drive the most sales and can inform inventory and marketing decisions.

### 4. **Line Chart: Profit by Month**
   - **Purpose:** 
     - The line chart tracks monthly profit trends throughout the year, identifying peaks and troughs in profitability.
     - This is crucial for spotting seasonal trends, allowing for strategic planning around inventory and promotions during high-profit periods.

### 5. **Bar Chart: Sum of Amount by Customer Name**
   - **Purpose:** 
     - This chart highlights the top customers contributing to sales, providing insights into customer value and segmentation.
     - It can be used to tailor customer loyalty programs or personalized marketing efforts for high-value customers.

### 6. **Pie Chart: Sum of Quantity by Payment Mode**
   - **Purpose:** 
     - This visualization shows the distribution of payment methods used by customers, helping to understand payment preferences.
     - It informs decisions on payment method offerings, partnerships with financial services, and potential for payment method-based promotions.

### 7. **Bar Chart: Sum of Profit by Sub-Category**
   - **Purpose:** 
     - The bar chart visualizes the profitability of different product sub-categories.
     - This helps in identifying the most and least profitable product lines, guiding decisions on inventory management, product focus, and promotional strategies.

### 8. **Slicers**
   - **Purpose:** 
     - Slicers provide interactive filtering options for users, enabling them to explore data for specific time periods (quarters) or geographic regions (states).
     - This enhances the dashboard’s interactivity, allowing users to drill down into specific segments of the data for more detailed analysis.
   - **Types of Slicers Used:**
     - **Quarter Slicer:** Q1, Q2, Q3, Q4
     - **State Slicer:** Allows filtering by specific states
       
### 9. **Clustered Bar Chart**
   - **Purpose:** 
     - Displays grouped data across multiple categories, allowing for comparison between different segments within the same category.
       
### 10. **Donut Chart**
   - **Purpose:** 
     - Similar to a pie chart, but with a blank center, used for comparing parts of a whole, such as category-wise sales distribution.
       
### 11. **Area Chart**
   - **Purpose:** 
     - Combines features of line charts and bar charts to show quantities over time, emphasizing the total value across a trend.



- **Microsoft Excel:** Used for preliminary data cleaning, processing, and basic analysis.
- **DAX (Data Analysis Expressions):** Employed in Power BI for creating calculated fields and advanced data manipulation.

# Key Findings:
- **Geographical Insights:**
- Maharashtra emerged as the top-performing state, followed by Madhya Pradesh and Uttar Pradesh.
- Delhi showed the lowest sales among the key states analyzed.

![image](https://github.com/user-attachments/assets/8f1e181d-f081-47a5-8ecc-ffe1ff8766e2)

- **Category-Wise Performance:**

- Clothing dominated sales, accounting for 63% of the total quantity sold.
- Electronics and Furniture contributed 21% and 17%, respectively.

![image](https://github.com/user-attachments/assets/f6f3396c-cbb8-49ee-8e66-9a3443c26b47)

- **Customer Insights:**

- The top customers contributing to sales are Harivansh and Madhav.
- These customers have higher transaction values compared to others like Madan Mohan and Shiva.
  
![image](https://github.com/user-attachments/assets/bda79087-ed42-4704-991a-d33fc43212d9)


- **Payment Mode Analysis:**

- Cash on Delivery (COD) is the most popular payment method, accounting for 44% of the transactions.
- UPI and Debit Card payments together make up 34% of the transactions, while Credit Card and EMI account for 22%.

![image](https://github.com/user-attachments/assets/bcc27e99-810c-4d4a-af4a-fa49442ba966)

- **Product Profitability by Sub-Category:**

- Printers lead in profit generation among sub-categories, followed by Bookcases and Sarees.
- Tables and Accessories have lower profit margins but still contribute to overall profitability.

![image](https://github.com/user-attachments/assets/a73cf8f8-88ac-4811-a3bc-51121907f305)


# Conclusion:
The analysis revealed key opportunities for Madhav Ecommerce to enhance sales and profitability:

- **Targeting High-Performing States:** Focusing marketing and sales efforts on Maharashtra, Madhya Pradesh, and Uttar Pradesh could yield significant returns.

- **Leveraging Peak Months:** By capitalizing on peak months (February, April, December) with targeted promotions and inventory optimization, overall profitability could be increased by 10-15%.

- **Promoting High-Profit Products:** Emphasizing high-margin sub-categories like Printers and Bookcases could further boost profitability by up to 8%.

- **Payment Method Optimization:** Encouraging the use of profitable payment methods and offering incentives for digital payments could enhance customer satisfaction and reduce operational costs.


  
