Project: ES6 data manipulation
Author: Samuel Atiemo

Project Tasks:

0. Basic list of objects
mandatory
Create a function named getListStudents that returns an array of objects.

Each object should have three attributes: id (Number), firstName (String), and location (String).

1. More mapping
mandatory
Create a function getListStudentIds that returns an array of ids from a list of object.

This function is taking one argument which is an array of objects - and this array is the same format as getListStudents from the previous task.

2. Filter
mandatory
Create a function getStudentsByLocation that returns an array of objects who are located in a specific city.

It should accept a list of students (from getListStudents) and a city (string) as parameters.

3. Reduce
mandatory
Create a function getStudentIdsSum that returns the sum of all the student ids.

It should accept a list of students (from getListStudents) as a parameter.

4. Combine
mandatory
Create a function updateStudentGradeByCity that returns an array of students for a specific city with their new grade

It should accept a list of students (from getListStudents), a city (String), and newGrades (Array of “grade” objects) as parameters.

5. Typed Arrays
mandatory
Create a function named createInt8TypedArray that returns a new ArrayBuffer with an Int8 value at a specific position.

It should accept three arguments: length (Number), position (Number), and value (Number).

6. Set data structure
mandatory
Create a function named setFromArray that returns a Set from an array.

7. More set data structure
mandatory
Create a function named hasValuesFromArray that returns a boolean if all the elements in the array exist within the set.

8. Clean set
mandatory
Create a function named cleanSet that returns a string of all the set values that start with a specific string (startString).

It accepts two arguments: a set (Set) and a startString (String).

9. Map data structure
mandatory
Create a function named groceriesList that returns a map of groceries with the following items (name, quantity):

10. More map data structure
mandatory
Create a function named updateUniqueItems that returns an updated map for all items with initial quantity at 1.

It should accept a map as an argument. The map it accepts for argument is similar to the map you create in the previous task.

11. Weak link data structure
#advanced
Export a const instance of WeakMap and name it weakMap.
