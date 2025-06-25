## 📘 **Assignment: Comprehensive Sales & Budget Analysis**

Given below is a comprehensive **Excel assignment** that combines all the following advanced topics:

* ✅ **VLOOKUP**
* ✅ **Data Consolidation**
* ✅ **Data Validation**
* ✅ **What-If Analysis**
* ✅ **Pivot Tables & Charts**

---

### 🧑‍🎓 **Objective:**

To apply advanced Excel functions and features to solve real-world business problems involving sales tracking, budgeting, and data analysis.

---

## 📂 **Part 1: Product Master & Sales Sheet (VLOOKUP)**

### 🧾 **Task:**

1. Create a **Product Master Table** with the following data:

| Product Code | Product Name | Unit Price |
| ------------ | ------------ | ---------- |
| P001         | Notebook     | ₹40        |
| P002         | Pen          | ₹10        |
| P003         | Marker       | ₹15        |
| P004         | Mouse        | ₹500       |
| P005         | Keyboard     | ₹700       |

2. Create a **Sales Entry Table** like below:

| Date      | Product Code | Quantity | Unit Price | Line Total |
| --------- | ------------ | -------- | ---------- | ---------- |
| 01-Jan-24 | P001         | 10       |            |            |
| 02-Jan-24 | P004         | 2        |            |            |
| 03-Jan-24 | P002         | 20       |            |            |

3. Use **VLOOKUP** to fetch `Unit Price` from the Product Master and calculate `Line Total` as `Quantity × Unit Price`.

---

## 📂 **Part 2: Monthly Data Consolidation**

You are given **Sales Data for Jan, Feb, and Mar** on separate sheets.

### 🧾 **Task:**

1. Consolidate the `Total Sales` per Product for each month into a **Summary Sheet**.
2. Use **Data → Consolidate** to combine the data using `Sum` function.
3. List consolidated values in a structured table.

---

## 📂 **Part 3: Data Validation for New Products Entry**

### 🧾 **Task:**

Create a data entry sheet with validation rules:

| Product Code | Product Name | Price | Description |
| ------------ | ------------ | ----- | ----------- |

Validation Rules:

* `Product Code`: Must start with "P" followed by 3 digits (e.g., P010)
* `Price`: Must be between ₹10 and ₹10,000
* `Description`: Must be 50 to 200 characters in length

Use **Data → Data Validation → Custom Formulas**.

---

## 📂 **Part 4: Budget What-If Analysis**

You are given a monthly personal budget table:

| Category      | Amount (₹) |
| ------------- | ---------- |
| Rent          | 12,000     |
| Groceries     | 6,000      |
| Utilities     | 2,000      |
| Entertainment | 4,000      |
| Miscellaneous | 3,000      |
| **Total**     | (Formula)  |

### 🧾 **Tasks:**

1. Use **Goal Seek** to find how much Entertainment you can afford if total must stay below ₹25,000.
2. Use **Scenario Manager** to compare:

   * **Frugal Mode** (low entertainment & groceries)
   * **Balanced Mode**
   * **Luxury Mode** (increased entertainment & rent)

---

## 📂 **Part 5: Pivot Tables & Charts**

Use your consolidated monthly sales data for this.

### 🧾 **Tasks:**

1. Create a **Pivot Table** showing:

   * Product-wise monthly sales
   * Region-wise or category-wise totals (if applicable)
2. Insert a **Pivot Chart** (Column or Pie)
3. Add **Slicer** for filtering by Product or Month

---

## ✅ **Submission Requirements**

* Excel workbook (.xlsx)
* At least 5 sheets: Product Master, Sales, Consolidation, Budget, Pivot
* Use proper formatting and formulas
* Include Slicer and at least 1 Timeline (if using dates)
