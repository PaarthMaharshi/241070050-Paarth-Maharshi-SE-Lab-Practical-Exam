

---

#  Smart Waste Management System – Test Suite

This repository contains a Python-based testing suite for the **Report Overflowing Bin subsystem**, a core component of a Smart Waste Management System.

The suite demonstrates advanced software testing methodologies, including:

*  Functional Testing (**Black Box Testing**)
*  Structural Testing (**White Box Testing**)

---

###  Thresholds

* Fill levels must be within:

  ```
  0% ≤ Fill Level ≤ 100%
  ```

---

###  Decision Matrix

| Condition        | Vehicle Availability | Status               |
| ---------------- | -------------------- | -------------------- |
| Fill Level ≥ 80% |  Available          | **DISPATCHED**       |
| Fill Level ≥ 80% |  Not Available      | **PENDING** (queued) |
| Fill Level < 80% | —                    | **NORMAL**           |

---

* **Python 3.x**
  Make sure Python is installed on your system.

* **Modern Terminal (Recommended)**
  Supports ANSI color codes for better output visualization:

  * VS Code Integrated Terminal
  * macOS Terminal
  * Linux Bash

---

### 🛠 Installation & Execution

1. **Save the Script**

   Copy the source code into a file named:

   ```bash
   test_report_overflowing_bin.py
   ```
* Include sample output screenshots
* Or convert this into a more “portfolio-style” README for projects 🚀
