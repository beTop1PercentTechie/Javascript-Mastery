# Master JavaScript: An Interactive Learning Journey With Vishwa

**Elevate Your Skills with Comprehensive Tutorials, Quizzes, and Hands-On Exercises**

Unlock the potential to impress employers and tackle exciting projects with confidence.

## By the end of this course, you will:

**🎉 Master Complex Challenges**

Learn how to approach and solve complex coding challenges using JavaScript.

**❤️ Understand Best Practices**

Gain a clear understanding of why certain coding approaches are more effective than others.

**💻 Integrate APIs**

Become proficient in working with APIs and integrating them seamlessly into your JavaScript applications.

**☢️ Debug and Test Efficiently**

Implement best practices for debugging and testing your code to ensure optimal performance.

**🖖 Build Dynamic Web Apps**

Develop a deep understanding of how JavaScript interacts with HTML and CSS to create dynamic and responsive web applications.

**☀️ Stay Current with ES6**

Stay updated with the latest advancements in JavaScript, focusing on the ES6 standard.

## A Revolutionary Approach to Learning JavaScript

Build your JavaScript skills from the ground up by emphasizing practical, hands-on learning.

Starting from the basics, you'll progressively tackle more advanced concepts, all while engaging in bite-sized exercises directly in your browser.

**Interactive Course Highlights:**

🔥 100+ Interactive Exercises
Practice with hands-on exercises that provide immediate feedback to reinforce learning.

🔥 100+ Quiz Questions
Test your understanding and retention with a variety of quiz questions.

🔥 13 Comprehensive Cheatsheets
Utilize lesson-specific cheatsheets to review and solidify your knowledge.

All elements are meticulously designed to ensure you have the most effective and engaging learning experience.

**Start Your JavaScript Mastery Journey Today!**

## Data types in JS

### Arithmetic

**Q:Write a program to determine the area of a rectangle with a width of 6 and a height of 4, then print the result to the console.**

```js
const width = 6;
const height = 4;
const area = width * height;
console.log(`The area of the rectangle is: ${area}`);
```

### Fahrenheit to Celcius

**Q:Write a program that converts a temperature in Fahrenheit to Celsius. The conversion formula is:**

Celsius = (Fahrenheit - 32) \* 5 / 9

```js
const fahrenheit = 90;
const celsius = ((fahrenheit - 32) * 5) / 9;
console.log(celsius); //32.22
```

### Is Even

**Q:Write a program that checks if a number is even or odd and logs the result to the console.**

```js
const number = 4;

if (number % 2 === 0) {
  console.log(`${number} is even.`);
} else {
  console.log(`${number} is odd.`);
}
```

### Absolute Value

**write a program that calculates the absolute value of a number and then logs the result to the console?**

```js
const num = -6;
const absoluteValue = Math.abs(num);
console.log(absoluteValue);
```

### Access Nested Object

**Q:Given the following user object, please use dot notation to log the value of the "email" property to the console.**

```js
const user = {
  name: "Prabir",
  contact: {
    email: "prabir@gmail.com",
    phone: "123-456-7890",
  },
};
```

**Answer**

```js
const user = {
  name: "Prabir",
  contact: {
    email: "prabir@gmail.com",
    phone: "123-456-7890",
  },
};
console.log(user.contact.email);
```

### Add Method to Object

**Q:Please add a method named "calculateSum" . This method should take two parameters, "num1" and "num2", and return their sum.**

```js
const calculator = {
  calculateSum: function (num1, num2) {
    return num1 + num2;
  },
};
console.log(calculator.calculateSum(5, 4));
```

### Rectangle Area

Q:Create an object named `rectangle` with properties for `length` and `width`. Additionally, include a method named `area` within the object that computes and returns the rectangle's area (length multiplied by width).

```js
const rectangle = {
  length: 15,
  width: 4,
  area: function () {
    return this.length * this.width;
  },
};
console.log(rectangle.area());
```

### Add Element to Array

Given an array `animal`, append the string `Elephant` to its end using the push() method, and then print the resulting array to the console.

```js
const animal = ["Dog", "Cat", "Tiger", "Parrot"];
animal.push("Elephant");

console.log(animal); //[ 'Dog', 'Cat', 'Tiger', 'Parrot', 'Elephant' ]
```

### Remove the first element from the Array

Remove the First element using shift() method and then print the resulting array to the console.

```js
const animal = ["Dog", "Cat", "Tiger", "Parrot"];
animal.shift();

console.log(animal); //[ 'Cat', 'Tiger', 'Parrot' ]
```

### Filtering Arrays

Given an array 'numbers', use a filter to remove all numbers less than 10, and then print the filtered array to the console.

```js
const numbers = [1, 2, 3, 4, 5, , 23, 45, 34];

const filteredNum = numbers.filter((num) => num >= 10);

console.log(filteredNum); //[ 23, 45, 34 ]
```

### Find the Largest Number in an array

```js
const numbers = [1, 2, 3, 4, 5, 23, 45, 34];

const LargeNumb = Math.max(...numbers);

console.log(LargeNumb); //45
```

### Concatenate Arrays

```js
const array1 = [1, 2, 3];
const array2 = [4, 5, 6];
const concatenatedArray = array1.concat(array2);
console.log(concatenatedArray); //[ 1, 2, 3, 4, 5, 6 ]
```

### Reverse String

In this exercise, you'll reverse the letters of the given string str. To achieve this, first convert str into an array using the split() method, then reverse the array with the reverse() method, and finally, convert it back to a string using the join() method. Afterward, log the resulting string to the console.

```js
const str = "hello world";
const charArray = str.split("");
const reversedCharArray = charArray.reverse();
const reversedStr = reversedCharArray.join("");
console.log(reversedStr); //dlrow olleh
```

Given an array `arr` and an element `elem`, use the `indexOf()` method to find the index of the first occurrence of `elem` in the array, and log the index to the console.

```js
const arr = ["Dog", "Cat", "Tiger", "Parrot"];
const elem = "Cat";
const index = arr.indexOf(elem);
console.log(index); //1
```

## Datatype Cheatsheet

### Numbers

- In JavaScript, numbers can be whole numbers or decimals. To find out what type a number is, use the typeof keyword with the number you want to check. Here's an example:

```js
console.log(typeof 20); // Output: "number"
console.log(typeof 8.799); // Output: "number"
```

- To do simple math in JavaScript, you use symbols like + (plus), - (minus), \* (multiply), / (divide), and % (modulo). For example:

```js
console.log(5 + 4); //9
console.log(5 - 4); //1
console.log(5 * 6); //30
console.log(20 / 6); //3.33333
console.log(20 % 6); //2
```

You can also use JavaScript's built-in Math tool to do more complicated math tasks. For example:

```js
console.log(Math.random()); // Output: a random number between 0 and 1
console.log(Math.PI); // Output: 3.141592653589793
```

### String

- In JavaScript, strings are sequences of characters from any language and are enclosed in either single (' ') or double (" ") quotes. To find out how many characters are in a string, use the built-in length property.

```js
console.log("Prabir".length); // Output: 6
```

- To convert a string to uppercase, we use `toUppercase() method`

```js
console.log("prabir".toUpperCase()); // Output: "PRABIR"
```

- To concatenate strings, We use the + operator.

```js
console.log("Prabir" + " Kumar"); // Output: "Prabir kumar"
```

- You can also get specific characters from a string using the charAt() method in JavaScript.

```js
console.log("prabir".charAt(0)); // Output: "p"
```

### Booleans

- In JavaScript, booleans can be either true or false. You can check if a value is a boolean using the typeof keyword.

```js
console.log(typeof true); // Output: "boolean"
```

- You can also convert other data types to booleans using the Boolean() constructor.

```js
console.log(Boolean(0)); // Output: false
console.log(Boolean("Prabir")); // Output: true
```

### Falsy Values

When JavaScript needs a Boolean value, like in an if statement or a while loop, some values are automatically treated as false. These are called "falsy values".

The following are the falsy values:

- **false**: The boolean value false is obviously false.

- **0**: The number 0 is also considered false, whether it's an integer (whole number) or a float (decimal number).

- **null and undefined**: These represent absence of value and are considered false.

- **NaN**: Stands for Not-a-Number, occurs when you perform an invalid mathematical operation in JavaScript.

- **"" (empty string)**: A string with no characters inside it is also considered false because it has no meaningful value.

### Initializing objects with object literal syntax

Object literal syntax is a quick way to create an object in JavaScript by defining its properties and values inside curly braces. Here's how you do it:

```js
let newObj = {}; // create an empty object
newObj.key1 = "value1"; // add a key-value pair
newObj.key2 = "value2"; // add another key-value pair
```

Another way to create an object quickly in JavaScript is by directly defining its properties and values inside curly braces. Here's how you do it:

```js
let newObj = {
  key1: "value1",
  key2: "value2",
};
```

### Adding key-value pairs to an object

- To add a property and its value to an object in JavaScript, you can use either the dot notation or square bracket notation. Here's an example using the dot notation explained in simple terms:

```js
newObj.key3 = "value3"; // add another key-value pair using the dot notation
```

- Using Square bracket

```js
newObj["key4"] = "value4"; // add another key-value pair using the square bracket notation
```

### Creating an object using the new keyword

You can also create an object using the new keyword in JavaScript, but it's generally not recommended because it's more complex and verbose.

Here's an example explained in simpler terms:

```js
let newObj = new Object(); // create an object using the new keyword
newObj.key1 = "value1"; // add a key-value pair
```

### Accessing values in an object

To get a value from an object in JavaScript, you can use either the dot notation or square bracket notation.

Here's a simple explanation of how to do it using the dot notation:

```js
console.log(newObj.key1); // logs 'value1'
```

Here's an example using the square bracket notation:

```js
console.log(newObj["key1"]); //'value1'
```

### Using Nested objects

You can also put objects inside other objects, which is called nested objects. To get a value from a nested object, you can use either dot notation or square bracket notation to follow the chain of properties.

Here's an example explained simply:

```js
let myObject = {
  name: "Prabir",
  contact: {
    email: "prabir@gmail.com",
    phone: "9878-2345-45",
  },
};

console.log(myObject.contact.email); // prabir@gmail.com
console.log(myObject["contact"]["phone"]); // 9878-2345-45
```

### Constructor Function

Constructor functions are used to create objects in JavaScript by defining a function that serves as a blueprint for creating multiple instances of similar objects.

Lets take an example :

```js
function Person(name, age) {
  this.name = name;
  this.age = age;
}

// Creating an object using the constructor function
let person1 = new Person("Prabir", 30);
let person2 = new Person("Vishwa", 25);

console.log(person1); // Outputs: Person { name: 'Prabir', age: 30 }
console.log(person2); // Outputs: Person { name: 'Vishwa', age: 25 }
```

### Declaring Functions Inside Objects

We can declare a function inside a object to create method

```js
const myCalculator = {
  // Method to add two numbers
  addition: function (number1, number2) {
    return number1 + number2;
  },
  // Method to subtract two numbers
  subtraction: function (number1, number2) {
    return number1 - number2;
  },
};

// Using the calculator object
console.log(myCalculator.addition(2, 3)); // Output: 5
console.log(myCalculator.subtraction(5, 3)); // Output: 2
```

### `this` Keyword

In JavaScript, the this keyword refers to the object that is currently executing the function where this is used. It allows functions to access and operate on the object's properties and methods.

```js
let person = {
  firstName: "Prabir",
  lastName: "Kumar",
  fullName: function () {
    // 'this' refers to the 'person' object
    return this.firstName + " " + this.lastName;
  },
};

// Accessing object method using 'this'
console.log(person.fullName()); // Output: Prabir Kumar
```

### What is an Array ?

An array in JavaScript is a special type of object that is used to store multiple values within a single variable. It allows you to group values together under a single name .

#### Accessing elements in an array using indexing

- In JavaScript, arrays start counting their elements from zero. This means the first element in an array is at position 0, the second element is at position 1, and so on.
- To get a specific element from an array, you use square brackets with the index number of the element you want to access. For example, if you have an array named myArray and you want to get the second element, you would use myArray[1] (remember, arrays start counting from 0).

#### Finding the length of an array

In JavaScript, you can determine the number of elements in an array using the length property. It tells you how many items are in the array. For example, if you have an array named myArray, you can find its length with myArray.length.

#### Declaring an array

n JavaScript, you can declare an array in two ways. The first method is using array literal notation, represented by square brackets containing elements separated by commas.

For example:

```js
const arr = [3, 5, 7, 8, 9, 11];
```

the second way to declare an array is to use Array() constructor function.

for example:

```js
const arr = new Array(3, 5, 7, 8, 9, 11);
```

#### Adding and removing elements

- We can use push() method to add elements to the end of the array.

```js
const arr = [3, 5, 7, 8, 9, 11];
arr.push(14);
console.log(arr); //[3, 5, 7, 8, 9, 11,14]
```

- We can also remove the elements from an array using pop() method. The pop() method removes the last element from an array .

```js
const arr = [3, 5, 7, 8, 9, 11];
const lastElement = arr.pop();
console.log(lastElement); // Output: 11
console.log(arr); // Output: [3, 5, 7, 8, 9];
```

#### sorting Arrays

In JavaScript, you can arrange the elements of an array in order using the sort() method. It rearranges the elements directly within the array and gives back the sorted array. By default, sort() organizes elements alphabetically.

For example:

```js
const myArray = ["banana", "apple", "orange", "litchi", "guava"];
myArray.sort();
console.log(myArray); //[ 'apple', 'banana', 'guava', 'litchi', 'orange' ]
```

let's take another example

```js
const myArray = ["banana", "apple", "orange", "Litchi", "Guava"];
myArray.sort();
console.log(myArray); //[ 'Guava', 'Litchi', 'apple', 'banana', 'orange' ]
```

#### Slicing an array

We can extract a subarray from an existing array in JavaScript using the `slice()` method. This method requires two arguments: **the starting index and the ending index (exclusive).**

For example:

```js
const myArray = ["banana", "apple", "orange", "Litchi", "Guava"];

const slicedArray = myArray.slice(1, 4);

console.log(slicedArray); //[ 'apple', 'orange', 'Litchi' ]
```

#### Concatenating Arrays

We can use concat() method to concatenate two or more arrays

```js
const fruitsArray = ["Apple", "Banana", "Cherry"];
const moreFruits = ["Date", "Elderberry"];
const allFruits = fruitsArray.concat(moreFruits);
console.log(allFruits); // ["Apple", "Banana", "Cherry", "Date", "Elderberry"]
```

#### Joining array elements

We can convert an array into a string using the join method. This method accepts a separator as an argument.

For example:

```js
const colorsArray = ["red", "blue", "green", "yellow"];
const joinedColors = colorsArray.join(" - ");
console.log(joinedColors); // "red - blue - green - yellow"
```

#### Reversing Arrays

Another helpful method for arrays is `Array.prototype.reverse()`. This method changes the order of the elements in an array to be the opposite, which can be useful in some situations. For example:

```js
const letters = ["a", "b", "c", "d", "e"];
letters.reverse();
console.log(letters); // Output: ['e', 'd', 'c', 'b', 'a']
```

#### Using Arrays with object

A common use case for arrays and objects together is in creating dynamic user interfaces, such as those found in web applications. For example, suppose we have a web page that displays a list of products. Each product consists of several pieces of data, including the product name, manufacturer, price, and description. We can represent this data using an array of objects:

```js
const products = [
  {
    name: "Product 1",
    manufacturer: "Company A",
    price: 29.99,
    description: "This is the description for Product 1...",
  },
  {
    name: "Product 2",
    manufacturer: "Company B",
    price: 49.99,
    description: "This is the description for Product 2...",
  },
  {
    name: "Product 3",
    manufacturer: "Company C",
    price: 19.99,
    description: "This is the description for Product 3...",
  },
];
```

## Quiz

1. Which of the following is a primitive data type in JavaScript?

   A. Array

   B. Object

   C. String

   D. Function

Ans: String

2. How do you create an array in JavaScript?

   A. let arr = {};

   B. let arr = [];

   C. let arr = ();

   D. let arr = <>;

Answer: let arr = []

3. How can you add an element to the end of an array in JavaScript?

   A. arr.add(element);

   B. arr.push(element);

   C. arr.append(element);

   D. arr.insert(element);

Answer: arr.push(element);

4. How do you access the first element of an array named myArray?

   A. myArray[0]

   B. myArray[1]

   C. myArray.first()

   D. myArray.get(0)

Answer: myArray[0]

5. Which of the following methods is used to iterate over all properties of an object?

   A. for...of

   B. for...in

   C. forEach

   D. map

Answer: for...in

6. What will be the output of the following code?

   let obj = { a: 1, b: 2, c: 3 };

   console.log(Object.keys(obj));

   A. [a, b, c]

   B. ['a', 'b', 'c']

   C. [1, 2, 3]

   D. ['1', '2', '3']

Answer: ['a', 'b', 'c']

7. Which method is used to remove the last element from an array?

   A. shift()

   B. unshift()

   C. pop()

   D. splice()

Answer: pop()

8. What is the correct way to create an object in JavaScript?

   A. let obj = [];

   B. let obj = ();

   C. let obj = {};

   D. let obj = <>;

Answer: let obj = {};

9. How do you check the type of a variable in JavaScript?

   A. typeof variable

   B. type variable

   C. varType(variable)

   D. checkType(variable)

Answer: typeof variable

10. Which of the following will correctly merge two arrays arr1 and arr2?

    A. arr1.merge(arr2);

    B. arr1.concat(arr2);

    C. arr1.add(arr2);

    D. arr1.combine(arr2);

Answer: arr1.concat(arr2);

## Variables

### Is String or Number

Create a function called `isStringOrNumber` that accepts a parameter value and returns true if value is a string or a number, and false otherwise.

```js
  return typeof value === 'string' || typeof value === 'number';
}

console.log(isStringOrNumber("Prabir")); // true
console.log(isStringOrNumber(30)); // true
console.log(isStringOrNumber(true)); // false

```

## Variable Scope

Q:Create a function printNumbers that prints the numbers from 1 to a specified number n to the console. Also, print a variable callCount that keeps track of how many times the function has been called. The variable callCount should only be accessible inside the printNumbers function and should start at 0 every time the function is called.

```js
function printNumbers(n) {
  let callCount = 0;

  for (let i = 1; i <= n; i++) {
    // Loop to print numbers from 1 to n
    console.log(i);
  }

  callCount++; // Increment the call count
  console.log("Function call count: " + callCount); // Print the call count
}

printNumbers(5); // This will print numbers from 1 to 5 and the call count
```

## Last Minute Notes

### What are Variables?

A variable is a placeholder that holds data or information. In programming, variables are constantly used to store and manipulate data. JavaScript variables are particularly simple because you don't need to worry about types. You can assign variables in JavaScript the same way, regardless of the data type.

### Declaration and Assignment of Variables

#### Declaration

Declaration is the process of creating a variable. In JavaScript, you can declare a variable using var, let, or const.

```js
var myVariable;
let anotherVariable;
const fixedVariable;
```

#### Assignment

Assignment is the process of giving a value to a variable. You use the assignment operator `=` for this purpose.

```js
myVariable = 10;
anotherVariable = "Hello";
fixedVariable = 3.14; // Note: const variables must be assigned a value when they are declared.
```

### Declaration and Assignment Together

u can also declare and assign a variable in a single step.

```js
var myVariable = 10;
let anotherVariable = "Hello";
const fixedVariable = 3.14; // Required for const
```

In JavaScript, variables are dynamically typed, meaning the type of the variable can change based on the value assigned to it. For example:

```js
let myVariable = 10; // Initially a number
myVariable = "Now a string"; // Now it's a string
```

### Data Types in JavaScript Variables

JavaScript variables can store various types of data, including strings, numbers, arrays, and objects. Data types are not explicitly specified in JavaScript, and variables can contain any type of data.

Here are some examples:

#### Strings

```js
var myName = "Prabir";
```

#### Numbers

```js
var myFavNum = 07;
```

#### Booleans

A Boolean variable holds one of two values: true or false. You can use it to check if something is either "yes" or "no," like whether a user is logged in or a button is clicked.

```js
var isUserLoggedIn = true; // User is logged in
var isButtonClicked = false; // Button is not clicked
```

#### Arrays

An array is like a list that can hold different types of values, such as numbers, text, or even other arrays

```js
var myList = ["apple", 5, true];
console.log(myList); // Outputs: ["apple", 5, true]
```

#### Objects

Objects store data in a key-value format. Think of it like a dictionary: keys are the words, and values are their meanings.

```js
var person = {
  name: "Prabir",
  age: 30,
};
console.log(person.name); // Outputs: Prabir
console.log(person.age); // Outputs: 30
```

#### Null

Null means "empty" or "nothing." It is used when you want to say that a variable has no value on purpose.

```js
var emptyBox = null; // The box is empty
console.log(emptyBox); // Outputs: null
```

#### Undefined

Undefined means a variable exists but has not been given a value yet.

```js
var notAssigned;
console.log(notAssigned); // Outputs: undefined
notAssigned = "Now it has a value!";
console.log(notAssigned); // Outputs: Now it has a value!
```

### Reassignment and Coercion of Variables

You can change the value of a variable anytime, even to a different type like from a number to a string. JavaScript automatically converts (coerces) types if needed.

Ex:

```js
var age = 25; // A number
age = "Twenty-five"; // Now it's a string

var greeting = "Hi";
var number = 10;
console.log(greeting + number); // Outputs: Hi10 (number becomes part of the string)
```

### Variable Scope in JavaScript

#### Global Scope

A globally scoped variable is created outside of any function and can be used anywhere in your code.

```js
var globalMessage = "Hello, world!";

function showMessage() {
  console.log(globalMessage); // Accessible here
}

showMessage();
console.log(globalMessage); // Accessible here too
```

#### Local Scope

A locally scoped variable is created inside a function and can only be used within that function.

```js
function showLocalMessage() {
  var localMessage = "I exist only here";
  console.log(localMessage); // Works here
}

showLocalMessage();
// console.log(localMessage); // Error: localMessage is not defined
```

## Block Scope with let and const

With let and const, variables are limited to the block where they are defined, like inside {} braces.

Example (with let):

```js
function testBlockScope() {
  if (true) {
    let message = "Inside block";
    console.log(message); // Works here
  }
  // console.log(message); // Error: message is out of scope
}
testBlockScope();
```

Example (with const):

```js
const appName = "SuperApp";
console.log(appName); // Outputs: SuperApp
// appName = "AnotherApp"; // Error: Cannot reassign a const variable
```

## Mutating Data in const Variables

Even though const variables cannot be reassigned, you can change the content inside an object or array declared with const.

```js
const fruits = ["apple", "banana"];
fruits.push("orange"); // Adding a new fruit
console.log(fruits); // Outputs: ["apple", "banana", "orange"]

const user = { name: "Alice", age: 25 };
user.age = 26; // Changing the age
console.log(user); // Outputs: { name: "Alice", age: 26 }
```

## Naming Rules for Variables

Variable names can only use letters, numbers, \_ (underscore), or $ (dollar sign) but cannot start with a number or use reserved keywords.

Valid Examples:

```js
var userName = "Alice";
var _id = 101;
var $price = 50;
```

Invalid Examples:

```js
// var 1user = "John"; // Cannot start with a number
// var var = 10; // Cannot use reserved keywords
```

## Conditionals & Operators

1. Compare Three Numbers

Write a program to find the largest of three numbers.

```js
var num1 = 45,
  num2 = 89,
  num3 = 32;

if (num1 > num2 && num1 > num3) {
  console.log(num1 + " is the largest");
} else if (num2 > num3) {
  console.log(num2 + " is the largest");
} else {
  console.log(num3 + " is the largest");
}
```

2. Loan Eligibility Checker

Check if a person is eligible for a loan based on their age and income.

```js
var age = 28;
var income = 30000;

if (age >= 21 && age <= 60 && income >= 25000) {
  console.log("You are eligible for the loan.");
} else {
  console.log("You are not eligible for the loan.");
}
```

3. Leap Year Checker

   Check if a given year is a leap year or not.

```js
var year = 2024;

if ((year % 4 === 0 && year % 100 !== 0) || year % 400 === 0) {
  console.log(year + " is a leap year.");
} else {
  console.log(year + " is not a leap year.");
}
```

4. Grade Calculator

   Calculate a student's grade based on their marks.

```js
var marks = 85;

if (marks >= 90) {
  console.log("Grade: A+");
} else if (marks >= 80) {
  console.log("Grade: A");
} else if (marks >= 70) {
  console.log("Grade: B");
} else if (marks >= 60) {
  console.log("Grade: C");
} else {
  console.log("Grade: F");
}
```

5.  Even or Odd Checker

    Check if a number is even or odd.

```js
var number = 15;

if (number % 2 === 0) {
  console.log(number + " is even.");
} else {
  console.log(number + " is odd.");
}
```

6. Simple Calculator

Create a basic calculator for addition, subtraction, multiplication, and division.

```js
var num1 = 12,
  num2 = 4;
var operator = "*";

if (operator === "+") {
  console.log("Result: " + (num1 + num2));
} else if (operator === "-") {
  console.log("Result: " + (num1 - num2));
} else if (operator === "*") {
  console.log("Result: " + num1 * num2);
} else if (operator === "/") {
  console.log("Result: " + num1 / num2);
} else {
  console.log("Invalid operator");
}
```

7. Password Strength Checker

   Check if a password is strong based on length and character rules.

```js
var password = "Passw0rd123";

if (password.length >= 8 && /\d/.test(password) && /[A-Z]/.test(password)) {
  console.log("Strong password");
} else {
  console.log("Weak password");
}
```

8. FizzBuzz

Print numbers from 1 to 100. For multiples of 3, print "Fizz"; for multiples of 5, print "Buzz"; for multiples of both, print "FizzBuzz.

```js
for (var i = 1; i <= 100; i++) {
  if (i % 3 === 0 && i % 5 === 0) {
    console.log("FizzBuzz");
  } else if (i % 3 === 0) {
    console.log("Fizz");
  } else if (i % 5 === 0) {
    console.log("Buzz");
  } else {
    console.log(i);
  }
}
```

9. Positive, Negative, or Zero Checker

   Check if a number is positive, negative, or zero.

```js
var num = -10;

if (num > 0) {
  console.log(num + " is positive.");
} else if (num < 0) {
  console.log(num + " is negative.");
} else {
  console.log("The number is zero.");
}
```

10. Traffic Light System

Simulate a traffic light system using conditional statements.

```js
var light = "green";

if (light === "red") {
  console.log("Stop");
} else if (light === "yellow") {
  console.log("Get ready");
} else if (light === "green") {
  console.log("Go");
} else {
  console.log("Invalid light color");
}
```

## Last Minute Notes

1. What is a Conditional?

A conditional is a way to make decisions in your code. It allows your program to behave differently based on certain conditions or values.

2. The if Statement

The if statement checks a condition and runs the code inside its block only if the condition is true.

Syntax:

```js
if (condition) {
  // Code to run if condition is true
}
```

Example:

```js
const age = 18;
if (age >= 18) {
  console.log("You are an adult.");
}
```

If age is 18 or more, the message will appear. Otherwise, nothing happens.

3. Adding More Conditions with else and else if

- else: Runs code when the if condition is false.
- else if: Adds another condition to check.

Syntax:

```js
if (condition1) {
  // Code if condition1 is true
} else if (condition2) {
  // Code if condition2 is true
} else {
  // Code if none of the above is true
}
```

Example:

```js
const temperature = 30;

if (temperature > 35) {
  console.log("It's very hot!");
} else if (temperature > 25) {
  console.log("It's warm.");
} else {
  console.log("It's cold.");
}
```

4. Logical operators

   Logical operators let you combine multiple conditions:

   - AND (&&): True if all conditions are true.
   - OR (||): True if at least one condition is true.
   - NOT (!): Reverses the condition (true becomes false, and vice versa).

Examples:

```js
// AND (&&)
const hasMoney = true;
const isStoreOpen = true;
if (hasMoney && isStoreOpen) {
  console.log("You can buy something.");
}

// OR (||)
const hasCash = false;
const hasCreditCard = true;
if (hasCash || hasCreditCard) {
  console.log("You can still pay.");
}

// NOT (!)
const isWeekend = false;
if (!isWeekend) {
  console.log("It's a weekday.");
}
```

5. Comparison operator

This table summarizes the common comparison operators in JavaScript, along with their meanings, examples, and results:

| Operator | Meaning                       | Example   | Result |
| -------- | ----------------------------- | --------- | ------ |
| ==       | Equal (value only)            | 5 == "5"  | true   |
| ===      | Strictly equal (value + type) | 5 === "5" | false  |
| !=       | Not equal                     | 5 != "6"  | true   |
| !==      | Strictly not equal            | 5 !== "5" | true   |
| >        | Greater than                  | 5 > 3     | true   |
| <        | Less than                     | 3 < 5     | true   |
| >=       | Greater than or equal to      | 5 >= 5    | true   |
| <=       | Less than or equal to         | 5 <= 3    | false  |

6. Nested Conditionals

You can place an if inside another if to check multiple levels of conditions.

Examples:

```js
const balance = 100;
const itemPrice = 50;
const tax = 0.1;

if (balance >= itemPrice) {
  if (tax < 0.2) {
    console.log("Purchase successful!");
  } else {
    console.log("Tax is too high.");
  }
} else {
  console.log("Not enough balance.");
}
```

7. The switch Statement

The switch statement is a cleaner way to handle multiple cases.

Syntax:

```js
switch (expression) {
  case value1:
    // Code if expression matches value1
    break;
  case value2:
    // Code if expression matches value2
    break;
  default:
  // Code if no match is found
}
```

Example:

```js
const fruit = "apple";

switch (fruit) {
  case "apple":
    console.log("I love apples!");
    break;
  case "banana":
    console.log("Bananas are cool.");
    break;
  default:
    console.log("Unknown fruit.");
}
```

8. Key Differences: if-else vs switch

- Use if-else for complex conditions.
- Use switch for simple value matching.

Example with multiple cases in switch:

```js
switch (num) {
  case 1:
  case 2:
  case 3:
    console.log("Low range");
    break;
  case 4:
  case 5:
    console.log("Mid range");
    break;
  default:
    console.log("Out of range");
}
```

**Summary**

- Use if to run code based on a condition.
- Use else if and else for additional checks.
- Use &&, ||, and ! for combining conditions.
- Use comparison operators to compare values.
- Use switch for matching exact cases.

##
