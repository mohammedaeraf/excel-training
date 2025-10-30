## 📘 **Assignment 08: VLOOKUP with Named Ranges**

### 🎯 Objective:

Use the `VLOOKUP` function with **Named Ranges** to retrieve Employee details based on their ID.

---

### 📊 Sample Data

#### Sheet Name: `EmployeeData`

| **EmpID** | **Name**     | **Department** | **Location** | **Salary** |
| --------- | ------------ | -------------- | ------------ | ---------- |
| E101      | Rahul Sharma | HR             | Delhi        | ₹45,000    |
| E102      | Priya Mehra  | Sales          | Mumbai       | ₹55,000    |
| E103      | Amit Verma   | IT             | Bengaluru    | ₹70,000    |
| E104      | Neha Joshi   | Marketing      | Pune         | ₹50,000    |
| E105      | Mohan Reddy  | Finance        | Hyderabad    | ₹60,000    |

---

### 📝 Instructions:

1. **Define a Named Range**:

   - Select the entire data range (A2\:E6) and create a Named Range called `EmpTable`.

2. **Create a new sheet** named `Lookup`.

3. In the `Lookup` sheet, create the following structure:

| **Enter EmpID** | `E102` (or any other valid ID) |
| --------------- | ------------------------------ |
| **Name**        |                                |
| **Department**  |                                |
| **Location**    |                                |
| **Salary**      |                                |

4. Use the `VLOOKUP` function to fill in Name, Department, Location, and Salary using the `EmpTable` named range.

---

### 🧠 Learning Outcomes:

- Understand how to define and use Named Ranges.
- Learn how to use `VLOOKUP` to fetch related data.
- Practice designing clean, interactive lookup sheets.

---

### ✅ Solution (Only refer if you are not able to solve on your own):

- Name: `=VLOOKUP(B1, EmpTable, 2, FALSE)`
- Department: `=VLOOKUP(B1, EmpTable, 3, FALSE)`
- Location: `=VLOOKUP(B1, EmpTable, 4, FALSE)`
- Salary: `=VLOOKUP(B1, EmpTable, 5, FALSE)`
