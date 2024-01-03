Project: ES6 Basics Author: Samuel Atiemo

Project Tasks:

Const or let? mandatory Modify
function taskFirst to instantiate variables using const function taskNext to instantiate variables using let

Block Scope mandatory Given what you’ve read about var and hoisting, modify the variables inside the function taskBlock so that the variables aren’t overwritten inside the conditional block.

Arrow functions mandatory Rewrite the following standard function to use ES6’s arrow syntax of the function add (it will be an anonymous function after)

Parameter defaults mandatory Condense the internals of the following function to 1 line - without changing the name of each function/variable.

Rest parameter syntax for functions mandatory Modify the following function to return the number of arguments passed to it using the rest parameter syntax

The wonders of spread syntax mandatory Using spread syntax, concatenate 2 arrays and each character of a string by modifying the function below. Your function body should be one line long.

Take advantage of template literals mandatory Rewrite the return statement to use a template literal so you can the substitute the variables you’ve defined.

Object property value shorthand syntax mandatory Notice how the keys and the variable names are the same?

Modify the following function’s budget object to simply use the keyname instead.

No need to create empty objects before adding in properties mandatory Rewrite the getBudgetForCurrentYear function to use ES6 computed property names on the budget object

ES6 method properties mandatory Rewrite getFullBudgetObject to use ES6 method properties in the fullBudget object

For...of Loops mandatory Rewrite the function appendToEachArrayValue to use ES6’s for...of operator. And don’t forget that var is not ES6-friendly.

Iterator mandatory Write a function named createEmployeesObject that will receive two arguments:

departmentName (String) employees (Array of Strings)

Let's create a report object mandatory Write a function named createReportObject whose parameter, employeesList, is the return value of the previous function createEmployeesObject.

Iterating through report objects #advanced Write a function named createIteratorObject, that will take into argument a report Object created with the previous function createReportObject.

This function will return an iterator to go through every employee in every department.

Iterate through object #advanced Finally, write a function named iterateThroughObject. The function’s parameter reportWithIterator is the return value from createIteratorObject.
