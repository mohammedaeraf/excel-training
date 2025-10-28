## 🧮 **Assignment 06: Apply Data Validation**

### 📊 **Product Data**

| **Product Code** | **Product Title** | **Price (₹)** | **Description**                                                                          |
| ---------------- | ----------------- | ------------- | ---------------------------------------------------------------------------------------- |
| PRD-100001       | Wireless Mouse    | 699           | A high precision wireless mouse with ergonomic design suitable for long usage.           |
| PRD-100002       | Gaming Keyboard   | 2499          | A gaming keyboard with a high performance build and responsive keys for smooth gameplay. |
| PRD-100003       | 27-inch Monitor   | 15999         | Full HD 27-inch LED monitor with HDMI and VGA ports for crystal-clear display.           |
| PRD-100004       | USB-C Hub         | 1299          | Compact USB-C hub with 4 USB ports and SD card reader for easy data transfer.            |
| PRD-100005       | Bluetooth Speaker | 1899          | Portable Bluetooth speaker with deep bass and 10-hour battery life.                      |

---

### ⚙️ **Validation Rules to Apply in Excel**

| **Field**            | **Validation Rule**                                  | **Example Formula / Tip**                                                             |
| -------------------- | ---------------------------------------------------- | ------------------------------------------------------------------------------------- |
| **1. Product Code**  | Must start with **"PRD-"** followed by **6 digits**. | Use Custom Formula: `=AND(LEFT(A2,4)="PRD-",ISNUMBER(VALUE(MID(A2,5,6))),LEN(A2)=10)` |
| **2. Price**         | Must be a **positive number greater than 0**.        | Use **Data Validation → Whole number → greater than 0**                               |
| **3. Product Title** | Length should be **between 10 and 200 characters**.  | Use formula: `=AND(LEN(B2)>=10, LEN(B2)<=200)`                                        |
| **4. Description**   | Length should be **between 100 and 500 characters**. | Use formula: `=AND(LEN(D2)>=100, LEN(D2)<=500)`                                       |

---

### 📝 **Instructions**

1. Open Excel and enter the above data.
2. Apply **Data Validation** rules as per the table.
3. Try entering invalid data (e.g., price = 0, short title) to test your validations.
4. Highlight invalid entries using **Conditional Formatting** (optional bonus task 🌟).