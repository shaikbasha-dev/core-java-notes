// CalculatorSC program performing a selected arithmetic operation on two user-input integers

import java.util.Scanner; // Import Scanner class for reading user input

public class CalculatorSC { // Define class named CalculatorSC
    public static void main(String[] args) { // Main method: program entry point
        Scanner sc = new Scanner(System.in); // Create Scanner to read from console
        System.out.print("Please enter first integer: "); // Prompt for first integer
        int num1  = sc.nextInt(); // Read first integer from user
        System.out.println(); // Print blank line
        System.out.print("Please enter second integer: "); // Prompt for second integer
        int num2  = sc.nextInt(); // Read second integer from user
        System.out.println(); // Print blank line
        System.out.println("1. Addition"); // Show option 1
        System.out.println("2. Subtraction"); // Show option 2
        System.out.println("3. Multiplication"); // Show option 3
        System.out.println("4. Division"); // Show option 4
        int add; // Declare variable for addition result
        int sub; // Declare variable for subtraction result
        int mul; // Declare variable for multiplication result
        int div; // Declare variable for division result
        System.out.println("Please enter your choice: "); // Prompt for operation choice
        int choose = sc.nextInt(); // Read the user's menu choice
        if(choose == 1) { // If user chooses addition
            add = num1+num2; // Calculate addition
            System.out.println("Addition Result: " + add); // Print addition result
        }
        else if(choose == 2) { // If user chooses subtraction
            sub = num1-num2; // Calculate subtraction
            System.out.println("Subtraction Result: " + sub); // Print subtraction result
        }
        else if(choose == 3) { // If user chooses multiplication
            mul = num1*num2; // Calculate multiplication
            System.out.println("Multiplication Result: " + mul); // Print multiplication result
        }
        else if(choose == 4) { // If user chooses division
            div = num1/num2; // Calculate integer division
            System.out.println("Division Result: " + div); // Print division result
        }
        else { // If user enters a choice outside 1-4
            System.out.println("Choose correct pin"); // Print invalid choice message
        }
        sc.close();
    }
}

/* 
Output:
Please enter first integer: 
Please enter second integer: 
1. Addition
2. Subtraction
3. Multiplication
4. Division
Please enter your choice: 
Addition Result: 15

Pseudocode
Start program
Import Scanner for input
Create Scanner object for console input
Prompt user for first integer
Read first integer into num1
Prompt user for second integer
Read second integer into num2
Display menu:
Addition
Subtraction
Multiplication
Division
Prompt user for choice
Read choice into choose
If choose == 1, compute add = num1 + num2 and print result
Else if choose == 2, compute sub = num1 - num2 and print result
Else if choose == 3, compute mul = num1 * num2 and print result
Else if choose == 4, compute div = num1 / num2 and print result
Else print "Choose correct pin"
End program

Code Explanation
import java.util.Scanner;
Imports the Scanner class so the program can read input from the user.
public class CalculatorSC { ... }
Declares the class CalculatorSC containing the calculator logic.
public static void main(String[] args) { ... }
Declares the main method where execution begins.
Scanner sc = new Scanner(System.in);
Creates a Scanner instance that reads from standard input (keyboard).
System.out.print("Please enter first integer: ");
Prompts the user to enter the first integer.
int num1 = sc.nextInt();
Reads the first integer value entered by the user.
System.out.print("Please enter second integer: ");
Prompts the user to enter the second integer.
int num2 = sc.nextInt();
Reads the second integer value entered by the user.
System.out.println("1. Addition"); ... System.out.println("4. Division");
Displays the operation menu options.
System.out.println("Please enter your choice: ");
Asks the user to choose an operation.
int choose = sc.nextInt();
Reads the chosen menu option.
if(choose == 1) { ... }
If the choice is 1, performs addition and prints the result.
else if(choose == 2) { ... }
If the choice is 2, performs subtraction and prints the result.
else if(choose == 3) { ... }
If the choice is 3, performs multiplication and prints the result.
else if(choose == 4) { ... }
If the choice is 4, performs integer division and prints the result.
else { ... }
If the choice is invalid, prints an error message.
 */
