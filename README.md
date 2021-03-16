# Statements-and-Expression
JavaScript Statement
JavaScript statement consist of a list of instructions to be run to be browser, they are made up of Values, Expressions, Operators, Keywords and Comments, and they are separated by the Semicolon (;).
JavaScript statements often start with a statement identifier to identify the JavaScript action to be performed, and these statement identifiers are reserved words and cannot be used as variable names. 
Example of a JavaScript statement:
if CONDITION: Marks a block of statements to be executed depending on a condition
else if CONDITION: Marks a block of statements to be executed depending on a condition
JavaScript Expression
JavaScript expression are valid set of codes that can be resolved to a single value. The value may be a number or a string.
JavaScript has the following expressions:
Arithmetic:  Evaluates to a number. For example: 7,20.
String: Evaluates to a character string. For example: “Emmanuel”, “900”.
Logical: Evaluates to either true or false (Boolean).

Example of Expression
True
False
45
2.5


Difference between Statement and Expression
All expressions are statements, but statements are not expression. Statements cannot be assigned to a variable, they are semantic elements that serve a purpose, meaning that they can’t evaluate to anything. 
For example, x= if CONDITION;
The above wont work.  


Explain JavaScript functions in your own words
A JavaScript function allows you to create a block of code, give it a name and run it as many times as you want.
In JavaScript function can be defined using the keyword function.
Example of defining a code of block:
Function  displayMessage() {
alert(“Welcome”)
}
displayMessage();

In the above example, we have defined a function named displayMessage that displays a popup message "Welcome!". This function can be execute using () operator e.g. displayMessage().







Difference Between Function Argument and Parameter with Example

Function parameters are the names listed in the function definition, while Function arguments are the real values passed to (and received by) the function.


Example of a Function Parameter:

function squareOfNumber (number) {
  return number * number;
}

Example of a Function Argument:

squareOfNumber(8,8)




Explain Concatenation with Example

In JavaScript we can assign strings to a variable and use concatenation to add the assigned variable to another string.

In order to concatenate a string, you need the plus sign (+) between the string or the string variable you want to connect together


Example
let name = 'kehinde'
 let age = 100
 console.log ('My name is '+ name + ' I am a '+ age+ 'years old today!' )

Above I created two variables name and age and assigned them to values ‘Kehinde’ and 100, then I concacated using the + sign. The result is “My name is Kehinde I am a 100 years old today!.



                    In a markdown file, explain JavaScript DOM

DOM (Document Object Model) is created by the browser when a web page is loaded. In graphical form, it looks like a tree of elements/nodes which represents every single element on your page.
JavaScript Document Object Model interaction allows for change/Remove HTML in the DOM, create new HTML elements and insert them into the DOM, change and add CSS styles to elements. 
