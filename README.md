# redesigned-fishstick
# School Financial Analytics Dashboard (Power BI)
This project analyzes the financial performance of a simulated K–12 school with 1000 students across classes 1–12 over a 3-year period (2022–2024).

The dashboard helps monitor fee collection, revenue trends, expenses, and overall financial health to support data-driven decision making for school administration.

## Project Overview

This project analyzes the financial performance of a simulated K–12 school using Power BI. The dataset represents a school with approximately **1000 students across classes 1–12** over a **3-year period (2022–2024)**.

The dashboard provides insights into **fee collection performance, revenue composition, expense distribution, and overall financial health**. The goal of the project was to design a realistic financial analytics model similar to what school administrators might use to monitor operations and make informed decisions.

---

## Key Business Questions

The dashboard helps answer several important financial questions:

* How much revenue is being collected each month?
* What percentage of fees are successfully collected?
* Which classes contribute the most revenue?
* How much revenue remains outstanding?
* What are the major expense categories for the school?
* Is the school running a financial surplus or deficit?

---

## Dataset Description

The project uses a simulated dataset designed to reflect a real school financial system.

Main tables include:

* **Students** – Student details including class and transport usage
* **Fee Payments** – Monthly fee transactions including tuition and transport fees
* **Fee Structure** – Tuition and additional charges by class
* **Expenses** – Monthly operational expenses such as salaries, utilities, and maintenance
* **Transport Fees** – Transport fee categories by zone
* **Date Table** – Time dimension for trend analysis

The dataset covers **36 months of financial activity** and includes **36,000+ fee payment records**.

---

## Data Model

A **star schema data model** was implemented to support efficient analysis.

Fact tables:

* Fee Payments
* Expenses

Dimension tables:

* Students
* Fee Structure
* Transport Fees
* Date Table

This structure enables flexible filtering and time-based analysis across the dashboard.

---

## Key Metrics (DAX Measures)

The following financial KPIs were created using DAX:

* **Total Revenue** – Total amount of fees collected
* **Total Expected Fees** – Total fees expected from students
* **Outstanding Fees** – Difference between expected and collected fees
* **Collection Rate** – Percentage of fees successfully collected
* **Total Expenses** – Total operational expenses
* **Net Surplus** – Revenue minus expenses

---

## Dashboard Insights

The dashboard provides several important insights:

* Tuition fees are the **primary revenue source**, while transport contributes a smaller portion.
* Revenue trends show **consistent monthly collection with occasional spikes from late payments**.
* Salary expenses (teachers and staff) represent the **largest cost category**.
* The school maintains a **positive financial surplus**, indicating sustainable operations.

---

## Tools Used

* **Power BI** – Data modeling and dashboard creation
* **DAX** – KPI calculations and financial metrics
* **Python (Pandas & NumPy)** – Dataset generation and simulation

---

## Dashboard Preview

*(Add screenshots of the dashboards here)*

Example:

* Revenue Overview
* Fee Collection Analysis
* Expense Breakdown
* Financial Health Dashboard

---

## Key Learning Outcomes

Through this project I practiced:

* Designing a **multi-table star schema data model**
* Creating financial **KPIs using DAX**
* Performing **time-series analysis**
* Building **interactive dashboards for operational decision-making**

---

## Future Improvements

Potential improvements to the project include:

* Adding student-level payment tracking for more detailed analysis
* Incorporating teacher-level salary expenses
* Forecasting future revenue trends using historical data

---

## Author

Sam Sanderson

This project is part of my **Data Analytics portfolio**, where I build practical analytics solutions to explore real-world business problems.
