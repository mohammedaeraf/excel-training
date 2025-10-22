## 💼 Assignment 02: Sales Performance Evaluation using `IFS()` Function

### 🎯 Objective

Use the **`IFS()` function** to categorize sales representatives based on their total sales performance.

---

### 📘 Scenario

You are a data analyst in a retail company. The manager wants to classify each salesperson into a **performance category** based on their monthly sales figures.

---

### 📊 Sales Data

| Sr. No | Salesperson   | Monthly Sales (₹) | Performance Category |
| :----: | ------------- | :---------------: | :------------------: |
|   1    | Arjun Mehta   |      95,000       |                      |
|   2    | Bhavna Joshi  |      72,000       |                      |
|   3    | Dinesh Kapoor |      56,000       |                      |
|   4    | Farah Sheikh  |      38,000       |                      |
|   5    | Gopal Naik    |     1,10,000      |                      |
|   6    | Harini Reddy  |      67,000       |                      |
|   7    | Imran Khan    |      85,000       |                      |
|   8    | Jyoti Verma   |      42,000       |                      |
|   9    | Kunal Patil   |      31,000       |                      |
|   10   | Lata Sharma   |      97,000       |                      |

---

### 🧠 Task

Classify each salesperson according to the rules below using the **`IFS()` function**:

| Sales Amount       | Category             |
| ------------------ | -------------------- |
| ₹90,000 and above  | ⭐ Excellent         |
| ₹70,000 to ₹89,999 | 👍 Good              |
| ₹50,000 to ₹69,999 | 🙂 Average           |
| Below ₹50,000      | ⚠️ Needs Improvement |

---

### 🪄 Steps

1. In the **Performance Category** column (D2), enter this formula:

   ```
   =IFS(C2>=90000,"Excellent",C2>=70000,"Good",C2>=50000,"Average",C2<50000,"Needs Improvement")
   ```

2. Press **Enter** and copy the formula down the entire column.
3. Format the **Monthly Sales** column as **Currency (₹)**.
