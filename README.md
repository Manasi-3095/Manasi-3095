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



//cretaing an object

let employee={
    name:"ram",
    age:38,
    gender:"Male",
    
};

console.log(employee.name);
console.log(employee["age"]);


//object methods or object as a functions
let person={
    name:"arun",
    greet:function(){
        console.log("hii "+this.name);
    } ,
};
person.greet();


//modifying or updating object and its elments
person.age=35;
console.log(person);

console.log(employee);
employee.department="finance";
console.log(employee);
delete employee.gender;
console.log(employee);


//. Iterating Over Objects
 for(let key in employee){
    console.log(key +" : "+ employee[key]);
 }
 

//'for` loop:
// let fruits = ["Apple", "Banana", "Orange"];
// for (let i = 0; i < fruits.length; i++) {
// console.log(fruits[i]);
// }

//`forEach()`:
let fruits = ["Apple", "Banana", "Orange"];
fruits.forEach((fruit) => console.log(fruit));







assignment

let Array=[];
function printArray(){
    console.log(Array);
}

function push(){
    let value1=parseInt(prompt("enter no. to perform push operation in array"));
    Array.push(value1);
    console.log("value pushed ");
}

function pop(){
    Array.pop();
    console.log("value popped ");
}

function unshift(){
    let value3=parseInt(prompt("enter no. to perform shift operation in array"));
    Array.push(value3);
    console.log("value unshifted ");
}

function shift(){
    Array.shift();
    console.log("value shifted");
}

function slice(){
    let value1=parseInt(prompt("enter first index no.to perform slice operation in array"));
    let value2=parseInt(prompt("enter first index no.to perform slice operation in array"));
    Array.slice(value1, value2);
    console.log("value slice");
}

function splice(){
    let value1=parseInt(prompt("enter first index no.to perform splice operation in array"));
    let value2=parseInt(prompt("enter first index no.to perform splice operation in array"));
    Array.splice(value1, value2);
    console.log("value splice");
}

let value=true;
while(value){
    let operation=prompt("Enter any one array operation from give list : push.pop.unshift,shift and to exit type endloop")

if(operation==="push"){
    push();
    printArray();
}
else if(operation==="pop"){
    pop();
    printArray();
}
else if(operation==="unshift"){
    unshift();
    printArray();
}
else if(operation==="shift"){
    shift();
    printArray();
}
else if(operation==="endloop"){
    value=false;
}

}

