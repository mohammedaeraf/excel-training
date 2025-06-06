## 📘 **Assignment 04: Data Consolidation Using 3D Formulas**

### 🎯 Objective:

Learn how to consolidate data from multiple worksheets using **3D formulas** across similar structured sheets.

---

### 📊 Sample Scenario:

You are provided sales data for three different zones in a workbook:

* Sheet1: `North`
* Sheet2: `South`
* Sheet3: `West`

Each sheet contains monthly sales figures in the following structure:

| **Product** | **Jan** | **Feb** | **Mar** |
| ----------- | ------- | ------- | ------- |
| Laptop      | 150000  | 160000  | 170000  |
| Printer     | 30000   | 32000   | 35000   |
| Monitor     | 45000   | 47000   | 49000   |
| Keyboard    | 25000   | 26000   | 27000   |
| Mouse       | 20000   | 21000   | 22000   |

---

### 📝 Instructions:

1. **Create the same structure** in three sheets: `North`, `South`, and `West`, with different values.
2. Add a new sheet called `Consolidated`.
3. In the `Consolidated` sheet, use **3D formulas** to calculate **total sales** across all three regions for each product and each month.

---

### ✅ Solution (Please refer only in case you have tried and aren't able to do it on your own):

In `Consolidated` Sheet:

* For **Laptop - Jan**:

  ```
  =SUM(North:West!B2)
  ```
* For **Monitor - Mar**:

  ```
  =SUM(North:West!D4)
  ```

> 💡 Note: This formula will **sum cell D4 across all sheets from North to West** (including any sheet in between).

---

### 🧠 Learning Outcomes:

* Understand how 3D formulas work.
* Practice using structured and consistent layouts.
* Learn to consolidate data without copy-pasting.