# Task-Manager-gitTask
### The following program helps a business to manage tasks assigned to each member. It offers functionality like adding users, adding and viewing tasks.

### Please note that the following functionality has been coded into the program. Whenever there is user input required, the following scenarios are applicable:
### 1. If the user enters nothing or a string where a number is required:
### 2. The error is caught and the user is requested to enter correct data. 
### 3. This is accomplished either by a loop or try / except.
### 4. The user can enter -1 at any time to return to the main menu except at login and when already at the main menu.

### The following libraries are imported to increase functionality to the program.
### * import os
### * from datetime import datetime
### * import time

## FUNCTIONS 
### * Loop through the users list and check if the user inputs the username and corresponding password correctly. 
### * If the user does not enter a correct username or password, the user is notified and requested to retry.
### * If the user inputs 'r' the user can add a new user.
### * The user is requested to enter a username and password to add. The user must confirm the password.
### * If the passwords do not match the user is requested to retry. Only the admin is allowed to register users.
### * If the user inputs 'a' the user can add a new task.
### * The user is requested to input the various details and the task printed to the text file.
### * If the user inputs 'vm' all the tasks associated with that user is printed. 
### * The program checks and prints only information associated with the current logged in user.
### * The user is requested to choose a task number to edit.
### * After choosing a task number, the user can either mark the task as complete, or edit the username and due date.
### * If the user enters 'ds' and the user happens to be the "admin", various statistics are shown to the user on screen and the corresponding reports that are generated in text files.
### * In the event that the user inputs 'gr', then reports will be generated with statistics about the tasks and each user. The logged in user must be "admin" to access this function.
