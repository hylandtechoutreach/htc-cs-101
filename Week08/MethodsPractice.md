# Methods Practice
Complete the following exercises in a `Program.cs` file.

## Reference
Remember the syntax for defining and calling methods:

**Defining**
```cs
public static <<returntype>> <<methodname>>(<<parameters>>)
{

}
```

Example
```cs
public static string MyMethodName(string myInput)
{

}
```

**Calling**
```cs
<<methodname>>(<<arguments>>);
```

Example
```cs
string myString = "StringVal";

MyMethodName(myString);
```

Complete the following exercises to practice using methods!

## Print Hat
1. Define a new method named `PrintHat` in the `Program.cs` file
    - The method should take in no parameters
    - The method should return `void` (nothing)
1. In the body of the `PrintHat` method, use 6 `Console.WriteLine` statements to print the following ASCII hat:
    ```
       .--------.
      /          `.
     |         .-. .
     |         |  `.|
     |_________|   <|>
    (___________)
    ```
1. In the body of the `Main` method, call the `PrintHat` method a few times to see multiple hats appear!

## Inches to Centimeters
1. Define a new method named `InToCm` in the `Program.cs` file
    - The method should take in no parameters
    - The method should return a `double` (the value in centimeters)
1. In the body of the `InToCm` method, ask the user for a measurement in inches using `Console.ReadLine`
    - Convert the number to a `double` type using `Convert.ToDouble`
    - Store the double in a new variable named `inches`
1. Define a new `double` variable named `centimeters`, and set its value to the value of `inches` multiplied by `2.54`
1. Return the new `centimeters` variable at the end of the method
1. In the body of the `Main` method, call the `InToCm` method
1. Store the returned value in a new variable named `centimeters`
    - Note that this `centimeters` variable and the `centimeters` variable from the `InToCm` method are different
1. Display a message to the user saying the value in centimeters
    - Ex: If the user entered 2, display "5.08 cm"
    - Ex: If the user entered 2.1, display "5.334 cm"

## Hi Name
1. Define a new method named `HiName` in the `Program.cs` file
    - The method should take in no parameters
    - The method should return a `string` (the message)
1. In the body of the `HiName` method, ask the user to input their name, and store their input in a variable
1. Return a greeting of "Hi, {name}"
    - Ex: If the user enters "Alice", return "Hi, Alice"
    - Ex: If the user enters "Alex", return "Hi, Alex"
1. Call the `HiName` method from within the `MainMethod`, and store the returned message in a variable
1. Display the returned message to the user

## Password Check
1. Define a new method named `PasswordCheck` in the `Program.cs` file
    - The method should take in a `string` (the password to check) as a parameter
    - The method should return `void` (nothing)
1. In the body of the `PasswordCheck` method, use an `if` statement to check if the password is equal to your password
1. If the password is correct, print a message saying "Correct Password"
1. Otherwise, if the password is incorrect, print a message saying "Incorrect Password"
1. In the `Main` method, ask the user to enter their password, and store their input in a variable
1. Call the `PasswordCheck` method on the user's input to see if it is correct or incorrect!

## (CHALLENGE) Coupon Code
The goal of this method is to calculate the final price of a service depending on a coupon code.

1. Define a new method named `CouponCode` in the `Program.cs` file
    - The method should take in a `double` (the initial price) and a `string` (the coupon code) as parameters
    - The method should return a `double` (the final price)
1. In the body of the `CouponCode` method, check if the value of the coupon code is "PUNCH"
    - If it is, return the initial price with a 15% discount applied
1. Check if the value of the coupon code is "HANDBOOK"
    - If it is, return the intial price with a 25% discount applied
1. Check if the value of the coupon code is "FREE"
    - If it is, return the initial price with a 100% discount applied
1. In body of the `Main` method, ask the user to input their initial price
    - Convert the `string` value to a `double` and store it in a variable
1. In `Main`, under the initial price, ask the user to input their coupon code
    - Store it in a variable
1. Call the `CouponCode` method, passing in the initial price and coupon code
    - Store the returned value in a new `double` variable
1. Display a message to the user with the final price after the coupon

### Extra Challenge
In the body of the `CouponCode` method, instead of using `if` statements, use a `switch`!

>Reference: https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/switch