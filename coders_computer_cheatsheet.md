# Choosing a Text Editor
A *Text Editor* is a piece of software that you can download and install on your computer, or that can be accessed online through a web browser, which will allow you to write and manage text. Especially used for the text that you write in prder to build a website.  It is one of the most important tools of an aspiring web developer.  Need to find out what suits you the best.

**Features** to look for when selecting a text editor:
* code completion- saves time, and prevents possible mistakes.  Closes tags for you.
  * Emmet- a shorthand language for HTML and CSS, often included in Text Editors, but can also be added via and extension.  Will increase your speed of writing code.
* syntax highlighting- differentiates code via different colors.  Attributes, elements, copy, etc. will all vary in what colors they appear in. Allows for mistakes to be found easier and also make the text easier to read.
* a nice variety of themes- it will help to ease eye strain and fatigue.  
* ability to access a wide variety of extensions, when you need them-  the ability to make your writing code easier throught added features.  Like giving you super powers that you did not previously have.  Add functionality.

If coding in TextEditior-
* change settings so you are writing in plain text, no need for there added features
* create a folder on computer to store your entire website
* make sure when you save that your are assigning the proper extensions

3rd Party options:
* NotePad++- Free, for Windows only
* TextWrangler/ BB Edit- Mac only- 30 days free
* Visual Studio Code (VS Code)- made by Microsoft.  It has Emmet shorthand for HTML and CSS.
* Atom- Made by GitHub.
* Brackets- Made by Adobe.  Only supports HTML, CSS, and JavaScript.  
* Sublime Text-premium software.  fast and responsive 

Difference between Text Editors and IDEs:
_IDE_ (Integrated Development Environment)- is a suite of different software all coming together IDE is a text editor, file manager, compiler and debugger, all at once. while text editior is just for dealing with text.
____________________________________

# The Command Line!
Bash is what we are running.
- is a text based inerface for accessing the system.  You type in a command and feed back will be given back in a similar text.
-Within a termnal you have what is known as a _shell_.  Bash is a shell.
_ when commands are entered they are stored in the history and can be accessed later by using the arrow up key.

# Key commands:
_ when commands are entered they are stored in the history and can be accessed later by using the arrow up key.
* **pwd** which stands for Print Working Directory.  tells you what your current working directory is.
* **ls** short for list.  show listings of current location. Outline of its usage: \[options]\[location]You can also add to it with options within: 
  * **ls -l** would do a Long List.  **Need to add description of what the text insicates**
  * **ls /etc** would tell the ls not to list our current directory.  Instead lists the directories content.
  * **ls -l /etc** would indicate both a option and an argument were included.
  * **cd** stands for change directory.  If run without command it will always take you back to home directory.  Should add the location where you'd like to go, the location is a path.

**Root** directory is the top of the hierarchical structure of the directory, it is denoted by a single forward slash

* **Paths**. Referring to a file or a directory on the command line.  It is a means to get to a particular file or directory within the system.
  * Absolute- specify a location based on a location in relation to the root.
  * Relative- specify a location based on where we currentky are within the system.  Will not begin with a slash.
  * Can add more on Paths: ~ is a shortcut to home directory,  . is a reference to current directory, .. is reference to parent directory.
    --Can add paths with **Tab Completion**, when you begin to type a path just hit the tab key, if nothing happens just means there are multiple options if you hit again will show those.
    
    -----------------------------------
# Everything is a file

## Extensionless System
The terminal does not read any file extensions and just looks in the files to determine the type of file it is.  Command called **file** can help to figure this out. file\[path]

### Case Sensitive
Read Uppercase and lowercase just as they are.

#### Space in names- 
in file name is approptiate but in a command it is how you seperate items.  need to do the following to find files with a space in their name :
* Quotes '' around file name
* Escape Characters \ is and escape Character, use after first word

##### Hidden files and directories


 

    
