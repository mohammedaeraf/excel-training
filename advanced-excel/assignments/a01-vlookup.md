## 🧮 Assignment 01: VLOOKUP using Cell Range 

### 🎯 Objective

Learn how to use **VLOOKUP** with a **cell range** to find and display data automatically from a reference table.

---

### 📊 Scenario

You are given two tables:

#### **1️⃣ Employee Master Table (Reference Table)**

| Emp ID | Employee Name | Department | Basic Salary |
| :----: | ------------- | ---------- | -----------: |
|  E101  | Arjun Mehta   | HR         |      ₹45,000 |
|  E102  | Bhavna Joshi  | Finance    |      ₹52,000 |
|  E103  | Dinesh Kapoor | IT         |      ₹60,000 |
|  E104  | Farah Sheikh  | Marketing  |      ₹48,000 |
|  E105  | Imran Khan    | IT         |      ₹55,000 |

This table is your **lookup range** (e.g., `A2:D6`).

---

#### **2️⃣ Salary Slip Table (Main Table)**

| Emp ID | Employee Name | Department | Basic Salary |
| :----: | ------------- | ---------- | -----------: |
|  E101  |               |            |              |
|  E104  |               |            |              |
|  E102  |               |            |              |
|  E105  |               |            |              |
|  E103  |               |            |              |

---

### 🧠 Task

Use **VLOOKUP** to fill in the missing details (Employee Name, Department, and Basic Salary) in the Salary Slip table.

---

### 🪄 Steps

1. Place your cursor in **cell B10** (under Employee Name for first Emp ID).

2. Type the formula:

   ```
   =VLOOKUP(A10, A2:D6, 2, FALSE)
   ```

   ➤ This looks for the **Emp ID** in `A10` within the range `A2:D6` and returns the **2nd column (Employee Name)**.

3. Similarly, fill in the next columns:

   * **Department:**

     ```
     =VLOOKUP(A10, A2:D6, 3, FALSE)
     ```
   * **Basic Salary:**

     ```
     =VLOOKUP(A10, A2:D6, 4, FALSE)
     ```

4. Copy the formulas down for all rows in the Salary Slip table.

