## 📘 **Assignment 14: Conditional Formatting in Excel**

### 🎯 **Objective:**

To help students understand how to visually analyze and interpret data using **Conditional Formatting** tools such as Highlight Rules, Data Bars, Color Scales, Icon Sets, and Custom Formulas.

---

### 📊 **Data Table: Retail Sales Report**

| Date        | Region | Salesperson  | Product    | Category    | Units Sold | Unit Price (₹) | Total Sales (₹) |
| ----------- | ------ | ------------ | ---------- | ----------- | ---------- | -------------: | --------------: |
| 01-Jan-2024 | North  | Arjun Mehta  | Laptop     | Electronics | 5          |         50,000 |         250,000 |
| 03-Jan-2024 | South  | Priya Sharma | Printer    | Electronics | 3          |         15,000 |          45,000 |
| 04-Jan-2024 | East   | Sneha Iyer   | Desk Chair | Furniture   | 6          |          5,000 |          30,000 |
| 05-Jan-2024 | West   | Rahul Singh  | Sofa Set   | Furniture   | 2          |         25,000 |          50,000 |
| 06-Jan-2024 | North  | Karan Patel  | Router     | Electronics | 4          |          8,000 |          32,000 |
| 07-Jan-2024 | East   | Farah Khan   | Monitor    | Electronics | 3          |         20,000 |          60,000 |
| 08-Jan-2024 | South  | Amit Roy     | Laptop     | Electronics | 2          |         55,000 |         110,000 |
| 09-Jan-2024 | West   | Nisha Verma  | Sofa Set   | Furniture   | 1          |         28,000 |          28,000 |
| 10-Jan-2024 | North  | Deepak Rao   | Mouse      | Accessories | 10         |          1,200 |          12,000 |
| 11-Jan-2024 | East   | Meena George | Projector  | Electronics | 3          |         30,000 |          90,000 |

---

### ✅ **Tasks**

#### 🔹 **Task 1: Highlight Sales Performance**

Use **Highlight Cell Rules** to:

- Highlight **Total Sales > ₹70,000** in **green**.
- Highlight **Total Sales < ₹30,000** in **red**.

📍 _Hint:_ Use “Conditional Formatting → Highlight Cells Rules → Greater Than / Less Than”.

---

#### 🔹 **Task 2: Apply Data Bars**

Add **Data Bars** in the _Total Sales_ column to show sales magnitude visually.

📍 _Hint:_ Use “Conditional Formatting → Data Bars → Gradient Fill”.

---

#### 🔹 **Task 3: Use Color Scales**

Apply a **3-color scale** to the _Unit Price (₹)_ column:

- Green for highest values
- Yellow for middle range
- Red for lowest values

📍 _Purpose:_ To visualize pricing trends.

---

#### 🔹 **Task 4: Use Icon Sets**

Apply a **3-arrow icon set** on _Units Sold_:

- ↑ for >6 units
- → for 3–6 units
- ↓ for <3 units

📍 _Hint:_ Conditional Formatting → Icon Sets → 3 Arrows (Colored).

---

#### 🔹 **Task 5: Formula-Based Formatting**

Highlight rows where **Total Sales exceed ₹50,000** and **Category = Electronics**.

📍 _Formula Example:_

```excel
=AND($H2>50000, $E2="Electronics")
```

Apply **Light Green Fill** to those rows.

---

#### 🔹 **Task 6 (Bonus): Top and Bottom Performers**

- Highlight **Top 3 Total Sales** in **light blue**.
- Highlight **Bottom 3 Total Sales** in **light orange**.

📍 _Hint:_ Conditional Formatting → Top/Bottom Rules → Top 10 Items → Change number to 3.

---

### 🧾 **Deliverables**

- Submit your Excel workbook with each task on a **separate sheet**:

  - Sheet1 → Highlight Rules
  - Sheet2 → Data Bars
  - Sheet3 → Color Scales
  - Sheet4 → Icon Sets
  - Sheet5 → Formula-Based Formatting
  - Sheet6 → Top/Bottom Performers

---

### 🧠 **Learning Outcomes**

After completing this assignment, students will be able to:

- Apply **visual cues** to quickly identify key data points.
- Use **Conditional Formatting formulas** for dynamic formatting.
- Combine **multiple rules** to create interactive reports.
- Enhance **data readability and presentation** in dashboards.
