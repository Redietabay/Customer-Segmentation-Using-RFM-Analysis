# 🛍️ Customer Segmentation Using RFM Analysis

## 📌 Project Overview

This project applies **RFM (Recency, Frequency, Monetary)** analysis to segment customers based on their purchasing behavior. The goal is to help businesses better understand their customers and design **targeted marketing strategies** to improve engagement, retention, and revenue.

---

## 🎯 Objectives

* Perform data cleaning and preprocessing
* Calculate RFM metrics for each customer
* Segment customers into meaningful groups
* Generate actionable business insights

---

## 📊 Dataset Information

* **Dataset**: Online Retail Dataset
* **Records**: 500,000+ transactions
* **Features**:

  * `InvoiceNo`
  * `StockCode`
  * `Quantity`
  * `InvoiceDate`
  * `UnitPrice`
  * `CustomerID`
  * `Country`

---

## ⚙️ Tools & Technologies

* **Python**
* **Pandas** – Data processing and analysis
* **Matplotlib & Seaborn** – Data visualization

---

## 🔄 Workflow

### 1. Data Preprocessing

* Removed missing `CustomerID` values
* Filtered invalid transactions (negative quantity or price)
* Converted `InvoiceDate` to datetime format
* Ensured data consistency and quality

---

### 2. RFM Feature Engineering

* **Recency (R)** → Days since last purchase
* **Frequency (F)** → Number of purchases
* **Monetary (M)** → Total spending

---

### 3. Customer Segmentation

* Assigned scores using quantiles
* Combined RFM scores to create segments such as:

  * ⭐ **VIP Customers**
  * 👍 **Loyal Customers**
  * ⚠️ **At-Risk Customers**

---

## 📈 Key Insights

* High-value customers contribute significantly to revenue
* Loyal customers show consistent purchasing behavior
* At-risk customers need re-engagement strategies

---

## 💡 Business Value

This project helps businesses:

* Identify their most valuable customers
* Improve customer retention
* Design personalized marketing campaigns
* Increase overall profitability

---

## ▶️ How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/Redietabay/Customer-Segmentation-Using-RFM-Analysis.git
   ```

2. Install required libraries:

   ```bash
   pip install pandas matplotlib seaborn
   ```

3. Add dataset:

   * Place `RetailData.csv` in the project folder

4. Run the notebook:

   * Open `Task_3_RFM.ipynb`

---

## 📁 Project Structure

```
├── RetailData.csv
├── Task_3_RFM.ipynb
└── README.md
```

---

## 🚀 Project Status

✅ Completed – Ready for use and analysis

---

## 📬 Contact

For questions, feedback, or collaboration:

* 📧 Email: [your-email@gmail.com](abayrediet7@gmail.com)
* 🐙 GitHub: https://github.com/Redietabay

---
