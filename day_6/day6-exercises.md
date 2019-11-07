1.  If we have a function defined as `function sayHello(){console.log("Hello!")}`, what is the difference between entering `sayHello` and `sayHello()` in the console?

`sayHello()` calls the function and would write out "Hello!" whereas `sayHello` would just print out the line of code showing what the function has been defined as.

2.  What is the difference between function parameters and arguments?

Arguments are the declared variables which act as the integers or other inputs in the function.  Parameters are the actual values (like specific integers) that are used in a function.  

3.  What is the keyword `return` used for?

The `return` keyword is used to return a value to the code that called the function.  So if a variable is defined as var area = width * height; then return area; would print width * height.

4.  How are local variables better than global variables? Are there instances you can think of where you might want to use a variable that is globally scoped over local?

Local variables are contained within the function where they are defined.  This keeps them separate and isolated so they only impact the function that is relevant to their values.  Maybe an appropriate globally scoped variable would be something like userName that would stay consistent throughout a user's entire experience on a website instead of needing to define the variable of the user's name within each function throughout the page.  
