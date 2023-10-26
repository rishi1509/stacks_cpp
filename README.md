# Stacks

## **THEORY**

A stack is an abstract data structure that contains a collection of elements. Stack implements the LIFO mechanism i.e. the element that is pushed at the end is popped out first. Some of the principle operations in the stack are −

- Push - This adds a data value to the top of the stack.

- Pop - This removes the data value on top of the stack

- Peek - This returns the top data value of the stack

![image](https://github.com/Purvansha022609/Stack/assets/139473344/539f0a75-7b89-48b2-82c5-fcf638478bc7)

## **ALGORITHM**

- Algorithm for the Stack Implementation Program:

1.Start.

2.Define a constant ERROR with the value -9999 to represent errors and a constant MAXSIZE with the value 10 to define the maximum size of the stack.

3.Create a Stack class with private members:

top: an integer to track the top of the stack.

array: an integer array to store the elements of the stack.

In the constructor of the Stack class (Stack::Stack()):


4.Initialize the top to -1 to indicate an empty stack.

5.Define the Push method in the Stack class:

Check if the top is equal to MAXSIZE - 1 (indicating a full stack).

If the stack is full, print "Stack overflow" and return.

Otherwise, increment top and add the item to the array.

Define the Pop method in the Stack class:

Check if the top is equal to -1 (indicating an empty stack).

If the stack is empty, print "Stack is empty" and return ERROR.

Otherwise, retrieve the element from the array at the top position, decrement top, and return the element.

6.Define the Peek method in the Stack class:

Check if the top is not equal to -1 (indicating a non-empty stack).

If the stack is not empty, return the element from the array at the top position.

If the stack is empty, return ERROR.

7.In the main function:

Create an instance of the Stack class (S1).

Comment out the lines that push elements onto the stack (S1.Push(10) and S1.Push(20)).

Call the Pop method to attempt to pop an element from the stack and store the result in variable v.

Check if v is not equal to ERROR. If not, print the value of v.

Comment out the line that attempts to peek at the top of the stack (int x = S1.Peek()).

8.End.

- Algorithm for Stack Implementation Program:

1.Start.

2.Create a Stack class with private members:

maxSize: an integer to store the maximum size of the stack.

top: an integer to keep track of the top of the stack.

stackArray: a dynamic integer array to store stack elements.

3.Define the constructor Stack(int size) for the Stack class:

Initialize maxSize with the given size.

Initialize top to -1 to indicate an empty stack.

Allocate memory for the stackArray with a size of maxSize.

4.Define the destructor ~Stack() for the Stack class:

Deallocate the memory for the stackArray.

Implement the isFull() method to check if the stack is full by comparing top with maxSize - 1.

Implement the isEmpty() method to check if the stack is empty by checking if top is -1.

5.Define the push(int value) method:

Check if the stack is full using isFull().

If the stack is full, print "Stack is full. Cannot push."

Otherwise, increment top, and add the value to the stackArray. Print "Pushed [value] onto the stack."

6.Define the pop() method:

Check if the stack is empty using isEmpty().

If the stack is empty, print "Stack is empty. Cannot pop."

Otherwise, decrement top, and print "Popped [value] from the stack."

7.Define the display() method:

Check if the stack is empty using isEmpty().

If the stack is empty, print "Stack is empty."

Otherwise, print "Stack elements:" and display the elements in the stackArray from index 0 to top.

8.In the main function:

Prompt the user to enter the size of the stack.

Create a Stack instance called stack with the specified size.

Create a loop for displaying a menu of options:

Push a value onto the stack.

Pop an element from the stack.

9.Display the elements in the stack.

10.Exit the program.

11.Based on the user's choice, call the corresponding methods from the Stack class.

Continue the loop until the user chooses to exit.

12.End.

The program provides a menu-driven interface for managing a stack, allowing the user to push elements onto the stack, pop elements from the stack, display the stack's contents, or exit the program. The stack's status (empty or full) is checked before performing push and pop operations.


### **OUTPUT**

1.
![exp18_1](https://github.com/Purvansha022609/Stack/assets/139473344/dcbf5f73-a11a-4ec9-9794-a8671cd5d483)

2.
![exp18_2](https://github.com/Purvansha022609/Stack/assets/139473344/dc63a21d-0d14-4517-afb0-54339a8a3810)
![exp18_3](https://github.com/Purvansha022609/Stack/assets/139473344/719d856c-3362-47b1-8c03-923e7cb978a8)
![exp18_4](https://github.com/Purvansha022609/Stack/assets/139473344/f256d78c-9df5-466b-8b5c-b9fe8fa149a2)
