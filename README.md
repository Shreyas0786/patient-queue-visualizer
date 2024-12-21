# Patient Queue Visualizer

This program is a **C-based healthcare queue visualizer** designed to represent the number of patients assigned to different departments in a hospital. Each department's patient capacity is visualized using a pyramid-like structure, where each `#` symbol corresponds to a **single patient slot**.

---

## Features
- **Interactive Input:** Allows users to input the number of departments (1–8).
- **Patient Distribution Visualization:** Uses `#` symbols to represent patient slots for each department.
- **Department Names:** Displays the names of departments alongside their respective patient counts.
- Built using the **CS50 library** for seamless input handling and validation.

---

## How It Works
1. The user is prompted to enter the number of hospital departments (between 1 and 8).
2. The program validates the input and then prints a pyramid-like visualization:
   - Each **row** represents a department.
   - Each **#** symbol corresponds to **one patient slot** in that department.
3. The number of `#` symbols increases with each row, reflecting departments that can handle more patients.

---

## What Does `#` Represent?
- **# Symbol = 1 Patient Slot**  
  Each `#` in the pyramid visualization represents a single patient that can be accommodated in the department. For example:
  - **Critical Care Unit (CCU):** `#` (1 patient slot).
  - **Emergency Room (ER):** `##` (2 patient slots).
  - **Surgical Ward:** `###` (3 patient slots), and so on.
  
This representation helps visualize patient load and capacity for each department.

---
**Compile the Program**
make patients

---
**Run the Program**
./patients
