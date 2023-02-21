// assign the lengths of the sides of the triangle to variables
const a = 5;
const b = 6;
const c = 7;

// calculate the semi-perimeter of the triangle
const s = (a + b + c) / 2;

// calculate the area of the triangle using Heron's formula
const area = Math.sqrt(s * (s - a) * (s - b) * (s - c));

// print the result to the console
console.log(`The area of the triangle is ${area}`);