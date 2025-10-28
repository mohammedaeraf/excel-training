## 📘 **Assignment 07: Data Cleaning & Transformation**

### 🎯 **Objective:**

To practice importing data, splitting columns, removing duplicates, and using Flash Fill to transform text efficiently.

---

### **🧩 Part 1 – Text to Columns / Import Data**

You are provided with a CSV file named **`customer_data.csv`** (sample data shown below).

#### Sample Data:

| Customer Info                                                           | City      |
| ----------------------------------------------------------------------- | --------- |
| Rahul Mehta - [rahul@gmail.com](mailto:rahul@gmail.com) - 9876543210    | Mumbai    |
| Anita Desai - [anita@gmail.com](mailto:anita@gmail.com) - 9823456789    | Bengaluru |
| Suresh Kumar - [suresh@yahoo.com](mailto:suresh@yahoo.com) - 9876543210 | Delhi     |
| Priya Sharma - [priya@gmail.com](mailto:priya@gmail.com) - 9811122233   | Chennai   |
| Amit Jain - [amit@outlook.com](mailto:amit@outlook.com) - 9898989898    | Hyderabad |

**Task:**

1. Import this CSV into Excel.
2. Use **Text to Columns** (Delimiter = Hyphen "-") to separate:

   * Customer Name
   * Email
   * Phone Number
3. Rename the headers accordingly.

---

### **🧩 Part 2 – Remove Duplicates**

Once you split the data properly:

1. Check if there are any **duplicate records** based on **Email** or **Phone Number**.
2. Remove the duplicate entries using the **Remove Duplicates** feature.
3. Count the number of **unique customers** remaining.

---

### **🧩 Part 3 – Flash Fill**

Now add a new column named **“First Name”** and another named **“Last Name”**.

1. In the first row, type only the **first name** manually.
2. Use **Flash Fill (Ctrl + E)** to auto-fill the rest of the column.
3. Repeat the same for **Last Name**.
4. Verify that Flash Fill correctly splits all names.