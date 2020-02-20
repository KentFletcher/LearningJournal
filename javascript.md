#JAVASCRIPT
* JAVASCRIPT or \(JS) is the behavior layer, or interactive layer of a website.  It include buttons, dropdowns, media players, etc.
 It is added last and enhances the usbility of the page or the experience of interacting with the site.  The site can work even if the JS does not, where as  without HTML \(or the content) and CSS \(the presentation layer), your  site would not function.  The interaction between these 3 is called progressive *enhancement*.  
* **Script**- A series of instructions
* We created a conditional script, where if it was a certain time of the day it would greet you differently.  You place a link to your\.js file within your HTML code inside of a \<script> tag where you would like the interaction to take place. and you write a small line at the bottom of your JS.
 * A **Calling**- Ex. \document.write('Good Afternoon')- document is the *Object*, \. is the *member operator*, and Good Afternoon is the *parameters*, while \write(Good Afternoon) is the *Method*.
*WHen the browser comes across a \<script> element, it stops to load the sript and then checks to see if it needs to do anything.


## Chapter 2-
* **Statements**-  Each individual instruction or step of a script.  **Should end in a \;**
* **Comments**-  These should be written to explain what your code does.  
  * Multi-line comments- often to describe how the script works.  Start with \/* and end with the \*/ characters.
  * Single-line comments- short descriptions of what the code is doing, good for when you have to look back at a script. Anything after \// will be ignored.
* **Variables**- A script will have to temporarilly store the bits of information it nees to do its job, it store that data as variables.  Data stored within a variable will often change each time a script runs.  Result of a script  are said to be calculated using the data stored in variables.
 * Before you can use a variable you must declare the variable so you would say var quantity;, with quantity being the variable name or identifier..  var is a *keyword*.  That keyword now represents the var.  
 * Once you have created a var, you can tell it what info you would like it to store for you.  Programmers say you would **assign**, represented by \=, a value to the var.
   EX.  \quantity = 3; with quantity the var name, \= as the assignment operator, and 3 as the var value, then always end with \;
* **Data Types**-
  * Numeric
  * String- letters and other characters
  * Boolean- true or false
* Rules for naming a Variable:
  1. name must begin with a letter, dollar sign, or underscore.  It cannot start witha number
  1. can have letter, \$, \_.  Cannot have dash or period.
  1. cannot use keywords of reserved words.
  1. they are case sensitive
  1. need to describe the kind of info that is stores.
  1. if it is more than one word, use a capital letter for the start of every word
  