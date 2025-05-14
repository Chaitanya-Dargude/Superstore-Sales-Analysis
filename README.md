# **Superstore Sales Performance Analysis using Python.**
## Objective:
This project aims to analyze a retail superstore’s historical sales data to extract meaningful insights that can help improve decision-making.
## Problem Statements Addressed:
- Which regions and states have the highest and lowest profit?
- Which product categories and sub-categories are the most/least profitable?
- How does discount impact profitability?
- Which shipping mode is most used and which one gives higher profit?
- Which segments (Consumer, Corporate, Home Office) generate the most revenue?
- What are the top-selling products by sales and quantity?
- How does sales performance vary by region and city?
- What is the correlation between sales, quantity, discount, and profit?
- Which orders or products lead to losses, and why?
- What are the recommendations to improve profit and reduce losses?
## Dataset Information
- Source: Superstore Sales CSV file
- Total Rows: 9,994 And Columns: 21
- Key Columns:
    - Order ID, Order Date, Ship Date
    - Customer ID, Customer Name
    - Region, State, City
    - Category, Sub-Category, Product Name
    - Sales, Quantity, Discount, Profit
## Technologies & Libraries Used
- Language: Python
- Libraries:
   - pandas – for data manipulation
   - numpy – for numerical operations
   - matplotlib, seaborn – for data visualization
   - plotly – for interactive charts (optional)
   - jupyter notebook – for analysis and visualization
## Project Workflow / Steps
### Step	Description
- Data Loading	Loaded CSV file using pandas
- Data Exploration	Used .info(), .describe(), .isnull() to understand structure
- Data Cleaning	Converted date columns, checked for duplicates, dropped unused columns
- Feature Engineering	Extracted year/month from dates for time analysis
- Exploratory Data Analysis (EDA)	Created charts to visualize sales, profit, discounts, etc.
- Business Insights	Identified trends, risks, and opportunities
- Final Summary	Compiled results and visual findings into conclusions
## Results / Insights
- West Region is the top performer by profit; Central Region has the most orders.
- Tables sub-category causes high losses; avoid offering heavy discounts on it.
- High discounts often lead to negative profits.
- Consumer segment contributes the most to sales.
- Standard Class is the most used shipping mode.
- New York city has the highest sales; Springfield has lower sales.
## Folder Structure
![image](https://github.com/user-attachments/assets/b9fdc17f-862f-4a53-8e61-8e7651c730e1)

## Output Screenshots
You can save these charts as PNG or JPG:
- Region-wise Profit Bar Chart :  ![image](https://github.com/user-attachments/assets/94108900-b878-47bd-b49e-80bbbad18fae)
- Sub-Category Sales vs Profit : ![image](https://github.com/user-attachments/assets/babdbc48-efbe-4145-ad49-e077ce80464b)
- Discount vs Profit Scatter Plot : ![image](https://github.com/user-attachments/assets/e3ad4d22-4ac2-4e10-b29f-34c967aa6afe)
- Segment-wise Sales Pie Chart : ![image](https://github.com/user-attachments/assets/57f3e741-4c19-4191-9362-34a04f94e7b4)
- Top 10 Cities by Sales : ![image](https://github.com/user-attachments/assets/9a0a5ba2-af0c-4c53-ac6e-ce89c8f814a7)

## How to Run the Project
 - Clone the repo: bash, Copy, Edit
   - git clone https://github.com/yourusername/superstore-sales-analysis.git
   - cd superstore-sales-analysis
 - Install dependencies: bash, Copy, Edit
   - pip install -r requirements.txt
 - Run Jupyter Notebook: bash, Copy, Edit
   - jupyter notebook
## Author Information
 - Name: Chaitanya Rangnath Dargude
  - Email: chaitanyadargude16@gmail.com
  - LinkedIn: linkedin.com/in/chaitanya-dargude-63957a134
  - Location: Nashik, Maharashtra, India
## Conclusion
This project helped me understand how real-world sales data can be explored and visualized using Python. I learned how to clean data, perform EDA, and interpret trends for better decision-making. It is a foundational project for my data science journey and demonstrates my ability to work with business data end-to-end.
## Future Work:
   - Build a sales prediction model using ML
   - Create a dashboard in Power BI or Tableau
   - Automate reporting using Python scripts
