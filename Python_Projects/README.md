# Automating File Updates with Python for Security Operations

## Project Overview
In a Security Operations Center (SOC), security analysts frequently need to automate repetitive tasks—such as updating access control lists, parsing logs, or modifying threat intelligence feeds. This project demonstrates a Python script designed to automate the process of updating an IP address allow list by removing revoked or unauthorized IP addresses from a restricted subnetwork text file.

This project was completed as part of my practical cybersecurity training to build foundational automation skills using Python.

---

## Project Objectives & Workflow
The Python script automates the file-update workflow through the following sequential steps:
1. Opening Files Safely: Accessing the allow list text file using secure context managers.
2. Reading Data: Loading the contents of the file into a variable.
3. Parsing Data:  Converting raw string data into a structured Python list format.
4. Iterating Through Elements:  Using a `for` loop to cycle through unauthorized IP addresses.
5. Filtering / Removing IPs: Checking if target IPs exist in the allow list and removing them.
6. Writing Updated Data:  Restructuring the list and rewriting the cleaned data back into the original file.

--

## Key Python Concepts Applied
**File Management:** Utilizing the `with` statement and the `open()` function with read (`"r"`) and write (`"w"`) parameters to ensure proper resource management.
**String & List Methods:** Using `.split()` to parse string data into lists, `.remove()` to strip unauthorized items, and `\n.join()` to restructure the data.
**Control Flow:** Implementing `for` loops combined with conditional `if` statements to evaluate elements logically.

-- View full notebook code here [https://github.com/djkayes/Cyber-Security-/blob/17031188d3d3fca36104f78dff26f9fc6f3debb7/Python_Projects/Python_Practice_1.ipynb]

-- SCREENSHOTS of Each step are listed here [

