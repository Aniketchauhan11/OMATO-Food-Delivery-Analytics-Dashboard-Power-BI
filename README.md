# OMATO-Food-Delivery-Analytics-Dashboard-Power-BI
Interactive Power BI dashboard analyzing 2,746 food delivery transactions from January to April 2023 using customer, food, restaurant, delivery, and payment data.

## 📊 Overview

An interactive Power BI dashboard developed to analyze OMATO food delivery transactions from January to April 2023.

The project combines monthly sales data with customer, food, and restaurant details to analyze transaction volume, quantity, delivery status, payment methods, customer membership, food categories, and restaurant types.

## 📁 Dataset

The Sales Data contains four monthly files:

* January 2023 – 626 transactions
* February 2023 – 792 transactions
* March 2023 – 765 transactions
* April 2023 – 563 transactions

**Total Transactions: 2,746**

### Sales Data Fields

* Order ID
* Order Date
* Customer ID
* Restaurant ID
* Food Item
* Quantity
* Delivery Status
* Payment Method

## 📌 Key Dashboard Metrics

* Total Transactions
* Total Quantity
* Average Quantity
* Monthly Transaction Trends
* Food-wise Quantity
* Customer Membership
* Food Type
* Delivery Status
* Payment Method
* Restaurant Type

## 🖼️ Dashboard Preview

### Dashboard Overview

<img width="1213" height="752" alt="1" src="https://github.com/user-attachments/assets/ffd2b91c-227c-417e-8050-80ac19a7a3aa" />


### Dashboard Analysis

<img width="1346" height="750" alt="2" src="https://github.com/user-attachments/assets/9a21e7aa-a407-4bc4-a493-c17a51d729da" />

## 🗂️ Data Model

The project uses multiple related tables:

* **Sales Data**
* **Customer Details**
* **Food Details**
* **Restaurant Details**

Sales Data acts as the main transaction table and is analyzed together with customer, food, and restaurant information for multidimensional analysis.

## 📈 Dashboard Features

* KPI cards for key performance metrics
* Monthly transaction trend analysis
* Food-wise quantity analysis
* Customer membership analysis
* Food type analysis
* Delivery status analysis
* Payment method analysis
* Restaurant type analysis
* Interactive slicers and filters
* Dedicated analytical dashboard

## 🔎 Key Findings

Across the January–April 2023 sales data:

* **2,746 total transactions** were recorded.
* **15,103 total quantities** were ordered.
* Average quantity per transaction was **5.5**.
* **2,588 transactions were delivered**.
* **158 transactions were cancelled**.
* **UPI** was used for 1,719 transactions.
* **COD** was used for 750 transactions.
* **Card** was used for 277 transactions.

## 🛠️ Tools & Technologies

* Power BI
* DAX
* Data Modeling
* Data Visualization
* Microsoft Excel

## 💡 Skills Demonstrated

* Power BI Dashboard Development
* DAX Measures
* Data Modeling
* KPI Development
* Data Visualization
* Interactive Reporting
* Trend Analysis
* Customer Segmentation
* Business Data Analysis

## 🎯 Project Outcome

Built an interactive Power BI dashboard that consolidates food delivery transaction data and enables users to explore customer, food, restaurant, delivery, payment, and monthly transaction patterns through interactive visualizations and filters.

## 📂 Project Structure

```text
OMATO-Food-Delivery-Analytics-Dashboard-Power-BI/
│
├── README.md
│
├── OMATO-Food-Delivery-Dashboard.pbix
│
├── Dataset/
│   ├── January_Sales_2023.xlsx
│   ├── February_Sales_2023.xlsx
│   ├── March_Sales_2023.xlsx
│   └── April_Sales_2023.xlsx
│
└── Screenshots/
    ├── dashboard-overview.png
    └── dashboard-analysis.png
```
