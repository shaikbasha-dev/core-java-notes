/*
## Headline
Java String Methods with Simple Example

## Definition
A String in Java is a sequence of characters. Java provides many built-in methods to perform operations like finding length, searching characters, changing case, replacing text, and checking prefixes or suffixes.

## Java Program with comments on each step
*/

public class StringDemo4 {
    public static void main(String[] args) {
        // Step 1: Create a string value
        String text = "  Java Programming  ";

        // Step 2: Use length() to get the number of characters
        int len = text.length();
        System.out.println("Length: " + len);

        // Step 3: Use charAt(index) to get a character at a specific position
        System.out.println("Character at index 0: " + text.charAt(0));

        // Step 4: Use concat() to join two strings
        String result = text.concat(" Language");
        System.out.println("After concat: " + result);

        // Step 5: Use equals() to compare exact content
        System.out.println("Equals with '  Java Programming  ': " + text.equals("  Java Programming  "));

        // Step 6: Use equalsIgnoreCase() to compare ignoring case
        System.out.println("EqualsIgnoreCase with '  java programming  ': " + text.equalsIgnoreCase("  java programming  "));

        // Step 7: Use toUpperCase() and toLowerCase()
        System.out.println("Uppercase: " + text.toUpperCase());
        System.out.println("Lowercase: " + text.toLowerCase());

        // Step 8: Use trim() to remove spaces from both ends
        System.out.println("Trimmed: " + text.trim());

        // Step 9: Use substring() to get part of a string
        String sub = text.trim().substring(0, 4);
        System.out.println("Substring: " + sub);

        // Step 10: Use replace() to replace characters or words
        System.out.println("Replace 'a' with '@': " + text.replace('a', '@'));

        // Step 11: Use indexOf() and lastIndexOf()
        System.out.println("Index of 'a': " + text.indexOf('a'));
        System.out.println("Last index of 'a': " + text.lastIndexOf('a'));

        // Step 12: Use contains() to check if a word exists
        System.out.println("Contains 'Programming': " + text.contains("Programming"));

        // Step 13: Use startsWith() and endsWith()
        System.out.println("Starts with space: " + text.startsWith(" "));
        System.out.println("Ends with space: " + text.endsWith(" "));
    }
}

/*
## Output
Length: 18
Character at index 0: [space]
After concat:   Java Programming   Language
Equals with '  Java Programming  ': true
EqualsIgnoreCase with '  java programming  ': true
Uppercase:   JAVA PROGRAMMING  
Lowercase:   java programming  
Trimmed: Java Programming
Substring: Java
Replace 'a' with '@':   J@v@ Progr@mming  
Index of 'a': 1
Last index of 'a': 13
Contains 'Programming': true
Starts with space: true
Ends with space: true

## Explanation
The program creates a string with leading and trailing spaces. It then uses different String methods to check length, access characters, compare values, change case, trim spaces, search positions, replace characters, and check prefixes or suffixes.

## Pseudocode
START
    text = "  Java Programming  "
    len = text.length()
    print len
    print text.charAt(0)
    result = text.concat(" Language")
    print result
    print text.equals("  Java Programming  ")
    print text.equalsIgnoreCase("  java programming  ")
    print text.toUpperCase()
    print text.toLowerCase()
    print text.trim()
    print text.trim().substring(0, 4)
    print text.replace('a', '@')
    print text.indexOf('a')
    print text.lastIndexOf('a')
    print text.contains("Programming")
    print text.startsWith(" ")
    print text.endsWith(" ")
END

## Code Explanation
- length() returns the number of characters in the string.
- charAt(index) returns the character at a specific index.
- concat() joins two strings together.
- equals() compares exact content.
- equalsIgnoreCase() compares content without caring about uppercase/lowercase.
- toUpperCase() converts letters to uppercase.
- toLowerCase() converts letters to lowercase.
- trim() removes spaces from the beginning and end.
- substring() extracts a part of the string.
- replace() replaces one character or sequence with another.
- indexOf() finds the first occurrence of a character or substring.
- lastIndexOf() finds the last occurrence.
- contains() checks whether a string contains another string.
- startsWith() checks the beginning of a string.
- endsWith() checks the ending of a string.

## Important Points
- String methods do not change the original string unless the result is stored in a new variable.
- Some methods like trim() and substring() return a new string.
- Character positions start from 0.
- The output may look different if the spaces are not clearly visible.

## Summary
This program demonstrates the most commonly used String methods in Java with a simple example.
*/
