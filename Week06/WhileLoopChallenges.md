# While Loops Challenges
Complete the following challenges.

## 1. While Loop Guessing game
Randomly pick a number, and use a `while` loop to ask a user to guess a number between 1 and 20. Make them guess until they are correct.

- If the users guess is too high tell them too high.
- If the guess is too low, tell them too low.
- If the guess is correct, congratulate them, and break out of the loop.

## 2. Calculate the next leap years
Leap years are defined as follows:
- If the year is divisible by `4` then it is a leap year
- Except if the year is divisible by `100` then it IS NOT a lear year
- Except if the year is divisible by `400` then it is a leap year

Write a program that does the following:
- Using the current year, generate the next 50 leap years
- Print those years to the console

## 3. Decreasing value
Repeatedly print the value of a variable `xValue`, decreasing it by `0.5` each time,
as long as `xValue` remains positive. Start by asking the user for a number, then store the value in the `xValue` variable.

## 4. Squares
Print the square of the first 25 odd positive integers.

## 5. Sums
Write a method with a `while` loop that computes the sum of first `n` positive integers:
```
sum = 1 + 2 + 3 + ... + n
```

### Examples
`n = 5`: `sum = 15`  
`n = 19`: `sum = 190`

Allow the user to input the value of `n`.

## 6. Factors
Write a method that calculates the largest factor of a number (not including the number itself).

### Examples
`n = 24`: `output = 12`  
`n = 19`: `output = 1`  
`n = 27`: `output = 9`

Allow the user to input the value of `n`.

## 7. Diamond
Write a method that prints out an ASCII diamond of stars, with a height supplied by the user. The height is defined by the distance between the top line of stars and the middle line of stars.

### Examples
User inputs `1`:  
```
 *
* *
 *
```

User inputs `3`:  
```
   *
  * *
 *   *
*     *
 *   *
  * *
   *
```

## 8. Menu-based application
Create a calculator application where the user is prompted with a menu, and can select which function they would like to perform. If they ever enter an invalid input, they should be prompted again to enter a valid input. The application should allow the user to add, subtract, multiply, or divide. There should also be a secret option (not shown on the menu).

## 9. Greatest Common Factor of two numbers
Take in two numbers and calculate their greatest common factor using a `while` loop.

>Resource: http://www.math.com/school/subject1/lessons/S1U3L2GL.html

## 10. Cutting Sticks Problem
### Problem Statement
You are given N sticks, where the length of each stick is a positive integer. A cut operation is performed on the sticks such that all of them are reduced by the length of the smallest stick.

Suppose we have six sticks of the following lengths:

```
5 4 4 2 2 8
```

Then, in one cut operation we make a cut of length 2 from each of the six sticks. For the next cut operation four sticks are left (of non-zero length), whose lengths are the following:

```
3 2 2 6
```

The above step is repeated until no sticks are left.

Given the length of N sticks, print the number of sticks that are left before each subsequent cut operations.

>Note: For each cut operation, you have to recalcuate the length of smallest sticks (excluding zero-length sticks).

### Input Format
The first line contains a single integer N. 
The next line contains N integers: a0, a1,...aN-1 separated by space, where  represents the length of the  stick.

### Output Format
For each operation, print the number of sticks that are cut, on separate lines.

### Constraints
```
1 < N < 1000
```
```
1 < ai < 1000
```

### Sample Input
```
8
1 2 3 4 3 3 2 1
```

### Sample Output
```
8
6
4
1
```

### Explanation
```
sticks-length         length-of-cut   sticks-cut
1 2 3 4 3 3 2 1         1               8
_ 1 2 3 2 2 1 _         1               6
_ _ 1 2 1 1 _ _         1               4
_ _ _ 1 _ _ _ _         1               1
_ _ _ _ _ _ _ _       DONE            DONE
```

## 11. ASCII Art Game
Make a game using ASCII art and `while` loops.
