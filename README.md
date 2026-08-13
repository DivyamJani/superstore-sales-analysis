# 🏬 SuperStore Sales Analysis

A retail sales analysis project exploring sales, profit, and customer trends for a SuperStore chain using **raw transactional data** and an interactive **Power BI dashboard**.

---

## 📌 Project Overview

This project analyzes **5,901 order records** from a SuperStore's sales data (2019–2020) to uncover which categories, regions, and customer segments drive revenue and profit — and where the business is losing money. The insights are visualized through a Power BI dashboard built directly on the raw dataset.

---

## 📂 Dataset

**File:** `SuperStore_Sales_Dataset.csv`

| Detail | Value |
|---|---|
| Total Records | 5,901 |
| Total Features | 23 |
| Date Range | Jan 2019 – Dec 2020 |
| Unique Customers | 773 |
| States Covered | 49 |
| Cities Covered | 452 |

**Key columns:**
`Order ID`, `Order Date`, `Ship Date`, `Ship Mode`, `Customer ID`, `Customer Name`, `Segment`, `Country`, `City`, `State`, `Region`, `Product ID`, `Category`, `Sub-Category`, `Product Name`, `Sales`, `Quantity`, `Profit`, `Returns`, `Payment Mode`

---

## 🧰 Tools & Technologies

- **Microsoft Excel / CSV** — raw data source
- **Power BI** — data modeling, DAX measures, interactive dashboard (`Super_Store_Sales_Analysis.pbix`)
- **Git & GitHub** — version control

---

## 📊 Key Insights

- Total sales of **$1,565,804**, generating **$175,262** in profit — an overall profit margin of **~11.2%**.
- **Office Supplies** is the top-selling category (**$643.7K**), ahead of Technology (**$470.6K**) and Furniture (**$451.5K**).
- **Tables** is the single biggest loss-making sub-category (**-$11,091**), followed by **Supplies** and **Bookcases** — all running negative profit despite sales volume.
- **Copiers** is the most profitable sub-category (**$42,774**), followed by Accessories and Phones.
- The **West region** leads in sales (**$522K**), followed by East, Central, and South.
- The **Consumer segment** drives the most revenue (**$753K**), nearly 1.5x the Corporate segment.
- **Standard Class** is the dominant shipping mode (58% of orders), while Same Day shipping is rare (~6%).
- **COD (Cash on Delivery)** is the most-used payment mode, followed by Online and Card payments.
- Only **287 orders** recorded returns — a relatively small fraction of total orders, but worth tracking against loss-making sub-categories like Tables.

---

## 📈 Power BI Dashboard

**File:** `Super_Store_Sales_Analysis.pbix`

The dashboard provides an interactive view of:
- **Sales & Profit KPIs** at a glance
- Sales and profit breakdown by **Category / Sub-Category**
- **Regional and State-wise** performance map
- **Segment-wise** sales contribution (Consumer / Corporate / Home Office)
- **Shipping mode & payment mode** distribution
- Loss-making sub-categories highlighted for corrective action
- Time-based trend analysis (2019 vs 2020)

> 💡 To view the dashboard: open `Super_Store_Sales_Analysis.pbix` in **Power BI Desktop** (free download from Microsoft).

---

## 🗂️ Project Structure

```
superstore-sales-analysis/
│
├── SuperStore_Sales_Dataset.csv        # Raw sales dataset
├── Super_Store_Sales_Analysis.pbix     # Power BI dashboard
└── README.md                            # Project documentation
```

---

## ⚙️ How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   ```
2. Open `Super_Store_Sales_Analysis.pbix` in **Power BI Desktop**.
3. If prompted, update the data source path to point to `SuperStore_Sales_Dataset.csv` in your local clone.
4. Use dashboard slicers/filters to explore by Region, Category, Segment, or Year.

---

## 🔍 Future Improvements

- Investigate root cause of losses in **Tables**, **Supplies**, and **Bookcases** (discounting, freight cost, etc.)
- Add a customer lifetime value (CLV) analysis by segment
- Build a forecasting model for next-quarter sales
- Publish the dashboard to Power BI Service for online sharing

---

## 🙋 Author

**Divyam**
📍 Ahmedabad, Gujarat, India

If you found this project useful, feel free to ⭐ the repo!
