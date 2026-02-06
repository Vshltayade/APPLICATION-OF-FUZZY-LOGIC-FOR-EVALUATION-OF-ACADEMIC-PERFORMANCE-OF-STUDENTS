# 🎓 Application of Fuzzy Logic for Academic Performance Evaluation

This project implements a **Mamdani Fuzzy Inference System (FIS)** to evaluate students’ academic performance using fuzzy logic.  
Unlike conventional evaluation systems, this approach handles uncertainty and provides a more flexible and fair assessment of student performance.

---

## 📖 Project Overview

Educational institutions traditionally evaluate students using rigid numerical methods. However, such systems often fail to consider ambiguity in performance factors like attendance consistency and assessment variability.

This project proposes a **fuzzy logic–based expert system** that evaluates student performance using:
- Attendance
- Internal Assessment Marks
- External Examination Marks  

The system applies **Mamdani fuzzy inference** to generate an overall performance score.

---

## 🎯 Objectives

- Apply fuzzy logic for academic performance evaluation
- Reduce complexity of classical evaluation systems
- Handle uncertainty and subjectivity in student assessment
- Provide flexible and interpretable performance results

---

## 🧠 Methodology

The system follows four major stages:

### 1️⃣ Crisp Input Data
Input values are collected from student records:
- Attendance (%)
- Internal Marks
- External Marks

### 2️⃣ Fuzzification
Each input is converted into linguistic variables such as:
- Poor
- Average
- Good
- Very Good
- Excellent  

Trapezoidal membership functions are used.

### 3️⃣ Fuzzy Rule Base (Mamdani)
Expert-defined **IF–THEN rules** combine the three inputs to infer student performance.

Example:
