## 📘 **Assignment 04: Sales Report Using `SUMIFS()` Function**

### 🎯 **Objective:**

Apply your understanding of the **`SUMIFS()`** function to summarize sales data based on **multiple criteria** such as *region, product type,* and *month*.

---

### 🧾 **Scenario:**

You work as a **Sales Analyst** for a company that sells multiple product categories across different regions in India. Your task is to prepare a **Sales Summary** using the `SUMIFS()` function.

---

### 📊 **Sales Data**

| Date        | Region | Product Category | Sales Amount (₹) |
| ----------- | ------ | ---------------- | ---------------: |
| 02-Jan-2025 | North  | Electronics      |           75,000 |
| 05-Jan-2025 | South  | Furniture        |           42,000 |
| 08-Jan-2025 | East   | Electronics      |           64,000 |
| 10-Jan-2025 | West   | Kitchen          |           31,000 |
| 12-Jan-2025 | South  | Electronics      |           59,000 |
| 14-Jan-2025 | North  | Furniture        |           47,000 |
| 16-Jan-2025 | East   | Kitchen          |           28,000 |
| 20-Jan-2025 | West   | Electronics      |           78,000 |
| 23-Jan-2025 | South  | Furniture        |           39,000 |
| 25-Jan-2025 | North  | Kitchen          |           33,000 |
| 27-Jan-2025 | East   | Furniture        |           41,000 |
| 30-Jan-2025 | West   | Electronics      |           69,000 |

---

### 📋 **Tasks**

1. Create a **Sales Summary Table** as shown below:

| Region | Product Category | Total Sales (₹) |
| ------ | ---------------- | --------------: |
| North  | Electronics      |                 |
| North  | Furniture        |                 |
| North  | Kitchen          |                 |
| South  | Electronics      |                 |
| South  | Furniture        |                 |
| East   | Electronics      |                 |
| East   | Furniture        |                 |
| East   | Kitchen          |                 |
| West   | Electronics      |                 |
| West   | Kitchen          |                 |

---

### 🧮 **Formula Hint:**

Use the `SUMIFS()` function to calculate each total:

```
=SUMIFS(D2:D13, B2:B13, "North", C2:C13, "Electronics")
```

This formula calculates total **Electronics sales in the North region**.