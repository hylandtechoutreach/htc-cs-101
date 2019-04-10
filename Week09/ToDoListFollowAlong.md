# To-Do List: Follow-Along Activity
Create a program that keep track of a user's to-do list.

## Part 1 - Setup
Set up the menu for the application.

1. In the `Main` method, display a message to the user welcoming them to the application
1. Under the welcome message, create an infinite `while` loop
    - This will allow the user to continue entering commands
1. Within the body of the infinite `while` loop, ask the user for a command to execute, and store their input in a variable
1. The program should be able to handle 3 commands: "Add", "View", and "Exit"
    - Create an `if` statement to handle a command of "Add"
    - Create an `else if` to handle a command of "View"
    - Create another `else if` to handle a command of "Exit"
1. If the user enters a command of "Exit", `break` out of the infinite loop

### Code
```cs
Console.WriteLine("Welcome to the To-Do List!");

while (true)
{
    Console.WriteLine("Enter a command:");
    string command = Console.ReadLine();

    if (command == "Add")
    {
        // Add
    }
    else if (command == "View")
    {
        // View
    }
    else if (command == "Exit")
    {
        break;
    }
}
```

## Part 2 - The List
The program needs a `List` to keep track of what the user wants to do!

### List Setup
1. At the top of the `Program.cs` file, add a `using` statement that will import `List`s:  
    ```cs
    using System.Collections.Generic;
    ```
1. At the top of the body of the `Main` method, declare a new `List` of `string`s and initialize it to an empty list:  
    ```cs
    List<string> toDoList = new List<string>();
    ```

### Adding to the List
1. Within the `Main` method, in the body of the `if` statement for "Add", ask the user what they want to do
1. Store the user's input in a variable
1. Add the input item to the `toDoList`!

#### Code
```cs
Console.WriteLine("Enter an item:");
string item = Console.ReadLine();

toDoList.Add(item);
```

## Part 3 - Viewing the List
Once the user has added some items to the list, they will want a way to view those items!

1. In the `Program` class, _define_ a method named `ViewList`
    - The method should return `void` (nothing)
    - The method should take a `List<string>` as a parameter
1. In the body of the `ViewList` method, print some text to the console saying "To Do:"
1. Under the "To Do" message, create a `foreach` loop that will loop through the list
    - `foreach` keyword
    - Initialize a new `string` variable
    - `in` keyword
    - Use the parameter variable for the list
    - Curly brackets
1. In the body of the `foreach` loop, print the list item, prefaced by "- "
1. In the `Main` method, in the `else if` for "View", _call_ the `ViewList` method with `toDoList` as the argument

Now the program should work properly!

## Code
```cs
using System;
using System.Collections.Generic;

namespace Week09
{
    class Program
    {
        static void Main(string[] args)
        {
            List<string> toDoList = new List<string>();
            Console.WriteLine("Welcome to the To-Do List!");

            while (true)
            {
                Console.WriteLine("Enter a command:");
                string command = Console.ReadLine();

                if (command == "Add")
                {
                    Console.WriteLine("Enter an item:");
                    string item = Console.ReadLine();
                    
                    toDoList.Add(item);
                }
                else if (command == "View")
                {
                    ViewList(toDoList);
                }
                else if (command == "Exit")
                {
                    break;
                }
            }
        }

        public static void ViewList(List<string> stringList)
        {
            Console.WriteLine("To Do:");
            foreach (string item in stringList)
            {
                Console.WriteLine("- " + item);
            }
        }
    }
}
```