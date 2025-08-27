
## **Assignment 02**
---

### ✅ **Calculate BMI and Category for 5 Individuals**

#### 📋 **Objective**:

Use Excel formulas to calculate **BMI (Body Mass Index)** and determine the **weight category** based on height and weight.

---

### 🧍 Sample Data Provided:

| Name  | Height (cm) | Weight (kg) | **Height (m)** | **BMI** | **Category** |
| ----- | ----------- | ----------- | -------------- | ------- | ------------ |
| Rahul | 171         | 73          |                |         |              |
| Priya | 155         | 73          |                |         |              |
| Anand | 180         | 80          |                |         |              |
| Riya  | 160         | 45          |                |         |              |
| Manoj | 175         | 95          |                |         |              |

---

### 🧮 **Formulas to Use**:

1. **Height (m)**
   `=Height(cm)/100`
   Example: `=B2/100`

2. **BMI Formula**
   `=Weight (kg) / (Height (m) ^ 2)`
   Example: `=C2/(D2^2)`

3. **BMI Category**
   Use the following ranges to assign a category:

   | BMI Range      | Category      |
   | -------------- | ------------- |
   | Less than 18.5 | Underweight   |
   | 18.5 to 24.9   | Normal weight |
   | 25 to 29.9     | Overweight    |
   | 30 and above   | Obese         |

   **Formula using IFs:**

   ```excel
   =IF(E2<18.5,"Underweight",IF(E2<25,"Normal weight",IF(E2<30,"Overweight","Obese")))
   ```

---

### 🎯 **Goal**:

- Fill all columns using formulas.
- Format BMI to **1 or 2 decimal places**.

---
