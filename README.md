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


