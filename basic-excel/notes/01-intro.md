## 📘 **Basic Excel Tutorial for Beginners**

---

### 📍 **Session Objectives**

By the end of this session, learners will understand:

* What is Excel?
* Working with rows, columns, and cells
* Performing basic arithmetic
* Using simple Excel functions like `SUM`, `IF`, `IFS`, `AVERAGE`, and `SUMIF`

---

### 🧭 **1. Introduction to Excel**

#### 💡 What is Excel?

Microsoft Excel is a **spreadsheet program** used to record data, perform calculations, analyze trends, and create reports or dashboards.

---

### 🧱 **2. Excel Layout Basics**

| Term             | Description                                       |
| ---------------- | ------------------------------------------------- |
| **Workbook**     | A complete Excel file (.xlsx)                     |
| **Worksheet**    | A single sheet inside the workbook                |
| **Cell**         | A box where a row and column intersect (e.g., A1) |
| **Row**          | Horizontal group (1, 2, 3...)                     |
| **Column**       | Vertical group (A, B, C...)                       |
| **Cell Address** | Unique identifier of a cell like A1, B3, etc.     |

#### ✅ Practice:

Type “Hello Excel” in cell A1. Now, click A1 — the **cell address** appears in the Name Box (left of the formula bar).

---

### ➕➖ **3. Basic Arithmetic in Excel**

Assume:

| A  | B | C |
| -- | - | - |
| 10 | 5 |   |

Now in `C1`:

| Operation | Formula    | Result |
| --------- | ---------- | ------ |
| Add       | `=A1 + B1` | 15     |
| Subtract  | `=A1 - B1` | 5      |
| Multiply  | `=A1 * B1` | 50     |
| Divide    | `=A1 / B1` | 2      |

---

### 🧮 **4. Common Excel Functions**

#### ✅ 4.1 `SUM()`: Add a Range

```excel
=SUM(A1:A5)
```

Adds all numbers from A1 to A5.

#### ✅ 4.2 `AVERAGE()`: Get Mean

```excel
=AVERAGE(A1:A5)
```

Returns average of numbers.

#### ✅ 4.3 `IF()`: Conditional Logic

```excel
=IF(A1>50, "Pass", "Fail")
```

If A1 is greater than 50, returns “Pass”, else “Fail”.

#### ✅ 4.4 `IFS()` (Excel 2016+)

```excel
=IFS(A1<35, "Fail", A1<60, "Pass", A1>=60, "Distinction")
```

Multiple conditions without nesting.

#### ✅ 4.5 `SUMIF()` – Add with a condition

Example Table:

| Product | Sales |
| ------- | ----- |
| Apple   | 200   |
| Orange  | 150   |
| Apple   | 300   |

```excel
=SUMIF(A2:A4, "Apple", B2:B4)
```

Returns 500 (Apple’s total sales).

---

### 🧪 **5. Practice Exercise**

| Name  | Math | Science | Total    | Result                               |
| ----- | ---- | ------- | -------- | ------------------------------------ |
| Rahul | 78   | 64      | `=B2+C2` | `=IF(D2>=75, "Distinction", "Pass")` |

---

### 📌 Bonus Tips:

* Use **AutoFill** to copy formulas
* Use **Formulas tab → Insert Function (fx)** to explore more
* Use `=MAX()`, `=MIN()`, `=COUNT()` for additional stats

---

### 🧠 Assignment for Students:

1. Create a Marks Table for 5 students with 3 subjects
2. Use formulas to calculate:

   * Total
   * Average
   * Result (with `IF` or `IFS`)
3. Highlight students with total > 250 using **Conditional Formatting**
