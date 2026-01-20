# SQL Queries & Theory

**Date:** 20th Jan 2026  

---

## Q1) What is SQL?

**SQL (Structured Query Language)** is the standard language used to interact with relational databases.

### Key Points:
- SQL is used to **store, retrieve, update, and manage data** in relational databases.
- It became a standard of:
  - **ANSI** in 1986
  - **ISO** in 1987
- DBMS tools like **MySQL, SQL Server, Oracle** provide an SQL engine and interface to execute queries.

### SQL Query Execution Steps:
1. **Input** – User submits a query (SELECT, INSERT, UPDATE, DELETE).
2. **Parsing** – SQL engine checks syntax and schema validity.
3. **Optimization** – Query optimizer selects the most efficient execution plan.
4. **Execution** – Database engine executes the query.
5. **Output** – Result set or success message is returned.

---

## Q2) Rules for Writing SQL Queries

Following standard SQL rules ensures consistency and portability across databases.

### Rules:
- **End with Semicolon (;):** Each SQL statement should end with a semicolon.
- **Case Insensitivity:** SQL keywords are not case-sensitive, but table and column names may be DBMS-dependent.
- **Whitespace Allowed:** Queries can span multiple lines; proper spacing improves readability.
- **Reserved Words:** Avoid using SQL keywords as object names. If required, use quotes (`" "`) or backticks (`).

---

## Comments in SQL

- **Single-line comment:**
```sql
-- This is a single-line comment

