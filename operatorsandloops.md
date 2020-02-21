# Operators
* Comparison Operators- Evaluate conditions. Generally return true or false.

* Logical Operators- Allow you to compare the results of more than one comparison operator.
  * \&& - Logical And- Tests more than one condition
  * \|| - Logical Or- Tests at least one condition
  * \! -  Logical Not- Returns true or false

* Loops- check a condition.  If it returns true, a code block will run.  Then the condition will be checked agin and if it still returns true, the code block will run again. It repeats until the condition returns false.
* Three common types of loops:
  * **For** - If you need to run code a specific number of times, use a **for** loop.  The condition is usually a counter which is used to tell how many times the loop should run. 
    * Loop Counters- Uses a counter as a condition, made up of 3 statements:
    1. Initialized- Create a variable and set it to 0. This variable is commonly i, and acts as the counter. EX. var i = 0;
    1. Condition - The loop should continue to run until the counter reaches a specified number.  Ex. i < 10;
    1. Update - Every time the loop has run the statements in the {}, it adds one to the counter.  Ex. i++
  * **While** - If you do not know how many times the code should run.  The condition can be something other than the counter, and the code will continue to loop for as long as the condition is true.
  * **Do While** - Similar to the while loop, but a key difference: it will always run the statements inside the curly brackets at least once, even if the condition evaluates to false.