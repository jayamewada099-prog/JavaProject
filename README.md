Student Grade Management System
This is a simple Java console project built to practice Object‑Oriented Programming (OOP) concepts and exception handling.
The project allows a user to enter basic student details, validate marks, and calculate a grade based on the input.

It was created as a beginner‑friendly assignment after learning the fundamentals of classes, objects, constructors, encapsulation, and custom exceptions.

Features:
  -> Add a student's name, roll number, and marks.
  -> Validate marks using a custom exception.
  -> Calculate a grade based on the marks.
  -> Clean separation of logic using multiple classes
  -> Proper use of OOP concepts:
    -> Classes & objects
    -> Encapsulation (private fields + getters/setters)
    -> Constructors
    -> Simple method logic
  -> Basic exception handling:
    -> try / catch
    -> InputMismatchException
    -> Custom exception: InvalidMarksException
    
Project Structure:
    src/
     ├── Main.java
     ├── Student.java
     ├── GradeCalculator.java
     ├── InvalidMarksException.java
  1. Student.java :
     Stores student details and keeps fields private for encapsulation.
  
  2. InvalidMarksException.java :
     A custom exception used when the user enters marks outside the valid range (0–100).
  
  3. GradeCalculator.java :
     Contains the logic for grade calculation and throws the custom exception when needed.
  
  4. Main.java :
     Handles user input, displays results, and catches errors.

How to Run:
    1. Open a terminal
    The program only accepts input through the terminal, not the VS Code "Output" panel.
    
    2. Compile the files
    javac *.java
    3. Run the main program
    java Main
    Important:
    If you’re using VS Code, make sure the console is set to Integrated Terminal so the program can accept input.
    
        Example Interaction
        Enter Student Name: Alex
        Enter Roll Number: 12
        Enter Marks: 85
        
        --- Student Details ---
        Name: Alex
        Roll No: 12
        Marks: 85.0
        Grade: B
Screenshots:
<img width="691" height="521" alt="SS4" src="https://github.com/user-attachments/assets/5903b416-2606-4b49-96e9-d0724f4c1b97" />
<img width="359" height="861" alt="SS3" src="https://github.com/user-attachments/assets/5bd32358-45a4-4e5e-8ffd-8142ad6a1704" />
<img width="729" height="703" alt="SS2" src="https://github.com/user-attachments/assets/573b6229-a3f3-416c-94f5-9e17e41a78fd" />
<img width="681" height="758" alt="SS1" src="https://github.com/user-attachments/assets/dce80c30-049a-4070-8b09-075aa837d0e6" />


Why This Project Exists:
    The goal of the project is to build confidence with basic Java programming using only the topics recently covered in class—mainly OOP and exception handling.
    Everything is kept simple so the focus stays on good structure, clean code, and understanding the concepts rather than complexity.
