# 📘 21 Days SQL Challenge – Day 2  
### **Topic:** Filtering Data with the WHERE Clause  

---

## 🎯 **Objective**  
The goal for **Day 2** was to learn how to **filter data using SQL’s WHERE clause** and apply comparison, logical, and pattern-matching operators to extract meaningful insights from datasets.

---

## 🧠 **Key Learnings**
- Learned how to use the **WHERE** clause to filter rows based on specific conditions  
- Applied operators like:
  - **Comparison:** `=`, `>`, `<`, `>=`, `<=`, `<>`, `!=`  
  - **Logical:** `AND`, `OR`, `NOT`  
  - **Pattern:** `IN`, `BETWEEN`, `LIKE`  
- Discovered the importance of:
  - Using **IN** instead of multiple ORs for cleaner queries  
  - Checking for NULL values with `IS NULL` / `IS NOT NULL`  
  - Grouping conditions using **parentheses** for clarity  

---

## 🧩 **Daily Challenge**
**Question:**  
Find all patients admitted to the **‘Surgery’** service with a **satisfaction score below 70**, showing their `patient_id`, `name`, `age`, and `satisfaction_score`.

**Query Used:**
```sql
SELECT patient_id, name, age, satisfaction
FROM patients
WHERE service = 'surgery' AND satisfaction < 70;
```

Thank you [Indian Data Club](https://www.linkedin.com/company/indian-data-club/posts/?feedView=all) for starting this challenge and [DPDzero](https://www.linkedin.com/company/dpdzero/) the title sponsor of this challenge

Connect with me on [LinkedIn](https://www.linkedin.com/posts/palak-patel-0711242a0_sqlwithidc-indiandataclub-dataanalytics-activity-7391432529515278336-2xib?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEiiCVUBy_p8ew-GJCFrX_Fd2dbsVwh8szw)
