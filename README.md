# OIBSIP Retail Sales EDA (Oasis Infobyte Internship – Task 1)
#  Exploratory Data Analysis (EDA) on Retail Sales Data

This project is part of my Oasis Infobyte Data Science Internship (Task 1) 
The goal of this task is to perform **Exploratory Data Analysis (EDA)** on a retail sales dataset to uncover meaningful insights, trends, and recommendations for business improvement.

##  Project Overview

In this project, I worked on a retail dataset and performed:

-  Data Cleaning & Preprocessing  
-  Descriptive Statistics (Mean, Median, Mode, Standard Deviation)  
-  Time Series Analysis (Daily & Monthly Sales Trends)  
-  Customer Analysis (Top Customers)  
-  Product Analysis (Top Products & Heatmap)  
-  Data Visualization (Bar charts, Line plots, Heatmaps)  
-  Actionable Recommendations for business decisions  

## Dataset

  - The dataset contains retail transaction details such as:
  - **Date**: Invoice/Transaction Date  
  - **CustomerID**: Unique customer identifier  
  - **Product**: Product purchased  
  - **Quantity**: Number of items purchased  
  - **Price**: Price per unit  
  - **Sales**: Total sales (Quantity × Price)  

*(Dataset provided as part of internship tasks)

## 🛠Technologies Used

- **Python**   
- **Pandas** → Data handling & cleaning  
- **Matplotlib / Seaborn** → Visualizations  
- **ReportLab** → PDF report generation  

## Key Insights

- Sales showed seasonal peaks in certain months.  
- Top customers contributed significantly to revenue (loyalty programs can be targeted).  
- Some products had consistently high demand, while others underperformed.  
- Business can optimize inventory & pricing using these insights.  

## Recommendations

1. Focus on promoting **top-selling products** during high-demand months.  
2. Provide **loyalty rewards** for top customers to improve retention.  
3. Identify **low-sales months** and run targeted marketing campaigns.  
4. Bundle or discount **underperforming products** to optimize inventory.  
5. Use **demand forecasting** to balance stock levels.  

## Report

- A detailed **EDA Report (PDF)** is generated with:
  - Descriptive Statistics  
  - Time Series Plots  
  - Top Customers & Products  
  - Heatmap Analysis  
  - Business Recommendations  

---

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Retail-Sales-EDA.git
   cd Retail-Sales-EDA
2. Install required libraries:
    pip install pandas matplotlib seaborn reportlab
3. Run the EDA script:
     python retail_sales_eda.py

## Acknowledgment

This project was completed as part of my Oasis Infobyte Data Science Internship (Task 1).


## Customer Segmentation Analysis[Task-2]

This project is part of my Oasis Infobyte Data Science Internship (Task 2).
The goal of this task is to perform Customer Segmentation Analysis on an E-commerce dataset to uncover meaningful customer groups, behaviors, and insights that can help businesses make data-driven marketing and sales decisions.
Thanks to Oasis Infobyte for the opportunity to learn and work on real-world datasets.

## Project Overview

In this project, I worked with an E-commerce customer transaction dataset and performed:

-Data Cleaning & Preprocessing (handling missing values, duplicates, negative values)
-Descriptive Statistics (Recency, Frequency, Monetary – RFM metrics)
-Feature Engineering (building customer behavior features)
-Customer Segmentation using K-Means Clustering
-Data Visualization (Scatter plots, Bar charts, Cluster visualizations)
-Insights & Recommendations for business strategies

## Dataset

The dataset contains retail transaction details such as:

-InvoiceNo: Unique transaction identifier
-StockCode: Product code
-Description: Product description
-Quantity: Number of items purchased
-InvoiceDate: Transaction date & time
-UnitPrice: Price per unit
-CustomerID: Unique customer identifier
-Country: Customer’s country
-(Dataset: E-commerce Data – Kaggle)

## Technologies Used

Python

-Pandas, NumPy → Data handling & cleaning
-Matplotlib, Seaborn → Visualizations
-Scikit-learn → Machine Learning (Clustering, Scaling)

## Key Insights

 Customers can be segmented into 4 groups:

   -VIP Loyal Customers (frequent & high spenders)
   -Regular Shoppers (steady but moderate purchases)
   -Lost Customers (inactive, long recency)
   -Bargain Shoppers (low frequency, small purchases)
   -Top customers contribute the majority of revenue → loyalty programs can boost retention.
   -Some customers are inactive for long periods → reactivation campaigns can be run.
    -High-value customers purchase more regularly → premium offers should target them.

## Recommendations

Provide loyalty rewards for VIP customers.
Run win-back campaigns (emails, discounts) for inactive customers.
Offer personalized discounts to regular shoppers to increase purchase frequency.
Bundle low-value items for bargain shoppers to increase total spend.

## Report

The detailed analysis includes:
-RFM Model (Recency, Frequency, Monetary metrics)
-Cluster Visualization
-Customer Segment Profiles
-Actionable Business Recommendations
 ## How to Run Clone this repository:

1. git clone https://github.com/your-username/Customer-Segmentation.git
cd Customer-Segmentation

2. Install required libraries:
pip install pandas numpy matplotlib seaborn scikit-learn

3. Run the segmentation script:
 python customer_segmentation.py

 ## Acknowledgment

This project was completed as part of my Oasis Infobyte Data Science Internship (Task 2).
Thanks to Oasis Infobyte for the opportunity to work on real-world datasets and apply data science techniques.

