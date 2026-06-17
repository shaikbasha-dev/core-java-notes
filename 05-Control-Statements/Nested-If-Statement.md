/*
## Headline
Nested If in Java

## Definition
A nested if is an if statement inside another if statement.
It is used when one condition depends on another condition.

## Java Program with comments on each step
*/

public class NestedIf {
    public static void main(String[] args) {
        // Step 1: Declare variables
        int age = 20;
        int weight = 55;

        // Step 2: Outer if condition
        if (age >= 18) {
            // Step 3: Inner if condition
            if (weight > 50) {
                // Step 4: Execute when both conditions are true
                System.out.println("You are eligible for the gym.");
            }
        }

        // Step 5: This line runs after the nested if block
        System.out.println("Program finished.");
    }
}

/*
## Output
You are eligible for the gym.
Program finished.

## Explanation
First, the outer condition age >= 18 is checked.
If it is true, then the inner condition weight > 50 is checked.
Because both are true, the message is printed.

## Pseudocode
if age >= 18 then
    if weight > 50 then
        print "You are eligible for the gym."
    end if
end if

## Code Explanation
- int age = 20; stores the age.
- int weight = 55; stores the weight.
- The outer if checks the first condition.
- The inner if checks another condition only when the outer condition is true.

## Important Points
- A nested if is an if inside another if.
- The inner if runs only if the outer if is true.
- It is useful for checking multiple related conditions.

## Summary
Nested if statements help in making decisions based on more than one condition.
*/
