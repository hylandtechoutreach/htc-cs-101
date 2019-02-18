# Conditional Challenges
Complete the following challenges within the `Main` method of your program. Or, create additional program files/methods to complete these challenges. Use `if`, `else`, and `else if` (do not use any other control flow statements)!

#### 1. Even or Odd
Write a program that reads an integer from the user. Then your program should display a message indicating whether the integer is even or odd.

#### 2. Maximum of Three
Write a program that asks the user for three numbers. Then, your program should tell the user which of the numbers is the largest.

#### 3. Vowel or Consonant
In this exercise you will create a program that reads a letter of the alphabet from the user. If the user enters `a`, `e`, `i`, `o` or `u` then your program should display a message indicating that the entered letter is a vowel. If the user enters `y` then your program should display a message indicating that sometimes y is a vowel, and sometimes y is a consonant. Otherwise your program should display a message indicating that the
letter is a consonant.

#### 4. Name that Shape
Write a program that determines the name of a shape from its number of sides. Read the number of sides from the user and then report the appropriate name as part of a meaningful message. Your program should support shapes with anywhere from 3 up to (and including) 10 sides. If a number of sides outside of this range is entered then your program should display an appropriate error message.

#### 5. Month Name to Number of Days
The length of a month varies from 28 to 31 days. In this exercise you will create a program that reads the name of a month from the user as a string. Then your program should display the number of days in that month. Display "28 or 29 days" for February so that leap years are addressed.

#### 6. Name that Triangle
A triangle can be classified based on the lengths of its sides as equilateral, isosceles or scalene. All 3 sides of an equilateral triangle have the same length. An isosceles triangle has two sides that are the same length, and a third side that is a different length. If all of the sides have different lengths then the triangle is scalene.

Write a program that reads the lengths of 3 sides of a triangle from the user. Display a message indicating the type of the triangle.

#### 7. Faces on Money
Write a program that begins by reading the denomination of a banknote from the user. Then, your program should display the name of the individual that appears on the banknote of the entered amount. An appropriate error message should be displayed if no such note exists.

#### 8. Season from Month and Day
The year is divided into four seasons: spring, summer, fall and winter. While the exact dates that the seasons change vary a little bit from year to year because of the way that the calendar is constructed, we will use the following dates for this exercise:

| Season | First Day |
|-|-|
| Spring  | March 20 |
| Summer | June 21 |
| Fall | September 22 |
| Winter | December 21 |

Create a program that reads a month and day from the user. The user will enter the name of the month as a string, followed by the day within the month as an integer. Then your program should display the season associated with the date that was entered.

_NOTE: It may be helpful to use **nested** statements to complete this challenge_

#### 9. Is a License Plate Valid?
In a particular jurisdiction, older license plates consist of three uppercase letters followed by three numbers. When all of the license plates following that pattern had been used, the format was changed to four numbers followed by three uppercase letters.

Write a program that begins by reading a string of characters from the user. Then your program should display a message indicating whether the characters are valid for an older style license plate or a newer style license plate. Your program should display an appropriate message if the string entered by the user is not valid for either style of license plate.

_REFERENCE: String (https://docs.microsoft.com/en-us/dotnet/api/system.string?view=netframework-4.7.2)_

#### 10. Decision Maker
Throughout the course of a person's life, they will have to make a number of decisions. Some of these decisions may be quite difficult, and may require a great deal of thought. In these situations, it would be nice to have an algorithm that weighs the options, and outputs the optimal decision. Create a program that will make decisions for a person, given a group of weighted pros and cons.

The program should do the following:
- Ask the user what they would like to decide
    - They should fill in the blank: "Should I \_\_\_\_?"
- Ask the user for five "pro" arguments
- For each "pro" argument, ask the user for a weighted value representing the importance of the item
- Ask the user for five "con" arguments, including weighted values
- Print the list of pros and cons in an easily-digestable format
- Calculate the result by adding the weighted values on each side
- Print out the final decision like so: "You should \_\_\_\_" OR "You should NOT \_\_\_\_"

##### Extra Challenge
Adapt your program so that it can choose between more than two options. For example, if the user were trying to choose between three different apartments to lease, they might use the rent price, the location, and the amenities to pick the best one. The program should be able to use at least 5 different criteria to compare three options, where each criterion has a weight, and each option has a value for each criterion. The program should then display the optimal choice.