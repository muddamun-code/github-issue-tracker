1. Difference between var, let and const

 ans : 
var is the old way to declare variables in JavaScript. It can be redeclared and updated.
let is a newer way and it cannot be redeclared in the same scope but it can be updated.
const is used when we do not want to change the value of the variable. Once assigned, it cannot be updated.


2. Spread operator (...)

The spread operator is used to expand elements from an array or object. It helps copy or merge data easily.

Example:

let arr1=[1,2]
let arr2=[...arr1,3,4]