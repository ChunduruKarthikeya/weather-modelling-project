
# 🌦 Weather Modeling using Quadratic Solutions (C Program)

This project implements a simple **weather modeling** system using a **quadratic equation** of the form:

[
T(t) = a t^2 + b t + c
]

The times `t` when temperature crosses a threshold are found using the **quadratic formula**:

[
t = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
]

---

## 📌 Features (Four Stages)

This single C program includes all assignment-required stages using a **menu-based system**:

| Stage                              | Description                                           |
| ---------------------------------- | ----------------------------------------------------- |
| 1️⃣ Hard-coded variables           | Coefficients `a`, `b`, and `c` are predefined in code |
| 2️⃣ Keyboard input                 | User enters a single set of values                    |
| 3️⃣ Read from file (single set)    | Reads one model from a file                           |
| 4️⃣ Read from file (multiple sets) | Reads and solves multiple models from a file          |

---

## 📂 File Requirements

### Example for Single Input File

Filename: `weather_input_single.txt`

```
1.0 -3.0 2.0
```

### Example for Multiple Inputs File

Filename: `weather_input_multi.txt`

```
1.0 -3.0 2.0
2.0 5.0 -3.0
1.0 2.0 5.0
```

---

## 🛠️ How to Compile

Make sure you have a C compiler like GCC installed.

```
gcc weather_quadratic_all.c -o weather -lm
```

---

## ▶️ How to Run

```
./weather
```

Then select the option from the menu:

```
================ WEATHER MODELING (QUADRATIC) ================
1. Hard-coded coefficients (single model)
2. Keyboard input (single model)
3. Read ONE model from a file
4. Read MULTIPLE models from a file
5. Exit
=============================================================
Enter your choice (1-5):
```

---

## 📌 Output Example

```
Model #1:
  Equation: T(t) = 1.00 t^2 + -3.00 t + 2.00
  Discriminant = 1.00
  Two real roots: t1 = 2.0000, t2 = 1.0000
```

---

## 🧑‍💻 Author

* **Your Name**
* GitHub: *(add link after creating account)*

---

## 🎯 Learning Outcomes

✔ Understanding and applying the **quadratic formula**
✔ Working with **conditions** and **math library**
✔ Taking input via **keyboard** and **file handling**
✔ Modularized code with **functions**
✔ Debugging & version tracking with **Git & GitHub**

---

