/*
## Headline
Java String intern() Method Example

## Definition
The intern() method returns the reference of the string from the string pool. It helps us reuse string objects that already exist in the pool.

## Java Program with comments on each step
*/

public class StringDemo7 {
    public static void main(String[] args) {
        // Step 1: Create two separate String objects with same content
        String s1 = new String("Java");
        // Step 2: Create another String object with same content
        String s2 = new String("Java");

        // Step 3: Print whether both references point to the same object
        System.out.println("s1 == s2: " + (s1 == s2));

        // Step 4: Call intern() to get the string from the string pool
        String s3 = s1.intern();
        // Step 5: Call intern() on the second string too
        String s4 = s2.intern();

        // Step 6: Check whether s1 and s3 still point to the same reference
        System.out.println("s1 == s3: " + (s1 == s3));
        // Step 7: Check whether s3 and s4 now refer to the same pooled object
        System.out.println("s3 == s4: " + (s3 == s4));

        // Step 8: Compare values of s1 and s2 using equals()
        System.out.println("s1.equals(s2): " + s1.equals(s2));
        // Step 9: Compare values of s3 and s4 using equals()
        System.out.println("s3.equals(s4): " + s3.equals(s4));
    }
}

/*
## Output
s1 == s2: false
s1 == s3: false
s3 == s4: true
s1.equals(s2): true
s3.equals(s4): true

## Explanation
s1 and s2 are created using new, so they point to different objects in heap memory.
After using intern(), both strings point to the same string pool object if the value already exists.

## Pseudocode
START
    s1 = new String("Java")
    s2 = new String("Java")
    print s1 == s2
    s3 = s1.intern()
    s4 = s2.intern()
    print s1 == s3
    print s3 == s4
    print s1.equals(s2)
    print s3.equals(s4)
END

## Code Explanation
- new String(...) creates a new object in heap memory.
- intern() checks the string pool and returns the pooled reference.
- == checks reference equality.
- equals() checks value equality.

## Important Points
- intern() is used to store a string in the string pool.
- It may return the same reference for strings with equal content.
- == compares references, while equals() compares content.

## Summary
This program shows how intern() can make two different string objects point to the same string pool object.
*/
