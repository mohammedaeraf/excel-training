## 📘 **Assignment: Using `SUMIFS` with Two Conditions**

### 🎯 Objective:

Learn to use the `SUMIFS` function to calculate conditional totals based on **more than one criteria**.

---

### 📊 **Scenario**:

You are analyzing monthly sales data for different **regions** and **product categories**.

#### 📄 Sheet Name: `SalesData`

| **Date**  | **Region** | **Product** | **Category** | **Sales** |
| --------- | ---------- | ----------- | ------------ | --------- |
| 01-Jan-25 | North      | Laptop      | Electronics  | 45,000    |
| 03-Jan-25 | South      | Printer     | Electronics  | 20,000    |
| 06-Jan-25 | North      | Chair       | Furniture    | 10,000    |
| 08-Jan-25 | East       | Desk        | Furniture    | 25,000    |
| 10-Jan-25 | South      | Laptop      | Electronics  | 40,000    |
| 13-Jan-25 | North      | Monitor     | Electronics  | 30,000    |
| 16-Jan-25 | West       | Sofa        | Furniture    | 15,000    |
| 20-Jan-25 | South      | Table       | Furniture    | 18,000    |
| 25-Jan-25 | East       | Printer     | Electronics  | 22,000    |
| 30-Jan-25 | North      | Laptop      | Electronics  | 50,000    |

---

### 📝 Instructions:

1. Create a section in the sheet called **"Summary"**.
2. Create drop-downs for `Region` and `Category` using **Data Validation**.
3. Use the `SUMIFS` formula to calculate **total sales** for the selected `Region` **and** `Category`.

---

### ✅ Solution (Refer only in case you can't solve it on your own):

If `G2` contains **Region** and `G3` contains **Category**:

```excel
=SUMIFS(E2:E11, B2:B11, G2, D2:D11, G3)
```

---

### 🔍 Bonus Tasks:

* Try changing dropdown values and observe the updated totals.
* Add a third condition like **Product** to make it more advanced.

---

### 🧠 Learning Outcomes:

* Understand conditional summing using `SUMIFS`.
* Learn to apply formulas based on dynamic dropdown filters.
* Practice using structured data for analysis.
