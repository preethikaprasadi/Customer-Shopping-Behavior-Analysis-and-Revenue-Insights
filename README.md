# Customer Shopping Behavior Analysis and Revenue Insights

This project focuses on analyzing customer shopping data to derive meaningful insights and recommendations for improving business strategies. Using Python and popular data analysis libraries, we explore revenue patterns, customer demographics, and shopping behaviors, offering actionable insights for better inventory and marketing management.

---

## Dataset Overview

The dataset contains detailed records of customer transactions, including:

- **Invoice Details**: Invoice number, date.
- **Customer Information**: Customer ID, gender, and age.
- **Product Details**: Category, quantity, and unit price.
- **Transaction Information**: Payment method, shopping mall, and total revenue.

---

## Key Features

1. **Data Preprocessing**:
   - Handle missing values.
   - Convert `invoice_date` to datetime for temporal analysis.
   - Add calculated columns like `revenue` and `age_group`.

2. **Revenue Analysis**:
   - Calculate total revenue, revenue by category, gender, and shopping mall.
   - Analyze average revenue by age groups.

3. **Customer Segmentation**:
   - Perform RFM (Recency, Frequency, Monetary) analysis.
   - Cluster customers into groups using the K-Means algorithm.

4. **Visualizations**:
   - Revenue by product category and shopping mall.
   - Payment method preferences.
   - Monthly revenue trends.

5. **Insights & Recommendations**:
   - Identify top-performing product categories and shopping malls.
   - Highlight potential growth opportunities and areas for improvement.

---

## Tools and Libraries

- **Programming Language**: Python
- **Data Analysis and Manipulation**: Pandas, NumPy
- **Data Visualization**: Matplotlib, Seaborn
- **Machine Learning**: Scikit-learn
- **Other Tools**: Jupyter Notebook

---

## Results and Insights

1. **Top Categories**: 
   - Categories like "Clothing" and "Shoes" generate the highest revenue.
   
2. **Shopping Mall Performance**:
   - "Mall of Istanbul" is the top performer, while "Forum Istanbul" has untapped potential.

3. **Customer Demographics**:
   - Customers aged 18-30 contribute significantly to revenue.
   - Credit cards are the most preferred payment method.

4. **RFM Analysis**:
   - Customers are segmented into clusters to identify high-value and potential churn segments.

---

## Recommendations

1. **Inventory Management**:
   - Stock popular categories (e.g., Clothing, Shoes) more frequently.

2. **Targeted Campaigns**:
   - Focus on underperforming malls with personalized promotions.

3. **Payment Rewards**:
   - Promote credit card rewards to increase usage.

---

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/preethikaprasadi/customer-analysis.git
   cd customer-analysis
