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
