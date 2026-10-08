## About

This repository contains my submission for Exercise 3: "SQL CASE Statements." The exercise covers 10 handwritten SQL queries based on 10 tables (`products`, `orders`, `employees`, `students`, `deliveries`, `tickets`, `attendance`, `products_inventory`, `classes`, and `payments`), focusing on classifying rows into labelled categories using `CASE` expressions.

## Contents

- `SQL-Exercise-3.pdf` – scanned handwritten SQL queries with expected output tables

## Topics Covered

- Writing `CASE` expressions inside a `SELECT` statement
- Searched `CASE` with `WHEN ... THEN ... ELSE ... END`
- Simple `CASE` for converting values into labels (e.g. numeric priority to `'High'`, `'Medium'`, `'Low'`)
- Classifying rows into business categories: price tiers, order values, letter grades, delivery performance, stock status, and class sizes
- Filtering conditions using comparison operators (`>`, `<`, `>=`, `<=`, `=`) and `BETWEEN`
- Combining conditions using `AND` and `OR` (e.g. department and salary, payment method and amount)
- Calculating a value inside a query (attendance percentage) and classifying the result
- Handling remaining cases with `ELSE`
- Renaming result columns with `AS` (aliases) to match the expected output
