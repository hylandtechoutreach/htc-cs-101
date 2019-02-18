# Conditional Statements Challenges - Number Guessing
Challenges 1-3 build on each other, so you do not need to create three separate programs.

## Part 1 - Just an `if`
1. Ask the user to guess a number between 1 and 10
	- Remember to convert it to an int: `int num = Convert.ToInt32(input);`
1. Use an `if` statement to test if the number is greater than 4, i.e. `if (num > 4)`
1. If it is greater, use `Console.WriteLine` to say "Too High!"
1. Run the Program and fix any mistakes before moving on

## Part 2 - Adding an `else if`
1. Ask the user to guess a number between 1 and 10
1. Use an `if` statement to test if the number is greater than 4
1. If it is greater, use `Console.WriteLine` to say "Too High!"
1. Use an `else if` to test if the number is less than 4, i.e. `num < 4`
1. If it is less, use `Console.WriteLine` to say "Too Low"
1. Run the Program and fix any mistakes before moving on

## Part 3 - Adding an `else`
1. Ask the user to guess a number between 1 and 10
1. Use an `if` statement to test if the number is greater than 4
1. If it is greater, use `Console.WriteLine` to say "Too High!"
1. Use an `else if` to test if the number is less than 4, i.e. `num < 4`
1. If it is less, use `Console.WriteLine` to say "Too Low"
1. Use an "else", to test if the number is equal to 4
1. If it is, use `Console.WriteLine` to say "Just Right"
1. Run the Program and fix any mistakes before moving on

## Super Challenge
Use the System.Random class to generate your number for Number Guesser:
https://msdn.microsoft.com/en-us/library/system.random(v=vs.110).aspx
