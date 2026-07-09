#  E-Commerce Sales Analysis

An end-to-end exploratory data analysis project that analyzes customer purchasing behavior, sales performance, payment trends, and delivery performance using Python, Pandas, Matplotlib, Git, and GitHub.

---

##  Project Overview

This project analyzes an e-commerce dataset containing customer, order, payment, and product information.

The objective is to answer business questions such as:

- Which months generated the highest revenue?
- Which product categories contribute the most revenue?
- Which payment methods are most commonly used?
- Which customer states generate the highest revenue?
- How long does product delivery typically take?

The analysis focuses on data understanding, data preparation, exploratory data analysis (EDA), feature engineering, and business insights using Python.

---

##  Technologies Used

| Category | Technology |
|----------|------------|
| Programming Language | Python |
| Data Analysis | Pandas |
| Data Visualization | Matplotlib |
| Version Control | Git |
| Repository Hosting | GitHub |
| Development Environment | Jupyter Notebook, VS Code |

---

##  Repository Structure

```text
Ecommerce-Data-Analysis/
│
├── data/
│   ├── customers.csv
│   ├── orders.csv
│   ├── order_items.csv
│   ├── order_payments.csv
│   └── products.csv
│
├── notebooks/
│   └── ecommerce_analysis.ipynb
│
├── images/
│
└── README.md
```

---

##  Dataset Description

The project uses five datasets representing different parts of an e-commerce business.

| Dataset | Description |
|----------|-------------|
| customers.csv | Customer information including customer ID, city, state, and zip code |
| orders.csv | Order details including purchase timestamp and delivery status |
| order_items.csv | Product information for each order including price and freight cost |
| order_payments.csv | Payment type, payment installments, and payment value |
| products.csv | Product ID and product category information |

---

##  Project Workflow

The project was completed using the following workflow:

1. Loaded all datasets using Pandas.
2. Performed data understanding using `.head()`, `.shape`, `.info()`, `.describe()`, and `.isnull().sum()`.
3. Merged related datasets using common keys (`customer_id`, `order_id`, and `product_id`).
4. Created new features such as purchase month and delivery time.
5. Performed exploratory data analysis (EDA).
6. Generated business insights using Python.
7. Version-controlled the project using Git.
8. Published the project on GitHub.

---

##  Exploratory Data Analysis

The analysis includes:

- Monthly Revenue Analysis
- Revenue by Customer State
- Average Order Value (AOV)
- Top Revenue-Generating Product Categories
- Most Frequently Purchased Product Categories
- Payment Method Distribution
- Delivery Time Analysis

---

##  Key Business Insights

The analysis revealed the following insights:

- São Paulo (SP) generated the highest revenue among all customer states.
- Credit Card was the most frequently used payment method.
- Average Order Value (AOV) was approximately **158.54 BRL**.
- **Beauty & Health (`beleza_saude`)** generated the highest revenue.
- **Bed, Bath & Table (`cama_mesa_banho`)** was the most frequently purchased product category.
- The average delivery time was approximately **12 days**.
- Revenue varied across different months, indicating seasonal purchasing patterns.

---

##  How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/raghu123R/Ecommerce-Data-Analysis.git
```

### 2. Navigate to the project folder

```bash
cd Ecommerce-Data-Analysis
```

### 3. Open Jupyter Notebook

```bash
jupyter notebook
```

### 4. Open the notebook

```text
notebooks/ecommerce_analysis.ipynb
```

### 5. Run all cells

Run all notebook cells to reproduce the complete analysis.

---

##  Future Improvements

The project will be expanded by adding:

- SQL analysis using PostgreSQL
- Advanced SQL queries (CTEs, Window Functions, RANK(), LAG())
- Interactive Power BI dashboard
- Dashboard screenshots
- Customer segmentation (RFM Analysis)
- Sales forecasting using Machine Learning

---

##  Author

**Raghu Ravichandran**

- GitHub: https://github.com/raghu123R

Thank you for visiting this repository.