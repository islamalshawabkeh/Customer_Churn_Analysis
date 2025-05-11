# Customer_Churn_Analysis
# 📉 Customer Churn Analysis Dashboard (Power BI)

This repository contains an interactive Power BI dashboard designed to analyze and visualize customer churn behavior using detailed subscription, demographic, and usage data. The dashboard enables stakeholders to explore key drivers of churn, identify patterns, and support strategic retention initiatives.

---

## 🎯 Objective

To uncover insights behind customer churn by:
- Analyzing demographics, contract details, usage behavior, and billing patterns.
- Identifying churn categories and reasons.
- Highlighting characteristics of high-risk customers to inform retention strategies.

---

## 🗂️ Dataset Overview

The dataset provides comprehensive metadata grouped into key categories:

### 📌 Customer Status
- `Customer ID`: Unique customer identifier.
- `Churn Label`: Indicates if a customer has churned (Yes/No).
- `Churn Reason`: Specific reason for cancellation.
- `Churn Category`: Aggregated churn type for high-level analysis.

### 👥 Demographics
- `Age`, `Under 30`, `Senior`: Age indicators and flags.
- `Gender`: Male, Female, or Prefer not to say.
- `Group`: Indicates if the customer is on a group contract.
- `Number in Group`: Size of the customer’s contract group.

### 📞 Contract Information
- `Phone Number`: Customer’s contact number.
- `State`: U.S. state where the customer resides.
- `Payment Method`: Credit Card, Direct Debit, or Paper Check.
- `Contract Type`: Month-to-Month, One Year, or Two Year.

### 📶 Subscription & Usage
- `Account Length`: Duration with the company (in months).
- `Local Calls`, `Intl Calls`, `Intl Mins`: Usage details.
- `Intl Plan`: Indicates if an international calling plan is active.
- `Extra International Charges`: Charges incurred without a plan.
- `Customer Service Calls`: Number of support interactions.
- `Avg Monthly GB Download`: Internet usage per month.
- `Unlimited Data Plan`: Yes/No indicator for unlimited data.
- `Extra Data Charges`: For customers without unlimited plans.

### 💰 Billing Information
- `Monthly Charges`: Recurring monthly fee.
- `Total Charges`: Cumulative amount paid over time.

---

## 📊 Dashboard Features

- 🚦 **Churn Rate Breakdown** by demographics, contract type, and group status.
- 🌍 **Geographic Churn Map** by state.
- 💳 **Churn by Payment and Contract Type** to identify risky combinations.
- 📈 **Usage vs Charges Correlation** to analyze cost-impact behavior.
- 📞 **Customer Service Call Trends** linked to churn likelihood.
- 📦 **Impact of International and Data Plans** on retention.

---

## 🛠 Tools Used

- **Power BI Desktop**
- **DAX** (Data Analysis Expressions)
- **Power Query (M Language)**
- **Excel** (for data preprocessing)
- **Custom Visuals** (for enhanced storytelling)

---

## 🚀 Getting Started

1. Clone or download this repository.
2. Open the `.pbix` file using Power BI Desktop.
3. Interact with filters and slicers to explore different segments of churn behavior.
4. Use the dashboard to derive insights or customize it to fit your organization's needs.

---

## 🔄 Future Improvements

- Integrate **predictive churn modeling** using Python or R.
- Add **user role-level security (RLS)** for tailored access control.
- Enable **Power BI Service publishing** for online sharing and collaboration.
- Include **trend analysis** for churn over time.

---

## 📬 Contact

Feel free to reach out or connect:

- 📧 islamshawabkeh12@gmail.com  
- 🔗 [LinkedIn](https://www.linkedin.com/in/islamalshawabkeh)  
- 💻 [GitHub Portfolio](https://github.com/islamalshawabkeh/Data_Analysis.git)

---

> ⭐ *If you found this helpful, consider starring the repository and following for more projects!*
