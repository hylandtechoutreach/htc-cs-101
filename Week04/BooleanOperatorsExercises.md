# Boolean Operators - Exercises
Complete the following exercises.

## Boolean Evaluation
### Part 1
What is the boolean result of the following statements?

Determine what you think the answer is, and then write code to check your answer.
Example: `25 == 25` -> `true`

1. `"Random String" != "Random String"`
1. `15 > 7` 
1. `27 <= 152` 
1. `"My Name Is Jordan" == "my name is jordan"`
1. `35 >= 35` 
1. `3.1254798 <=  5` 
1. `9001 < 9001` 

### Part 2
What is the FINAL boolean result for the following conditional?
Example `( true && true )` -> `true`

1. `(false || false)`
1. `(true || false)`
1. `(true && false)`
1. `!(true && false)`
1. `(false || (true && true))`
1. `(true && (true && false))`
1. `((false || !(true || false)) && !false)`
1. `(false && (false || true))`
1. `(3.1254798 <=  5 && 9001 < 9001)`
1. `("Random String" != "Random String" || (27 <= 152 && 35 >= 35)`
1. `(false || (true && (false || true) || !(true && false) || (true && false)))`

## Parking Challenge
Take a look at the following set of parking ordinances: 
![](https://i.imgur.com/W7iGhcr.jpg)

Based on the signs, determine if a user is able to park.
1. Ask the user to provide the Day, Time of Day, and Length of parking time
1. Tell them how long they can park (2 hours, 4 hours, 0 hours, or no stopping)