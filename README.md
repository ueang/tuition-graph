# 📊 Tuition Graph – Visualizing School Tuition Costs

This program displays international student tuition costs at different universities using a bar chart.

Built during the "How to Code: Simple Data" course on edX (offered by UBC and Microsoft).

---

## 🎯 What It Does

- Represents each school using a `(make-school String Natural)` structure.
- Accepts a list of schools (`ListOfSchool`).
- Uses the 2htdp/image library to render a **bar chart**, where each bar height represents tuition.

---

## 💡 Concepts Practiced

- Compound data types
- Recursive list processing (`ListOfSchool`)
- Data-driven visual rendering
- Function decomposition and abstraction
- Basic functional programming

---

## 🖼 Screenshot

<img width="331" height="203" alt="image" src="https://github.com/user-attachments/assets/a36d432e-3ce6-46cf-8df0-9b3fbd218ee0" />

---

## 📁 Files

- `tuition-graph.rkt` – main Racket code
- `README.md` – this file

---

## 🔍 Notes

We separate the visual logic into smaller functions, keeping our chart code modular and clean.
This version uses a more **traditional list-based** structure, which encourages good decomposition.
