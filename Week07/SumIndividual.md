# Sum: Individual Exercise
Write a program that prints out the sum of a given sequence of integers. The program should ask the user for an ending point for the sequence, and then add all the integers between 0 and the ending point and print the result.

##### Examples
```
Enter a top number: 10
Result: 55
```
This is because `1+2+3+4+5+6+7+8+9+10=55`.

```
Enter a top number: 5
Result: 15
```
This is because `1+2+3+4+5=15`.

## Part 1 - User input
1. Print a message asking the user to enter an integer for the top number
1. Get input from the user using `Console.ReadLine`
1. Define a new variable to store the number the user enters (`topNumber`)
1. Convert the string input into an integer using `Convert.ToInt32`

## Part 2 - `for` loop set up
1. Build out the `for` loop structure:
    - `for` keyword
    - Parentheses (`()`)
    - Within the parentheses: two semi-colons (`;`)
    - After the parentheses: curly brackets (`{}`)
1. Fill in the for loop initializer, conditional, and modifier:
    - Declare the `i` variable, set it equal to `1`
    - Check that `i` is less than or equal to the `topNumber` variable the user entered
    - Increment the `i` variable by `1`

## Part 3 - Finishing up
1. Above the `for` loop, create a variable to keep track of the sum (name it `sum`)
    - Set its initial value to `0`
1. Within the body of the `for` loop, update the value of `sum`
    - Add the current value of `i` to the current value of `sum`
1. Beneath the `for` loop, print out the resulting `sum`

## (BONUS) Part 4 - User-defined starting point
Instead of using the `1` as the first value in the sequence, ask the user for a value. Use that value in the `for` loop so that it only sums the integers between that value and the `topNumber` value.

##### Examples
```
Enter a top number: 10
Enter a bottom number: 8
Result: 27
```
This is because `8+9+10=27`.

```
Enter a top number: 5
Enter a bottom number: 2
Result: 14
```
This is because `2+3+4+5=14`.