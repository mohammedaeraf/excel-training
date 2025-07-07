## ✅ 1. **Nested IF** Example

**Scenario:**
You want to assign grades based on student scores:

| Student | Marks |
| ------- | ----- |
| Asha    | 92    |
| Rahul   | 76    |
| Neha    | 61    |
| Amir    | 43    |

**Formula to assign grade (in C2):**

```excel
=IF(B2>=90, "A", IF(B2>=75, "B", IF(B2>=60, "C", IF(B2>=40, "D", "F"))))
```

**Explanation:**

* A for ≥90
* B for ≥75
* C for ≥60
* D for ≥40
* F for below 40

---

## ✅ 2. **IFS Function** (Simpler alternative to Nested IFs)

**Same scenario as above**, using the `IFS` function:

```excel
=IFS(B2>=90, "A", B2>=75, "B", B2>=60, "C", B2>=40, "D", B2<40, "F")
```

**Note:** `IFS` is available in Excel 2016 and later versions.

---

## ✅ 3. **SUMIFS** Example

**Scenario:**
You want to calculate total sales **for region 'South'** and **product 'Pen'**:

| Region | Product | Sales |
| ------ | ------- | ----- |
| South  | Pen     | 500   |
| South  | Pencil  | 300   |
| North  | Pen     | 200   |
| South  | Pen     | 400   |

**Formula:**

```excel
=SUMIFS(C2:C5, A2:A5, "South", B2:B5, "Pen")
```

**Explanation:**

* `C2:C5` → Sum Range (Sales)
* `A2:A5, "South"` → First condition (Region)
* `B2:B5, "Pen"` → Second condition (Product)

**Result:** 500 + 400 = **900**

---
### **SUMIFS** Example 2

#### The scenario is **sales tracking** across different **regions**, **salespersons**, and **products**.

---

### 📊 **Sample Data: Sales Records**

| Date      | Region | Salesperson | Product  | Sales |
| --------- | ------ | ----------- | -------- | ----- |
| 01-Apr-25 | North  | Amit        | Pen      | 1200  |
| 02-Apr-25 | South  | Priya       | Notebook | 1500  |
| 03-Apr-25 | East   | Rahul       | Pen      | 900   |
| 04-Apr-25 | West   | Neha        | Pencil   | 500   |
| 05-Apr-25 | South  | Priya       | Pen      | 1000  |
| 06-Apr-25 | North  | Amit        | Notebook | 1600  |
| 07-Apr-25 | East   | Rahul       | Pencil   | 700   |
| 08-Apr-25 | West   | Neha        | Notebook | 1400  |
| 09-Apr-25 | South  | Priya       | Pencil   | 600   |
| 10-Apr-25 | East   | Rahul       | Notebook | 1700  |
| 11-Apr-25 | North  | Amit        | Pencil   | 800   |
| 12-Apr-25 | West   | Neha        | Pen      | 1100  |
| 13-Apr-25 | South  | Priya       | Pen      | 900   |
| 14-Apr-25 | East   | Rahul       | Notebook | 1300  |
| 15-Apr-25 | West   | Neha        | Pen      | 950   |
| 16-Apr-25 | North  | Amit        | Notebook | 1450  |
| 17-Apr-25 | South  | Priya       | Pencil   | 550   |
| 18-Apr-25 | East   | Rahul       | Pen      | 980   |
| 19-Apr-25 | North  | Amit        | Pen      | 1250  |
| 20-Apr-25 | South  | Priya       | Notebook | 1350  |

---

### **Example `SUMIFS` Questions**

1. **Total sales of "Pen" in the "South" region:**

```excel
=SUMIFS(E2:E21, B2:B21, "South", D2:D21, "Pen")
```

2. **Total sales made by "Priya" for "Notebook":**

```excel
=SUMIFS(E2:E21, C2:C21, "Priya", D2:D21, "Notebook")
```

3. **Total sales in the "East" region:**

```excel
=SUMIFS(E2:E21, B2:B21, "East")
```

---

## ✅ 4. **`AVERAGEIF`** Function

---

### 📊 **Example Scenario: Student Scores**

| Student | Subject | Score |
| ------- | ------- | ----- |
| Rahul   | Math    | 85    |
| Priya   | Math    | 92    |
| Amit    | Science | 78    |
| Neha    | Math    | 88    |
| Riya    | Science | 82    |
| Varun   | Math    | 79    |
| Anjali  | Science | 91    |

---

### **Formula Example**

**Q: What is the average score of students in Math?**

```excel
=AVERAGEIF(B2:B8, "Math", C2:C8)
```

* **Range**: `B2:B8` – The range to evaluate the condition (subject).
* **Criteria**: `"Math"` – The condition.
* **Average Range**: `C2:C8` – The range of scores to average if condition is met.

---

### 🧮 **Answer**

This will calculate the average of scores for students who have "Math" as their subject:

* (85 + 92 + 88 + 79) ÷ 4 = **86**

Sure! Here's a simple example to demonstrate the **`COUNTIFS`** function in Excel, which is used to **count the number of rows that meet multiple conditions**.

---

### 📊 **Example Scenario: Student Attendance**

| Student | Class | Status  |
| ------- | ----- | ------- |
| Rahul   | 10    | Present |
| Priya   | 10    | Absent  |
| Amit    | 9     | Present |
| Neha    | 10    | Present |
| Riya    | 9     | Absent  |
| Varun   | 10    | Present |
| Anjali  | 9     | Present |

---

### **Formula Example**

**Q: How many students from Class 10 were Present?**

```excel
=COUNTIFS(B2:B8, 10, C2:C8, "Present")
```

* **Criteria Range 1**: `B2:B8` (Class)
* **Criteria 1**: `10`
* **Criteria Range 2**: `C2:C8` (Status)
* **Criteria 2**: `"Present"`

---

### 🧮 **Answer: 3**

The students from Class 10 who were present:

* Rahul
* Neha
* Varun

So the result is **`3`**.

---

