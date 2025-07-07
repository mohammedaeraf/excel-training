## ✅ 1. **`VLOOKUP`** Function

| Product ID | Product Name | Category    | Price (INR) | Stock Quantity |
| ---------- | ------------ | ----------- | ----------- | -------------- |
| 101        | Laptop       | Electronics | 50,000      | 25             |
| 102        | Smartphone   | Electronics | 20,000      | 50             |
| 103        | Headphones   | Accessories | 2,500       | 100            |
| 104        | Desk Chair   | Furniture   | 7,000       | 15             |
| 105        | Coffee Mug   | Kitchen     | 500         | 200            |

You can apply `VLOOKUP` to find details based on the **Product ID**. For example, if you want to find the price of a product with ID `103`, the formula would be:

```excel
=VLOOKUP(103, A2:E6, 4, FALSE)
```

This will return **2500**, which is the price of the headphones.

## ✅ 2. **`HLOOKUP`** Function

| Product ID   | 101         | 102         | 103         | 104        | 105        |
| ------------ | ----------- | ----------- | ----------- | ---------- | ---------- |
| Product Name | Laptop      | Smartphone  | Headphones  | Desk Chair | Coffee Mug |
| Category     | Electronics | Electronics | Accessories | Furniture  | Kitchen    |
| Price (INR)  | 50,000      | 20,000      | 2,500       | 7,000      | 500        |

### Example HLOOKUP formula:

If you want to find the **price of Product ID 103**, use:

```excel
=HLOOKUP(103, A1:F4, 4, FALSE)
```

### Explanation:

- **`103`** → Lookup value (Product ID).
- **`A1:F4`** → Table range.
- **`4`** → Row index (retrieving the price, which is in the fourth row).
- **`FALSE`** → Exact match required.

This will return **2,500**, which is the price of **Headphones**.

## ✅ 3. **`XLOOKUP`** Function

---

### 📊 **Example Scenario: Employee Salary Lookup**

| Employee ID | Name  | Department | Salary   |
| ----------- | ----- | ---------- | -------- |
| E101        | Rahul | Sales      | ₹ 45,000 |
| E102        | Priya | HR         | ₹ 50,000 |
| E103        | Amit  | IT         | ₹ 60,000 |
| E104        | Neha  | Finance    | ₹ 55,000 |
| E105        | Varun | Sales      | ₹ 47,000 |

---

### ✅ **Goal**

**Q: Find the salary of employee with ID `E103`**

---

### 💡 **Formula**

```excel
=XLOOKUP("E103", A2:A6, D2:D6)
```

- **Lookup Value**: `"E103"`
- **Lookup Array**: `A2:A6` (Employee ID column)
- **Return Array**: `D2:D6` (Salary column)

---

### 🧮 **Result: ₹ 60,000**

The formula finds E103 in column A and returns the corresponding salary from column D.

---

### 🔁 Optional Enhancements

- **If not found, show custom message:**

```excel
=XLOOKUP("E999", A2:A6, D2:D6, "Not Found")
```

- **Search from last to first (optional fifth parameter):**

```excel
=XLOOKUP("E103", A2:A6, D2:D6, "Not Found", -1)
```
