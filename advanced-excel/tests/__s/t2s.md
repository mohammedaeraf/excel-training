## 📘 **Excel Test: What-If Analysis**

### ⏱ Duration: 45 Minutes

### 🧩 Tools Covered:

* **Goal Seek**
* **Scenario Manager**
* **Two-Variable Data Table**

---

## 🎯 **Objective:**

To test your understanding of **What-If Analysis** tools and how they can be used for **decision-making** in Excel using dynamic data.

---

## 📊 **Base Data – Product Pricing and Sales**

| Product         | Unit Price (₹) | Units Sold | Total Revenue (₹) |
| --------------- | -------------: | ---------: | ----------------: |
| Laptop          |         55,000 |         80 |            =B2*C2 |
| Printer         |         15,000 |         60 |            =B3*C3 |
| Monitor         |         20,000 |         45 |            =B4*C4 |
| Router          |          8,000 |        100 |            =B5*C5 |
| Projector       |         30,000 |         30 |            =B6*C6 |
| **Grand Total** |                |            |       =SUM(D2:D6) |

---

## ✅ **Tasks**

### 🔹 **Task 1 – Goal Seek (10 Marks)**

> You are targeting a **Total Revenue of ₹15,00,000**.
> Find out **how many Laptops (Units Sold)** are needed to achieve this goal.

📘 **Steps (Students to Perform):**

1. Use **Goal Seek** from the **Data → What-If Analysis** menu.
2. Set cell → Grand Total (D7)
3. To value → 1500000
4. By changing cell → Laptop Units Sold (C2)
5. Record your answer in a new cell labeled **“Required Laptop Units”**

---

### 🔹 **Task 2 – Scenario Manager (15 Marks)**

> Create 3 business scenarios to analyze revenue outcomes based on price and sales changes.

| Scenario        | Laptop Price | Laptop Units | Printer Price | Printer Units |
| --------------- | ------------ | ------------ | ------------- | ------------- |
| **Optimistic**  | ₹60,000      | 90           | ₹18,000       | 70            |
| **Realistic**   | ₹55,000      | 80           | ₹15,000       | 60            |
| **Pessimistic** | ₹50,000      | 65           | ₹12,000       | 50            |

📘 **Instructions:**

1. Go to **Data → What-If Analysis → Scenario Manager**
2. Changing cells: `B2, C2, B3, C3`
3. Add all 3 scenarios using the values above.
4. Create a **Scenario Summary** showing **Total Revenue (D7)** as the result cell.
5. Save the summary sheet as **“Scenario Summary”**.

---

### 🔹 **Task 3 – Two-Variable Data Table (20 Marks)**

> Analyze how **Profit** changes with different combinations of **Unit Price** and **Units Sold** for Monitors.

| Unit Price → | ₹18,000 | ₹20,000 | ₹22,000 |
| ------------ | ------- | ------- | ------- |
| Units Sold ↓ |         |         |         |
| 40           |         |         |         |
| 50           |         |         |         |
| 60           |         |         |         |

📘 **Instructions:**

1. Assume **Profit = (Unit Price × Units Sold) – 5,00,000** (Fixed Cost).
2. Enter the formula in the top-left corner of the table (above 40 and beside ₹18,000).
3. Use **Data Table** (Row input = Unit Price, Column input = Units Sold).
4. Display how profit changes for each combination.

---

## 📤 **Submission Guidelines:**

* Save your file as:
  `YourName_WhatIf_Test.xlsx`
* Include:

  * **Sheet1:** Goal Seek
  * **Sheet2:** Scenario Manager Summary
  * **Sheet3:** Two-Variable Data Table
* Ensure all calculations are properly formatted with ₹ currency and borders.
* Submit before the end of the class.

---

## 🧠 **Evaluation Criteria (Total 45 Marks)**

| Criteria                                         | Marks |
| ------------------------------------------------ | ----: |
| Goal Seek Accuracy                               |    10 |
| Scenario Manager Setup & Summary                 |    15 |
| 2-Variable Data Table (Correct Formula & Layout) |    15 |
| Formatting, Clarity & Presentation               |     5 |
