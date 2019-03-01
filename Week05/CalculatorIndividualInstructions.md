# Calculator - Individual
Update the existing calculator to make it more robust.

## Multiplication
Add the option to multiply the two integers the user provides.

### Define the Method
Start with the method signature:
- Visibility: `public`
- Modifier: `static`
- Return type: `int`
- Name: `MultiplyNumbers`
- Parameters: `int integer1`, `int integer2`

In the body of the method:
- Multiply the two `int`s together
- Return the result

### Call the Method
1. Check if the user would like to multiply numbers  
    - Use an `else if` underneath the existing checks for addition and subtraction
1. If they want to multiply, call the `MultiplyNumbers` method and store the result in a new variable
    - The parameters for the `MultiplyNumbers` call should be the input from the user (`a` and `b`)
1. Print the product to the console

## Division
Add the option to divide the two integers the user provides. Follow the steps for multiplication, but use the division operator instead.

## CHALLENGE: Quadratic Formula
1. Allow the user to enter an additional number (`c`)
1. Define a method that takes three inputs (`a`, `b`, and `c`), and returns one of the results of the quadratic formula: https://www.purplemath.com/modules/quadform.htm#distform
1. If the user enters `"quadratic"` for the operation they would like to perform, call the quadratic formula method on the inputs
1. Print the result to the console in the form `"x = {answer}"`

### EXTRA CHALLENGE:
>Learn about C# `out` parameters: https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/out-parameter-modifier

Use an `out` parameter so that the program can return **both** results of the quadratic formula, and print both to the console.