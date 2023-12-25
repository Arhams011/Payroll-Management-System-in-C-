# Payroll Management System - Automated Compensation Management

## Project Overview

- **Made By:** Arham Siddiqui

The project aims to alleviate the hassle of maintaining and distributing payrolls by:

### Automation of Payroll Processes:

- Streamlining the manual aspects of payroll management.
- Efficient handling of salary calculations and disbursements.

### Centralized Employee Data Management:

- Consolidation and organization of employee information.
- Accessible platform for HR personnel to manage employee records.

### Accurate Tax and Deduction Calculations:

- Automated computation of taxes and deductions.
- Minimizing errors in salary-related calculations.

### Reporting Capabilities:

- Generation of comprehensive reports for payroll analysis.
- Providing insights into payroll trends and expenditures.

## Introduction

### What is the project about and what are its utilities?

The project involves the automation of fundamental payroll processes, focusing on:

### Scope of the Project and Potential Future Developments

#### Scope:

- Concentrates on automating fundamental payroll processes.
- Covers essential features such as salary calculations and employee data management.

#### Scalability:

- Designed to accommodate the potential addition of new features.
- Allows for scalability to meet the evolving needs of the organization.

#### Future Working:

- Module Expansion: Consideration for the addition of supplementary modules (e.g., Benefits administration, time and attendance tracking).
- Integration Possibilities: Explore integration with other organizational systems.

## Welcome Page and Functionality

- Admin Login
- Menu
  - Add New Record
  - Update Record
  - Delete Record
  - Search Record
  - List Records
  - Payslip Generation
  - Quit
- Excel File Generated
- Exit

## Project Particulars

- **Language used for Console Application:** C++
- **Prospective GUI Builder:** [Walnut (Based on the Vulkan Framework)](https://github.com/StudioCherno/Walnut)

### Header Files and Their Uses:

- `#include<iostream>`: C++ header file for input and output streams.
- `#include<stdlib.h>`: Header file for standard library functions in C.
- `#include<conio.h>`: Non-standard header file for console input and output functions.
- `#include<windows.h>`: Windows-specific header file for Windows API functions.
- `#include<time.h>`: Header file for date and time functions.
- `#include<iomanip>`: C++ header file for input and output formatting.
- `#include<ctype.h>`: C header file for character handling functions.

## Rudimentary GUI

Using built-in functions, a rudimentary GUI was created with functions/methods such as:

- `void loginFrame1(int xLenS, int yLenS, int xLenE, int yLenE)`: Utilizes the `gotoXY()` function to position the cursor.
- `void setWindowSize(int width, int height)`: Sets the size of the console window.
- `void border(int xLenS, int yLenS, int xLenE, int yLenE)`: Implements a border around the data.
- `void Cdelay(int msec)`: Delays the program using the `clock()` function.

## Keeping Records - Excel (.xls)

To keep a comprehensive record of the payslips generated by the program, an Excel file is generated and updated with each entry. This allows for the tabulation of data and meaningful insights.

## Getting Started

Download the payroll.cpp file and ensure the presence of non-standard libraries.

## Requirements

- [Visual Studio Code](https://code.visualstudio.com/) or any other code editor.

## Reference For This Project

- [Reference](https://github.com/VangaPoornaChand/Payroll-management-System-in-CPP-With-Documentation)
