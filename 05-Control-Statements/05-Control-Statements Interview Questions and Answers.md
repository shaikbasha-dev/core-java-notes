# Interview Questions and Answers

## Control Statements in Java

### Q1. What are control statements in Java?

Answer:
Control statements are used to control the flow of execution of a program.

They are mainly divided into:

1. Decision Making Statements
2. Looping Statements
3. Jump Statements

---

### Q2. What are decision making statements?

Answer:

Decision making statements are used to execute code based on conditions.

Examples:

* if
* if else
* else if ladder
* nested if
* switch

---

### Q3. What are looping statements?

Answer:

Looping statements are used to execute a block of code repeatedly.

Examples:

* for loop
* while loop
* do while loop

---

### Q4. What are jump statements?

Answer:

Jump statements are used to transfer control.

Examples:

* break
* continue

---

## if Statement

### Q5. What is an if statement?

Answer:

The if statement executes a block of code only when the condition is true.

Syntax:

```java id="v1m5h6"
if(condition){
   statements;
}
```

---

### Q6. What type of expression is used in if?

Answer:

Boolean expression.

Example:

```java id="u7a6d2"
if(age >= 18)
```

---

### Q7. What happens if the condition is false?

Answer:

The code inside the if block is skipped.

---

## if else Statement

### Q8. What is if else statement?

Answer:

It executes one block if the condition is true and another block if the condition is false.

Syntax:

```java id="6ztm9x"
if(condition){

}
else{

}
```

---

### Q9. When do we use if else?

Answer:

When there are exactly two possible outcomes.

Example:

Even or Odd

Pass or Fail

---

## else if Ladder

### Q10. What is else if ladder?

Answer:

It is used to check multiple conditions one by one.

Example:

```java id="r08e2h"
if()

else if()

else if()

else
```

---

### Q11. Does Java execute all else if conditions?

Answer:

No.

Once a condition becomes true, the remaining conditions are skipped.

---

### Q12. Which program commonly uses else if ladder?

Answer:

* Grade Calculation
* Greatest of Three Numbers
* Menu Driven Programs

---

## Nested if

### Q13. What is nested if?

Answer:

An if statement inside another if statement is called nested if.

Example:

```java id="yovpr0"
if(age>=18){

   if(weight>50){

   }

}
```

---

### Q14. When is nested if used?

Answer:

When one condition depends on another condition.

---

## Switch Statement

### Q15. What is switch statement?

Answer:

The switch statement selects one block of code among many options.

Syntax:

```java id="dxtq2f"
switch(expression){

case value:

break;

default:

}
```

---

### Q16. Which data types are allowed in switch?

Answer:

* byte
* short
* int
* char
* String
* enum

---

### Q17. What is default case?

Answer:

The default block executes when no case matches.

---

### Q18. Why is break used in switch?

Answer:

break stops execution of remaining cases.

---

### Q19. What happens if break is omitted?

Answer:

Control falls through to the next case.

This is called:

Fall Through

---

## for Loop

### Q20. What is for loop?

Answer:

A for loop repeats a block of code a fixed number of times.

Syntax:

```java id="yecf13"
for(initialization;
condition;
increment){

}
```

---

### Q21. Which parts are present in for loop?

Answer:

1. Initialization
2. Condition
3. Increment or Decrement

---

### Q22. When is for loop preferred?

Answer:

When the number of iterations is known.

---

## while Loop

### Q23. What is while loop?

Answer:

while loop executes repeatedly as long as the condition is true.

Syntax:

```java id="w4ft31"
while(condition){

}
```

---

### Q24. When is while loop preferred?

Answer:

When the number of iterations is not known in advance.

---

### Q25. Is condition checked before execution in while?

Answer:

Yes.

while is an entry controlled loop.

---

## do while Loop

### Q26. What is do while loop?

Answer:

do while executes the block first and checks the condition later.

Syntax:

```java id="6jz6wq"
do{

}while(condition);
```

---

### Q27. How many times does do while execute at minimum?

Answer:

At least one time.

---

### Q28. Why?

Answer:

Because the condition is checked after executing the loop body.

---

### Q29. Which is called entry controlled loop?

Answer:

* for loop
* while loop

---

### Q30. Which is called exit controlled loop?

Answer:

do while loop

---

## break Statement

### Q31. What is break statement?

Answer:

break immediately terminates the loop or switch statement.

---

### Q32. Where can break be used?

Answer:

* for loop
* while loop
* do while loop
* switch statement

---

### Q33. What is the use of break?

Answer:

To stop execution when a condition is satisfied.

---

## continue Statement

### Q34. What is continue statement?

Answer:

continue skips the current iteration and moves to the next iteration.

---

### Q35. Does continue stop the loop?

Answer:

No.

It only skips the current iteration.

---

### Q36. Difference between break and continue?

Answer:

break

* Terminates loop completely

continue

* Skips current iteration only

---

### Q37. Which is better for menu driven programs?

Answer:

switch statement.

---

### Q38. Which loop is most commonly used?

Answer:

for loop.

---

### Q39. Which loop executes at least once?

Answer:

do while loop.

---

### Q40. Which control statement topics are frequently asked in interviews?

Answer:

* if vs switch
* else if ladder
* Nested if
* for loop
* while loop
* do while loop
* break
* continue
* Entry controlled loop
* Exit controlled loop
