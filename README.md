# Oracle-Schema-Data-Search
This repository contains an Oracle PL/SQL script designed to search for a specific value ('PC5876880' in this case) across all tables and columns within the current schema. The script dynamically queries each table and column to determine where the value exists.

Overview:
This SQL script searches for a specified value ('PC5876880') across all tables and columns within the current Oracle schema using dynamic SQL.

How to Use:
Modify the v_search variable in the script to specify the value you want to search for.
Execute the entire script in an Oracle SQL environment with PL/SQL support and sufficient privileges to access user tables and columns.
The script will output the tables and columns where the specified value is found.
