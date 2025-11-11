# ⚽ freeCodeCamp SQL Bash Script World Cup Lab

## 📘 Overview
The `insert_data.sh` bash script connects to a `worldcup` PostgreSQL database** and executes a series of SQL queries to automatically import and manage data from a CSV file into the database. 
The `queries.sh` bash script retrieve detailed information about goal statistics, winning teams and participating teams. It uses the `psql` command-line tool to query data and display formatted results directly in the terminal.

---

## ⚙️ Requirements
Before running this script, ensure that you have:

- 🐘 **PostgreSQL** installed and running  
- A database named **`worldcup`** that can be populated using the `insert_data.sh` bash script.
- A PostgreSQL user named **`freecodecamp`** with access to the database  
- The following tables present and populated:
  - `teams`
  - `games`

---

## 🚀 How to Run

1. Save the script as `queries.sh`
2. Make it executable (This applies too for the `insert_data.sh` script):
   ```bash
   chmod +x queries.sh
   ````
3. Run the script:
   ./queries.sh
4. The script will connect to the PostgreSQL database and display results for each query.

## 👨‍💻 Author

Created by: Hugo Rocha
