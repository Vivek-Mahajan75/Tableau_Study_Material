# SQL Queries & Theory

**Date:** 20th Jan 2026  

---

## Q1) What is SQL?
### Ans**SQL (Structured Query Language)** is the standard language used to interact with relational databases.
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
### Ans: Following standard SQL rules ensures consistency and portability across databases.
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
/* comment */  This is a Multi-line comment

## Q3)What are Different SQL Commands or Queries?
### Ans
**Structured Query Language (SQL)** commands are standardized instructions used to interact with data stored in relational databases.  
They allow users to **create, retrieve, modify, and control data and database structures**.

SQL commands are categorized based on their functionality.
---

## 1️⃣ Data Definition Language (DDL)

DDL commands are used to **define and manage database structures** such as tables, views, and indexes.  
Database engineers use these commands to create and modify database objects as per business requirements.

| Command   | Description |
|---------|------------|
| CREATE  | Creates new database objects such as tables, views, or indexes |
| ALTER   | Modifies an existing database object |
| DROP    | Deletes database objects permanently |
| TRUNCATE| Removes all records from a table but retains its structure |
| RENAME  | Changes the name of an existing database object |

---

## 2️⃣ Data Manipulation Language (DML)

DML commands are used to **insert, update, and delete data** in database tables.  
These commands are commonly used by applications.

| Command | Description |
|-------|------------|
| INSERT | Adds new records to a table |
| UPDATE | Modifies existing records |
| DELETE | Removes records from a table |

---

## 3️⃣ Data Query Language (DQL)

DQL commands are used to **retrieve data** from relational databases.

- The most commonly used command is `SELECT`
- Used to filter, sort, and return required data

```sql
SELECT name, salary 
FROM employees 
WHERE salary > 50000;

---
