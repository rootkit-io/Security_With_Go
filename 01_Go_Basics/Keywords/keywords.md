# Keywords 

## Data Types

1. var : This defines a new variable.
2. const : This defines a constant value that does not change.
3. type : This defines a new data type.
4. struct : This defines a new structured data type that contains multiple varibles.
5. map : This defines a new map or hash variable.
6. interface : This defines a new interface.

---

## Functions

7. func : This defines a new function.
8. return : This exits a func, optionally returning values.

---

## Packages

9. import : This imports an external package in the current package.
10. package : This specifies what package a file belongs to.

---

## Program Flow

11. if : This is used for branch execution based on a condition that is true.
12. else : This is used for a branch if a condition is not true.
13. goto : This is used to jump directly to a label; it is rarely used and not
encouraged.

---

## Switch Statements

14. switch : This is used to branch based off of a condition.
15. case : This defines the condition for the switch statement.
16. default : This defines default execution when no case is matched.
17. fallthrough : This is used to continue executing the next case.

---

## Iteration

18. for : In Go, there is no while loop and the for keyword takes on the role of both for and while. A for loop can be used just like a while loop if one expression, the condition, is passed.
19. range : The range keyword is used with a for loop to iterate over a map or slice.
20. continue : The continue keyword will skip any execution left in the current loop and jump directly to the next iteration.
21. break : The break keyword will immediately exit the for loop completely, skipping any remaining iterations.

---

## Concurrency 

22. go : Goroutines are lightweight threads built in to the language. You simply put the go keyword in front of a call to a function and Go will execute that function call in a separate thread.
23. chan : To communicate between threads, channels are used. Channels are used to send and receive specific data types. They are blocking by default.
24. select : The select statements allow channels to be used in a nonblocking fashion.

---

## Convenience

25. defer : keyword is a relatively unique keyword that I have not
previously encountered in other languages. It allows you to
specify a function to be called later when the surrounding
function returns. It is useful when you want to ensure some type
of cleanup action whenever the current function ends, but you are
not sure when or where it might return. A common use case is to
defer a file closure.

