/*
## Headline
Do-While Loop in Java

## Definition
A do-while loop executes the loop body at least once before checking the condition.

## Java Program with comments on each step
*/

public class DoWhileLoopDemo {
    public static void main(String[] args) {
        // Step 1: Initialize the loop variable
        int i = 1;

        // Step 2: Execute the loop body first
        do {
            // Step 3: Print the current value of i
            System.out.println(i);

            // Step 4: Update the loop variable
            i++;

            // Step 5: Check the condition after each iteration
        } while (i <= 5);

        // Step 6: Message after the loop ends
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
The loop body runs once before checking the condition.
After each iteration, the condition i <= 5 is checked.

## Pseudocode
set i = 1
do
    print i
    i = i + 1
while i <= 5

## Code Explanation
- int i = 1; starts the loop from 1.
- do {...} while (i <= 5); ensures the body runs at least once.
- i++; increases the value after each iteration.

## Important Points
- do-while is useful when the loop must run at least once.
- The condition is checked after the loop body.
- It is different from while because it does not skip the first execution.

## Summary
A do-while loop guarantees at least one execution before checking the condition.
*/
