/* 2. No return type, with argument

Definition
A method with no return type does not send back any value.
A method with arguments receives input values from the caller. */

public class Method2 {                           // class declaration
    public static void main(String[] args) {     // main method starts execution
        displayMessage("Java");                 // call displayMessage() and pass the value "Java"
    }                                            // end of main method

    public static void displayMessage(String name) { // method with no return type and one argument
        System.out.println("Hello " + name);     // print the message using the argument
    }                                            // end of displayMessage method
}                                                // end of class

/*
Output
Hello Java

Explanation
In this example, the displayMessage() method:
- takes one argument (String name)
- does not return any value because it uses void
- prints a message using the passed value

The main() method calls displayMessage("Java") to execute it.

Pseudocode
START
    call displayMessage("Java")
END

displayMessage(name)
    print "Hello " + name
END

Code Explanation
- public class Method2
  Declares the class.

- public static void main(String[] args)
  The starting point of the program.

- displayMessage("Java");
  Calls the method and passes the value.

- public static void displayMessage(String name)
  Defines a method that has no return type and one parameter.

- System.out.println("Hello " + name);
  Prints the message.

Additional Notes
- void means the method does not return a value.
- The argument passed to the method is used inside the method.
*/
