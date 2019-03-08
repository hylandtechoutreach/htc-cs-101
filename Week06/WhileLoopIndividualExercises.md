# Even numbers using a While Loop - FollowAlong
Start by creating a new `.cs` file/project. Then, follow the instructions below to create a program that prints some even numbers.

## Part 1 - Starting from 0
1. Declare a new variable `x` and set its value to `0`
1. Use an `if` statement to check if `x` is even
    - Use the `%` operator to accomplish this: if any number `%` 2 equals 0, that means it is even
1. If `x` *is* even, print it to the console

At the end of this part, the program should print `0` to the console (it is already known that `x` is even)

## Part 2 - While Loop
Instead of simply using `0`, the program should iterate through 0, 1, 2, 3, ..., all the way to 100.

1. Above the `if` statement, create the `while` loop
    - `while` keyword
    - Parentheses `()`
    - Curly brackets `{}`
1. Within the parentheses, use a condition to make sure the count is capped at 100
    - HINT: Compare `x` to `100` in some way
1. In the body of the `while` loop (between the curly braces), increment the value of `x` by 1

At the end of this part, the loop should execute 101 times... but it's missing something

## Part 3 - Putting it all together
The last step is to put the check for evenness within the body of the `while`!

1. Copy the `if` code that checks a number's evenness
    - Include the `if`, and the body that prints to the console
1. Paste the `if` code within the `while` loop
    - Make sure it comes before the increment of `x`

Now, the program should print out each even number: 0, 2, 4, 6, ..., 100!

## BONUS - User Input
Lastly, instead of using `100` as the cap, the program should ask the user which number to use.