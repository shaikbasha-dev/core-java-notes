// EvenOdd program determining whether a user-input number is even or odd using conditional logic

import java.util.Scanner;

public class EvenOdd {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Please enter a number: ");
        int num = sc.nextInt();
        if(num%2==0) {
            System.out.println("Given number is a Even Number");
        }
        else {
            System.out.println("Given number is a Odd Number");
        }
        sc.close();
    }    
}

/* 
Output:
Please enter a number: 
5
Given number is a Odd Number

Please enter a number: 
4
Given number is a Even Number

Pseudocode
Start program
Create Scanner object for user input
Display prompt "Please enter a number: "
Read integer from user and store in num
If num divided by 2 has remainder 0 (check using num % 2 == 0):
Print "Given number is a Even Number"
Else:
Print "Given number is a Odd Number"
End program

Code Explanation
import java.util.Scanner;
Imports the Scanner class to enable reading user input from the console.
public class EvenOdd { ... }
Defines a class named EvenOdd that determines if a number is even or odd.
public static void main(String[] args) { ... }
Declares the main method, which is the entry point for the program.
Scanner sc = new Scanner(System.in);
Creates a Scanner object to read user input from the standard input stream.
System.out.println("Please enter a number: ");
Prints a message prompting the user to enter a number.
int num = sc.nextInt();
Reads the next integer entered by the user and stores it in the num variable.
if(num%2==0) { ... }
Checks if the remainder of num divided by 2 is equal to 0. If true, the number is even.
System.out.println("Given number is a Even Number");
Prints a message indicating the number is even.
else { ... }
Executes if the if condition is false (remainder is not 0).
System.out.println("Given number is a Odd Number");
Prints a message indicating the number is odd.
 */
