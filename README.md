# Water Billing System (DBMS Web App)

Built a DBMS-backed web application to manage customers, users, and monthly water bills with automated bill calculation.

## Objective
Automatically calculate customer bills using previous meter reading, current reading, and price per unit, and maintain bill history.

## Features
- User login (authorized users only)
- Customer management (add/edit/delete)
- Billing management (create bill, view/print bill history)
- User management (add/edit/delete users)

## System Design
- Workflow: login → customer/user/billing modules → bill history → logout
- Database: 3 tables (User, Customer, Bill)

## Tech Stack
HTML, CSS, JavaScript, PHP, MySQL (XAMPP / localhost)

## Key Visuals
![Workflow](artifacts/01_workflow_flowchart.png)
![ER Diagram](artifacts/02_er_diagram.png)
![Login/Home](artifacts/03_login_home.png)
![Customer CRUD](artifacts/04_customer_crud.png)
![Billing Flow](artifacts/05_billing_flow.png)

## Docs
- Project synopsis: docs/dbms_project_synopsis.pdf
- Design artefacts: docs/artefacts_flow_er.pdf
- Output screenshots: docs/output_screenshots.pdf
