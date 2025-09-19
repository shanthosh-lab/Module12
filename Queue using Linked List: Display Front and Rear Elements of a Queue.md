## 📚 Stack using Linked List: Check and Display Whether the Stack is Full or Not
This Python program demonstrates how to check if a stack (using LifoQueue from the queue module) is full or not. It uses the full() method to determine the stack's status and then displays the appropriate message.

## 🎯 Aim
To write a Python program that: -Creates a stack with a fixed size. -Adds elements to the stack. -Checks if the stack is full. -Displays a message indicating whether the stack is full or not.

## 🧠 Algorithm
1. Import the LifoQueue class: Import LifoQueue from the queue module to create the stack.
2. Create a Stack: Instantiate a LifoQueue with a maximum size (e.g., 4).
3. Add Elements to the Stack: Add elements (e.g., 'a', 'b', and 'c') to the stack using the put() method.
4. Check if the Stack is Full: Use the full() method of LifoQueue to check if the stack has reached its maximum capacity.
5. Display the Status: Print "Stack is full" if the stack is full. Otherwise, print "Stack is not full".
   
## 📝 Program
from queue import LifoQueue

queue = LifoQueue(maxsize = 4)

queue.put('a')

queue.put('b')

queue.put('c')

print("Queue is full") if queue.full() else print("Queue is not full")

## Sample Input & Output
<img width="403" height="134" alt="491484050-a3c91bac-9752-40e9-97fc-ed85efe432d0" src="https://github.com/user-attachments/assets/c70d9f33-c091-4042-af11-0580270130ab" />

## Result
The program is run successfully.
