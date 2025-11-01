🛍️ **Online Retail Database Analysis & Dashboard**

A SQL + Python project analyzing retail data to uncover sales trends, top customers, and revenue insights.

📘 **Project Overview**

This project analyzes an Online Retail Dataset using SQL and Python to explore customer purchasing patterns, product performance, and regional sales trends.
The goal is to transform raw transactional data into actionable business insights through database queries and visual dashboards.

🧠 **Methodology**

Data Preparation:
Cleaned and formatted data; removed missing values and duplicates.

Database Setup:
Created an SQLite3 table sales_data with fields like InvoiceNo, StockCode, Quantity, UnitPrice, and Country.

**Key SQL Queries:**

-- Top 10 customers by spend
SELECT CustomerID, SUM(Quantity * UnitPrice) AS TotalSpent
FROM sales_data
GROUP BY CustomerID
ORDER BY TotalSpent DESC
LIMIT 10;


**Visualization:**

Built summaries in Python for:

Revenue by country

Monthly sales trend

Top customers & products

⚗️ **Challenges & Learnings**

Managed missing customer IDs and inconsistent data.

Practiced optimized SQL queries for analysis.

Improved visual storytelling using Python plots.

🔑 **Key Findings**

UK generated the highest total revenue.

December recorded peak monthly sales.

Top 20% of customers contributed ~80% of revenue (Pareto principle).

💼 **Freelance Pitch**

“Developed a SQL-powered retail dashboard that reveals key sales insights, top-performing products, and customer trends — enabling smarter business decisions.”

🧾 **File Structure**

online_retail_analysis/
├─ Online_Retail.ipynb
├─ retail_data.csv
├─ screenshots/
├─ requirements.txt
└─ README.md

⚙️ **How to Clone and Run the Project**

🪜 1️⃣**Clone the Repository**
git clone https://github.com/<your-username>/online_retail_analysis.git
cd online_retail_analysis

⚙️ 2️⃣ **Install Dependencies**

If you have a requirements.txt file:

pip install -r requirements.txt


Or manually install:

pip install pandas matplotlib seaborn sqlite3 jupyter

💻 3️⃣ **Run the Notebook**

Start Jupyter:

jupyter notebook


Then open:

Online_Retail.ipynb


If using Google Colab:

Upload the notebook

Mount your Drive or upload retail_data.csv

▶️ 4️⃣**Execute the Notebook**

Run all cells (Shift + Enter) to:

Load and clean data

Execute SQL queries

Generate dashboard visuals

📊 5️⃣ **View Outputs**

You’ll see visualizations such as:

💰 Revenue by Country

📈 Monthly Sales Trend

👥 Top Customers

✅**Quick Summary**

Step	Command	Description
1	git clone <repo-url>	Clone the repository
2	cd online_retail_analysis	Enter project folder
3	pip install -r requirements.txt	Install dependencies
4	jupyter notebook	Open and run notebook

👩‍💻 **About Me**

Hi, I’m Nadia Hafsa — a Data Science & Analytics Enthusiast passionate about using Python, SQL, and data visualization to turn raw data into powerful insights.
I enjoy creating interactive dashboards, automated data pipelines, and analytics-driven business solutions.

💼 **Freelance Focus:**
Data analysis • Visualization • Automation • Business dashboards

📫 **Connect**: 
GitHub: https://github.com/NadiaHafsa | LinkedIn: www.linkedin.com/in/nadia-hafsa-93986975
