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
