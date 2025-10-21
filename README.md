# Mini SQL Engine in C

![Language: C](https://img.shields.io/badge/Language-C-00599C?style=for-the-badge&logo=c) ![Status: Prototype](https://img.shields.io/badge/Status-Prototype-yellow?style=for-the-badge)
![Platform: Linux/macOS/Windows](https://img.shields.io/badge/Platform-Linux%20%7C%20macOS%20%7C%20Windows-lightgrey?style=for-the-badge)
![Docs](https://img.shields.io/badge/Docs-Available-blue?style=for-the-badge)
![Features: SELECT/WHERE](https://img.shields.io/badge/Features-SELECT%20%7C%20WHERE-orange?style=for-the-badge)

# Mini SQL Engine in C

## 📌 Project Overview
This project is a simplified SQL-like query parser and executor written in C.  
It can read data from `.txt` files (representing tables) and execute `SELECT` queries with optional `WHERE` conditions.

## 🗂 File Structure
- `main.c` → Source code
- `students.txt` → Sample table data
- `README.md` → Project details
- `docs/` → Screenshots & test queries

## ⚡ Features
- Parse and validate simplified SQL queries  
- Support for `SELECT field1, field2 ...` or `SELECT *`  
- `FROM table_name` → Reads `.txt` file  
- Optional `WHERE field=value` condition  
- Error handling for missing fields, tables, or invalid queries  

## 📝 Example Queries
```sql
SELECT name, grade FROM students WHERE age=20;
SELECT * FROM students WHERE grade=A;
SELECT age FROM students WHERE name=Bob;
