/*
## Headline
Switch Statement in Java

## Definition
The switch statement is used to select one block of code from many possible options based on the value of an expression.

## Java Program with comments on each step
*/

public class SwitchDemo {
    public static void main(String[] args) {
        // Step 1: Declare a variable for the day
        int day = 3;

        // Step 2: Use switch on the variable
        switch (day) {
            case 1:
                // Step 3: If day is 1
                System.out.println("Monday");
                break;
            case 2:
                // Step 4: If day is 2
                System.out.println("Tuesday");
                break;
            case 3:
                // Step 5: If day is 3
                System.out.println("Wednesday");
                break;
            default:
                // Step 6: If no case matches
                System.out.println("Invalid day");
        }

        // Step 7: This line runs after the switch
        System.out.println("Program finished.");
    }
}

/*
## Output
Wednesday
Program finished.

## Explanation
The switch checks the value of day.
Since day is 3, the program executes the case 3 block and prints Wednesday.

## Pseudocode
switch day
    case 1: print "Monday"
    case 2: print "Tuesday"
    case 3: print "Wednesday"
    default: print "Invalid day"
end switch

## Code Explanation
- int day = 3; stores the day number.
- switch (day) checks the value of day.
- break stops the switch after a matching case.

## Important Points
- switch is used for multiple choices.
- break is important to avoid running other cases.
- default handles values that do not match any case.

## Summary
The switch statement is used to make decisions from multiple possible values.
*/
