# PROG5121 POE Part 1 - QuickChat
Student Number: ST10505293
Student: Mbali Mazibuko
Module: PROG5121
Part 1: Registration and login feature

## What the program does
This is a console application. A user can create an account and then log in.
There is no GUI and no JOptionPane. Scanner is used for input.

## How to run
1. Open the project in NetBeans.
2. Right-click QuickChatApp.java.
3. Click Run File.
4. Choose 1 to register, 2 to login, 3 to exit.

## Demo data
First name: Kyle
Last name: Smith
Username: kyl_1
Password: Ch&&sec@ke99!
Cell number: +27838968976

## Validation rules
- Username must contain an underscore and be no more than 5 characters.
- Password must be at least 8 characters, with a capital letter, a number and a special character.
- Cell number must start with +27 and be 12 characters long.

## How to test
1. Right-click LoginTest.java.
2. Click Test File.
3. All tests should pass.

## Classes
- Login: checks username, password, cell number, registration and login.
- QuickChatApp: console menu.
- LoginTest: JUnit 4 unit tests using the official test data.
