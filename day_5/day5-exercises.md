1.  How do you declare a variable. What does the equals sign really mean in JavaScript? What is it called in JavaScript?

The command var is used to declare a variable.  For example "var variable;"  Once the variable is declared you can set the value of variable with variable = 3; An equals sign sets the value for the variable to represent for the script.  In JavaScript it's called an Assignment Operator.


2.  There are three big data types in JavaScript: numbers, strings, and booleans. Describe what each of them are.

Numeric: Identified by just a number without quotes.  Used to calculate sums.  
String: Letters numbers and symbols contained in " "s to indicate text.  
Boolean: A true or false statement (no quotes) that indicates whether something is basically on or off.


3.  What are the six rules for naming variables? What are a few JavaScript reserved words that you should avoid using for variable names?

1. The name must begin with a letter, dollar sign, or an underscore.  Must not start with a number.
2. The name can contain letters, numbers, dollar sign, or an underscore. No dashes or periods.
3. You cannot use **keywords** or **reserved** words.  Keywords are special words that tell the interpreter to do something.  For example, **var** is a keyword used to declare a variable.  Reserved words are ones that may be used in a future version of JavaScript.
4. All variables are case sensitive.
5. Use a name that describes the kind of information that the variable stores.  
6. If your variable name is made up of more than one word, use a camelCase to define it.  


4.  How can an array be useful when dealing with multiple related values? How do you access/change a value in an array?

An array doesn't have to know how many values will be in it, so if using multiple related values it can save time by not having to define multiple variables.  To access or change the values in an array you use an integer that is equal to the position of the variable on the list.  Starting with 0 as the first item then 1 and so on.  To change the value you can write variable[2] /(3rd list item)/ = "new array value";.


5.  What is the difference between an expression and a statement?  

Each individual instruction in JS is known as a statement where Expressions specifically result in a single value.



6.  What are three types of operators and how are they used?

Assignment operators assign a value to a variable.
var = "variable";

Arithmetic operators perform basic math (+ - * / % -- ++)

String operators combine strings together
hello = "Hey there, " + "how's it going?";
