
# 🧸 Toy Sales Analysis (2023)

This project provides a Power BI dashboard for analyzing toy sales performance in 2023.  
It includes a breakdown of sales, inventory, product performance, and store-level insights, along with a forecast for the remaining days of the year.

---

## 📁 Project Structure

```
Toy-Sales/
├── Dashboard.pbix         → Main Power BI dashboard file
├── README.md              → Project documentation (this file)
└── data/                  → Dataset folder
    ├── Dates.xlsx
    ├── inventory.csv
    ├── products.csv
    ├── sales.csv
    └── stores.csv
```

---

## 🧾 Dataset Description

| File Name         | Description                                 |
|-------------------|---------------------------------------------|
| `Dates.xlsx`      | Calendar table used for time intelligence   |
| `inventory.csv`   | Inventory levels across stores              |
| `products.csv`    | Product list with categories and prices     |
| `sales.csv`       | Sales transactions data for 2023            |
| `stores.csv`      | Store locations and related metadata        |

---

## 📊 Dashboard Features

- Monthly sales trend across 2023  
- Sales by product, store, and category  
- Inventory overview by store  
- Forecasting for remaining days of the year  
- Year-to-date (YTD) metrics using DAX  

---

## 🚀 How to Use

1. Clone or download the repository.
2. Open `Dashboard.pbix` using **Power BI Desktop**.
3. Make sure the data source paths are correctly mapped to the `data/` folder.
4. Explore sales insights and future predictions interactively.

---

## 📌 Notes

- Forecasting logic is built with DAX measures using Power BI's time intelligence.
- The dataset is clean and ready for analysis.
- You can modify or expand the dashboard with your own visuals.

---

## 🙋‍♂️ Author

**Omar Ghareib**  
Data Analyst | Power BI | SQL | Python  
[GitHub: omargharib12](https://github.com/omargharib12)
