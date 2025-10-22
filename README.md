[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/oqKLEXJJ)
# 🎓 Ethical Admissions Algorithm Simulation

This repository is a classroom exercise exploring **ethics and fairness in algorithmic decision-making** — specifically in college admissions.

You’ll implement and reflect on how feature selection and weighting can impact fairness, transparency, and equity in automated systems.

---

## 🧩 Overview

You are part of the admissions committee for **Anonymous University**, located near Anonymous City.  
Due to a large number of applications, the committee decides to use an algorithm to help **rank and shortlist applicants**.

Your task:
- Decide which factors to include (GPA, test scores, extracurriculars, essays, recommendation letters, legacy status, income, etc.)
- Assign weights to each factor.
- Compare outcomes under two models:
  - **Blind model**: Ignores sensitive factors.
  - **Aware model**: Includes them intentionally to promote fairness (e.g., extra weight for first-gen or low-income applicants).

---
## So for this assignment I tweaked both the blind and aware models. I only kept Locality and Disability weights for the aware model. This is what I deemed fair as I dont believe that other factors matter when dealing with applications. For the blind model I lowered extra and essay's down to .01, I lowered reccomendations to 0.02 and lastly I lowered test scored and GPA down to 0.3 each. The I changed both of these models to demonstrate how I would like to have been judged in my application. In my eyes, this model is fair. I dont think that having extra curriculars should give you an advantage. I worked during highschool so I never had time to do things like that.

## ⚙️ How to Run

You can run the code on any online Java compiler (e.g. [Replit](https://replit.com/~) or [Programiz Java Compiler](https://www.programiz.com/java-programming/online-compiler))  
or locally via terminal:

```bash
javac Applicant.java Admissions.java Main.java
java Main
 
