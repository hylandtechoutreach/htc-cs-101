# To-Do List: Individual Exercises
Complete the following exercises to make the to-do list more robust.

## Count
When the user asks to view the to-do list, display the total count of the list before printing out the list itself.

- Update the `ViewList` method
- Use `.Count` to see how many to-do items are in the list
- Test the program with a few different lists!

### Empty Message
If the user has not added any items to the to-do list, display a message saying "No items added" when they attempt to view the list. The program should not attempt to print out the list in this case.

## Get item
Add a command to the application that will get one specific item from the to-do list.

1. Define a method named `GetItem`
    - The method should take the `List<string>` as a parameter, very similar to the `ViewList` method
    - The method should return nothing
    - The program should call the method if the user enters "Get Item" as the command
1. In the body of the `GetItem` method, the program should ask the user for an **index**
1. The program should store the number as an `int`
1. The program should then print out the specific item by accessing the given index in the list
    - Use square brackets (`[]`) to accomplish this
