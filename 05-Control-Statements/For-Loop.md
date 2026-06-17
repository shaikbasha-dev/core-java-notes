/*
## Headline
For Loop in Java

## Definition
A for loop is used to repeat a block of code a fixed number of times.

## Java Program with comments on each step
*/

public class ForLoopDemo {
    public static void main(String[] args) {
        // Step 1: Use a for loop to repeat from 1 to 5
        for (int i = 1; i <= 5; i++) {
            // Step 2: Print the current value of i
            System.out.println(i);
        }

        // Step 3: Message after the loop ends
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
The loop starts with i = 1.
It keeps running while i <= 5, and increases i by 1 each time.

## Pseudocode
for i = 1 to 5
    print i
end for

## Code Explanation
- for (int i = 1; i <= 5; i++) sets the starting value, condition, and update.
- System.out.println(i); prints the current value.
- The loop runs exactly 5 times.

## Important Points
- for loop is best when the number of iterations is known.
- The update part changes the loop variable.
- The condition must become false to stop the loop.

## Summary
A for loop is used when you want to repeat a task a fixed number of times.
*/
