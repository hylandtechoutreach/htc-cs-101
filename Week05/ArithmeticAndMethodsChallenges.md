# Arithmetic and Methods Challenges
Complete the exercises below using a single `.cs` file. In the `Main` method, appropriately _call_ each of the methods you _define_.

## 1 - Simple Operations
1. Write a method that takes in a number and adds `1` to it, return your new number  
	- Try to use some of the new arithmetic operators you learned!
1. Write a method that takes in a number and adds `3` to that number, return your new number 
1. Write a method that takes in a number and multiplies that number by `3`, return your new number 

## 2 - Calculate the next leap years
1. Write a method that asks the user for a year
1. Write another method that takes that user input and determines if it is a leap year

Leap years are defined as follows:
* If the year is divisible by 4 then it is a leap year
* Except if the year is divisible by 100 then it IS NOT a lear year
* Except if the year is divisible by 400 then it IS a leap year

### Challenge
Write a program that does the following:
* Using the current year, generate the next 50 leap years
* Print these years out to the console

## 3 - Countdown
Create a program that will ask the user for a date and the name of an event, and then display how many days there are until that date (ex: "There are 52 days until my birthday").

### Challenge items
- The program should calculate the amount of time remaining in years, months, weeks, days, hours, minutes, and seconds
- The program should properly handle invalid input (e.g., fake months like `Smarch` or invalid numbers like `the 28.3th of April`)
- The program should be able to handle a date provided in as many forms as possible (e.g., `03/09/2019`, `March 9th, 2019`, `9 Mar 2019`, `the 9th of March in 2019`)

### Extra challenge
- The program should be able to display multiple countdowns at once
- The program should store each countdown name/date in a text file, and load them from the text file each time the program runs