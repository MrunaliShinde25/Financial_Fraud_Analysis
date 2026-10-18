# 🏦 Financial Fraud Analysis Dashboard

> **Excel-Based Data Analytics Project | 10,500 Transactions Across India (Sep 2025 – Aug 2026)**

An interactive **Microsoft Excel data analytics project** that analyzes digital payment transactions to find fraud patterns by bank, state, transaction type, fraud type, device, customer age group, gender, and time of day.

The project uses **Pivot Tables, Pivot Charts, Slicers, and Excel formulas** to turn raw transaction data into a dashboard with clear insights.

---

## 📌 Project Overview

Digital payments (UPI, cards, net banking, wallets) are growing fast in India, and so is payment fraud. This project answers practical questions such as:

- Which banks have the highest fraud amount?
- Which states lose the most money to fraud?
- How does fraud change month by month?
- Which transaction type has the highest fraud rate?
- Which fraud types happen most often?
- Which device type is used most for transactions?
- Which age groups and genders are affected most?
- Is fraud higher on weekdays or weekends?
- Is fraud higher during the day or at night?

---

## 📊 Dataset Overview

| Metric | Value |
| --- | --- |
| Total Transactions | **10,500** |
| Date Range | **01 Sep 2025 – 31 Aug 2026** |
| Total Transaction Amount | **₹13.21 Crore (₹132,111,677)** |
| Fraud Cases | **297** |
| Overall Fraud Rate | **2.83%** |
| Total Fraud Amount | **₹75.16 Lakh (₹7,516,079)** |
| Banks | **10** |
| States / Cities | **14 / 21** |
| Unique Customers | **8,874** |

### Columns in the dataset

| Column | Description |
| --- | --- |
| TransactionID, CustomerID | Unique IDs |
| Date, Time, Hour | When the transaction happened |
| Gender, AgeGroup | Customer details |
| State, City, Bank | Location and bank |
| TransactionType | UPI, Debit Card, Credit Card, Net Banking, Mobile Wallet, ATM Withdrawal |
| MerchantCategory | Type of merchant (11 categories) |
| Amount | Transaction amount (₹) |
| DeviceType | Mobile App, Web Browser, ATM, POS Terminal |
| Status | Completed, Failed, Blocked |
| IsFraud | 1 = fraud, 0 = not fraud |
| FraudType | Type of fraud (10 types) |
| RiskFlag | Low / Medium / High Risk |
| FraudAmount | Amount lost to fraud |
| DayType | Weekday / Weekend (formula) |
| TimeOfDay | Day / Night (formula) |

---

## 🛠️ Tools & Technologies

- Microsoft Excel
- Pivot Tables & Pivot Charts
- Slicers (interactive filters)
- Excel Formulas (`IF`, `WEEKDAY`, `OR`)
- Data Cleaning & Data Visualization

---

## ❓ Business Questions Answered

| # | Question | Sheet |
| --- | --- | --- |
| Q1 | Total transaction amount and fraud amount by bank | `pt1` |
| Q2 | States with the highest fraud amount | `pt2` |
| Q3 | How does fraud trend over the months? | `pt3` |
| Q4 | Which transaction type has the highest volume and fraud rate? | `pt4` |
| Q5 | How many fraud cases by fraud type? | `pt5` |
| Q6 | Which device type is used most for transactions? | `pt6` |
| Q7 | Fraud cases by age group and gender | `pt7` |
| Q8 | Weekday vs weekend fraud comparison | `pt8` |
| Q9 | Transactions by device type, day vs night | `pt9` |

---

## 🔍 Key Insights

- **Overall fraud rate is 2.83%** (297 fraud cases out of 10,500 transactions), with ₹75.16 lakh lost.
- **IndusInd Bank** has the highest fraud amount (about ₹12.2 lakh), followed by **Yes Bank** (about ₹9.5 lakh) and **Kotak Mahindra Bank** (about ₹9.0 lakh).
- **Madhya Pradesh** has the highest fraud amount among the states shown (about ₹11.0 lakh), followed by **Bihar** (about ₹9.4 lakh).
- **UPI** has the most fraud cases (149), but **Mobile Wallet** has the highest fraud rate (3.43%), just ahead of **UPI** (3.30%). **Debit Card** has the lowest (1.66%).
- **OTP Fraud (65)** and **QR Code Scam (63)** are the most common fraud types, followed by UPI Collect Scam (45).
- **December and May** have the most fraud cases (32 each); **February and August** have the fewest (17 each).
- **Weekdays** account for 222 fraud cases and **weekends** for 75.
- **Mobile App** (4,374) and **Web Browser** (4,303) are the most used devices.
---

## 🚀 How to Use

1. Download `fraud_analysis.xlsx` from this repository.
2. Open it in **Microsoft Excel** (2016 or later recommended).
3. Go to the **Dashboard** sheet and use the **slicers** to filter the data.
4. Open sheets `pt1` to `pt9` to see each pivot table and chart.

---

## 📈 Skills Demonstrated

- Data cleaning and preparation
- Pivot Tables and Pivot Charts
- Dashboard design with slicers
- Fraud pattern and trend analysis
- Turning data into business insights

---

## 👩‍💻 Author

**Mrunali Shinde**
BCA Graduate (2026), Savitribai Phule Pune University
🔗 [LinkedIn](https://www.linkedin.com/in/mrunali-shinde-aa249428a)

---

⭐ If you found this project useful, please star the repository!
