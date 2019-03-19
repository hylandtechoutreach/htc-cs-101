# For Loop Challenges
Complete the following challenges.

## Palindrome
Check if a string is a palindrome. A palindrome is defined as follows:
- A group of characters that is the same forward as it is backwards
- Palindromes normally do not take into account letter casing, spaces or punctuation

Examples of some palindromes:
- Tacocat
- Hannah
- Kayak
- Never odd or even
- Rats live on no evil star
- A man, a plan, a canal - Panama!
- https://users.math.yale.edu/public_html/People/frame/Fractals/Panorama/Literature/Martin/MartinPalindrome.html

Write a program that does the following:
- Asks the user to enter in a word or phrase
- Check to see if this string is a palindrome
- If it is a palindrome, print out Yes
- Otherwise, print out No

## Generate Fibonacci numbers
Fibonacci numbers are a sequence of integers where the next integer is defined as the sum of the previous two values.

The first 10 Fibonacci numbers are as follows:
```
1, 1, 2, 3, 5, 8, 13, 21, 34, 55
```
Write a program that does the following:
- Asks the user to enter an integer
- Generates Fibonacci numbers out to this value

Example:
```
> Enter an integer: 10
> 1, 1, 2, 3, 5, 8, 13, 21, 34, 55
```

## The Floyd's Triangle
Write a program to print Floyd's Triangle. Floyd's triangle, named after Rober Floyd, is a right angled triangle, which is made using natural numbers. It starts from 1 and consecutively selects the next greater number in sequence.

```
1
2 3
4 5 6
7 8 9 10
```

Write a program that does the following:
- Asks the user to enter an integer
- Generates Floyd's Triangle the given number of rows

Examples:
```
> Enter an integer: 2

1
2 3
```

```
> Enter an integer: 5

1
2 3
4 5 6
7 8 9 10
11 12 13 14 15
```

## Prime Number
Write a program to determine whether a given number is prime or not. A _prime number_ is defined as a natural number greater than 1 that cannot be formed by multiplying two smaller natural numbers. Example prime numbers: `2, 3, 5, 7, 11`

The program should:
- Ask the user for a number
- Display whether the number is prime or not

Examples:
```
> Enter an integer: 3098191
> 3098191 is prime!
```
``` 
> Enter an integer: 3098192
> 3098192 is not prime.
```

## Triangle
Write a program that prints out an ASCII-art right triangle of a given height using a `for` loop. The program should use the star character (`*`) to build the triangle.

Examples:
```
Enter a height: 3

*
**
***
```

```
Enter a height: 7

*
**
***
****
*****
******
*******
```

## Sum of Digits
Write a program that calculates the sum of the digits of a given number. The user should provide the number.

Examples:
```
Enter a number: 12345
The sum of digits of 12345 is: 15
```
`1+2+3+4+5=15`

```
Enter a number: 2242
The sum of digits of 2242 is: 10
```
`2+2+4+2=10`

## Sum of Series
Write a program that calculates the sum of the following series up to _n_ terms: `1+11+111+1111+11111+...` The user should input a value for _n_ and then the program should perform the calculation.

Examples:
```
Enter a number: 4
1 + 11 + 111 + 1111
The sum of the series is: 1234
```

```
Enter a number: 6
1 + 11 + 111 + 1111 + 11111 + 111111
The sum of the series is: 123456
```

## ASCII Scroll
Generate an ASCII scroll based on text the user enters. The scroll should dynamically grow based on the length of the message.

Basic Examples:

```
Enter a message: This is short
   ______________________________
 / \                             \.
|   |                            |.
 \_ |                            |.
    |   This is short            |.
    |   _________________________|___
    |  /                            /.
    \_/____________________________/.
```
```
Enter a message: Hello and welcome to this scroll...
   ______________________________
 / \                             \.
|   |                            |.
 \_ |                            |.
    |   Hello and welcome to t   |.
    |   his scroll...            |.
    |   _________________________|___
    |  /                            /.
    \_/____________________________/.
```

```
Enter a message: It is a period of civil war. Rebel spaceships, striking from a hidden base, have won their first victory against the evil Galactic Empire.
   ______________________________
 / \                             \.
|   |                            |.
 \_ |                            |.
    |   It is a period of civi   |.
    |   l war. Rebel spaceship   |.
    |   s, striking from a hid   |.
    |   den base, have won the   |.
    |   ir first victory again   |.
    |   st the evil Galactic E   |.
    |   mpire.                   |.
    |   _________________________|___
    |  /                            /.
    \_/____________________________/.
```

### Challenge
When extending to an additional line, words should not split if possible. If not possible, a dash should separate words that are too long.

Examples:
```
Enter a message: Hello and welcome to this scroll...
   ______________________________
 / \                             \.
|   |                            |.
 \_ |                            |.
    |   Hello and welcome to     |.
    |   this scroll...           |.
    |   _________________________|___
    |  /                            /.
    \_/____________________________/.
```

```
Enter a message: It is a period of civil war. Rebel spaceships, striking from a hidden base, have won their first victory against the evil Galactic Empire.
   ______________________________
 / \                             \.
|   |                            |.
 \_ |                            |.
    |   It is a period of        |.
    |   civil war. Rebel         |.
    |   spaceships, striking     |.
    |   from a hidden base,      |.
    |   have won their first     |.
    |   victory against the      |.
    |   evil Galactic Empire.    |.
    |   _________________________|___
    |  /                            /.
    \_/____________________________/.
```
