# Employee Management System (SAP ABAP)

## 📌 Overview
End-to-end Employee Management System built in SAP ABAP.  
Covers database design, CRUD operations, ALV reporting, and function modules for salary statistics.

## 🧩 Features
- Custom table `ZEMPLOYEEMS` with domains and data elements.
- ABAP programs for:
  - Insert employee records (`ZINSERT_EMP`)
  - Display all employees (`ZDISPLAY_EMP`)
  - Search employees by department (`ZSELECTION_SCREEN_MS`)
  - ALV report for professional tabular output (`ZALV_EMP`)
  - Salary statistics report (`ZSALARY_REPORT`)
- Function Module `Z_EMP_SALARY_STATS` to calculate average, max, and min salary.

## 📸 Screenshots
### 🔹 Database Design
![Table Definition](SCREENSHOTS/table_definition.png)

### 🔹 CRUD Operations
![Insert Success](SCREENSHOTS/insert_success.png)
![Employee Display](SCREENSHOTS/display_emp.png)

### 🔹 Interactive Selection Screen
![Selection Screen](SCREENSHOTS/selection_screen.png)

### 🔹 Reporting
![ALV Report](SCREENSHOTS/alv_report.png)
![Salary Report](SCREENSHOTS/salary_report.png)

### 🔹 Function Module
![FM Code](SCREENSHOTS/fm_code.png)


## 🚀 How to Run
1. Import programs into SAP system via SE38.
2. Create table `ZEMPLOYEEMS` in SE11 using provided structure.
3. Activate all objects.
4. Execute reports to insert, display, and analyze employee data.

## 🛠 Skills Demonstrated
- SAP ABAP Data Dictionary (Domains, Data Elements, Tables)
- ABAP Reports (CRUD, Selection Screens)
- ALV Reporting
- Function Modules
