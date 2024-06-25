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
