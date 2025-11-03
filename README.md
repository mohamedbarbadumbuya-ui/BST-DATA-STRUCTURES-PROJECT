[README.md](https://github.com/user-attachments/files/23304099/README.md)
# 💻 Stack Implementation for Expression Evaluation  

📚 **Course:** DCOMP320 — *Data Structures and Algorithms*  
🧮 **Assignment Title:** Stack-Based Expression Evaluation  
👨🏽‍🏫 **Examiner:** Amandus Benjamin Coker  
👨🏽‍💻 **Student:** **Barba M. Dumbuya**  
🆔 **Student ID:** 905004091  
📅 **Date:** October 31, 2025  

---

## 🚀 Project Overview  
This project showcases the implementation of a **stack-based algorithm** to evaluate mathematical expressions written in **infix notation**.  
Using the **Shunting-Yard Algorithm**, expressions are converted into **postfix notation**, which is then evaluated using a **stack** for operands and operators.  

It highlights core **stack operations** such as `push()`, `pop()`, `peek()`, and `is_empty()`, illustrating their role in managing operator precedence and nested parentheses.

---

## 🧩 Key Components  

### 🔹 1. Tokenization  
Breaks input expressions into tokens (numbers, operators, parentheses).  
Supports:
- Integers and decimal numbers  
- Negative numbers  
- Operators: `+`, `-`, `*`, `/`, `^`  
- Parentheses for grouping  

### 🔹 2. Infix ➡️ Postfix Conversion  
Implements operator precedence and associativity using the **Shunting-Yard algorithm** with an **operator stack**.

### 🔹 3. Postfix Evaluation  
Uses a **value stack** to evaluate postfix expressions and compute final results efficiently.

### 🔹 4. File I/O  
- 📥 Reads expressions from `input.txt`  
- 📤 Writes evaluated results to `output.txt`  
- ⚠️ Handles invalid expressions or division by zero gracefully  

---

## ⚙️ How to Run  

```bash
# 1️⃣ Clone the repository
git clone https://github.com/buharibangura111/data-structure-Assignment-.git
cd data-structure-Assignment-

# 2️⃣ Run the evaluator
python evaluate.py
```

➡️ Ensure `input.txt` contains one expression per line.  
Results will appear in `output.txt`.

---

## 🧪 Example  

**🗒️ Input (input.txt):**
```
3 + 5 * 2
(8 / 4) + 7 * 2
10 - (2 + 3) * 4
-5 + 3 * (2 + 4)
(3.5 + 2.5) * 2
2 ^ 3 + 1
(10 / (3 - 3)) + 1
```

**📤 Output (output.txt):**
```
13
16
-10
13
12
9
ERROR: Division by zero encountered in expression
```

---

## 🧠 Algorithm Flowchart  
🖼️ The complete logic is visualized in `Flowchart_of_Stack-Based_Evaluation.png`.

---

## 📊 Testing and Results  
✅ Handles:
- Nested parentheses  
- Mixed arithmetic operations  
- Floating-point calculations  
- Syntax and runtime errors  

⏱️ **Complexity:** O(n) — linear in the number of tokens.  

---

## 🗣️ Discussion  
This implementation demonstrates how **stack data structures** simplify arithmetic expression evaluation.  
It efficiently resolves **operator precedence**, **parentheses nesting**, and **error handling** through modular design.

---

## 🏁 Conclusion  
The project successfully achieves the objectives of the **Stacks Implementation Assignment**, integrating:  
- Algorithmic logic  
- Stack manipulation  
- File handling  
- Robust exception management  

---

## 📚 References  
- Knuth, D. E. (1997). *The Art of Computer Programming, Vol. 1: Fundamental Algorithms*. Addison-Wesley.  
- Weisstein, E. W. (n.d.). *Shunting-Yard Algorithm*. MathWorld — A Wolfram Web Resource.  

---

## 📎 Files Included  
📁 `evaluate.py` — Main program  
📄 `input.txt` — Input expressions  
📄 `output.txt` — Evaluation results  
🖼️ `Flowchart_of_Stack-Based_Evaluation.png` — Algorithm flowchart  
📘 `Stack_Implementation_Assignment_Completed.docx` — Full report  
📑 `README.md` — This documentation  

---

## ✨ Author  
👨🏽‍💻 **Buhari Bangura**  
🎓 *Limkokwing University of Creative Technology (LUCT)*  
📧 *Data Structures and Algorithms — Semester 2, 2025*
