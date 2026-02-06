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
IF Attendance is Good AND Internal Marks are Very Good AND External Marks are Good
THEN Performance is Very Good


### 4️⃣ Defuzzification
The fuzzy output is converted into a crisp value representing final student performance.

---

## 🛠️ Tools & Technologies Used

- **MATLAB (R2013a or later)**
- Mamdani Fuzzy Inference System
- Trapezoidal Membership Functions
- MS Excel (for statistical validation)

---

## 📊 Results & Analysis

- Tested on real student data (54 students)
- Compared fuzzy system results with conventional evaluation
- Performed **two-sample t-test**
- Results show **no significant difference** between conventional and fuzzy evaluation
- Fuzzy system effectively incorporates attendance flexibility

---

## ✅ Advantages of the System

- Handles ambiguity and imprecision
- More flexible than traditional grading
- Fair assessment considering multiple attributes
- Easily extendable with more parameters

---

## 📌 Conclusion

The fuzzy logic–based evaluation system produces results comparable to traditional methods while offering greater flexibility and robustness.  
It is especially effective in cases where students have similar marks but different attendance patterns.

This approach can be used as a **decision-support system** alongside existing evaluation methods.

---

## 📚 References

- Bakal et al., *Use of Fuzzy Logic in Evaluating Students’ Learning Achievement*
- Rajiv Bhatt et al., *Fuzzy Logic based Student Performance Evaluation Model*
- Ibrahim Saleh et al., *A Fuzzy System for Evaluating Students’ Learning Achievement*
- L.A. Zadeh, *Fuzzy Sets*

---

## 👨‍🎓 Authors

- Akshay Shekade  
- Amit Wakade  
- Vishal Tayade  
- Shubham Makar  

Department of Computer Engineering  
Sinhgad College of Engineering, Pune  
Savitribai Phule Pune University  

---

## 📜 License

This project is developed for **academic and educational purposes only**.

