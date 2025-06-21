# 🧮 Simple GUI Calculator using Python (Tkinter)

This project is a basic calculator built with Python using the Tkinter library for the graphical user interface (GUI). It performs simple arithmetic operations: addition, subtraction, multiplication, and division.

---

## 🚀 Features

- User-friendly GUI
- Performs:
  - Addition (+)
  - Subtraction (−)
  - Multiplication (×)
  - Division (÷)
- Real-time input and result display
- Clear button to reset the expression

---


## 🛠️ Requirements

- Python 3.x

Tkinter comes bundled with most Python distributions. If it's not available, install it via:

```bash
sudo apt-get install python3-tk    # Linux


## ▶️ How to Run

1. Clone the repository or download the source files.  
2. Save the script as `calculator.py`.  
3. Open a terminal and run the script:
"python calculator.py"

```

---
## 🧾 Code Overview

- **Tkinter**: Used for GUI creation.
- **Entry widget**: To input and show expressions.
- **Button widgets**: For digits, operators, equal, and clear.
- **eval()**: Evaluates arithmetic expressions entered via the UI.

---

## ⚠️ Note

This calculator uses Python’s `eval()` to compute expressions. While it is safe in this context due to button-only input, `eval()` should be avoided in security-sensitive applications.

---

