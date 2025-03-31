// let fruits = ["Apple", "Banana", "Orange"];
// console.log(fruits[0]); // Outputs "Apple"
// console.log(fruits[2]); 

// //PUSH:                          (add an elemnets in the end of the ARRAY )
// let numbers = [1, 2, 3];
// numbers.push(4);
// console.log(numbers); // Outputs [1, 2, 3, 4]

// //POP:       (REMOVES AN ELEMENT FROM THE END (LAST ELEMENT ) OF THE ARRAY)
// let number = [1, 2, 3];
// numbers.pop();
// console.log(number); // POP : Outputs [1, 2]

// //SHIFT:             (REMOVES AN ELEMENT FROM START (1ST ELEMENT) OF THE ARRAY)
// let fruit = ["Apple", "Banana", "Orange"];
// fruit.shift();
// console.log(fruit); // Outputs ["Banana", "Orange"]

// //UNSHIFT:   (REPLACES THE FIRST ELEMENT INT THE ARRAY)
// let fruites = ["Apple", "Banana", "Orange"];
// fruites.unshift("Strawberry");
// console.log(fruites); // Outputs ["Strawberry","Apple","Banana", "Orange"]

// //slice:  (RETURNS THE PART/PORTION OF AN ARRAY WITHOUT DISTURBING THE WHOLE ARRAY)
// let nos = [1, 2, 3, 4, 5];
// let sliced = numbers.slice(1, 3);
// console.log(sliced); // Outputs [2, 3]

// //splice:
// let num = [1, 2, 3, 4, 5];
// num.splice(2, 1); // Removes 1 element at index 2
// console.log(num); // Outputs [1, 2, 4, 5]

// //filter:
// let no = [1, 2, 3, 4, 5];
// let evenNumbers = no.filter(num => num % 2 === 0);
// console.log(evenNumbers); // Outputs [2, 4]

// let nums = [1, 2, 3, 4];
// let sum = nums.reduce((acc, curr) => acc + curr, 0);
// console.log(sum); // Outputs 10

//'for` loop:
// let fruits = ["Apple", "Banana", "Orange"];
// for (let i = 0; i < fruits.length; i++) {
// console.log(fruits[i]);
// }

//`forEach()`:
let fruits = ["Apple", "Banana", "Orange"];
fruits.forEach((fruit) => console.log(fruit));
