/* 4. Return type, with argument

Definition
A method with a return type sends back a value to the caller.
A method with arguments receives input values from the caller. */

public class Method4 {                           // class declaration
    public static void main(String[] args) {     // main method starts execution
        int result = addNumbers(10, 20);         // call addNumbers() and store the returned value
        System.out.println(result);              // print the result
    }                                            // end of main method

    public static int addNumbers(int a, int b) { // method with return type int and two arguments
        int sum = a + b;                         // calculate sum of a and b
        return sum;                              // return the sum to the caller
    }                                            // end of addNumbers method
}                                                // end of class

/*
Output
30

Explanation
In this example, the addNumbers() method:
- has a return type int
- takes two arguments (a and b)
- calculates and returns the sum of the values

The main() method calls addNumbers(10, 20) and stores the result.

Pseudocode
START
    result = addNumbers(10, 20)
    print result
END

addNumbers(a, b)
    sum = a + b
    return sum
END

Code Explanation
- public class Method4
  Declares the class.

- public static void main(String[] args)
  The starting point of the program.

- int result = addNumbers(10, 20);
  Calls the method and stores the returned value.

- public static int addNumbers(int a, int b)
  Defines a method that returns an int and takes two parameters.

- return sum;
  Sends the calculated value back to the caller.

Additional Notes
- A method can take multiple arguments separated by commas.
- The return type should match the type of value being returned.
*/
