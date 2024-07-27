# Name-Hemant Baghel
# Company-CodeAlpha
# Student ID-CA/JL1/20299
# Domain-C++ Programming
# Duration- 15TH July TO 15TH August 2024
# Overview of the Project-
Project- C++ Program that act as a Login and Registration System
Objective- The objective of this project is to build a program that act as a Login and Registration System.The login And Registration System project in C++ involves mainly the user registration process. User Credentials like usernames and passwords are asked from the user. If the registration of the user is successful then with the given credentials a file will be created of a particular user in the database.
# Key Objectives-
Data Security:
The program stores passwords in plain text, which is not secure. Implementing password hashing and salting would make it more secure.

File Handling:
The code creates a separate file for each user, which could become cumbersome if the number of users grows. Using a database or a more structured file format could be more efficient.#

Error Handling:
The program does basic error handling (e.g., checking if files can be opened). Additional checks, such as ensuring unique usernames and handling incorrect file formats, could improve robustness.

User Experience:
The program could be enhanced with more user-friendly features, such as allowing users to reset their passwords or providing hints if login fails due to incorrect credentials.

Input Validation:
Ensuring that inputs (like usernames and passwords) are valid (e.g., no special characters, minimum length) would help prevent potential issues.

# Technologies Used:
1. C++ Programming Language:
The program is written in C++, a widely-used programming language known for its performance and flexibility.

2. Standard Library:
iostream: Used for standard input and output operations. The cin object is used to read user input, and cout is used to display messages to the user. fstream: Provides file stream classes (ifstream and ofstream) to handle file operations. ifstream is used for reading from files, while ofstream is used for writing to files. string: The program uses the string class from the standard library to handle text data, such as usernames and passwords.

3. File Handling:
The program uses file handling to store user credentials. Each user has a separate file named after their username (with a .txt extension). This file stores the username and password. File handling operations include opening, reading from, writing to, and closing files.

4. Basic Input/Output:
The program uses basic console I/O for interacting with the user, such as taking input for usernames and passwords and displaying messages for successful operations or errors.

5. Control Structures:
Conditional Statements: Used to check the success of file operations and validate user credentials. Switch Case: Used in the main menu to handle different user choices, such as registration or login.

6. Error Handling:
Basic error handling is implemented to check if files can be opened and if user credentials are valid.
# 
# Output for Registration-
![Screenshot (38)](https://github.com/user-attachments/assets/4dad75fe-1fd0-462b-b5f2-2c4452feda33)
# 
#  Output for Login-
![Screenshot (39)](https://github.com/user-attachments/assets/ec3a2e87-0846-4af0-b868-15f4dd34f728)
#
# Output for invalid login or password-
![Screenshot (40)](https://github.com/user-attachments/assets/fb8f5c5d-819d-4671-974b-2cbe97aa740f)










