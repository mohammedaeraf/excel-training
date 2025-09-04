## 📘 **Sorting & Filtering in Excel**

### 🎯 **Objective:**

By the end of this tutorial, you will be able to:

* Sort data in ascending or descending order
* Perform multi-level sorting (e.g., by Section and then Marks)
* Filter data based on conditions
* Use Number Filters, Text Filters, and Clear Filters

---

## 🧾 **Step 1: Prepare Sample Data**

Use this table in Excel:

| Roll No | Name          | Class | Section | Subject | Marks | Grade |
| ------- | ------------- | ----- | ------- | ------- | ----- | ----- |
| 101     | Priya Mehta   | 10    | A       | Math    | 85    | B     |
| 102     | Rahul Shah    | 10    | B       | Science | 92    | A     |
| 103     | Aman Verma    | 10    | A       | Math    | 76    | C     |
| 104     | Sneha Reddy   | 10    | B       | Science | 88    | B     |
| 105     | Arjun Singh   | 10    | A       | English | 91    | A     |
| 106     | Meera Joshi   | 10    | A       | Science | 79    | C     |
| 107     | Karan Patel   | 10    | B       | Math    | 84    | B     |
| 108     | Fatima Sheikh | 10    | A       | English | 66    | D     |
| 109     | Deepak Rao    | 10    | B       | Math    | 95    | A     |
| 110     | Riya Kulkarni | 10    | A       | Science | 72    | C     |

---

## 🔢 **Step 2: How to Apply Sorting**

### ✅ **Sort by Single Column (e.g., Marks)**

1. Click any cell in the **Marks** column
2. Go to **Home > Sort & Filter**
3. Choose:

   * **Sort Smallest to Largest** (Ascending)
   * **Sort Largest to Smallest** (Descending)

🧠 *Use case: Rank students by their marks.*

---

### ✅ **Sort by Multiple Columns (e.g., Section and Marks)**

1. Select the entire table (A1\:G11)
2. Go to **Data tab > Sort**
3. Click **Add Level**
4. First Sort by: `Section` → A to Z
5. Then by: `Marks` → Largest to Smallest
6. Click **OK**

🧠 *Use case: Group students by Section, then sort by their performance.*

---

## 🔍 **Step 3: How to Apply Filtering**

### ✅ **Enable Filters**

1. Select your header row (Row 1)
2. Go to **Home > Sort & Filter > Filter**
3. Small drop-down arrows will appear on each column

---

### ✅ **Apply Basic Filters**

* Click the drop-down on **Subject**, and select only “Math”
* Click the drop-down on **Grade**, and select only “A”

---

### ✅ **Use Number Filter (e.g., Marks > 80)**

1. Click drop-down on **Marks**
2. Hover over **Number Filters > Greater Than…**
3. Enter `80` → OK

🧠 *Use case: View all students who scored above 80.*

---

### 🔄 **Clear Filters**

* Go to **Home > Sort & Filter > Clear**
* OR click the filter icon on column header and choose **Clear Filter from \[Column]**

---

## 🎓 **Practice Exercise for Students**

Using the sample table:

1. Sort students alphabetically by **Name**
2. Sort by **Section**, then by **Marks**
3. Filter students who got **“A” grade**
4. Filter only **Science** subject students with **Marks ≥ 80**
5. Clear all filters
