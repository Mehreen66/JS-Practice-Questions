# JS-Practice-Questions
 1. Write a code to check difference between null and undefined data type. Also check their type using typeof

     In JavaScript, both null and undefined represent the absence of a value, but they are distinct data types.
 
     ```
     let x;           // variable declared but not initialized
     console.log(x);  // Output: undefined

    let y = null;    // variable intentionally set to null
    console.log(y);  // Output: null 
     ```
    <H3>Type of null and undefined</H3>
    
     ```
     let nullValue = null;
     let undefinedValue;
     
     console.log("Type of nullValue:", typeof nullValue);
     console.log("Type of undefinedValue:", typeof undefinedValue);
     ```
     <H3>Output</H3>
     Type of nullValue: object
     
     Type of undefinedValue: undefined

2. Guess the Output and Explain Why?
    ```
     let languages = 'java javaScript python cSharp';
     
     let result = languages.lastIndexOf('S');
     
     console.log(result);
    ```
    <H3>Output</H3>
    24
    
    The lastIndexOf method in JavaScript is used to find the index of the last occurrence of a specified value within a string. In this code the last occurence of S is in last word 
    CSharp and the index of S is 24.

3. Guess the Output and Explain Why?
    ```

      let variable = 'hello programmers';
      
      let result = Number(variable);
      
      console.log(result);
     ```
    <H3>Output</H3>
    NaN

    The Number() function in JavaScript is used to convert a value to a number. In this case, the variable variable contains the string 'hello programmers'. Converting this string to a      number using Number(), it will result in NaN because the entire string cannot be interpreted as a valid number.

4.  Guess the Output and Explain Why?

```
    let num1 = 32;
    
    let num2 = '32';
    
    let result1 = num1 !== num2;
    
    let result2 = num1 != num2;
    
    console.log(result1, result2);
```
<H3>Output</H3>
true,false

In JavaScript, the !== operator checks for strict inequality, which means it considers both value and type. 

The != operator checks for loose inequality, only considering the value and performing type coercion if necessary.

5.Guess the Output and explain Why?
    
    ```
        let str = 'Hello Programmers';
        
        let result = str.includes('r');
        
        console.log(result);
    ```
    <H3>Output</H3>
    true
    
    The includes() method in JavaScript is used to check if a string contains a specific substring.

6.Guess the Output and Explain Why?
    
    ```
    let num1 = 2;
    
    let num2 = 5;
    
    let result = num1 ** num2 * 2;
    
    console.log(result);
    ```
    <H3>Output</H3>
    64
    
    In JavaScript, the ** operator is the exponentiation operator. So 2^5*2=64

 7.Guess the Output and Explain Why?

   ```
   let num1 = [1, 2, 4, 5];
   
   let num2 = [6, 5, 8, 0];
   
   let result = num1.concat(num2);
   
   console.log(result);
   ```
   <H3>Output</H3>
   [1, 2, 4, 5, 6, 5, 8, 0]
   
   The concat() method in JavaScript is used to concatenate two or more arrays, creating a new array without modifying the existing arrays.
  8.Guess the Output and Explain Why?
       ```
       let a = 5;
       
       let b = 7;
       
       let c = 8;
       
       let result = a < b > c;
       
       console.log(result);
       ```
       <H3>Output</H3>
       false

       a < b > c Equivalent to (a < b) && (b > c)
   9.Guess the Output And Explain Why?

```
       let i = 4;
       
       for (let j = 0; i < 10; i++) {
         if (j === 1 || i === 6) {
           continue;
         } else {
           console.log(i, j);
       
           if (i === 7) {
             break;
           }
         }
       }
```
<H3>Output</H3>
4 0
5 0
7 0
 
10. Guess the Output and Explain Why?

let i = 0;

for (i; i < 5; i++) {
  console.log(i);
}
11. Write a simple Program in which You have to print first 10 numbers in descending order (10...1)?
12. Lets say John is looking a new country to live in. He want to live in a country that speaks English, has less than 10 million people. One of the food option between these two must present Spanish food OR English food.

Write an if/else if statement to help john figure out Your country is right for him?

13. Guess the Output And Explain Why?

for (let i = 0; i < 10; i++) {
  console.log(i);
}

console.log(i);
14. use nested-if statement to check your age>18

than check your height height > 5.10.

If both true show any message(I can sit in exam) in the console?

15. Create two variables grade and passingYear.Check if your grade == "A" and passingYear < 2020 with the help of ternary operator(Not allowed to use any logical operator).If both condition true print on console Qualify. Otherwise Fail

WOW Set 3:
Assignments
16. Create a function Declaration called describeYourState Which take three parameters Population, traditional food and historical place. Based on this input function should return a String with this format.

My state population is ** Its traditional food is ** and historical place name is ___

17. Create a function expression which does the exact same thing as defined in Question 1

18. Create function addition which takes two numbers as an argument And return the result of sum of two numbers

Important Note: In the function call you are not passing any parameter. You can modify function to achieve this.

Example;

function addition(num1, num2) {
  return num1 + num2;
}
console.log(addition()); //You are not allowed to modify this line any more
19. Identify which type of value passed below into the function greet(). What will be the return value of greet ?

let person = {
  name: 'john',

  age: 25,
};

function greet(person) {
  person.name = `Mr ${person.name}`;

  return `Welcome ${person.name}`;
}

greet(person);
20. Create higher order function named as transformer which take string and firstUpperCaseWord function as an arguments. firstUpperCaseWord is function which make first word UpperCase from a given String.

21. create function which will display Your name after every 5 seconds

input

let  yourName  =  "john";
output

"john"  after  5  second

"john"  after  5  second

"john"  after  5  second

"john"  after  5  second

.

.

.

and  so  on.
22. Guess the Output And Explain Why?

let arrowFunction = (name = 'Coders') => {
  `Welcome ${name}`;
};

console.log(arrowFunction('Programmers'));
23. Create a JavaScript Function to find the area of a triangle where lengths of the three of its sides are 5, 6, 7. : Area = Square root of√s(s - a)(s - b)(s - c) where s is half the perimeter, or (a + b + c)/2.

input: area_of_triangle(5, 6, 7);

output: 14.69;
24. Create a JavaScript Function to capitalize the first letter of each word of a given string.

input: capitalize('we are the champions');

output: 'We Are The Champions';
WOW Set 4:
Assignments
25. Guess the Output And Explain ?

console.log(Math.round(Math.random() * 10));
26. Create an object called country for a country of your choice, containing properties name , capital, language, population and neighbors

Increase the country population by two million using dot notation.
Decrease the country population by one million using bracket notation.
Make language value in Uppercase.
27. Guess the Output and explain Why?

let car = {
  color: 'Blue',

  model: 2021,

  company: 'Toyota',
};

let carColor = 'Blue';

console.log(car[carColor]);

console.log(car.carColor);
28. Create a method describeCar inside car object in which you have to print like this in console using template literals

Company of my car is __. Its color is __. And Model of my car is __ **

29. Generate random numbers between 0 and 10 using trunc method of MATH object

Example

getRandomNumbers(){



}

Ouput  value  0-10
30: Guess the Output and Explain Why?

let  arr  = [1,2,3,4];

arr.forEach(elem  =>{

if(elem  ==  1){

continue;

}
console.log(elem);

})
31. Guess the Output And explain Why?

Important Note: if there is any error, How we can solve that error?

let airplane = {
  flightName: 'fly india',

  atacode: 'FI',

  ratings: 4.9,

  book(passenger, flightNum) {
    console.log(
      `${passenger} Booked flight in ${this.flightName} with flight Number ${this.atacode}${flightNum}`
    );
  },
};

let bookMethod = airplane.book;

bookMethod('john', 8754);
32: Guess the Output And Explain Why?

let arr = [1, 2, 3, 4];

for (let elem in arr) {
  console.log(elem);
}
