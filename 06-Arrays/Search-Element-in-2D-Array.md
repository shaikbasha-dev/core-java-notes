/*
## Headline
Search an Element in a 2D Array

## Definition
This program checks whether a given integer is present in a 2D array or not.
It uses loops to scan every element of the array.

## Program to search an integer in a 2D array using Scanner
*/

import java.util.Scanner;

public class SearchElement {
    public static void main(String[] args) {
        // Step 1: Create Scanner object for input
        Scanner sc = new Scanner(System.in);

        // Step 2: Ask for number of rows
        System.out.println("Enter number of rows:");
        int rows = sc.nextInt();

        // Step 3: Ask for number of columns
        System.out.println("Enter number of columns:");
        int cols = sc.nextInt();

        // Step 4: Declare a 2D array
        int[][] arr = new int[rows][cols];

        // Step 5: Take input for the 2D array
        System.out.println("Enter array elements:");
        for (int i = 0; i < rows; i++) {
            for (int j = 0; j < cols; j++) {
                arr[i][j] = sc.nextInt();
            }
        }

        // Step 6: Ask the user for the value to search
        System.out.println("Enter the element to search:");
        int key = sc.nextInt();

        // Step 7: Search the element using loops
        boolean found = false;
        for (int i = 0; i < rows; i++) {
            for (int j = 0; j < cols; j++) {
                if (arr[i][j] == key) {
                    found = true;
                    break;
                }
            }
            if (found) {
                break;
            }
        }

        // Step 8: Display result
        if (found) {
            System.out.println("Element found in the 2D array.");
        } else {
            System.out.println("Element not found in the 2D array.");
        }

        // Step 9: Close the Scanner object
        sc.close();
    }
}

/*
## Output
Enter number of rows:
2
Enter number of columns:
3
Enter array elements:
1 2 3
4 5 6
Enter the element to search:
5
Element found in the 2D array.

## Pseudocode
START
    read rows
    read cols
    create 2D array arr[rows][cols]
    read elements of the array
    read key
    set found = false
    for each row
        for each column
            if arr[i][j] == key
                found = true
                stop loops
            end if
        end for
    end for
    if found
        print "Element found"
    else
        print "Element not found"
END

## Code Explanation
- Scanner is used to take input from the user.
- The nested loops check each element of the 2D array.
- If a match is found, the flag 'found' becomes true.
- The program prints the result based on the flag.

## Summary
This program checks whether a specified integer exists in a 2D array.
It uses nested loops and the Scanner class for user input.
*/
