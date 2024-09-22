# Variables and Data Types in JavaScript


## Introduction
In JavaScript, variables are used to store data values. A variable can be thought of as a container that holds information which can be changed later on. JavaScript is a dynamically typed language, meaning that you don't have to specify the data type of a variable when you declare it. The data type is automatically determined by the value assigned to the variable.

## Table of Questions

### Activities
| Task | Question |
|----------|-------------|
| 1 | [Declare a variable using var, assign it a number, and log the value to the console?](#declare-a-variable-using-var-assign-it-a-number-and-log-the-value-to-the-console) |
| 2 | [Declare a variable using let, assign it a string, and log the value to the console?](#declare-a-variable-using-let-assign-it-a-string-and-log-the-value-to-the-console) |
| 3 | [Declare a variable using const, assign it a boolean value, and log the value to the console?](#declare-a-variable-using-const-assign-it-a-boolean-value-and-log-the-value-to-the-console) |
| 4 | [Create variables of different data types (number, string, boolean, object, array) and log each variable's type using the typeof operator?](#create-variables-of-different-data-types-number-string-boolean-object-array-and-log-each-variables-type-using-the-typeof-operator) |
| 5 | [Declare a variable using let, assign an initial value, reassign a new value, and log both values to the console.](#declare-a-variable-using-let-assign-an-initial-value-reassign-a-new-value-and-log-both-values-to-the-console) |
| 6 | [Try reassigning a variable declared with const and observe the error.](#try-reassigning-a-variable-declared-with-const-and-observe-the-error) |

### Feature Request
| Feature | What to do ?? |
|-------------|----------------|
| 1 | [Variable Types Console Log: Write a script that declares variables of different data types and logs both the value and type of each variable to the console.](#variable-types-console-log-write-a-script-that-declares-variables-of-different-data-types-and-logs-both-the-value-and-type-of-each-variable-to-the-console) |
| 2 | [Reassignment Demo: Create a script that demonstrates the difference in behavior between let and const when it comes to reassignment.](#reassignment-demo-create-a-script-that-demonstrates-the-difference-in-behavior-between-let-and-const-when-it-comes-to-reassignment) |

## Questions and Answers

1. ### Declare a variable using var, assign it a number, and log the value to the console?
    ```javascript
    var variable = 15;

    console.log(variable); // output: 15
    ```

    ⬆️ [Go to questions](#table-of-questions)


2. ### Declare a variable using let, assign it a string, and log the value to the console?
    ```javascript
    let str = "Hello World!";

    console.log(str) //output: Hello World!
    ```

    ⬆️ [Go to questions](#table-of-questions)

3. ### Declare a variable using const, assign it a boolean value, and log the value to the console?
    ```javascript
    const PI = 3.14;

    console.log(PI) //output: 3.14
    ```

    ⬆️ [Go to questions](#table-of-questions)

4. ### Create variables of different data types (number, string, boolean, object, array) and log each variable's type using the typeof operator?
    ```javascript
    // Number
    let number = 2450;
    
    console.log(typeof number) //output: number

    // String
    let str = "dot stepped bare magic current discussion probably";

    console.log(typeof str); // output: string

    // Boolean
    let isChecked = true;

    console.log(typeof isChecked) //output: boolean

    // Object
    let obj = {
        firstName: "John",
        secondName: "Doe",
    };
    console.log(typeof obj); // output object

    // Array
    let arr = [1,2,3,4,5,6];
    console.log(typeof arr) //output: object
    ```


    ⬆️ [Go to questions](#table-of-questions)

5. ### Declare a variable using let, assign an initial value, reassign a new value, and log both values to the console.
    ```javascript
        // initial value
        let x = 5;
        console.log(x); // output 5

        // reassign a new value
        x = 10;
        console.log(x); // output 10

    ```

    ⬆️ [Go to questions](#table-of-questions)

6. ### Try reassigning a variable declared with const and observe the error.
    ``` javascript
        // value assign by const
        const a = 10;

        a = 20; // Error: Assignment to constant variable.

    ```

    ⬆️ [Go to questions](#table-of-questions)

## Feature Request

1. ### Variable Types Console Log: Write a script that declares variables of different data types and logs both the value and type of each variable to the console.
    ```javascript
        // Declare variables of the following types:
        // String
        const stringVar = 'Hello World';

        // Number
        const numberVar = 42;

        // Boolean
        const booleanVar = true;

        // Object
        const objectVar = { key: 'value' };

        // Array
        const arrayVar = [1, 2, 3];

        // Function
        const functionVar = function() {console.log('Hello World')};
        // Undefined
        const undefinedVar = undefined;

        // Null
        const nullVar = null;

        // Symbol
        const symbolVar = Symbol('foo');

        console.log(`String: ${stringVar}, Type: ${typeof stringVar}`); // String: Hello World, Type: string
        console.log(`Number: ${numberVar}, Type: ${typeof numberVar}`); // Number: 42, Type: number
        console.log(`Boolean: ${booleanVar}, Type: ${typeof booleanVar}`); // Boolean: true, Type: boolean
        console.log(`Object: ${objectVar}, Type: ${typeof objectVar}`); // Object: [object Object], Type: object
        console.log(`Array: ${arrayVar}, Type: ${typeof arrayVar}`); // Array: 1,2,3, Type: object
        console.log(`Function: ${functionVar}, Type: ${typeof functionVar}`); // Function: function() {console.log('Hello World')}, Type: function
        console.log(`Undefined: ${undefinedVar}, Type: ${typeof undefinedVar}`); // Undefined: undefined, Type: undefined
        console.log(`Null: ${nullVar}, Type: ${typeof nullVar}`); // Null: null, Type: object
        console.log(`Symbol: ${symbolVar.toString()}, Type: ${typeof symbolVar}`); // Symbol: Symbol(foo), Type: symbol


    ```

    ⬆️ [Go to questions](#table-of-questions)

2. ### Reassignment Demo: Create a script that demonstrates the difference in behavior between let and const when it comes to reassignment.
    ```javascript
        // let
        let reassignableLet = 1; // Declare a variable with let and assign it a value of 1
        console.log(reassignableLet); // Output the value of the variable

        reassignableLet = 2; // Reassign the variable to a value of 2
        console.log(reassignableLet); // Output the new value of the variable

        // const
        const reassignableConst = 1; // Declare a variable with const and assign it a value of 1
        console.log(reassignableConst); // Output the value of the variable

        // reassignableConst = 2; // Attempt to reassign the variable to a value of 2
        // console.log(reassignableConst); // Output the new value of the variable

        // The above code will throw an error because const variables cannot be reassigned. Uncommenting lines 14-15 will result in a TypeError.


    ```


    ⬆️ [Go to questions](#table-of-questions)


























