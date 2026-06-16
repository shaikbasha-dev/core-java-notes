// SquareOfInteger program calculating the square of an integer

public class SquareOfInteger { // Define class named SquareOfInteger
    public static void main(String[] args) { // Main method: entry point of the program
        int num = 8; // Declare integer variable num and assign 8
        int sq = num * num; // Multiply num by itself and store result in sq
        System.out.println("Square of Integer: " + sq); // Print label and square value
    } // End of main method
} // End of class SquareOfInteger

/* 
Output
Square of Integer: 64

Pseudocode
Start program
Set num to 8
Compute sq = num * num
Print "Square of Integer: " followed by sq
End program

Code Explanation
public class SquareOfInteger { ... }
Defines a class named SquareOfInteger that calculates the square of a number.
public static void main(String[] args) { ... }
Declares the main method, which is the entry point for Java execution.
int num = 8;
Creates an integer variable num and assigns it the value 8.
int sq = num * num;
Multiplies num by itself and stores the result 64 in the variable sq.
System.out.println("Square of Integer: " + sq);
Prints a message combining the label and the calculated square value, then moves to a new line.
 */
