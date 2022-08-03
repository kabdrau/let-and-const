# let-and-const

var PI = 3.14;
PI = 42; // stop me from doing this!

const PI = 3.14;
PI = 42; // Error but this is what we need)

let PI = 3.14;
PI = 42; // OK but undesirable)

What is the difference between var and let?
var can reassign, redeclare and mutate, active within the function scope
let can reassign and mutate, can't redeclare, active within the block scope

What is the difference between var and const?
var can reassign, redeclare and mutate, active within the function scope
const can mutate, can't reassign and redeclare, active within the block scope

What is the difference between let and const?
let can reassign and mutate, can't redeclare, active within the block scope
const can mutate, can't reassign and redeclare, active within the block scope

What is hoisting?
When using var, you can access the variable name and it’s undefined value before it is declared and assigned value
In case of let and const it is impossible