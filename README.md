# Python-Developer-Assignment-Part-1-and-Part-2-
all the 5 tasks are completed

Python Developer Assignment (For Freshers)
Author

Mayank Kumar
Overview

This project contains solutions to the Python Developer Assignment (For Freshers).
It includes Part 1 (Coding Challenges) and Part 2 (Mini Project – To-Do List Manager).
All code follows PEP 8 guidelines and uses Python 3.8+ standard libraries only.

Part 1 – Coding Challenges
Q1. String & List Manipulation

Function: analyze_sentence(sentence)

Returns:

Total word count

Longest word

Alphabetically sorted list of unique words

Example:

sentence = "python is great and python is fun"
print(analyze_sentence(sentence))
# Output: (7, "python", ["and", "fun", "great", "is", "python"])

Q2. File Handling

Function: read_student_file(filename)

Reads student data, sorts by marks, and displays:

All students

Top 3 students

Average marks

Data is simulated internally for demonstration.

Q3. OOP – Bank Account

Class: BankAccount

Features:

Deposit & withdrawal handling with validations

Balance retrieval

Custom string representation

Q4. Algorithm – Two Sum

Function: two_sum(nums, target)

Returns indices of two numbers that sum to the target.

Q5. Algorithm – Group Anagrams

Function: groupAnagrams(strs)

Groups words that are anagrams of each other.

Part 2 – Mini Project: To-Do List Manager

A console-based To-Do List Manager that allows users to:

Add new tasks

View all tasks

Mark tasks as completed

Delete tasks

Exit the program

Features

Tasks are saved persistently in tasks.json

Each task has:

Unique ID

Description

Status (completed / pending)

User-friendly menu-driven interface.

Usage Example
python todo_manager.py


Sample Output:

To-Do List Manager
------------------
1. Add Task
2. View Tasks
3. Complete Task
4. Delete Task
5. Exit
------------------
Enter your choice:

How to Run

Clone or extract the project:

git clone <your_repo_link>
cd Python_Assignment


or unzip the provided file.

Run individual question files:

python q1_to_q5.py


Run the To-Do List Manager:

python todo_manager.py


Ensure tasks.json is in the same directory.
It will be created automatically if missing.

Requirements

Python 3.8+

No external libraries needed

Project Structure
Python_Assignment/
│
├── q1_to_q5.py              # Solutions to Part 1 (All Questions)
├── todo_manager.py          # Mini project (Part 2)
├── tasks.json               # Persistent storage file (auto-created)
├── README.md                # Project documentation
└── student_data.txt         # Example file for Q2 (optional)

