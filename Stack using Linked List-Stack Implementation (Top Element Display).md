# 📚 Stack using Linked List: Stack Implementation (Top Element Display)

## 🎯 Aim

To write a Python program that implements a **stack**.  
The program allows inserting 3 elements from the user and then prints the **top element** of the stack.

---

## 🧠 Algorithm

1. **Start the program.**
2. **Initialize** an empty list called `stack` to simulate the stack.
3. **Repeat 3 times**:
   - Prompt the user to **input a value**.
   - Use `stack.append(value)` to **push** the value onto the stack.
4. After inserting 3 elements:
   - Access the **top element** using `stack[-1]`.
5. **Print** the top element.
6. **End the program.**

---

## 💻 Program
stack = []

stack.append('a') stack.append('b') stack.append('c') stack.append('d')

print('Initial stack: ' + str(stack))

top = stack[-1]

print("\nElement at the top of the stack is .... ", top)

## Output
<img width="735" height="123" alt="491486908-63548fd9-dca2-41f1-8340-47b2154f9601" src="https://github.com/user-attachments/assets/0b4a4d33-1414-4686-8b5b-5ff00dabc3c0" />

## Result
Thus the program is excuted and verified.
