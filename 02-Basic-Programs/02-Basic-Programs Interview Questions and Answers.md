# Interview-Questions-And-Answers

## Basic Programs Interview Questions and Answers

### Hello World

#### Q1. What is the simplest Java program?

Answer:
The simplest Java program is the Hello World program which prints a message on the console.

#### Q2. Which method is the entry point of a Java program?

Answer:
`public static void main(String[] args)`

#### Q3. What does System.out.println() do?

Answer:
It prints the specified text and moves the cursor to the next line.

#### Q4. Difference between print() and println()?

Answer:

* print() prints without a new line.
* println() prints and moves to the next line.

#### Q5. What is System in Java?

Answer:
System is a predefined class in the java.lang package.

#### Q6. What is out?

Answer:
out is a static object of PrintStream class.

#### Q7. Why is main() static?

Answer:
Because JVM calls it without creating an object.

#### Q8. What does void mean?

Answer:
The method does not return any value.

#### Q9. Why is String[] args used?

Answer:
It stores command line arguments.

#### Q10. Can we write public static void main(String args[])?

Answer:
Yes, both forms are valid.

---

### Sum Of Integers

#### Q11. How do you add two numbers in Java?

Answer:
Using the + operator.

Example:

int sum = a + b;

#### Q12. Which operator is used for addition?

Answer:
The + operator.

#### Q13. What is a variable?

Answer:
A named memory location used to store data.

#### Q14. What is initialization?

Answer:
Assigning a value to a variable.

Example:

int num = 10;

#### Q15. What is an integer?

Answer:
An integer is a whole number stored using int data type.

---

### Square Of Integer

#### Q16. How do you find the square of a number?

Answer:

number * number

Example:

int square = n * n;

#### Q17. Can Math.pow() be used to find square?

Answer:
Yes.

Example:

Math.pow(5,2)

#### Q18. What is the output of 5 * 5?

Answer:

25

---

### Even Odd Program

#### Q19. How do you check whether a number is even or odd?

Answer:

Using modulus operator.

Example:

number % 2 == 0

#### Q20. What does % operator do?

Answer:

It returns the remainder after division.

Example:

10 % 2 = 0

11 % 2 = 1

---

### Greatest Of Three Numbers

#### Q21. Which statement is used to find the greatest among three numbers?

Answer:

if else if ladder

#### Q22. Which operator is used for comparison?

Answer:

>

<

> =

<=

#### Q23. What does && mean?

Answer:

Logical AND operator.

It returns true only if both conditions are true.

---

### Escape Sequence

#### Q24. What is an escape sequence?

Answer:

Escape sequences are special characters beginning with backslash ().

Examples:

\n -> New Line

\t -> Tab

\b -> Backspace

" -> Double Quote

\ -> Backslash

#### Q25. What does \n do?

Answer:

Moves the cursor to the next line.

#### Q26. What does \t do?

Answer:

Creates horizontal tab space.

---

### String Concatenation

#### Q27. What is string concatenation?

Answer:

Joining two strings using + operator.

Example:

"Java" + "Programming"

Output:

JavaProgramming

#### Q28. What is the output?

System.out.println("Result: " + 20 + 30);

Answer:

Result: 2030

#### Q29. What is the output?

System.out.println("Result: " + (20 + 30));

Answer:

Result: 50

#### Q30. Why are parentheses used?

Answer:

To perform arithmetic operation before concatenation.

---

### Basic Calculator

#### Q31. Which operators are used in a calculator?

Answer:

* Addition

- Subtraction

* Multiplication

/ Division

% Modulus

#### Q32. What is integer division?

Answer:

Division between two integers returns an integer.

Example:

10 / 3 = 3

#### Q33. What is modulus operation?

Answer:

It returns the remainder.

Example:

10 % 3 = 1

---

### Scanner Questions

#### Q34. Which package contains Scanner?

Answer:

java.util.Scanner

#### Q35. How do you create Scanner object?

Answer:

Scanner sc = new Scanner(System.in);

#### Q36. Which method reads integer input?

Answer:

nextInt()

#### Q37. Which method reads String input?

Answer:

nextLine()

#### Q38. Why should Scanner be closed?

Answer:

To release system resources.

Example:

sc.close();

---

### General Questions

#### Q39. What is hard coding?

Answer:

Values are directly written in the program.

Example:

int a = 10;

#### Q40. What is soft coding?

Answer:

Values are taken from the user during runtime.

Example:

Scanner sc = new Scanner(System.in);

int a = sc.nextInt();

---

### Q41. Which programs are most frequently asked in interviews?

Answer:

* Hello World
* Even Odd
* Greatest Of Three Numbers
* Sum Of Integers
* Square Of Integer
* Calculator Program
* Palindrome
* Arrays
* Strings
