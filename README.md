# SQL Queries & Theory
# Date:- 20th Jan 2026
#  Q1) What is SQL ?
#  ans: 
#  i) Structured Query Language (SQL) is the Standard Language used to interact with relational databases.
#  ii) It allows users to store, retrieve, update and manage data efficiently through simple commands.
#  iii) SQL became a standard of the American National Standards Institute (ANSI) in 1986, and of the International Organization for Standardization (ISO) in 1987.
#  iv) We interact with databases using SQL queries. DBMS tools like MySQL and SQL Server have their own SQL engine and an interface where users can write and execute SQL queries.
#  Below are the detailed steps involved in the SQL query execution.
#      Input: The user submits a query (e.g., SELECT, INSERT, UPDATE, DELETE) via an application or interface.
#      Parsing: The query processor breaks the query into parts (tokens) and checks for syntax and schema correctness.
#      Optimization: The optimizer finds the most efficient way to run the query using indexes, statistics and available resources.
#      Execution: The execution engine runs the query using the chosen plan, accessing or modifying the database as needed.
#      Output: Results are returned to the user, either data (for SELECT) or a success message (for other operations).
      
 # Q2)Rules for Writing SQL Queries
 # Ans: 
 # There are certain rules for SQL which would ensure consistency and functionality across databases. By following these rules, queries will be well formed and well executed in any database.
 # i) End with Semicolon (;): Each SQL statement must end with a semicolon to execute properly.
 # ii) Case Insensitivity: SQL keywords (e.g., SELECT, INSERT) are not case-sensitive. However, table or column names may be case-sensitive depending on the DBMS.
 # iii) Whitespace Allowed: Queries can span multiple lines, but use spaces between keywords and names.
 # iv) Reserved Words: Avoid using SQL keywords as names. If needed, wrap them in quotes (" ") or backticks (`).
      
  # Comments
  #    Single-line: -- comment
  #    Multi-line: /* comment */
  #    Data Constraints: Use NOT NULL, UNIQUE, PRIMARY KEY, etc., to ensure data accuracy.
  #    String Values: Enclose strings in single quotes ('text').
      
   # Naming Rules:
   #   We Start with a letter
   #   We can only use Max 30 characters
   #   We only use letters, numbers and underscores (_)
