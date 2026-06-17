/*
## Headline
While Loop in Java

## Definition
A while loop repeats a block of code as long as a given condition is true.

## Java Program with comments on each step
*/

public class WhileLoopDemo {
    public static void main(String[] args) {
        // Step 1: Initialize the loop variable
        int i = 1;

        // Step 2: Check the condition before each iteration
        while (i <= 5) {
            // Step 3: Print the current value of i
            System.out.println(i);

            // Step 4: Update the loop variable
            i++;
        }

        // Step 5: Message after the loop ends
        System.out.println("Loop finished.");
    }
}

/*
## Output
1
2
3
4
5
Loop finished.

## Explanation
The condition i <= 5 is checked before each iteration.
As long as it is true, the loop body runs and i increases by 1.

## Pseudocode
set i = 1
while i <= 5 do
    print i
    i = i + 1
end while

## Code Explanation
- int i = 1; starts the loop from 1.
- while (i <= 5) keeps repeating until i becomes 6.
- i++; increases the value after each iteration.

## Important Points
- while loop is used when the number of iterations is not fixed.
- The condition is checked before the loop body runs.
- If the condition is false at the start, the loop never runs.

## Summary
A while loop repeats code while a condition remains true.
*/
