## Data and Formulas for Day 3

### 🧮 **COUNTIFS Example**

| Class | Status | No. of Students |
| :---: | :----: | :-------------: |
|   8   | Absent |                 |

| Student | Class | Status  |
| ------- | ----- | ------- |
| Rahul   | 10    | Present |
| Priya   | 10    | Absent  |
| Amit    | 9     | Present |
| Neha    | 10    | Present |
| Riya    | 9     | Absent  |
| Varun   | 10    | Present |
| Anjali  | 9     | Present |
| Sohail  | 8     | Present |
| Javed   | 8     | Present |
| John    | 8     | Absent  |

👉 **Example Formula:**

```
=COUNTIFS(B2:B11,10,C2:C11,"Present")
```

This counts students in **Class 10** who are **Present**.

---

### 💰 **SUMIF Example**

| Category    |         Total Price         |
| :---------- | :-------------------------: |
| Accessories | =SUMIF(B2:B11, B15, C2:C11) |

| Product Name | Category    | Price (INR) |
| ------------ | ----------- | ----------- |
| Laptop       | Electronics | ₹ 50,000    |
| Smartphone   | Electronics | ₹ 20,000    |
| Headphones   | Accessories | ₹ 2,500     |
| Desk Chair   | Furniture   | ₹ 7,000     |
| Coffee Mug   | Kitchen     | ₹ 500       |
| Smartwatch   | Electronics | ₹ 15,000    |
| Keyboard     | Accessories | ₹ 1,500     |
| Monitor      | Electronics | ₹ 25,000    |
| Mouse        | Accessories | ₹ 1,000     |
| Power Bank   | Electronics | ₹ 3,500     |

👉 **Example Formula:**

```
=SUMIF(B2:B11,"Electronics",C2:C11)
```

This sums up prices of all **Electronics** products.

---

### 🏙️ **SUMIFS Example**

| Product | Town  |             Total Sales              |
| :------ | :---- | :----------------------------------: |
| CCTV    | Udupi | =SUMIFS(C2:C6, B2:B6, E2, A2:A6, F2) |

| Town    | Product | Sales |
| ------- | ------- | ----- |
| Udupi   | CCTV    | 500   |
| Bhatkal | Laptops | 300   |
| Bhatkal | CCTV    | 200   |
| Udupi   | CCTV    | 400   |
| Udupi   | Laptops | 300   |

👉 **Example Formula:**

```
=SUMIFS(C2:C6,A2:A6,"Udupi",B2:B6,"CCTV")
```

This gives total **Sales of CCTV in Udupi**.

---

### 📘 **AVERAGEIF Example**

| Subject |            Average Score            |
| :------ | :---------------------------------: |
| Math    |  =AVERAGEIF(B2:B11,"Math",C2:C11)   |
| Science | =AVERAGEIF(B2:B11,"Science",C2:C11) |
| English | =AVERAGEIF(B2:B11,"English",C2:C11) |

| Student | Subject | Score |
| ------- | ------- | ----- |
| Rahul   | Math    | 85    |
| Priya   | Math    | 92    |
| Amit    | Science | 43    |
| Neha    | Math    | 88    |
| Riya    | Science | 32    |
| Varun   | Math    | 79    |
| Anjali  | Science | 48    |
| Ashok   | English | 60    |
| Javed   | English | 62    |
| Yunus   | English | 58    |

👉 **Example Formula:**

```
=AVERAGEIF(B2:B11,"Math",C2:C11)
```

This calculates the **average Math score**.

---

### 🎓 **AVERAGEIFS Example**

| Subject | Section |                Average Score                 |
| :------ | :------ | :------------------------------------------: |
| Math    | A       |  =AVERAGEIFS(D2:D9,B2:B9,"Math",C2:C9,"A")   |
| Math    | B       |  =AVERAGEIFS(D2:D9,B2:B9,"Math",C2:C9,"B")   |
| Science | A       | =AVERAGEIFS(D2:D9,B2:B9,"Science",C2:C9,"A") |
| Science | B       | =AVERAGEIFS(D2:D9,B2:B9,"Science",C2:C9,"B") |

| Student | Subject | Section | Score |
| ------- | ------- | ------- | ----- |
| Rahul   | Math    | A       | 85    |
| Priya   | Math    | B       | 92    |
| Amit    | Science | A       | 78    |
| Neha    | Math    | A       | 88    |
| Riya    | Science | B       | 82    |
| Varun   | Math    | A       | 79    |
| Anjali  | Science | A       | 91    |
| Javed   | Science | B       | 40    |

👉 **Example Formula:**

```
=AVERAGEIFS(D2:D9,B2:B9,"Math",C2:C9,"A")
```

This calculates the **average score of Math students in Section A**.
