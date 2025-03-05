// String Methods
let myString = "Hello, JavaScript!";

console.log("Original String:", myString);
console.log("Length:", myString.length);
console.log("Uppercase:", myString.toUpperCase());
console.log("Lowercase:", myString.toLowerCase());
console.log("Substring (0,5):", myString.substring(0, 5));
console.log("Index of 'JavaScript':", myString.indexOf("JavaScript"));
console.log("Replace 'JavaScript' with 'JS':", myString.replace("JavaScript", "JS"));
console.log("Split into array:", myString.split(" "));

// Array Methods
let myArray = ["Apple", "Banana", "Mango", "Orange"];

console.log("\nOriginal Array:", myArray);
console.log("Length of array:", myArray.length);
console.log("Push 'Grapes':", myArray.push("Grapes"), myArray);
console.log("Pop last element:", myArray.pop(), myArray);
console.log("Unshift 'Strawberry':", myArray.unshift("Strawberry"), myArray);
console.log("Shift first element:", myArray.shift(), myArray);
console.log("Join elements:", myArray.join(" - "));
console.log("Reverse array:", myArray.reverse());
console.log("Sort array:", myArray.sort());
console.log("Slice (1,3):", myArray.slice(1, 3));
console.log("Splice (remove 1 element at index 1):", myArray.splice(1, 1), myArray);
console.log("Check if includes 'Mango':", myArray.includes("Mango"));
console.log("Find element starting with 'O':", myArray.find(item => item.startsWith("O")));
