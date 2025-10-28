## ☕ **Assignment 06b: What-If Analysis – Café Monthly Profit Planner**

### 🎯 **Objective:**

To help students learn how changes in pricing, customer volume, and costs affect profits using **Goal Seek**, **Data Tables**, and **Scenario Manager**.

---

### 📊 **Base Data: Café Operations (per month)**

| Category                     | Amount (₹)                            |
| ---------------------------- | ------------------------------------- |
| Average Price per Coffee Cup | ₹ 120                                 |
| Average Cost per Cup         | ₹ 60                                  |
| Monthly Fixed Costs          | ₹ 40,000                              |
| Expected Customers per Month | 1,000                                 |
| **Total Revenue**            | =Price × Customers                    |
| **Total Variable Cost**      | =Cost × Customers                     |
| **Profit**                   | =Revenue - Variable Cost - Fixed Cost |

---

### ✅ **Tasks**

---

#### 🔹 **Task 1: Goal Seek**

> Find the **number of customers** required to earn a **Profit of ₹50,000** per month.

📌 *Steps:*

* Set cell: `Profit`
* To value: `50000`
* By changing cell: `Customers per Month`

---

#### 🔹 **Task 2: One-Variable Data Table**

> Analyze how **Profit** changes as **number of customers** increases from 800 to 1600 (step: 100).

📌 *Instructions:*

* Put customer counts in a column.
* Use a one-variable data table to compute profit at each level.

---

#### 🔹 **Task 3: Two-Variable Data Table**

> Analyze how profit changes with different combinations of:

* **Customer Count**: 800 to 1600
* **Average Price per Cup**: ₹100 to ₹140

📌 *Instructions:*

* Set up customers in rows and prices in columns.
* Use formula `Profit` at top-left cell.

---

#### 🔹 **Task 4: Scenario Manager**

> Create 3 business scenarios:

1. **Standard Plan**

   * Price per Cup: ₹120
   * Cost per Cup: ₹60
   * Customers: 1000

2. **Premium Plan**

   * Price per Cup: ₹140
   * Cost per Cup: ₹65
   * Customers: 950

3. **Budget Plan**

   * Price per Cup: ₹100
   * Cost per Cup: ₹55
   * Customers: 1300

> Use **Scenario Manager** to compare the monthly **Profit** in each case.

