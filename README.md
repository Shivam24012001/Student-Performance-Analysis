# Overview

This project analyzes student performance using various Google Sheets functions, including IF, AND, OR, VLOOKUP, dropdowns, and filters. The aim is to generate a consolidated student report that includes total marks, grace marks, pass/fail status, and additional reports based on specified conditions.

## Features & Methodology

### 1. Total Marks Calculation

Total Marks = Academic Score + Internal Score

### 2. Grace Marks Allocation

If Social Score or Co-curricular Score is greater than 90 → +10 marks

If Social Score or Co-curricular Score is greater than 80 → +5 marks

If Social Score or Co-curricular Score is greater than 75 → +3 marks

Otherwise → 0 marks

### 3. Consolidated Marks Calculation

Consolidated Marks = Total Marks + Grace Marks

### 4. Pass/Fail Determination

A student is considered Pass if all the following conditions are met:

Academic Score ≥ 60

Internal Score ≥ 20

Attendance Percentage ≥ 50%

Consolidated Marks ≥ 90

Otherwise, the student is marked as Fail.

### 5. Reports and Insights

Filtering and summarizing data based on specified conditions.

Dropdown menus for dynamic selection and analysis.

Automated reports created to visualize student performance.

## Files Included

Google Sheets File: Contains formulas, conditional formatting, and reports.

README.md: Documentation explaining the project.

## How to Use

#### 1. Open the Google Sheets file.

#### 2. Navigate to the following tabs:

"Concept Building Problems" – for problem-solving exercises.

"Student Consolidated Score" – for the final student report.

"Reports" – for additional insights and summaries.

#### 3. Review student performance based on the pre-defined logic and filters.

## Tools Used

Google Sheets

Functions Used: IF, Nested IF, AND, OR, VLOOKUP, Filters, Dropdowns, Array_Constrain, Sorting
