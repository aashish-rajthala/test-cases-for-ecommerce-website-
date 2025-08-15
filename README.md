QA Test Cases Repository
Overview

This repository contains UI and Functional Test Cases for the project, along with associated bug reports. It is intended for QA tracking, bug reporting, and reference for test execution.

Repository Structure
/QA-Test-Cases
│
├── Functional-Test-Cases
│   ├── Login_Module.xlsx
│   ├── Navigation_Module.xlsx
│   └── Search_Module.xlsx (to be added)
│
├── UI-Test-Cases
│   ├── Homepage_UI.xlsx
│   └── Header_Section_UI.xlsx
│
├── Bug-Reports
│   ├── Login_Bugs.xlsx
│   └── Navigation_Bugs.xlsx
│
└── README.md

Test Case Types
1. UI Test Cases

Purpose: Verify the visual elements of the application.

Examples:

Logo visibility on the homepage.

Image load in header and body sections.

Spelling mistakes and alignment issues.

Columns in Excel:

Test Case ID, Test Scenario, Steps to Execute, Expected Result, Actual Result, Status, Comments, Screenshot

2. Functional Test Cases

Purpose: Verify application functionality works according to requirements.

Modules Covered:

Login

Navigation

Search (to be added)

Registration (to be added)

Columns in Excel:

Test Case ID, Test Scenario, Steps to Execute, Input Data, Expected Result, Actual Result, Status, Comments, Screenshot

Bug Reports

Purpose: Document all failed test cases with clear steps, expected vs actual results, and severity.

Bug Report Columns:

Bug ID, Related Test Case ID, Title, Description, Steps to Reproduce, Expected Result, Actual Result, Screenshot, Severity, Status

Severity Levels:

Low – Minor issue not affecting functionality

Medium – Issue affects some functionality or minor usability

High – Critical functionality broken

Status Options:

Open, In Progress, Resolved, Closed
