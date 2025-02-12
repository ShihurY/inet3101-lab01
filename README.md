# INET 3101 Lab 1

## Code for INET 3101 Lab 1

### Who wrote the program (ensure all members are listed in the doc)
- Shihur Yang

### Program description paragraph
- Simple command-line menu for an Inventory Management System written in C.
- It has 7 menu options which are to show records, add/delete records, show database size, exit program, etc.

### Menu definition and usage
- Menu displays a list of options
- It reads user input and selects the desired menu option
- It will continue looping until the user chooses to exit

### Functions
- printRecords()
    - Input: None
    - Output: void
    - Description: Informs user that they had selected printRecords by printing "You have entered the Print all records function."

- addRecords()
    - Input: None
    - Output: void
    - Description: Collects user input with information about parts and prints each detail
 
- deleteRecord()
    - Input: None
    - Output: void
    - Description: Informs user that they had selected deleteRecord by printing "You have entered the Delete the last record function."
 
- printNumRecord()
    - Input: None
    - Output: void
    - Description: Informs user that they have selected printNumRecord by printing "You have entered the Print number of records function."
 
- printDataBaseSize()
    - Input: None
    - Output: void
    - Description: Informs user that they have selected printDataBaseSize by printing "You have entered the Print the size of the database function"
 
- printNumChanges()
    - Input: bool print
    - Output: void
    - Description: Tracks and prints the number of changes made to the database

- passValue()
  - Input: int mySelection
  - Output: void
  - Description: Prints the value passed to the function

- passAndReturn()
    - Input: int mySelection
    - Output: int
    - Description: Prints the value passed to the function and returns 7
 
- main()
  - Input: User Input
  - Output: int
  - Description: Displays a menu, processes user input, and calls the selected function

### Listing of files required and what type they are (.h header, .c c code, etc..)
- lab01.c
