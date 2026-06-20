# HR Management System & Analytics Dashboard (Excel)

A complete HR Management System built entirely in Microsoft Excel for **CoffeeCore Solutions** (a simulated company), covering employee records, attendance, leave, payroll, performance tracking, and an interactive analytics dashboard.

The goal of this project was to simulate how a real company manages its HR operations end-to-end, while practicing advanced Excel skills like Pivot Tables, XLOOKUP, dynamic dashboards, and data validation.

## Overview

The workbook is divided into 6 modules, each on its own sheet:

1. **Employee Database** - Central record of all employees with search, filters, and validated data entry
2. **Attendance Management** - Daily attendance tracking with automated present/absent/leave calculations
3. **Leave Management** - Leave requests, approval status, and leave history per employee
4. **Payroll Management** - Automated salary calculation based on attendance and performance
5. **Performance Tracking** - KPI, attendance, and productivity scoring with auto-generated ratings
6. **HR Analytics Dashboard** - A single-page interactive dashboard tying everything together

## Features

### Employee Database
- Unique Employee IDs with dropdown-based data validation (Gender, Department, Status)
- Instant employee lookup by ID using XLOOKUP
- Department-wise filtering via Excel Tables

### Attendance Management
- Daily status tracking (Present / Absent / Leave / Half Day)
- Auto-calculated present/absent counts and attendance percentage per employee
- Conditional formatting to visually flag low attendance

### Leave Management
- Leave types: Casual, Sick, Emergency
- Auto-calculated leave duration from start/end dates
- Approved vs Pending vs Rejected leave summary
- Per-employee leave history lookup

### Payroll Management
- Net Salary = Basic Salary + Bonus - Leave Deduction
- Bonus tied to attendance performance (10% for 95%+ attendance, 5% for 85%+)
- Deductions scaled to attendance shortfall
- Top 5 highest-paid employees highlighted automatically

### Performance Tracking
- KPI Score, Attendance Score, and Productivity Score per employee
- Automatic Overall Rating (Excellent / Good / Average / Poor) based on weighted average
- Color-coded ratings for quick scanning

### HR Analytics Dashboard
- KPI cards: Total Employees, Active Employees, Average Salary, Total Payroll Cost, Attendance Rate, Employees on Leave, Best Performing Department
- Department-wise employee distribution (pie chart)
- Monthly attendance trend (line chart)
- Salary distribution (column chart)
- Performance rating distribution (donut chart)
- Leave analysis by type and approval status (stacked bar chart)
- Interactive slicers for Department and Approval Status filtering

## Excel Skills Demonstrated

- Pivot Tables & Pivot Charts
- XLOOKUP / INDEX-MATCH
- COUNTIFS / SUMIFS
- Nested IF statements
- Conditional Formatting
- Data Validation (dropdown lists)
- Dashboard design with Slicers
- Data cleaning and structuring
- HR analytics and KPI reporting

## Tech Stack

Microsoft Excel (Tables, Pivot Tables, Pivot Charts, Slicers, Conditional Formatting, Data Validation)

## Disclaimer

All employee names, salaries, and records in this workbook are fictional dummy data generated for demonstration purposes only.
