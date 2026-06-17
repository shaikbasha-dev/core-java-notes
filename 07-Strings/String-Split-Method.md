/*
## Headline
Java split() Method Example

## Definition
The split() method is used to break a string into parts using a specific delimiter. It returns an array of substrings.

## Java Program with comments on each step
*/

public class StringDemo5 {
    public static void main(String[] args) {
        // Step 1: Create a string that contains words separated by commas
        String text = "Java,Python,C,JavaScript";

        // Step 2: Use split() to divide the string by comma
        String[] words = text.split(",");

        // Step 3: Print the original string
        System.out.println("Original String: " + text);

        // Step 4: Print each part using loop
        System.out.println("Split parts:");
        for (int i = 0; i < words.length; i++) {
            System.out.println("Part " + i + ": " + words[i]);
        }
    }
}

/*
## Output
Original String: Java,Python,C,JavaScript
Split parts:
Part 0: Java
Part 1: Python
Part 2: C
Part 3: JavaScript

## Explanation
The split(",") method separates the string wherever a comma appears. Each separated piece is stored in an array.

## Pseudocode
START
    text = "Java,Python,C,JavaScript"
    words = text.split(",")
    print original string
    for each part in words
        print part
END

## Code Explanation
- split(",") breaks the string at every comma.
- The result is stored in a String array.
- A loop is used to print each part.

## Important Points
- split() needs a delimiter such as comma, space, or hyphen.
- The result is an array, so we use index values to access parts.
- If the delimiter is not found, the whole string is returned as one element.

## Summary
This program shows how to use the split() method to break a string into smaller parts.
*/
