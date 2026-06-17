/*
## Headline
Jagged Array in Java

## Definition
A jagged array is an array of arrays where each row can have a different number of columns.
It is useful when each row has different sizes.

## Program to store student ages using hard coding in a jagged array
*/

public class JaggedArray {
    public static void main(String[] args) {
        // Step 1: Declare a jagged array for schools, classes, and student ages
        int[][][] ages = new int[2][][];

        // Step 2: Store the number of classes in each school
        ages[0] = new int[2][];
        ages[1] = new int[3][];

        // Step 3: Store the number of students in each class
        ages[0][0] = new int[2];
        ages[0][1] = new int[3];
        ages[1][0] = new int[2];
        ages[1][1] = new int[3];
        ages[1][2] = new int[4];

        // Step 4: Store ages manually for School 1, Class 1
        ages[0][0][0] = 14;
        ages[0][0][1] = 15;

        // Step 5: Store ages manually for School 1, Class 2
        ages[0][1][0] = 16;
        ages[0][1][1] = 17;
        ages[0][1][2] = 18;

        // Step 6: Store ages manually for School 2, Class 1
        ages[1][0][0] = 13;
        ages[1][0][1] = 14;

        // Step 7: Store ages manually for School 2, Class 2
        ages[1][1][0] = 15;
        ages[1][1][1] = 16;
        ages[1][1][2] = 17;

        // Step 8: Store ages manually for School 2, Class 3
        ages[1][2][0] = 18;
        ages[1][2][1] = 19;
        ages[1][2][2] = 20;
        ages[1][2][3] = 21;

        // Step 9: Display ages for School 1, Class 1
        System.out.println("School 1, Class 1 ages:");
        System.out.println(ages[0][0][0]);
        System.out.println(ages[0][0][1]);

        // Step 10: Display ages for School 1, Class 2
        System.out.println("School 1, Class 2 ages:");
        System.out.println(ages[0][1][0]);
        System.out.println(ages[0][1][1]);
        System.out.println(ages[0][1][2]);

        // Step 11: Display ages for School 2, Class 1
        System.out.println("School 2, Class 1 ages:");
        System.out.println(ages[1][0][0]);
        System.out.println(ages[1][0][1]);

        // Step 12: Display ages for School 2, Class 2
        System.out.println("School 2, Class 2 ages:");
        System.out.println(ages[1][1][0]);
        System.out.println(ages[1][1][1]);
        System.out.println(ages[1][1][2]);

        // Step 13: Display ages for School 2, Class 3
        System.out.println("School 2, Class 3 ages:");
        System.out.println(ages[1][2][0]);
        System.out.println(ages[1][2][1]);
        System.out.println(ages[1][2][2]);
        System.out.println(ages[1][2][3]);
    }
}

/*
## Output
School 1, Class 1 ages:
14
15
School 1, Class 2 ages:
16
17
18
School 2, Class 1 ages:
13
14
School 2, Class 2 ages:
15
16
17
School 2, Class 3 ages:
18
19
20
21

## Pseudocode
START
    declare ages[2][][]
    create 2 rows for school 1 and school 2
    create 2 columns for school 1 classes
    create 3 columns for school 2 classes
    store student ages manually
    display ages for each class
END

## Code Explanation
- int[][][] ages = new int[2][][]; creates a jagged array with 2 schools.
- Each school has a different number of classes.
- Each class can have a different number of students.
- The values are stored manually without loops.

## Summary
A jagged array is useful when each row contains a different number of elements.
This example stores student ages for different class sizes in a structured way.
*/
