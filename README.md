# 🎓 Student Grade Calculator

##  Internship Task 2 — AI & ML Track

A Python-based Student Grade Calculator that assigns grades to students based on their marks using predefined grading criteria.

This project was developed as part of the **AI & ML Internship Track at Veda Technology**.

---

## Project Overview

The Student Grade Calculator takes student marks as input and determines the corresponding grade using Python conditional statements.

The project demonstrates how `if`, `elif`, and `else` statements can be used to implement decision-making logic and process student data.

---

## Objectives

- Practice Python conditional statements.
- Implement `if`, `elif`, and `else` logic.
- Define and apply grading criteria.
- Validate student marks.
- Process multiple student records.
- Generate a clear student grade report.

---

##  Technologies Used

- **Python**
- **Jupyter Notebook**

---

##  Grading Criteria

| Marks | Grade |
|------:|:-----:|
| 90 – 100 | A |
| 80 – 89 | B |
| 70 – 79 | C |
| 60 – 69 | D |
| 0 – 59 | F |
| Below 0 or Above 100 | Invalid |

---

##  How It Works

The program uses a `calculate_grade()` function to determine the grade based on the student's marks.

The grading logic follows these conditions:

```python
if marks < 0 or marks > 100:
    return "Invalid"
elif marks >= 90:
    return "A"
elif marks >= 80:
    return "B"
elif marks >= 70:
    return "C"
elif marks >= 60:
    return "D"
else:
    return "F"
