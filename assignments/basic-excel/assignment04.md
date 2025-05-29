## **Assignment 04**

### ✅ **Create an Invoice with Discount Calculation**

#### 📋 **Objective**:

Create a professional invoice in Excel that calculates discounts, discounted prices, and line totals based on item price and quantity.

---

### 🧾 **Sample Data: Invoice with Discounts**

| Sr. No | Item Name   | Unit Price | Discount (%) | Discount | Discounted Price | Quantity | Line Total |
| ------ | ----------- | ---------- | ------------ | -------- | ---------------- | -------- | ---------- |
| 1      | Wired Mouse | ₹ 300      | 50%          | ₹ 150    | ₹ 150            | 2        | ₹ 300      |
| 2      | Keyboard    | ₹ 450      | 15%          | ₹ 68     | ₹ 383            | 12       | ₹ 4,590    |
| 3      | Web Cam     | ₹ 1,100    | 20%          | ₹ 220    | ₹ 880            | 4        | ₹ 3,520    |

---

### 🧮 **Formulas to Use**:

1. **Discount** = `Unit Price × Discount (%)`
   Example: `=C2 * D2`

2. **Discounted Price** = `Unit Price – Discount`
   Example: `=C2 - E2`

3. **Line Total** = `Discounted Price × Quantity`
   Example: `=F2 * G2`

---

### 🎨 **Formatting Instructions**:

* Format all currency values with **₹ symbol** and **comma separator**.
* Align headers and make them **bold**.
* Use borders to clearly separate table cells.
* Add a **Grand Total** at the bottom :
  `=SUM(H2:H4)`

---

### 🎯 **Goal**:

* Understand pricing adjustments with percentage-based discounts.
* Apply arithmetic and cell referencing formulas.
* Practice formatting for readability and professionalism in business documents.

---
