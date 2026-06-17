/*
## Headline
Three-Dimensional Array in Java

## Definition
A three-dimensional array is used to store data in three levels.
Here, it is used to store school, class, and student information.

## Program to store names of students in 2 schools, 2 classes, and 3 students using hard coding
*/

public class ThreeDArrayDemo {
    public static void main(String[] args) {
        // Step 1: Declare a 3D array for storing school, class, and student names
        String[][][] schoolData = new String[2][2][3];

        // Step 2: Store names of students in School 1
        schoolData[0][0][0] = "Aman";
        schoolData[0][0][1] = "Riya";
        schoolData[0][0][2] = "Karan";

        schoolData[0][1][0] = "Neha";
        schoolData[0][1][1] = "Rahul";
        schoolData[0][1][2] = "Meera";

        // Step 3: Store names of students in School 2
        schoolData[1][0][0] = "Arjun";
        schoolData[1][0][1] = "Sita";
        schoolData[1][0][2] = "Vikram";

        schoolData[1][1][0] = "Pooja";
        schoolData[1][1][1] = "Ankit";
        schoolData[1][1][2] = "Deepa";

        // Step 4: Display the stored names
        System.out.println("School 1, Class 1 students:");
        System.out.println(schoolData[0][0][0]);
        System.out.println(schoolData[0][0][1]);
        System.out.println(schoolData[0][0][2]);

        System.out.println("School 1, Class 2 students:");
        System.out.println(schoolData[0][1][0]);
        System.out.println(schoolData[0][1][1]);
        System.out.println(schoolData[0][1][2]);

        System.out.println("School 2, Class 1 students:");
        System.out.println(schoolData[1][0][0]);
        System.out.println(schoolData[1][0][1]);
        System.out.println(schoolData[1][0][2]);

        System.out.println("School 2, Class 2 students:");
        System.out.println(schoolData[1][1][0]);
        System.out.println(schoolData[1][1][1]);
        System.out.println(schoolData[1][1][2]);
    }
}

/*
## Output
School 1, Class 1 students:
Aman
Riya
Karan
School 1, Class 2 students:
Neha
Rahul
Meera
School 2, Class 1 students:
Arjun
Sita
Vikram
School 2, Class 2 students:
Pooja
Ankit
Deepa

## Pseudocode
START
    declare schoolData[2][2][3]
    store names in schoolData[0][0][0..2]
    store names in schoolData[0][1][0..2]
    store names in schoolData[1][0][0..2]
    store names in schoolData[1][1][0..2]
    print all stored names
END

## Code Explanation
- String[][][] schoolData = new String[2][2][3] creates a 3D array.
- First index = school number.
- Second index = class number.
- Third index = student number.
- Each value stores the name of a student.
- The program uses direct assignment and prints the values manually.

## Summary
A 3D array can store data in multiple layers.
In this example, it stores student names under school and class levels without using loops.
*/
