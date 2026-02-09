**📊 Data Analytics Project – Customer Shopping Behavior**

**📌 Overview**

This project demonstrates an end-to-end data analytics workflow, starting from raw data ingestion to delivering actionable business insights through dashboards and presentations.
The objective is to analyze customer shopping behavior, identify trends, and support data-driven decision-making using Python, SQL, and Power BI.

**The project covers:**
- Exploratory Data Analysis (EDA)
- Data cleaning and feature engineering
- SQL-based business analysis
- Interactive dashboard creation
- Insight reporting and presentation

**📂 Dataset**
- Type: Customer transactional data
- Records: ~3,900 transactions
- Features:
  - Customer demographics (age, gender, location, subscription status)
  - Purchase details (category, item, amount, season, size, color)
  - Behavioral attributes (discount usage, purchase frequency, ratings, shipping type)
- Dataset used for analysis and reporting is documented in the project report 

**🛠️ Tools & Technologies**
- Python: Pandas, NumPy, Matplotlib, Seaborn
- SQL: PostgreSQL / MySQL / SQL Server
- BI Tool: Power BI
- Presentation: Gamma (PPT)
- IDE & Utilities: Jupyter Notebook, VS Code

**🔄 Project Workflow / Steps**

1. Data Loading
 - Loaded raw dataset using Pandas
- Verified schema, data types, and basic statistics

2. Exploratory Data Analysis (EDA)
- Distribution analysis of key variables
- Trend analysis by category, age group, and subscription status
- Identification of missing values and outliers

3. Data Cleaning & Feature Engineering
- Handled missing values using logical imputations
- Standardized column names
- Created derived features such as:
  - Age groups
  - Customer segments
  - Purchase frequency indicators
- Ensured data consistency before database ingestion

4. SQL Analysis
- Cleaned data was loaded into PostgreSQL / MySQL / SQL Server for structured analysis.

Key SQL analyses included:
- Revenue by gender and age group
- Subscriber vs non-subscriber spending behavior
- Top products and categories
- Discount impact on purchase behavior
- Customer segmentation (new, returning, loyal)

**📊 Power BI Dashboard**

An interactive Power BI dashboard was created to visualize insights, including:
- KPIs (total customers, average spend, ratings)
- Revenue by category and age group
- Subscription and shipping analysis
- Product performance insights
The dashboard enables quick exploration and filtering for business stakeholders.

**📈 Results & Insights**
- Identified high-value customer segments and revenue drivers
- Observed spending differences between subscribers and non-subscribers
- Highlighted top-performing products and categories
- Evaluated the effectiveness of discounts and promotions
- Delivered actionable recommendations for marketing and retention strategies

**▶️ How to Run This Project**

1. Clone the Repository

git clone https://github.com/your-username/data-analytics-project.git

2. Set Up Python Environment

pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2

3. Run EDA & Cleaning
- Open the Jupyter Notebook
- Execute cells sequentially to perform EDA and data cleaning

4. SQL Analysis
- Load cleaned data into PostgreSQL / MySQL / SQL Server
- Run SQL scripts provided in the /sql folder

5. Power BI Dashboard
- Open the .pbix file in Power BI Desktop
- Refresh data connection if needed

6. Reporting
- Review the analytical report and Gamma presentation for summarized insights
