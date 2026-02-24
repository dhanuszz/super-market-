📌 Project Statement

Title: Sales Data Analysis Using NumPy Array Operations

Project Statement:
The objective of this project is to analyze sales data efficiently using NumPy array operations in Python. The project focuses on handling large numerical datasets without relying on traditional loops, thereby improving performance and accuracy. By using NumPy’s powerful array manipulation, aggregation, and statistical functions, the project aims to extract meaningful business insights such as total revenue, average sales, best-performing products, monthly trends, and sales growth patterns.

This analysis helps organizations make data-driven decisions related to inventory management, marketing strategies, and revenue optimization.

🎯 Objectives of the Project

To store and manage sales data using NumPy arrays

To perform calculations like total sales, average sales, and profit

To analyze monthly and product-wise sales performance

To identify highest and lowest selling products

To understand sales trends using array operations

📊 Dataset Description

You can assume the dataset is collected from a retail store over several months.

Dataset 1: Monthly Sales Data

Each row represents a product, and each column represents monthly sales (in units).

Product	Jan	Feb	Mar	Apr	May	Jun
Product A	120	135	150	160	170	180
Product B	80	90	95	100	110	115
Product C	200	210	220	230	240	250
Product D	60	70	75	80	85	90

Converted into NumPy array:

sales_data = np.array([
    [120, 135, 150, 160, 170, 180],
    [80,  90,  95,  100, 110, 115],
    [200, 210, 220, 230, 240, 250],
    [60,  70,  75,  80,  85,  90]
])
Dataset 2: Product Prices

Price per unit of each product (in currency units).

Product	Price
Product A	25
Product B	20
Product C	30
Product D	15
prices = np.array([25, 20, 30, 15])
Dataset 3: Monthly Expenses

Operational expenses per month.

Month	Expenses
Jan	5000
Feb	5200
Mar	5400
Apr	5600
May	5800
Jun	6000
expenses = np.array([5000, 5200, 5400, 5600, 5800, 6000])
🔍 Possible Analysis Performed

Total sales per product using sum(axis=1)

Monthly total sales using sum(axis=0)

Revenue calculation using broadcasting

Average monthly sales using mean()

Highest and lowest selling products using max() and min()

Profit calculation by subtracting expenses
