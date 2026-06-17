/*
## Headline
If-Else Control Construct in Java

## Definition
The if-else statement is used to execute one block of code when a condition is true and another block when the condition is false.

## Java Program with comments on each step
*/

public class IfElseDemo {
    public static void main(String[] args) {
        // Step 1: Declare an integer variable
        int number = 10;

        // Step 2: Check the condition using if
        if (number % 2 == 0) {
            // Step 3: If condition is true, execute this block
            System.out.println("The number is even.");
        } else {
            // Step 4: If condition is false, execute this block
            System.out.println("The number is odd.");
        }

        // Step 5: This line runs after the if-else block
        System.out.println("Program finished.");
    }
}

/*
## Output
The number is even.
Program finished.

## Explanation
The condition number % 2 == 0 checks whether the number is divisible by 2.
Since 10 is divisible by 2, the condition is true, so the first block runs.

## Pseudocode
if number is even then
    print "The number is even."
else
    print "The number is odd."
end if

## Code Explanation
- int number = 10; stores the value to test.
- if (number % 2 == 0) checks whether the number is even.
- The else block handles the case when the condition is false.

## Important Points
- if-else is used for two possible paths.
- Only one of the two blocks executes.
- The condition must evaluate to true or false.

## Summary
The if-else statement helps the program choose between two actions.
*/
