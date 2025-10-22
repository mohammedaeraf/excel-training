## 🛍️ Assignment 03: COUNTIF – Customer Feedback Analysis

### 🎯 Objective

Use the **`COUNTIF()`** function to analyze customer feedback ratings and summarize the number of responses in each category.

---

### 📘 Scenario

You work as a **Customer Experience Analyst** at a retail store. After a recent product launch, customers were asked to rate their satisfaction level from **1 to 5**, where:

| Rating | Meaning   |
| :----: | --------- |
|    5   | Excellent |
|    4   | Good      |
|    3   | Average   |
|    2   | Poor      |
|    1   | Very Poor |

You’ve collected 30 feedback entries and need to count how many customers gave each rating.

---

### 📊 Feedback Data

| Sr. No | Customer Name  | Rating |
| :----: | -------------- | :----: |
|    1   | Aarti Sharma   |    5   |
|    2   | Bilal Khan     |    4   |
|    3   | Chitra Rao     |    5   |
|    4   | Deepak Patel   |    3   |
|    5   | Esha Nair      |    4   |
|    6   | Faisal Shaikh  |    2   |
|    7   | Gauri Desai    |    5   |
|    8   | Harish Gupta   |    1   |
|    9   | Iqra Hussain   |    3   |
|   10   | Jay Mehta      |    4   |
|   11   | Kavita Shetty  |    5   |
|   12   | Lalit Kumar    |    2   |
|   13   | Meena Reddy    |    3   |
|   14   | Nisha Jain     |    4   |
|   15   | Omkar Joshi    |    5   |
|   16   | Priya Singh    |    3   |
|   17   | Qasim Ali      |    4   |
|   18   | Ritu Agarwal   |    1   |
|   19   | Sohan Lal      |    2   |
|   20   | Tanya D’Souza  |    5   |
|   21   | Umesh Bhat     |    3   |
|   22   | Varun Goyal    |    5   |
|   23   | Waseem Khan    |    2   |
|   24   | Xenia Pereira  |    4   |
|   25   | Yogesh Patil   |    3   |
|   26   | Zara Fernandes |    5   |
|   27   | Arjun Menon    |    4   |
|   28   | Bhavna Kaur    |    3   |
|   29   | Chirag Naik    |    2   |
|   30   | Divya Rao      |    5   |

---

### 📈 Task

1. Create a **summary table** as below:

| Rating | Meaning   | Count |
| :----: | --------- | :---: |
|    5   | Excellent |       |
|    4   | Good      |       |
|    3   | Average   |       |
|    2   | Poor      |       |
|    1   | Very Poor |       |

2. In the **Count** column, use the **`COUNTIF()`** function to count how many customers gave each rating.

   Example:

   ```
   =COUNTIF($C$2:$C$31, 5)
   ```

3. Copy the formula for all rating levels (1 to 5).
