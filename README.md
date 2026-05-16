# BACS2093 Operating Systems - Practical Assignment 🐧

A Linux shell scripting project developed for the BACS2093 Operating Systems course. This assignment focuses on applying fundamental UNIX/Linux shell commands to manipulate text files and recreate a specific command-line interface based on provided academic requirements.

## 📝 Overview
This script implements a text-based "Patron Maintenance Menu" system. It does not utilize a traditional database; instead, it relies entirely on Linux shell commands (like `awk`, `sed`, `sort`, and `grep`) to read, parse, and format data from a local flat text file (`patron.txt`).

## ⚙️ Key Functionalities
* **Command-Line Interface:** Recreation of a structured menu system in the terminal.
* **Data Parsing:** Reads and processes patron records (Patron ID, Name, Mobile Number, Birth Date, etc.) from `patron.txt`.
* **Sorting & Filtering:** Sorts patron details based on specific criteria (e.g., by Last Name, Patron ID, or Joined Date) in ascending order.
* **Report Generation:** Includes functionality to export the formatted output into an ASCII text file.

## 🛠️ Tech Stack
* **Language:** Bash / Linux Shell Scripting
* **Environment:** Any standard Linux/UNIX terminal

## 🚀 How to Run
1. Clone this repository to your local Linux machine or environment.
2. Open your terminal and navigate to the project directory.
3. Ensure the script has execution permissions by running:
   ```bash
   chmod +x shell.sh
   ```
4. Execute the script
   ```bash
   ./shell.sh
   ```

## 👨‍💻 Author
* **Ting Rong You**
* **Yong Chong Xin**
* **Wan Zi Kang**

_Bachelor of Software Engineering (Honours)_

_Tunku Abdul Rahman University of Management and Technology (TARUMT)_

_Year 1 Semester 3 - Operating Systems Assignment_
