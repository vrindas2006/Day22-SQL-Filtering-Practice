# SQL Filtering Practice

## Overview

This project contains my SQL filtering practice completed using **MySQL Workbench** with the **Northwind database**.

The task focuses on retrieving specific records using different SQL filtering techniques.

## Objectives

- Practice the `WHERE` clause
- Use `IN` to filter multiple values
- Use `BETWEEN` to filter values within a range
- Use `LIKE` for pattern matching
- Improve SQL query-writing and data-filtering skills

## SQL Concepts Practiced

### 1. WHERE
Used to filter records based on a specific condition.

Example:
```sql
SELECT *
FROM customers
WHERE country_region = 'USA';
