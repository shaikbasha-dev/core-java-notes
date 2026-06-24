// EscapeSequences program demonstrating Java string escape sequences

public class EscapeSequences { // Define class named EscapeSequences
    public static void main(String[] args) { // Main method: program entry point
        System.out.println("Java\nPython"); // Print "Java" then newline, then "Python"
        System.out.println("Java\tPython"); // Print "Java" then tab, then "Python"
        System.out.println("Java\bPython"); // Print "Java", backspace removes previous char, then "Python"
        System.out.println("\"Java\" is a Programming Langauge"); // Print quoted Java in a sentence
        System.out.print("Java"); // Print "Java" without newline
        System.out.print("Python"); // Print "Python" on same line as previous text
    }
}

/* 
Output:
Java
Python
Java    Python
JavPython
"Java" is a Programming Langauge
JavaPython

Pseudocode
Start program
Print Java then newline then Python
Print Java then a tab then Python
Print Java then backspace then Python
Print the text "Java" is a Programming Langauge
Print Java without newline
Print Python on same line
End program

Code Explanation
public class EscapeSequences { ... }
Defines a Java class named EscapeSequences.
public static void main(String[] args) { ... }
Declares the main method, which is the entry point when the program runs.
System.out.println("Java\nPython");
Prints Java, then a newline, then Python.
System.out.println("Java\tPython");
Prints Java, then a tab space, then Python.
System.out.println("Java\bPython");
Prints Java, then a backspace, then Python; the backspace removes the character before it when displayed.
System.out.println("\"Java\" is a Programming Langauge");
Prints a string containing quotation marks around Java.
System.out.print("Java");
Prints Java without moving to the next line.
System.out.print("Python");
Prints Python directly after Java on the same line. 
*/
