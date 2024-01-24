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

5.  Guess the Output and explain Why?
    
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
   9.: Guess the Output And Explain Why?

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
 
