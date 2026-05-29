# IPL Auction Analysis using SQL

This repository contains a collection of SQL queries written to analyze an IPL auction dataset. The objective of the project is to practice and demonstrate proficiency in SQL concepts including:

* Aggregations
* Subqueries
* Correlated Subqueries
* Common Table Expressions (CTEs)
* Window Functions
* Ranking Functions
* Conditional Aggregation
* CASE Expressions

The queries explore player valuations, team spending patterns, role-based analysis and comparative statistics across different player categories.

---

## Dataset

The dataset consists of IPL player auction information with the following attributes:

* Player Name
* Team
* Role
* Price (in Crores)
* Player Type (Indian / Overseas)

---

## SQL Problems Solved

### Team-Level Analysis

* Calculate total spending by each team.
* Identify the highest-priced player in every team.
* Find players whose price exceeds their team's average spending.
* Compute each player's contribution percentage to their team's total spending.

### Player Ranking & Valuation

* Rank players within each team based on auction price.
* Retrieve the top 2 most expensive players from every team.
* Find the most expensive and second most expensive player in each team.

### Role-Based Analysis

* Find the top 3 highest-paid all-rounders.
* Identify the most expensive player for each role.

### Categorization & Classification

* Classify players into High, Medium, and Low price brackets using CASE expressions.
* Count players in each pricing category.

### Comparative Analysis

* Compare average auction prices of Indian and Overseas players using subqueries.

---

## Key Learning Outcomes

Through this project, I practiced:

* Writing analytical SQL queries for business-style problems.
* Using window functions for ranking and partition-based calculations.
* Applying correlated subqueries to solve group-wise maximum problems.
* Structuring complex queries using Common Table Expressions (CTEs).
* Performing comparative and percentage-based analysis using SQL.

---

## Technologies Used
MySQL 8.0+

---

## Author

Afreen S

This repository is part of my SQL learning and data analytics practice journey, focused on strengthening query-writing skills through real-world IPL auction scenarios.
