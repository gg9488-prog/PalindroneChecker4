# PalindroneChecker4
 Running Procedure:
Follow these steps to compile and run the Palindrome Checker application:
 Using Command Prompt / Terminal
Save the file
Save the program as: PalindromeChecker3.java
Open Terminal / Command Prompt
Navigate to the folder where the file is saved:
cd <your-folder-path>
Compile the program
javac PalindromeChecker3.java
Run the program
java PalindromeChecker3
Provide input
Enter any string when prompted

Flow of Project

The workflow of the Palindrome Checker application follows a simple step-by-step process:

📌 Step-by-Step Flow
Start the Program
Execution begins from the main method.
Display Welcome Message
The system shows a message to inform the user about the application.
Accept User Input
The user enters a string using the keyboard.
Preprocess the Input
Remove all spaces from the string
Convert all characters to lowercase
Reverse the String
Use StringBuilder to reverse the processed string.
Compare Strings
Compare the cleaned string with the reversed string.
Display Result
If both are equal → Display "Palindrome"
Otherwise → Display "Not a Palindrome"
End the Program
Close resources and terminate execution.


Objective:
The objective of this project is to design and implement a Java-based application that checks whether a given string is a palindrome.
The system ignores spaces and letter case to ensure accurate validation.

Topics Covered:
This project covers the following important programming concepts:

🔹 Core Java Concepts
Basic structure of a Java program
main() method execution
Class and object fundamentals
🔹 Input Handling
Using Scanner class
Taking user input from console
🔹 String Handling
String methods (replaceAll(), toLowerCase())
Removing spaces from a string
String comparison using equals()
🔹 StringBuilder Class
Creating mutable strings
Reversing a string using reverse()
🔹 Conditional Statements
if-else decision making
Logical comparison
🔹 Regular Expressions
Using \\s+ to remove whitespace
🔹 Program Logic
Step-by-step problem solving
Algorithm implementation
🔹 Memory & Resource Management
Closing Scanner using scanner.close()
🔹 Output Formatting
Displaying formatted output using System.out.println()

Use Case:
The Palindrome Checker application can be used in the following scenarios:
🔹 Educational Purpose
Helps students understand string manipulation and logical conditions
Useful for lab exercises, assignments, and viva exams
🔹 Data Validation
Can be used to check whether user-entered data follows palindromic patterns
Useful in form validations and simple input checking systems
🔹 Text Processing Applications
Can be integrated into systems that analyze words, phrases, or sentences
Helps in identifying symmetric patterns in text
🔹 Game Development
Can be used in word games and puzzles
Example: palindrome-based quiz or challenge games
🔹 Interview Preparation
Common logic problem asked in coding interviews
Helps improve problem-solving skills
🔹 Extension Use Cases
Can be extended to:
Check numeric palindromes
Build GUI-based applications
Develop mobile apps