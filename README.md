# 🎓 Advanced CGPA Calculator (C++)

A comprehensive Academic Grade Management System developed as part of my **CodeAlpha** C++ Programming Internship. This application simulates a real-world registrar's tool for generating student transcripts with precise GPA and percentage calculations.

## 🌟 Key Features
* **Official Branding:** Integrated fields for **College Name**, **Student Name**, and **University Roll Number** for professional output formatting.
* **Smart Input Handling:** Implemented robust buffer management (using `cin.ignore()`) to ensure seamless data entry across multiple course inputs.
* **Latin Honors Recognition:** Automatically evaluates student performance to award professional distinctions:
    * **Summa Cum Laude 🎓** (GPA 3.80+)
    * **Dean's List ⭐** (GPA 3.50 - 3.79)
    * **Academic Probation ⚠️** (GPA < 2.00)
* **Automated Calculations:** Computes total credits, weighted GPA, and overall percentage ($GPA \times 9.5$).
* **Individual Course Tracking:** Displays letter grades, corresponding points, and a PASS/FAIL status for every subject.

## 💻 Technical Implementation
* **Language:** C++
* **Logic:** Utilizes `std::vector` and `structs` for dynamic data storage.
* **Formatting:** Employs `<iomanip>` for perfectly aligned tabular reports.
* **Safety:** Includes input validation to prevent program crashes from invalid characters.

---

### 🚀 How to Run the Project
1. Clone this repository or download the `CGPACalculator.cpp` file.
2. Compile the code using any standard C++ compiler (e.g., GCC, Clang, or MSVC).
3. Follow the on-screen prompts to enter student details and academic scores.
4. View the generated **Official Academic Transcript** in your terminal.
