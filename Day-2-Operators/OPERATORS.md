# Operators in JavaScript

## Table of Questions

### Activities
| Task | Question |
|----------|-------------|
| 1 | [Write a program to add two numbers and log the result to the console.](#write-a-program-to-add-two-numbers-and-log-the-result-to-the-console) |
| 2 | [Write a program to subtract two numbers and log the result to the console.](#write-a-program-to-subtract-two-numbers-and-log-the-result-to-the-console) |
| 3 | [Write a program to multiply two numbers and log the result to the console.](#write-a-program-to-multiply-two-numbers-and-log-the-result-to-the-console) |
| 4 | [Write a program to divide two numbers and log the result to the console.](#write-a-program-to-divide-two-numbers-and-log-the-result-to-the-console) |
| 5 | [Write a program to find the remainder when one number is divided by another and log the result to the console.](#write-a-program-to-find-the-remainder-when-one-number-is-divided-by-another-and-log-the-result-to-the-console) |
| 6 | [Use the += operator to add a number to a variable and log the result to the console.](#use-the--operator-to-add-a-number-to-a-variable-and-log-the-result-to-the-console) |
| 7 | [Use the -= operator to subtract a number from a variable and log the result to the console.](#use-the--operator-to-subtract-a-number-from-a-variable-and-log-the-result-to-the-console) |
| 8 | [Write a program to compare two numbers using > and < and log the result to the console.](#write-a-program-to-compare-two-numbers-using--and--and-log-the-result-to-the-console) |
| 9 | [Write a program to compare two numbers using >= and <= and log the result to the console.](#write-a-program-to-compare-two-numbers-using--and--and-log-the-result-to-the-console) |
| 10 | [Write a program to compare two numbers using == and != and log the result to the console.](#write-a-program-to-compare-two-numbers-using--and--and-log-the-result-to-the-console) |
| 11 | [Write a program that uses the && operator to combine two conditions and log the result to the console.](#write-a-program-that-uses-the--operator-to-combine-two-conditions-and-log-the-result-to-the-console) |
| 12 | [Write a program that uses the \|\| operator to combine two conditions and log the result to the console.](#write-a-program-that-uses-the--operator-to-combine-two-conditions-and-log-the-result-to-the-console) |
| 13 | [Write a program that uses the ! operator to negate a condition and log the result to the console.](#write-a-program-that-uses-the--operator-to-negate-a-condition-and-log-the-result-to-the-console) |
| 14 | [Write a program that uses the ternary operator to check if a number is positive or negative and log the result to the console.](#write-a-program-that-uses-the-ternary-operator-to-check-if-a-number-is-positive-or-negative-and-log-the-result-to-the-console) |


### Feature Request
| Feature | What to do ?? |
|---------|---------------|
| 1 | [Arithmetic Operations Script: Write a script that performs basic arithmetic operations (addition, subtraction, multiplication, division, remainder) on two numbers and logs the results.](#arithmetic-operations-script-write-a-script-that-performs-basic-arithmetic-operations-addition-subtraction-multiplication-division-remainder-on-two-numbers-and-logs-the-results) |
| 2 | [Comparison and Logical Operators Script: Create a script that compares two numbers using different comparison operators and combines conditions using logical operators, logging the results.](#comparison-and-logical-operators-script-create-a-script-that-compare-two-numbers-using-different-comparison-operators-and-combines-conditions-using-logical-operators-logging-the-results) |
| 3 | [Ternary Operator Script: Write a script that uses the ternary operator to determine if a number is positive or negative and logs the result.](#ternary-operator-script-write-a-script-that-uses-the-ternary-operator-to-determine-if-a-number-is-positive-or-negative-and-logs-the-result.) |


## Questions and Answers

1. ### Write a program to add two numbers and log the result to the console.
    ```javascript
    
        // function to add two numbers
        function add(a, b) {
          return a + b;
        }

        console.log(add(2, 3)); // Expected output: 5
    ```

    ⬆️ [Go to questions](#table-of-questions)

2. ### Write a program to subtract two numbers and log the result to the console.
    ```javascript
    // function to subtract two numbers
    function subtract(a, b) {
      return a - b;
    }
    console.log(subtract(5, 3)); // Expected output: 2

    ```

    ⬆️ [Go to questions](#table-of-questions)

3. ### Write a program to multiply two numbers and log the result to the console.
    ```javascript
    // function to multiply two numbers
    function multiply(a, b) {
      return a * b;
    }

    console.log(multiply(2, 3)); // Expected output: 6

    ```

    ⬆️ [Go to questions](#table-of-questions)

4. ### Write a program to divide two numbers and log the result to the console.
    ```javascript
    // function to divide two numbers

    function divide(a, b) {
      return a / b;
    }

    console.log(divide(6, 3)); // Expected output: 2

    ```

    ⬆️ [Go to questions](#table-of-questions)

5. ### Write a program to find the remainder when one number is divided by another and log the result to the console.
    ```javascript
    // function to find the remainder when two numbers are divided

    function remainder(a, b) {
        return a % b;
        }

    console.log(remainder(5, 2)); // Expected output: 1

    ```

    ⬆️ [Go to questions](#table-of-questions)

6. ### Use the += operator to add a number to a variable and log the result to the console.
    ```javascript
    let num = 5;
    num += 2;
    console.log(num); // Expected output: 7

    ```

    ⬆️ [Go to questions](#table-of-questions)

7. ### Use the -= operator to subtract a number from a variable and log the result to the console.
    ```javascript
    let num1 = 5;
    num1 -= 2;
    console.log(num1); // Expected output: 3

    ```

    ⬆️ [Go to questions](#table-of-questions)

8. ### Write a program to compare two numbers using > and < and log the result to the console.
    ```javascript
    let num2 = 5;
    let num3 = 10;

    console.log(num2 > num3); // Expected output: false
    console.log(num2 < num3); // Expected output: true
    ```

    ⬆️ [Go to questions](#table-of-questions)

9. ### Write a program to compare two numbers using >= and <= and log the result to the console.
    ```javascript
    let num2 = 5;
    let num3 = 10;
    let num4 = 10;

    console.log(num2 >= num3); // Expected output: false 
    console.log(num2 <= num3); // Expected output: true
    console.log(num4 <= num3); // Expected output: true
    console.log(num4 >= num2); // Expected output: true


    ```

    ⬆️ [Go to questions](#table-of-questions)

10. ### Write a program to compare two numbers using == and != and log the result to the console.
    ```javascript
    let num1 = 10;
    let num2 = 20;

    if (num1 == num2) {
      console.log("Both numbers are equal");
    } else {
      console.log("Both numbers are not equal");
    }

    if (num1 != num2) {
      console.log("Both numbers are not equal");
    } else {
      console.log("Both numbers are equal");
    }
    ```

    ⬆️ [Go to questions](#table-of-questions)

11. ### Write a program that uses the && operator to combine two conditions and log the result to the console.
    ```javascript
    let condition1 = true;
    let condition2 = false;

    if (condition1 && condition2) {
        console.log("Both conditions are true");
    } else {
        console.log("At least one of the conditions is false");
    }

    ```

    ⬆️ [Go to questions](#table-of-questions)

12. ### Write a program that uses the \|\| operator to combine two conditions and log the result to the console.
    ```javascript
        let a = 5;
        let b = 10;

        if (a > 5 || b > 5) {
            console.log('At least one of the numbers is greater than 5');
        }
    ```

    ⬆️ [Go to questions](#table-of-questions)

13. ### Write a program that uses the ! operator to negate a condition and log the result to the console.
    ```javascript
    let condition = true;
    console.log(!condition); // false
    ```

    ⬆️ [Go to questions](#table-of-questions)

14. ### Write a program that uses the ternary operator to check if a number is positive or negative and log the result to the console.
    ```javascript
    let number = 5;
    let result = number > 0 ? "positive" : "negative";
    console.log(result); // positive
    ```

    ⬆️ [Go to questions](#table-of-questions)





## Feature Request

1. ### Arithmetic Operations Script: Write a script that performs basic arithmetic operations (addition, subtraction, multiplication, division, remainder) on two numbers and logs the results. 
    ```javascript

    class ArithmeticOperations {
        constructor(num1, num2) {
            this.num1 = num1;
            this.num2 = num2;
        }

        add() {
            return this.num1 + this.num2;
        }

        subtract() {
            return this.num1 - this.num2;
        }

        multiply() {
            return this.num1 * this.num2;
        }

        divide() {
            return this.num1 / this.num2;
        }

        remainder() {
            return this.num1 % this.num2;
        }
    }

    const arithmeticOperations = new ArithmeticOperations(10, 5);

    console.log(arithmeticOperations.add()); // 15
    console.log(arithmeticOperations.subtract()); // 5
    console.log(arithmeticOperations.multiply());// 75
    console.log(arithmeticOperations.divide());// 3
    console.log(arithmeticOperations.remainder());// 0

    ```

    ⬆️ [Go to questions](#table-of-questions)

2. ### Comparison and Logical Operators Script: Create a script that compares two numbers using different comparison operators and combines conditions using logical operators, logging the results.
    ```javascript
        class ComparisonAndLogicalOperators {
        constructor() {
          this.num1 = 10;
          this.num2 = 20;
        }

        compareNumbers() {
            console.log("Comparison and Logical Operators Script");
            console.log("Number 1: ", this.num1);
            console.log("Number 2: ", this.num2);

            console.log("Equal to (==): ", this.num1 == this.num2);
            console.log("Not equal to (!=): ", this.num1 != this.num2);
            console.log("Greater than (>): ", this.num1 > this.num2);
            console.log("Less than (<): ", this.num1 < this.num2);
            console.log("Greater than or equal to (>=): ", this.num1 >= this.num2);
            console.log("Less than or equal to (<=): ", this.num1 <= this.num2);

            console.log("Logical AND (&&): ", this.num1 < 15 && this.num2 < 25);
            console.log("Logical OR (||): ", this.num1 < 15 || this.num2 < 25);
            console.log("Logical NOT (!): ", !(this.num1 < 15));
        }
    }

    const comparisonAndLogicalOperators = new ComparisonAndLogicalOperators();
    
    comparisonAndLogicalOperators.compareNumbers();
    ```

    ⬆️ [Go to questions](#table-of-questions)

3. ### Ternary Operator Script: Write a script that uses the ternary operator to determine if a number is positive or negative and logs the result.
    ```javascript
        class TernaryOperator {
        constructor() {
            this.number = 0;
        }

        checkNumber() {
            this.number > 0 ? console.log("Positive") : console.log("Negative");
            }
        }
    ```

    ⬆️ [Go to questions](#table-of-questions)


