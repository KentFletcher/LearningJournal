# Intro to JavaScript
* Learning to program with JavaScript involves:
1. Understanding *basic programming concepts* and the terms that JavaScript use to describe them.
1. Learning •the language* itself and knowing the vocabulary and how to structure your sentences.
1. Becoming familiar with how *it is applied* by looking at examples of how it is commonly used in websites today.

* How JavaScript makes webpages more interactive:
1. **Access** Content- can use JS to select any element, attribute or text from and HTML page .
1. **Modify** Content- can use JS to add any element, attribute or text to the page, or remove them.
1. **Program** Rules- You can specify a set of steps to follow which allows it to change the content of the page.
1. **React** to Events- You can specify that a script should run when a specific event has occurred.  

* **Script**- is a series of instructions that a computer can follow to achieve a goal.  It is like writing a recipe or a manual, that allows a computer to solve a problem.
  * Scripts are made up of instructions a computer can follow step by step.
  * A browser may use different parts of the script depending on how the user interacts with the web page.
  * Scripts can run different sections of the code in response to the situation around them.

  * **To write a script you need to first state your goal and then list the tasks that you need to be completed in order to achieve it.**
  *  It is just a series of short instructions, each of which is performed to solve a problem at hand.  **A computer doesn't learn how to perform tasks, It needs to follow instructions *every time* it performs the task.**  Must give enough detail to perform the task as if every time was its first time.

* Start with the big picture of what you want to achieve, and then break that down to smaller tasks:
  1. Define the goal-
  1. Design the script-  *Flowcharts* Define tasks that need to be performed- then list the steps required for each task.  You can use the flowcharts to work out how the tasks fit together, shows the paths between each step.
  1. Code each step- Each step then needs to be written in a language a computer can understand, a code language
    * **Vocabulary**- words the computer will understand
    * **Syntax**- How to put words together to create instructions computers can follow.
*  **Programmatic** approach- to problem-solving.  Following a series of instructions, one after another.

* Flowchart- Generic step, Event, Input or output, and decision

* **Expressions**- evaluates into, results in, a single value.  2 Types:
  1. Expressions that just assign a value to a variable
  1. Expressions that use 2 or more values to return a single value

* **Operators**- allow programmers to create a single value from one or more values.
  * **Assignment operators**- (=) assign a value to a variable.
  * **Arithmetic operators**- perform basic math.
    1. addition (+)
    1. subtraction (-)
    1. division (/)
    1. multiplication (*)-
    1. increment (++)- adds one the current number
    1. decrement (--)- subtracts one from the current number
    1. modulus (%)- divides 2 values and returns the remainder
    - *Order of execution*- multiplication and division are performed before addition and subtraction.  This can affect the number you expect to see.  To account for this you can place the operations you want done 1st in ().
  * **String operators**- combine 2 strings. + is the only string operator.  *Concatenation* is the process of joining 2 or more string together.  Quotes around a number makes it a string, and so when concatenating you do not perform addition, you put the 1st string number 1st and the second string number second. Same goes for string numbers + text.  Any other arithmetic operators would return NoN "Not a Number".  Need a space at the end of the 1st string of words to allow for space on the return.
  * **Comparison operators**- compare 2 values and return true or false.
  * **logical operators**- combine expressions and return true and false.

# Functions-
* let you group a series of statements together to perform a specific task.  If different parts of the script repeat the same task, you can reuse the function (rather than repeating the same set of statements).
  * help to organize your code
  * help to store your the steps needed to achieve a task.
* If you are asking a function to perform the task later, you need to give it a name.  The name should describe its assigned task.  When asked to perform its task it is called **calling** the function.
* The steps that the function needs to perform to perform its task are packaged up in code block, or one or more statements contained within {}.  No need for ; after {}.
* SOme functions need to be provided with info in order to achieve a given task.  These pieces of info are **parameters**
* when you write a function and you expect it to provide you with an answer, the response is known as the **return value**

* Declaring a function:
![Parts of a Function](https://www.frontamentals.com/static/function-breakdown-e46e54ec2e0de641547f63411acb1d84-bf43a.png)
* Calling a function- look like: functionName();
* Declaring functions that need information- when you declare a function you give it **parameters**.  Inside of the function the parameters act like variables.
  * Ex. function getArea(width, height) /{
      return width * height;
  }
* Calling functions that need information- When you call a function that has parameters, you specify the values it should use in the () that follows its name.  The values are called **arguments**, and they can be provided as values or as variables.
  * Arguments as values- 
  * Arguments as variables-  
* Getting a single value out of a function-return information to the code that called them. Ex.- when they perform a calculation, they return the result.