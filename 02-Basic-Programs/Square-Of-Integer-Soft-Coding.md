// SquareOfIntegerSC program calculating the square of a user-input integer using Scanner

import java.util.Scanner; // Import the Scanner class from java.util package

public class SquareOfIntegerSC { // Define class named SquareOfIntegerSC
    public static void main(String[] args) { // Main method: entry point of the program
        Scanner sc = new Scanner(System.in); // Create Scanner object to read user input from console
        System.out.println("Please enter an Number"); // Print prompt message asking for number input
        int num = sc.nextInt(); // Read integer input from user and store in num variable
        int sq = num * num; // Multiply num by itself and store result in sq
        System.out.println("Square of Integer: " + sq); // Print label and calculated square value
        sc.close();
    } // End of main method
} // End of class SquareOfIntegerSC

/* 
Output:
Please enter an Number
8
Square of Integer: 64

Pseudocode
Start program
Import Scanner utility for user input
Create Scanner object to accept console input
Display prompt "Please enter an Number"
Read integer from user input and store in num
Compute sq = num * num
Print "Square of Integer: " followed by sq
End program

Code Explanation
import java.util.Scanner;
Imports the Scanner class from the java.util package to enable user input handling.
public class SquareOfIntegerSC { ... }
Defines a class named SquareOfIntegerSC that calculates the square of user-provided input.
public static void main(String[] args) { ... }
Declares the main method, which is the entry point for Java execution.
Scanner sc = new Scanner(System.in);
Creates a Scanner object to read user input from the console.
System.out.println("Please enter an Number");
Prints a prompt message asking the user to enter a number.
int num = sc.nextInt();
Reads the next integer value entered by the user and stores it in the num variable.
int sq = num * num;
Calculates the square by multiplying num by itself and stores the result in sq.
System.out.println("Square of Integer: " + sq);
Prints the label and the calculated square value on the console.

Difference Between Hard Coding and Soft Coding:

Hard Coding
Values are written directly into the source code.
Example: int num1 = 100;
Pros:
Simple and quick for small examples.
Cons:
Hard to change later.
Requires code edits and recompilation to update values.
Not flexible or reusable.

Soft Coding
Values are provided from outside the code at runtime.
Example: using Scanner sc = new Scanner(System.in); and int num = sc.nextInt();
Pros:
More flexible and user-friendly.
Can change behavior without modifying source code.
Easier to reuse and maintain.
Cons:
Slightly more complex to implement.
Requires input handling

Summary
Hard coding = fixed values inside code.
Soft coding = values come from users or external input.
Soft coding is better for programs that need flexibility and real-world use.
*/
